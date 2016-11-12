# JS Canvas Pinch Effect

[Pinch/pucker an image in canvas (StackOverflow)](http://stackoverflow.com/questions/33402497/pinch-pucker-an-image-in-canvas)

An attempt at imitating the pinch effect on canvas. The desired effect is the one in Gimp or glfx.js. Photoshop one is okay.

glfx.js is using WebGL. I can't reproduce the same effect using JS, because I have no WebGL knowledge.

```javascript
function pinch(canvas, x, y, radius, strength) {
	// code
	return pinchedCanvas;
}
```

![Pinch Effect Comparison](https://raw.githubusercontent.com/akinuri/canvas-pinch/master/pinched%20images/_comparison.jpg)