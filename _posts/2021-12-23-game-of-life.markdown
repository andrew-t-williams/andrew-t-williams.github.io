---
layout: default
title:  "Conway's Game of Life ( 🎮 interactive demo )"
description: "An interactive web app to visualize Conway's Game of Life."
date:   2021-12-23 22:00:00 -0800
---

# Conway's Game of Life
An interactive web app to visualize Conway's Game of Life. 

Two dimentional grid of cells. Each cell is either dead or alive, and each generation or frame has rules of how a cell's state changes. Evaluations are based on surrounding cells.

## Rules:
* Any live cell with fewer than two live neighbours dies, as if by underpopulation.
* Any live cell with two or three live neighbours lives on to the next generation.
* Any live cell with more than three live neighbours dies, as if by overpopulation.
* Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

<button id="goto_button" style="width: 100%; height: 34px; background-color: #34a55c; border-radius: 16px;">
        Check it out here!
</button>

<script>
    document.getElementById('goto_button').onclick = function () {
        window.open("https://game-of-life.andrew-williams.dev", '_blank');
    }
</script>