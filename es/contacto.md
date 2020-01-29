---
layout: page
title: Contáctame
lang: es
figures: assets/images
---

Envíame un mensaje :D

<form
  action="https://formspree.io/meqgqjdq"
  method="POST"
>
  <div class="form-group">
    <label>
      Nombre:
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
      Teléfono
      <input type="phone" name="_replyto">
    </label>
  </div>

  <div class="form-group">
    <label>
      Mensaje:
      <textarea name="message"></textarea>
    </label>
  </div>
  <input type="hidden" name="_next" value="{{ url }}/{{ page.lang }}/thanks.html">

  <button class="btn btn-success" type="submit">enviar</button>
</form>