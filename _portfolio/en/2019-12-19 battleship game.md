---
port_id: 3
layout: portfolio
title: Battleship Game
author: Carlos Del Real & António Fernandez
position: Main Developer of The Battleship Game
company: Microverse
date: 2019-12-19 08:00:00 -0500
categories: JavaScript HTML CSS Webpack Node Jest
live: Battleship
thumb: assets/portfolio/microverse/battleship/battleship.jpg
figures: assets/portfolio/microverse/battleship
description: "The most addicting and funniest Battleship Game Ever! Using JavaScript and tested with Jest."
lang: en
---

## Generalities

Battleship is an implementation of the Battleship Game coded in JavaScript. It was created completely form scratch
check the game at [Battleship game](https://carloshdelreal.github.io/battleship/dist/index.html){:target="_blank"}. if you want to checkout
the code look at the repository on [Battleship Game Repository](https://github.com/carloshdelreal/battleship){:target="_blank"}

## Game Flow

To start the game, simply click the Game Start button, and your boats will appear automatically. They will be placed randomly every time you click Game Start

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/game_start.jpg">
</figure>

Now you are ready to start firing!! Click the squares on the enemy board that you’d like to fire on. Every time you fire, the enemy will fire back.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/fire.jpg">
</figure>

Fire until the end, up to the last boat!

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/fire_until_the_end.jpg">
</figure>

Once you have sunk all the enemy boats or your enemy has destroyed all of yours, you will see a victory or loss message.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/game_end.jpg">
</figure>

## The coding Background

This project uses a series of techniques for modularizing the code. It uses Object oriented programming, and more specifically factory functions, to emulate classes on JavaScript and create the code as loosely-coupled as possible.

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/folder_structure.png">
</figure>

As a result, you can see at the folder structure that each of the folders correspond to any object that can be reused in the implementation of a similar game. In addition, the application of SOLID principles makes the code much more readable and easy to learn and understand. If you want to learn more about [Solid Principles](https://medium.com/@carloshdelreal/stop-coding-bad-practices-d976ce05dbc6){:target="_blank"} checkout an article that I have written about it.

## Testing

For this project was used jest as a testing framework, if you want a local copy of this project just follow the [Battleship Game Repository](https://github.com/carloshdelreal/battleship){:target="_blank"}.Navigate to your repository folder and type `npm install`. You will see the following:

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/install.png">
</figure>

Then you can check the testing results by typing `npm run test` Your results will look something like this:

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/tests_run.png">
</figure>

Once all tests pass, you will see:

<figure class="figure">
    <img src="{{ url }}/{{ page.figures }}/tests_pass.png">
</figure>
