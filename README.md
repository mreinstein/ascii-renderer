# ascii-renderer
Simple, performant, crisp ascii rendering via canvas or dom elements


NOTE: this code represents exploration I did around how to minimally render ascii grids with some different implementations. You're probably better of using rot.js, which is a lot more robust and featureful. 

https://github.com/ondras/rot.js

## available renderers

 * canvas-renderer: uses an HTML canvas element and a sprite font to render an ascii grid
 * dom-renderer: uses individual divs to represent each cell in the grid


The canvas renderer is a lot more performant for large grids,

The dom renderer is interesting in that each of the cells could be styled with css.


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
