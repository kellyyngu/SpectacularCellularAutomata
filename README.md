# Spectacular Cellular Automata

Originally created as a Software Engineering Group Project (SEGP) at the University of Nottingham, this project is now open-sourced for the community to explore and build upon. Please note that it is not under active development.

## Overview

- Simulate 2D cellular automata and visualize them on 3D mesh surfaces.
- Supports real-time rendering on dynamically generated spheres and tori.
- Try it out locally or visit the live demo on GitHub Pages.
- Licensed under the Mozilla Public License 2.0.

## Features

- GPU-accelerated rendering for both 2D and 3D views, with customizable graphics options.
- Interactive grid editor with drawing capabilities.
- Four distinct rule sets for cellular automata.
- Adjustable simulation speed, pause/play controls, and single-step mode.

## Controls

- Rotate the 3D view by dragging with the left or right mouse button.
- Zoom in and out using the scroll wheel in both 2D and 3D modes.
- Toggle cell states by clicking; click and drag to modify multiple cells at once.
- Switch between view modes using the pencil icon in the top left corner.
- Change the mesh shape with the shape icon in the top left corner.

## Getting Started

1. Install dependencies:
   ```
   npm install
   ```
2. Start the development server:
   ```
   npm run dev
   ```

## Building & Deployment

- Build the project for production:
  ```
  npm run build
  ```
  The output will be in the `dist/` directory, ready to be served by any web server.
- To preview the production build locally:
  ```
  npm run preview
  ```

Feel free to explore, modify, and share your own versions!
