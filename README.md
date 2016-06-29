---
# Random-Graph-JS
---

A simple JS extension that draws random graph following mouse movements.

### Demo 

Find the demo [here](http://jsfiddle.net/MrL1605/aLxo3o6c/1/embedded/result,js,html,css/light/)

### How to add

 - Add the [script](./draw-graph.js) to head tag of the page
 - Create a canvas with id as graph_canvas.
 - Add jquery to the page for proper size detection.
 - And... Done.

> **Note:** Jquery is only required for setting the size of canvas context 3, 4. If not required set the size manually.

### Customize

 - Change the `createRadius` variable to decide how far the graph should be created after every mouse move.
 - Change the `maxAllowedRadius` variable to decide the distance after which a node in graph shouls be deleted.
 - Change the color and line width by changing `context.strokeStyle` and `context.lineWidth`.

### LICENSE
[LICENSE](./LICENSE)
