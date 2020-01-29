---
port_id: 3
layout: portfolio
title: Battleship
author: Carlos Del Real & António Fernandez
position: Desarrollador del Juego Battleship
company: Microverse
date: 2019-12-19 08:00:00 -0500
categories: JavaScript HTML CSS Webpack Node Jest
live: Battleship
thumb: assets/portfolio/microverse/battleship/battleship.jpg
figures: assets/portfolio/microverse/battleship
description: "The most addicting and funniest Battleship Game Ever!"
lang: es
---

## Generalidades

Battleship es una implementación del juego battleship hecha en JavaScript. se creó completamente desde cero y puedes ver este juego en [Battleship game](https://carloshdelreal.github.io/battleship/dist/index.html){:target="_blank"}.

Si deseas puedes darle un vistazo al código en el repositorio [Battleship Game Repository](https://github.com/carloshdelreal/battleship){:target="_blank"}

## Flujo de Juego

para empezar el juego debes darle click en comenzar juego, y tus barcos y submarinos aparecerán en el tablero automáticamente. si no estás feliz con su localización puedes dar comenzar juego (start game) una vez mas y tus barcos volverán a acomodarse de manera aleatoria.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/game_start.jpg">
</figure>

ahora estás listo para comenzar a disparar!!, dale click al tablero del enemigo en los cuadros que desees disparar, cada vez que dispares el enemigo te disparará.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/fire.jpg">
</figure>

dispara hasta el final! hasta el último barco!

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/fire_until_the_end.jpg">
</figure>

una vez hayas hundido todos los barcos enemigos o el enemigo destruya los tuyos, verás un mensaje de victoria

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/game_end.jpg">
</figure>

## The coding Background

Para este proyecto se utilizaron una serie de técnicas importantes para la modularización del código. a nivel fundamental se utilizó Programación Orientada a Objetos, y más específicamente Factory Functions para simular clases en JavaScript y crear el código tan independiente y modularizado como fuera posible.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/folder_structure.png">
</figure>

Como resultado puedes ver la estructura de carpetas que corresponde y como cada archivo corresponde a un objeto independiente que puede ser reutilizado en la implementación de un juego similar. para este proyecto se aplicaron los principios SOLID que hace el código mucho más legible y fácil de aprender y entender. si quieres saber más de estos principios puedes ver mi artículo en medium [Solid Principles](https://medium.com/@carloshdelreal/stop-coding-bad-practices-d976ce05dbc6){:target="_blank"}

## Testing

Para hacer el testing de este proyecto se utilizó Jest como Framework, si deseas tener una copia local de este proyecto solo tienes que seguir las instrucciones del repositorio [Battleship Game Repository](https://github.com/carloshdelreal/battleship){:target="_blank"} descargarlo y navegar a la carpeta del repositorio desde la línea de comandos y teclear `npm install` y verás

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/install.png">
</figure>

Luego puedes revisar los resultados del test tecleando `npm run test` esto mostrará en la pantalla algo como 

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/tests_run.png">
</figure>

una vez todos los test pasen verás

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/tests_pass.png">
</figure>
