## Pre Scale Performance

This application compares the rendering speed of three drawing methods: scale, pre-scale, and pre-scaled-sheet. Scale draws graphics from the source image to a buffer, which is then scaled and drawn to the screen. Pre-scale creates individual scaled canvas elements for each sprite in the source image and then draws them directly to the screen. Pre-scaled-sheet draws the source image to a larger canvas element, and then those scaled graphics are drawn directly to the screen.Made by Arpan Poudel.

## Features:
* **scale** - Draws graphics directly from the source image to a buffer, which is then scaled and rendered to the screen on the fly.
* **pre-scale** - Creates separate, pre-scaled canvas elements for every single sprite in the source image, then draws them directly.
* **pre-scaled-sheet** - Draws the entire source image onto a larger, pre-scaled canvas element first, then pulls the scaled graphics from there to draw to the screen.

### Live Demo
You can see live here: https://pre-scale-performance.netlify.app/


## Tech Stack:
* **HTML**
* **CSS**
* **JS**

## ScreenShot:





## Author:Arpan Poudel.
