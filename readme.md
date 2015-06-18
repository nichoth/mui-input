#mui input

Material-esque text input implemented with sass, no javascript. [Demo](https://1c2a9482e1108db7a3d6ed2d0c39e4c4c1e2d7cf.htmlb.in)

## Install

    $ bower install mui-input

## Example

Markup
```html
<div style="width:50%">
  <input class="my-input" type="text" placeholder="example">
</div>
```

Sass
```sass
@import "bower_components/mui-input/mui-input";
.my-input {
  @extend %mui-input;
}
```

