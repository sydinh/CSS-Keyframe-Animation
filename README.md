# CSS Animation

## Animation Shorthand

```css
animation: name duration timing-function delay iteration-count direction fill-mode;
```

## Basic Declaration & Usage

### CSS

```css
@-webkit-keyframes NAME-YOUR-ANIMATION {
  0%   { opacity: 0; }
  100% { opacity: 1; }
}
@-moz-keyframes NAME-YOUR-ANIMATION {
  0%   { opacity: 0; }
  100% { opacity: 1; }
}
@-o-keyframes NAME-YOUR-ANIMATION {
  0%   { opacity: 0; }
  100% { opacity: 1; }
}
@keyframes NAME-YOUR-ANIMATION {
  0%   { opacity: 0; }
  100% { opacity: 1; }
}
```

### CSS
```css
#box {
  -webkit-animation: NAME-YOUR-ANIMATION 5s infinite; /* Safari 4+ */
  -moz-animation:    NAME-YOUR-ANIMATION 5s infinite; /* Fx 5+ */
  -o-animation:      NAME-YOUR-ANIMATION 5s infinite; /* Opera 12+ */
  animation:         NAME-YOUR-ANIMATION 5s infinite; /* IE 10+, Fx 29+ */
}
```

## References
* [https://www.w3schools.com/css/css3_animations.asp](https://www.w3schools.com/css/css3_animations.asp)
* [https://css-tricks.com/snippets/css/keyframe-animation-syntax/](https://css-tricks.com/snippets/css/keyframe-animation-syntax/)

## Author
* [A front-end developer with no special talents, only passionately curious.](https://sydinh.github.io/)
