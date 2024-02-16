# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Links

- Solution URL: [Github](https://github.com/jrc17/recipe-page-main)
- Live Site URL: [Website](https://jrc17.github.io/recipe-page-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Bootstrap 5](https://getbootstrap.com/) - Frontend Framework

### What I learned

This is my first webpage built using Bootstrap. Using bootstrap helped make some components faster to build.

```html
<div class="row px-5 py-4">
  <div class="border-bottom py-3 intr">
    <h1 class="mb-3">Simple Omelette Recipe</h1>
  </div>
</div>
```

```html
table class="table">
<tr class="table-borderless">
  <td class="category">Calories</td>
  <td class="value">277kcal</td>
</tr>
```

I learnt about the ::marker pseudo-element in css and differnt ways to stylize the points for list.

```css
ul li:before {
  content: "·";
  font-size: 1.5rem;
  vertical-align: middle;
  line-height: 20px;
  padding-right: 2rem;
  padding-left: 0;
  color: hsl(332, 51%, 32%);
}
```

```css
ol li::marker {
  font-weight: 600;
  color: hsl(14, 45%, 36%);
}
```

### Useful resources

- [Bootstrap](https://www.youtube.com/watch?v=-qfEOE4vtxE) - This video provided a comprehensive overview of Bootstrap components and demonstrated their usage.

- [style list style](https://stackoverflow.com/questions/7990429/how-to-control-size-of-list-style-type-disc-in-css) - different ways to style lists as discussed on Stack Overflow.

- [::marker](https://developer.mozilla.org/en-US/docs/Web/CSS/::marker) - Mozilla Developer Network documentation on the CSS ::marker pseudo-element for styling list item markers in ordered and unordered lists.

## Author

- Frontend Mentor - [@jrc17](https://www.frontendmentor.io/profile/jrc17)
