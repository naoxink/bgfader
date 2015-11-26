# bgfader
Set your favourite photos in the background of a div

# Demo
Coming soon :)

# Usage
Set the CSS and the JS
```html
<link rel="stylesheet" href="css/bgfader.css">
<script src="js/bgfader.js"></script>
```

Choose the div you want
```html
<div class='header'>
  <p>The greatest content in teh world</p>
</div>
```
Initialize the bgfader
```javascript
var myBgFader = $('.header').bgfader([
  'images/img1.jpg',
  'images/img2.jpg',
  'images/img3.jpg',
  'images/img4.jpg',
], {
  'timeout': 3000,
  'speed': 3000,
  'opacity': 0.4
})

myBgFader.start()
```

And **enjoy** your backgrounds!

## Available options
Name|type|Optional|Default
---|---|---|---
speed|`integer`|Yes|3000
timeout|`integer`|Yes|3000
opacity|`float`|Yes|0.5


## TODO list
- [ ] It explodes with big images (>8Mb~) -> Fade fails first time
- [ ] Images not showing in certain containers
