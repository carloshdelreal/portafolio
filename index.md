---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: welcome
title: Welcome // Bienvenido
---

### Select your Prefered Language // Selecciona tu Idioma preferido

<div class="welcome">
  <ul>
    {% for lang in site.data.languages %}
    {% assign language = lang[1] %}
    <li>
      <a href="{{site.baseurl}}{{lang[0]}}">
        {{ language.label }}
        <img src="{{ language.image }}" alt="language image">  
      </a>
    </li>
    {% endfor %}
  </ul>
</div>
