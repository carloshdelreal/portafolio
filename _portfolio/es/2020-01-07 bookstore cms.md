---
port_id: 5
layout: portfolio
title: Bookstore CMS
author: Carlos Del Real & Radouane Khiri
position: Desarrollador React & Redux Bookstore CMS
company: Microverse
date: 2020-01-07 08:00:00 -0500
categories: React Redux
live: Bookstore
thumb: assets/portfolio/microverse/bookstore/thumb.png
figures: assets/portfolio/microverse/bookstore
description: "Un sistema de manejo de contenido de libros en React"
lang: es
---

## Generalidades

Bookstore es un sistema de manejo de contenido elaborado en **React y Redux**, ésta aplicación maneja libros por nombre y categoría [Bookstore CMS](https://bookstore-cared.herokuapp.com/){:target="_blank"}. Por estar implementado en React es una aplicación de una sola página con capacidad para agregar, mostrar y seleccionar libros por categoría.

Si deseas revisar el código fuente puedes ver el repositorio en [Bookstore CMS Repository](https://github.com/Redvanisation/Bookstore){:target="_blank"}

## Características de la aplicación

Una vez tengas acceso al [Bookstore CMS](https://bookstore-cared.herokuapp.com/){:target="_blank"} sera llevado a la página principal, ahí verás los libros creados por defecto.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/home.png">
</figure>

luego puedes agregar un libro tecleando su título seleccionando una categoría, una vez des click en el botón submit, tu libro será agregado a las lista.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/add_book.png">
</figure>

Puedes seleccionar libros que quieras ver cambiando la selección en el cuadro combinado

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/select_books.png">
</figure>

Todo este se puede hacer sin recargar la página, desafortunadamente esta aplicación no tiene un backend para guardar los datos por lo que al recargar la página o cerrar el navegador se perderán todos los datos.
