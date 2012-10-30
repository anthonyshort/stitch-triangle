# Triangle Mixin for Sass

Triangles are pretty rad.

```scss
.dropdown {
  &:before {
    @include triangle($direction: 'bottom', $width: 100px, $height: 50px, $color: black);
  }
}
```

Pretty simple, directions are

* top
* top-right
* right
* bottom-right
* bottom
* bottom-left
* left
* top-left

Then pass a width, height and a color. Pretty easy.

## Install via Bower

```
bower install stitch-triangle
```