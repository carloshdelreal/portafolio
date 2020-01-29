---
layout: page
title: Contáctame
nav-title: Contacto
nav-order: 5
lang: es
figures: assets/images
---
{% assign thanks_url = site.url | append: "/" | append: page.lang | append: "/" | append: "thanks" %}

Envíame un mensaje :D

<form
  action="https://formspree.io/meqgqjdq"
  method="POST"
>
  <div class="form-group">
    <label>
      Nombre:
    </label>
    <input type="text" name="_name">
  </div>
  
  <div class="form-group">
    <label>
      email:
    </label>
    <input type="email" required name="_email">
  </div>
  
  <div class="form-group">
    <label>
      Teléfono:
    </label>
    <input type="phone" name="_phone">
  </div>

  <div class="form-group">
    <label>
      Mensaje:
    </label>
    <textarea required rows="5" name="_message"></textarea>
  </div>
  <input type="hidden" name="_next" value="{{ thanks_url }}">

  <button class="btn btn-success" type="submit">enviar</button>
</form>