---
layout: page
title: Contact Me
nav-title: Contact
nav-order: 5
lang: en
figures: assets/images
---
{% assign thanks_url = site.url | append: "/" | append: page.lang | append: "/" | append: "thanks" %}

Feel free to send me a message :D

<form
  action="https://formspree.io/meqgqjdq"
  method="POST"
>
  <div class="form-group">
    <label>
      Name:
    </label>
    <input type="text" name="_name">
  </div>
  
  <div class="form-group">
    <label>
      Email:
    </label>
    <input type="email" required name="_email">
  </div>
  
  <div class="form-group">
    <label>
      Phone:
    </label>
    <input type="phone" name="_phone">
  </div>

  <div class="form-group">
    <label>
      Your message:
    </label>
    <textarea required name="_message" rows="5"></textarea>
  </div>
  
  <input type="hidden" name="_next" value="{{ thanks_url }}">

  <button class="btn btn-success" type="submit">Send</button>
</form>