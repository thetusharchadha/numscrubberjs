# Numscrubber.js

>Let's change values of input numbers by dragging the mouse left & right


### Install

Include numscrubber.js file
```html
<script src="src/numscrubber.js"></script>
```
or use CDN
```html
<link rel="stylesheet" href="https://cdn.rawgit.com/mburakerman/numscrubberjs/master/src/numscrubber.js">
```

### Usage

Just add ```data-numscrubber``` to your input number  

```html
<input data-numscrubber type="number" value="6" min="4" max="50" />
```
and then call  ```init()```

```js
<script>
    Numscrubber.init();
</script>
```
Thats it!

[CodePen demo](http://codepen.io/anon/pen/zZwZpJ)

![CodePen demo](https://media.giphy.com/media/l0IygGSCTG9xhArXW/giphy.gif)

### Size

1.2 kb minified

### License

Licensed under the MIT License.
