---
layout: portfolio
title: Battleship Game
author: Carlos Del Real & António Fernandez
position: Main Developer of The Battleship Game
company: Microverse
date: 2019-12-19 08:00:00 -0500
categories: JavaScript HTML CSS Webpack Node Jest
permalink: battleship-game
thumb: assets/portfolio/microverse/battleship/battleship.jpg
figures: assets/portfolio/microverse/battleship
description: "The most addicting and funniest Battleship Game Ever!"
lang: en
---

## Generalities

Battleship is an implementation of the Battleship Game coded in JavaScript. It was created completely form scratch
check the game at [Battleship game](https://carloshdelreal.github.io/battleship/dist/index.html). if you want to checkout
the code look at the repository on [Battleship Game Repository](https://github.com/carloshdelreal/battleship)

## Game Flow

to start the game you simply click the game start button, and your boats will appear automatically. they will be placed
randomly every time you click the game start button.

<figure class="figure">
    <img src="{{ page.figures }}/game_start.jpg">
</figure>

now you are ready to start firing!!, go an click on the enemy board the squares that you want to fire, every time you fire
the enemy will fire you back.

<figure class="figure">
    <img src="{{ page.figures }}/fire.jpg">
</figure>

fire until the end, up to the last boat!

<figure class="figure">
    <img src="{{ page.figures }}/fire_until_the_end.jpg">
</figure>

once you have sink all the enemy boats or your enemy destroy all of yours, you will see victory message will be shown.

<figure class="figure">
    <img src="{{ page.figures }}/game_end.jpg">
</figure>

## The coding Background

For this project were used a series of very important techniques for modularizing the code. At a fundamental level it was used
Object oriented programming, and more specifically factory functions to emulate classes on javascript an create the code as 
loosely coupled as possible.

<figure class="figure">
    <img src="{{ page.figures }}/folder_structure.png">
</figure>

as result you can see at the folder structure that each of the folders correspond to and object that could be reused in the 
implementation of a similar game. not to mention that the application of the SOLID principles makes the code much more readable
and easy to learn and understand. if you want to know more about [Solid Principles](https://medium.com/@carloshdelreal/stop-coding-bad-practices-d976ce05dbc6) checkout an article that I have written
about it.

## Testing

For this project was used jest as a testing framework, if you want a local copy of this project just follow the [Battleship Game Repository](https://github.com/carloshdelreal/battleship) instructions. navigate to your repository folder and type `npm install` and you will see

<figure class="figure">
    <img src="{{ page.figures }}/install.png">
</figure>

Then you can check the testing results by typing `npm run test` this will show up somethin like this

<figure class="figure">
    <img src="{{ page.figures }}/tests_run.png">
</figure>

once all the test passes you will see

<figure class="figure">
    <img src="{{ page.figures }}/tests_pass.png">
</figure>

