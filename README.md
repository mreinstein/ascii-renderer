# ascii-renderer
Simple, performant, crisp ascii rendering via canvas or dom elements

There are 2 renderers:
 * canvas-renderer: uses an HTML canvas element and a sprite font to render an ascii grid
 * dom-renderer: uses individual divs to represent each cell in the grid


The canvas renderer is a lot more performant for large grids, but the dom renderer is interesting in that each of the cells could be styled with css.


The canvas render borrows a lot of logic, inspiration and sprite font from  https://github.com/munificent/malison

## installation

```bash
npm install
```

to run the demo:

```bash
npm start
open http://localhost:5000
```
