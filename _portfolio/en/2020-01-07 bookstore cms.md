---
port_id: 5
layout: portfolio
title: Bookstore CMS
author: Carlos Del Real & Radouane Khiri
position: Main Developer of The Bookstore CMS
company: Microverse
date: 2020-01-07 08:00:00 -0500
categories: React
live: Bookstore
thumb: assets/portfolio/microverse/bookstore/thumb.png
figures: assets/portfolio/microverse/bookstore
description: "A bookstore CMS built on React"
lang: en
---

## Generalities

Bookstore CMS is a **React & Redux** application that handles books by name and category [Bookstore CMS](https://bookstore-cared.herokuapp.com/){:target="_blank"}. as it is implemented in react is a single page application with capabilities adding, remove, display and select books by category.

If you want to review the source code you can check out the [Bookstore CMS Repository](https://github.com/Redvanisation/Bookstore){:target="_blank"}

## App Features

Upon accessing the [Bookstore CMS](https://bookstore-cared.herokuapp.com/){:target="_blank"} you will be taken to the home page. There you will see the books created by default

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/home.png">
</figure>

From the home page, you can add books by typing their title and category. Once you click the submit button, your book will be added to the list.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/add_book.png">
</figure>

You can then edit books by changing the value in the select box.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/select_books.png">
</figure>

All of this is done in a single page application. This application does not currently have a backend to save the data; when you reload the page or close the browser all the data will be lost.
