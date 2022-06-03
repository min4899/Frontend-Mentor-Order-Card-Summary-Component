# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [GitHub](https://github.com/min4899/Frontend-Mentor-Order-Summary-Card-Component)
- Live Site URL: [GitHub Pages](https://min4899.github.io/Frontend-Mentor-Order-Summary-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

Learned how to use clamp inside card elements to have responsive layout. For this case, padding is reduced as screen width gets smaller so there are less empty spaces. Description text area also gets smaller to match design layout.

```css
.text-area {
  text-align: center;
  padding: clamp(2.5rem, 8vw, 3rem) clamp(1.35rem, 5.5vw, 2.8rem) clamp(2rem, 8vw, 2.5rem);
  gap: 1.6rem;
}

.description {
  max-width: clamp(16.45rem, 40vw, 19rem);
}
```

### Continued development

After multiple challenges, I'm now fairly confident in using Flexbox. For future challenges, I'd like to learn how to use Grid.

### Useful resources

- [Documentation for CSS clamp function](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp) - Property values for clamp
- [CSS box-shadow Property](https://www.w3schools.com/cssref/css3_pr_box-shadow.asp) - Property values for box-shadow

## Author

- GitHub - [Minwoo Soh](https://github.com/min4899)
- Frontend Mentor - [@min4899](https://www.frontendmentor.io/profile/min4899)