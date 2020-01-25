---
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

if you want to review the source code you can check out the [Bookstore CMS Repository](https://github.com/Redvanisation/Bookstore){:target="_blank"}

## App Features

once you access to the [Bookstore CMS](https://bookstore-cared.herokuapp.com/){:target="_blank"} you will be taken to the home page, there you will see the books created by default

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/home.png">
</figure>

then you can add a book typing its title and category, once you click the submit button your book will be added to the book's list

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/add_book.png">
</figure>

you are able to select the books that you want to list by changing the value in the select box

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/select_books.png">
</figure>

All of this is done in a single page application without reloading the page, unfortunately this application doesn't have a backend to save the data so when you reload the page or close the browser all the data is lost.
