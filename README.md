# FAQ accordion card - Frontend Mentor Challenge

This is a solution to the [FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

![Design preview for the FAQ accordion card coding challenge](./design/desktop-preview.jpg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Links

- Live Site URL: [github.io](https://yoniakabecky.github.io/mini-projects-1/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

Had an idea making accordion without JS but details were missing. It was good recap what I leaned before.

```html
<input type="radio" name="select" class="accordion-selector" />
```

```css
.accordion-selector:checked ~ .answer {
  opacity: 1;
  padding-bottom: 1rem;
  height: auto;
}
```

### Useful resources

- [Accordion Slider Generator](https://accordionslider.com/) - Got some idea from here.
