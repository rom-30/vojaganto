# Vojaganto

![Demo](./img/demo.gif)

[Download the project](https://github.com/rom-30/vojaganto/archive/master.zip) or clone it
```bash
$ git clone git@github.com:rom-30/vojaganto.git
```

## Description
- No Javascript, Custom CSS and HTML only

- [SCSS](https://sass-lang.com/) \- Stylesheet language that’s compiled to CSS
- [Icons from IcoMoon](https://icomoon.io/app/#/select/library) \- SVG Sprite

- [Favicon from gauger.io/fonticon](https://gauger.io/fonticon/)

- [CSS Variables](https://css-tricks.com/difference-between-types-of-css-variables/)
- [BEM](https://en.bem.info/) \- Component-based approach to web development

## If you want to play with it
```bash
$ npm install
$ npm start
```
## To change the overall appearance
```scss
/* sass/_base.scss */
:root {
  --color-primary: cornflowerblue;
  --color-primary-light:  skyblue;
  --color-primary-dark: lightsteelblue;
}
```

## To make good use of the sprite
```html
<svg>
	<use xlink:href="img/sprite.svg#icon-magnifying-glass"></use>
</svg>
```
```bash
# List of SVGs in sprite /img/SVG
├── aircraft-take-off.svg
├── bookmark.svg
├── chat.svg
├── chevron-thin-right.svg
├── home.svg
├── key.svg
├── location-pin.svg
├── magnifying-glass.svg
├── map.svg
└── star.svg
```
##Once you're satisfied and ready to deploy
```bash
$ npm build:css
```
