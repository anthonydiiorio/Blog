---
title: "List of Mirrorless Cameras with UVC Webcam Support"
date: 2024-05-25T20:20:00-04:00
draft: false
tags: ["Cameras","Mirrorless","Webcam","Streaming"]
cover:
    image: "R6II.jpg"
    alt: "Canon R6 II"
    relative: true # To use relative path for cover image, used in hugo Page-bundles
---

Here is a list of UVC protocol mirrorless cameras you can use for video calls, live streaming, or recording directly to your PC with OBS. Cameras with UVC support don't need any extra software running on your computer to work, just plug and play. I'll try to keep this up to date as new cameras are released.

### Canon

- Canon EOS R1 [(1080p30)](https://cam.start.canon/en/C018/manual/html/UG-06_Network_0300.html)
- Canon EOS R5 Mark II [(1080p30)](https://cam.start.canon/en/C017/manual/html/UG-06_Network_0300.html)
- Canon EOS R6 Mark II [(1080p30)](https://cam.start.canon/en/C012/manual/html/UG-08_Set-up_0310.html)
- Canon EOS R8 [(1080p30)](https://cam.start.canon/en/C013/manual/html/UG-08_Set-up_0270.html)
- Canon EOS R50 [(1080p30)](https://cam.start.canon/en/C011/manual/html/UG-09_Set-up_0230.html)
- Canon PowerShot V10 [(1080p30)](https://cam.start.canon/en/C014/manual/html/UG-05_Set-up_0180.html)

#### Cinema EOS

- Canon EOS C80 [(1024x576 30p)](https://www.usa.canon.com/support/p/eos-c80)
- Canon EOS R5 C [(1024x576 30p)](https://www.usa.canon.com/support/p/eos-r5-c)

### DJI

- DJI Osmo Action 2, 3, 4, 5 Pro
- DJI Osmo Pocket 3

### Fujifilm

#### X-Processor 5 (4K60)

- Fujifilm X-H2 
- Fujifilm X-H2S
- Fujifilm X-M5
- Fujifilm X-S20
- Fujifilm X-T5
- Fujifilm X-T50

[Manual](https://fujifilm-dsc.com/en/manual/x-h2_connection/overview_usage/webcam/index.html)

📝 Note that you cannot power Fujifilm cameras over USB **and** use it as a UVC webcam at the same time. Not great for live streaming unless you plan to use a dummy battery like the [Kondor Blue D-Tap to NP-W235 adapter](https://kondorblue.com/products/d-tap-to-fuji-npw235-dummy-battery-cable).

### Nikon

- Nikon Z50II

A new addition for late 2024, Nikon has finally started making UVC cameras! 😀

### Sony

- Sony a1 [(4K30)](https://helpguide.sony.net/ilc/2420/v1/en/contents/211h_usb_streaming.html)
- Sony a1 II (4K30)
- Sony a7 IV [(1080p60)](https://helpguide.sony.net/ilc/2110/v1/en/contents/TP1000660156.html)
- Sony a7R V [(1080p60)](https://helpguide.sony.net/ilc/2230/v1/en/contents/TP1000669419.html)
- Sony a7C [(720p30)](https://helpguide.sony.net/ilc/2020/v1/en/contents/TP1000553122.html) ❗No USB-C Power Delivery
- Sony a7C II [(4K30)](https://helpguide.sony.net/ilc/2360/v1/en/contents/211h_usb_streaming.html)
- Sony a7CR [(4K30)](https://helpguide.sony.net/ilc/2370/v1/en/contents/211h_usb_streaming.html)
- Sony a6700 [(4K30)](https://helpguide.sony.net/ilc/2320/v1/en/contents/211h_usb_streaming.html)
- Sony ZV-E1 [(4K30)](https://helpguide.sony.net/ilc/2310/v1/en/contents/211h_usb_streaming.html)
- Sony ZV-E10 [(720p30)](https://helpguide.sony.net/ilc/2070/v1/en/contents/TP1000201566.html)
- Sony ZV-E10 II [(4K30)](https://helpguide.sony.net/ilc/2430/v1/en/contents/211h_usb_streaming.html)
- Sony ZV-1, ZV-1F, ZV-1 II [(720p30)](https://helpguide.sony.net/dc/2310/v1/en/contents/202h_usb_streaming.html)

### OM System

- OM System OM-1 II [(720p30)](https://learnandsupport.getolympus.com/sites/default/files/media/files/2024/01/OM-1Mk2_ENU_00.pdf)
- OM System OM-5 [(720p30)](https://learnandsupport.getolympus.com/sites/default/files/media/files/2022/10/OM-5_ENU_00.pdf)

### Capture Devices with UVC

#### Blackmagic
- [Blackmagic Atem Mini](https://www.blackmagicdesign.com/products/atemmini) 1080p
- [Blackmagic Video Assist](https://www.blackmagicdesign.com/ca/products/blackmagicvideoassist) 1080p

#### Elgato
- [Elgato Cam Link 4K](https://www.elgato.com/ca/en/p/cam-link-4k) 1080p60 / 4K30

---

### Cameras that can be used as webcams with desktop software

The following pieces of software can be used on older cameras that do not support UVC over USB. Note that most of these are going to be low resolution, low fps solutions. 

**📝 You are better off using an external capture card!**

- [Canon EOS Webcam Utility](https://www.usa.canon.com/cameras/eos-webcam-utility) (1024x576)
- [FUJIFILM X Webcam](https://fujifilm-x.com/en-ca/products/software/x-webcam/) (1024x768 low fps)
- [Lumix Webcam Software](https://www.panasonic.com/global/consumer/lumix/lumix_webcam_software.html) (1280x960 or 1280x720)
- [Nikon Webcam Utility](https://downloadcenter.nikonimglib.com/en/products/548/Webcam_Utility.html) (1024x768 low fps)
- [OM System OM Webcam](https://download.omsystem.com/pages/webcambeta/en/index.html) (720p low fps)
- [Sony Imaging Edge Webcam](https://support.d-imaging.sony.co.jp/app/webcam/en/) (1024x576)

Why are all these webcam tools so bad? Because they use the feed intended for tethering. These old cameras were never intended to be used as webcams. The feed is just there as a preview for professional studio software.
