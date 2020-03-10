---
port_id: 1
layout: portfolio
title: Doctor's App
author: Carlos Del Real
position: Full Stack Web Developer
company: Microverse
date: 2020-01-21 08:00:00 -0500
categories: "Ruby on Rails + React"
live: Doctors
thumb: assets/portfolio/microverse/doctors/thumb.png
figures: assets/portfolio/microverse/doctors
description: "A full-stack web application built with Ruby on Rails for the backend and React for the frontend. Tested using RSpec, Capybara, and Jest."
lang: en
---

## Generalities

A full-stack web application to allow users to search for local physicians, schedule, and manage appointments. Built using Ruby on Rails and React.

Doctor's Application is a partial implementation of the [MediCo - Medical Mobile App](https://www.behance.net/gallery/77208667/MediCo-Medical-mobile-app-UIUX-design?tracking_source=search%7Cmobile%20app){:target="_blank"} designed by Vinisha Panjikar.

You can see a live version of the implementation [At Doctor's App](https://doctorscapstone.herokuapp.com/){:target="_blank"}. This is a Full stack web application that has been designed for mobile devices.

The application consists of a login system, and a backend API that stores your data and feeds the frontend application implemented with React.

You can check out the source code on [Doctor's App Repository](https://github.com/carloshdelreal/doctors){:target="_blank"}

## Doctors App Features

To view the live demo, click the [Doctor's App link](https://doctorscapstone.herokuapp.com/){:target="_blank"}. You will be taken to the login page. There, you will be able to register as a new user. You may also log in using  `carlos@email.com` as your email and `foobar` as the password.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/home.png">
</figure>

Once you log in, you will be taken to the homepage. As this is a partial implementation, only the nav bar and the Doctor’s button are currently available.

Click on Doctor and behold the doctor search bar! There, you can select a specialty and the corresponding doctors will be filtered and displayed for you. Select the doctor that you prefer.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/search_doctor.png">
</figure>

Once you select your desired doctor, you will then be able to see information and feedback about the doctor and clinic. If you are happy with your selection, you can click on **Book Appointment**.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/doctor_profile.png">
</figure>

The most important and elaborate part of this application is the booking system, in which every doctor has a totally independent set of available appointments. You can choose the date and time for the appointment and click Book. You will then be taken to a confirmation window and voila: your appointment is arranged.

The nicest feature about this implementation is that the selected appointment will no longer be available to other users.

Once your appointment has been set, you can then go to the main men and check your booked appointments.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/booking.png">
</figure>
