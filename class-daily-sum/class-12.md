# Canvass and overview

Like other html elements it has an `Id=""` attribute and can have fallback content ascribed to it. If no styling has been applied, it will appear transparent at first. other attributes are similar to the img and video tags. 

you can run a script to check for browser suport by checking for the `getContext();` method.
below is a short list of basic functions associated with `<canvas>`

- `fillRect(x, y, width, height);`
- `strokeRect(x, y, width, height);`
- `clearRect(x, y, width, height);`
- `draw();`
- `beginPath();`
  - `closePath();`
  - `stroke();`
  - `fill();`
- `moveTo(x,y,);` this is used much like moving a *pen* and  is very useful when dealing with drawing paths.  

many other methods come into play when using canvas and can be found on [MDN web Docs](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes) 