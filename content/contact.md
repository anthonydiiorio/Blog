---
title: "Contact"
date: 2021-02-08T19:44:33-05:00
draft: false
page: true
hidemeta: true
---

{{< rawhtml >}}
<script src="https://challenges.cloudflare.com/turnstile/v0/api.js" async defer></script>
<div class="contact">
<form action="https://submit-form.com/LYR7glc3k">
    <label for="full-name">Name</label>
    <input type="text" name="name" id="full-name" placeholder="Name" required="">
    <label for="email-address">Email Address</label>
    <input type="email" name="email" id="email-address" placeholder="email@example.com" required="">
    <label for="message">Message</label>
    <textarea rows="5" name="message" id="message" placeholder="" required=""></textarea>
    <input type="hidden" name="_feedback.dark" value="true" />
    <input type="hidden" name="_feedback.success.title" value="Message sent!"/>
    <input type="text" name="_cheese" tabindex="-1" autocomplete="off" class="whole-milk" />
    <div class="cf-turnstile" data-sitekey="0x4AAAAAAAaPqMoRrPEYPeCr"></div>
    <button type="submit">Send</button>
</form>
</div>
{{< /rawhtml >}}