# Sakura Tree 🌸

A cherry blossom tree that grows branch by branch and blooms, drawn with HTML5 Canvas and vanilla JavaScript.

**Live demo:** https://najmiddinovadilnoza2007-art.github.io/sakura-tree/

## Features
- Recursive branch growth with randomized angles and lengths
- Blossoms that bloom with a smooth easing animation
- Responsive canvas with high-DPI (retina) support
- Click or tap anywhere to grow a new tree

## How it works
1. The trunk starts at the bottom center of the screen.
2. Each branch grows frame by frame, then splits into 2-3 smaller branches.
3. When the maximum depth is reached, blossoms appear at the branch tips.
4. Clicking the canvas restarts the animation.

## Tech stack
- HTML5 Canvas
- JavaScript (`requestAnimationFrame`)
- No libraries or dependencies

## Run locally
Open `index.html` in any modern browser.

## Customization
Edit these constants in `index.html`:
- `GROW_FRAMES` – how many frames each branch takes to grow
- `MAX_DEPTH` – how many times the tree branches
- `COLORS` – blossom color palette

## Author
Dilnoza – [@najmiddinova_dilnoza.01](https://instagram.com/najmiddinova_dilnoza.01)