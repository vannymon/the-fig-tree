# the-fig-tree 🌳

> _"I saw my life branching out before me like the green fig tree..."_ — Sylvia Plath

An interactive 3D fig tree for mapping your interests. Plant a branch for each thing that draws you, log your progress, and watch figs ripen as you grow — or fade when you stop showing up.

## Features

- **3D hand-drawn tree** — Three.js toon shading with wobbly ink outlines, floating fireflies, and a night-sky terminal aesthetic
- **Growth stages** — each branch progresses `curious → exploring → practising → confident → mastery`, with the fruit evolving from bud to flower to fig
- **Progress logs** — jot down what you did, tag a mood, and keep the branch alive
- **Wither system** — branches you neglect fade, wither, and eventually drop their fruit
- **Share** — export a snapshot of your tree as an image or share it to socials
- **Keyboard + touch** — WASD/arrows to move, drag to orbit, scroll/pinch to zoom

## Running locally

No build step. Serve the folder with any static server:

```sh
npx serve .
```

Or just open `index.html` in a browser.

## Data

Your tree lives entirely in your browser's `localStorage`. Nothing is uploaded anywhere — every visitor grows their own tree.

## Stack

A single `index.html`: [Three.js](https://threejs.org/) for the 3D scene, [GSAP](https://gsap.com/) for animation, JetBrains Mono for the terminal chrome. No framework, no bundler, no dependencies to install.
