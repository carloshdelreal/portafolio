---
port_id: 6
layout: portfolio
title: Aplicación Doctor
author: Carlos Del Real
position: Desarrollador Full-stack
company: Microverse
date: 2020-01-21 08:00:00 -0500
categories: Ruby on Rails React
live: Doctors
thumb: assets/portfolio/microverse/doctors/thumb.png
figures: assets/portfolio/microverse/doctors
description: "Aplicación Full-stack con backend hecho en Ruby on Rails y frontend React"
lang: es
---

## Generalidades

La aplicación Doctor es una implementación parcial de la aplicación [MediCo - Medical Mobile App](https://www.behance.net/gallery/77208667/MediCo-Medical-mobile-app-UIUX-design?tracking_source=search%7Cmobile%20app){:target="_blank"} diseñada por Vinisha Panjikar.

Puedes ver la versión en vivo de la implementación en [Doctor's App https://doctorscapstone.herokuapp.com/](https://doctorscapstone.herokuapp.com/){:target="_blank"}. Ésta es una aplicación web Full-stack que se diseño principalmente para dispositivos móviles.

La aplicación consiste de un sistema de registro y una API backend que almacena tus datos y alimenta la aplicación frontend desarrollada en react.

si quieres revisar el código fuente puedes hacerlo en el repositorio [Doctor's App Repository](https://github.com/carloshdelreal/doctors){:target="_blank"}

## Características de la App

Para ver esta maravilla funcionando sólo tienes que ir a [Doctor's App https://doctorscapstone.herokuapp.com/](https://doctorscapstone.herokuapp.com/){:target="_blank"} allí verás una página de registro en donde podrás registrate con usuario y contraseña, si no tienes una puedes registrarte o utilizar `carlos@email.com` como email y `foobar` como contraseña.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/home.png">
</figure>

una vez registrado serás llevado a una página principal en la que tienes diferentes opciones, como esta es una implementación parcial, como dije antes, sólo la barra de navegación y el botón Doctor's funcionan, da click en Doctor.

Contempla la implementación de Search Doctor, allí puedes seleccionar una especialidad y los doctores correspondientes a ella serán filtrados y mostrados, selecciona el que prefieras.
Behold the search doctor implementation!, there you can select an specialty and the corresponding doctors will be filtered and displayed to you, select the one that you prefer.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/search_doctor.png">
</figure>

Una vez selecciones el doctor de tu preferencia, verás información acerca de el o ella, la clínica en la que trabaja y comentarios de otros pacientes, luego si lo deseas puedes agendar una cita dando click en **Book Appointment**.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/doctor_profile.png">
</figure>

La parte más importante y elaborada de esta aplicación es el sistema de citas en el cual cada doctor tiene una independencia total de agendar sus citas, puedes escoger la fecha y la hora para la cita y dar click en agendar (**Book**), aparecerá entonces una ventana de confirmación y voila!, tu cita ha sido agendada.

lo mejor de esta implementación es que la cita seleccionada ya no estará disponible.

por ultimo puedes ir al menu principal y puedes ver tus citas agendadas

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/booking.png">
</figure>
