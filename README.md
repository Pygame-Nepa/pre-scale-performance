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

<img width="720" height="1276" alt="screenshot-1781011190978-2" src="https://github.com/user-attachments/assets/0bb29693-0f42-43f4-b130-0b4239a28a15" />
<img width="720" height="1309" alt="screenshot-1781011190001-1" src="https://github.com/user-attachments/assets/bfcd51f0-f8b2-4ef9-ac07-1a52d6b80c4c" />




## Author:Arpan Poudel.
