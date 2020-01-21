---
layout: portfolio
title: Doctor's App
author: Carlos Del Real
position: Full Stack Web Developer
company: Microverse
date: 2020-01-21 08:00:00 -0500
categories: "Ruby on Rails + React"
permalink: doctors-app
thumb: assets/portfolio/microverse/doctors/thumb.png
figures: assets/portfolio/microverse/doctors
description: "Fullstack Web application with backend Ruby on Rails and React Frontend"
lang: en
---

## Generalities

Doctor's Application is a partial implementation of the [MediCo - Medical Mobile App](https://www.behance.net/gallery/77208667/MediCo-Medical-mobile-app-UIUX-design?tracking_source=search%7Cmobile%20app){:target="_blank"} designed by Vinisha Panjikar.

You can see a live version of the implementation [At Doctor's App https://doctorscapstone.herokuapp.com/](https://doctorscapstone.herokuapp.com/){:target="_blank"}. This is a Full stack web application that has been designed for mobile devices.

The application consists of a login system, and a backend API that stores your data and feeds the frontend application implemented on React.

if you want to review the source code you can check out the [Doctor's App Repository](https://github.com/carloshdelreal/doctors){:target="_blank"}

## Doctors App Features

To see this marvel working you just have to go to the [At Doctor's App ](https://doctorscapstone.herokuapp.com/){:target="_blank"} there you will be taken to the login page. there you are able to register or login as `carlos@email.com` as your email and `foobar` as the password

<figure class="figure">
    <img src="{{ page.figures }}/home.png">
</figure>

once you log in you will be taken to the home page in which you have different options, as this is a partial implementation as I said before, the nav bar and the Doctor's button are the only available ones, click on Doctor.

Behold the search doctor implementation!, there you can select an specialty and the corresponding doctors will be filtered and displayed to you, select the one that you prefer.

<figure class="figure">
    <img src="{{ page.figures }}/search_doctor.png">
</figure>

once you select the desired doctor you are able to see information about him/her, the clinic and feedback commenting, then if you are happy you can click on **Book Appointment**.

<figure class="figure">
    <img src="{{ page.figures }}/doctor_profile.png">
</figure>

The most important and elaborated part of this application is the booking system in which every doctor has a totally independent set of available appointments, you can choose the date and time for the appointment and click on book, you will be prompted to a confirmation window and voila!, your appointment is arranged.

the nicest thing about this implementation is that the selected appointment won't be available anymore.

last but not least is that you can go to a main menu in with you can check your booked appointments.

<figure class="figure">
    <img src="{{ page.figures }}/booking.png">
</figure>
