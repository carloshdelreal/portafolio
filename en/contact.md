---
layout: page
title: Contact Me
nav-title: Contact
nav-order: 5
lang: en
figures: assets/images
---

feel free to send me a message :D

<form
  action="https://formspree.io/meqgqjdq"
  method="POST"
>
  <div class="form-group">
    <label>
      Name:
    </label>
    <input type="text" name="_replyto">
  </div>
  
  <div class="form-group">
    <label>
      email
      <input type="email" required name="_replyto">
    </label>
  </div>
  
  <div class="form-group">
    <label>
      Phone
      <input type="phone" name="_replyto">
    </label>
  </div>

  <div class="form-group">
    <label>
      Your message:
      <textarea name="message"></textarea>
    </label>
  </div>
  <input type="hidden" name="_next" value="{{ url }}/{{ page.lang }}/thanks.html">

  <button class="btn btn-success" type="submit">Send</button>
</form>