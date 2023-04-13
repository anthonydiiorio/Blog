---
title: "How to Add AirPrint to a Brother Printer With CUPS"
date: 2023-04-12T00:00:00-04:00
draft: false
tags: ["Printer","AirPrint","Brother","HL-2270DW"]
cover:
    image: "cups.png"
    alt: "CUPS Config"
    relative: true
---

First make sure your locale is set so the expected paper size is selected. The United States and Canada use Legal/Letter size. If you don't set your locale, it will default to A4 size.

``` bash
sudo dpkg-reconfigure locales

# Verify the locale is set
locale

# Expected output:
# LC_PAPER="en_CA.UTF-8" or "en_US.UTF-8"
```

Next,
- Install CUPS, Avahi, Brother Laser Driver
- Add your admin user account
- Enable remote Web UI and printer sharing
- Restart CUPS

``` bash
sudo apt install cups avahi-daemon printer-driver-brlaser 
sudo usermod -a -G lpadmin username
sudo cupsctl --remote-admin --share-printers
sudo service cups restart
```

## Web UI Setup

Navigate to `https://server-ip:631/admin`

Click `Add Printer` and select your printer from the list or configure it manually.

![](conf1.png)

Enable `Share This Printer`

![](conf2.png)

Select the driver.

![](conf3.png)

Set the printer options.

![](conf-defaults.png)

Done! The printer should now show up in AirPrint and the Android Default Print Service.

![](android.png)

### Troubleshooting Paper Size

If you try printing on an iOS or Android device and Letter Paper is missing try the following steps:

``` bash
# Set /etc/papersize to "letter"
sudo paperconfig -p letter

sudo vim /etc/cups/cupsd.conf

# Insert the following lines:
# DefaultPaperSize Letter
# DefaultLanguage en_US

# Clear the cache and restart CUPS
sudo rm -r /var/cache/cups/
sudo service cups restart

# Verify media-ready = na_legal_8.5x14in,na_letter_8.5x11in
ipptool -tv ipp://localhost:631/printers/Printer_Name /usr/share/cups/ipptool/get-printer-attributes.test | grep media-ready
```

### Notes

This tutorial was created using CUPS 2.4.2, and Ubuntu Server 22.10.