
## Anime.js

#### Documentation

1.Official documentation  https://animejs.com/documentation/#cssSelector
2. https://www.sitepoint.com/get-started-anime-js/
3. Medium article https://medium.com/@ajmeyghani/creating-javascript-animations-with-anime-js-f2b14716cdc6


#### Codepen

1.Hand written SVG text animation https://codepen.io/mellis84/pen/JpVZNw2
2.Back2School SVG Animation w/ anime.js https://codepen.io/Yasio/pen/wEWyLE


### Notes

Yo create an animation, we use the anime() function, which takes an object as an argument. 

```
let myAnimation = anime({
  /* describe the animation details */
});
```


There are several kinds of properties used to describe the animation. They are grouped into four distinct categories:

 - Targets – this includes a reference to the element(s) we want to animate. It could be a CSS selector (div, #square, .rectangle), DOM node or js object. 
 - Animatable Properties – height, opacity, color, translateX etc
 - Property Parameters –  duration, delay, easing, etc.
 - Animation Parameters – this includes animation-related parameters like direction, loop, etc.

```
let animation = anime({
  targets: 'div',
  // Properties 
  translateX: 100,
  borderRadius: 50,
  // Property Parameters
  duration: 2000,
  easing: 'linear',
  // Animation Parameters
  direction: 'alternate'  (3 direction parameter : normal, reverse, and alternate. )
});  
```
