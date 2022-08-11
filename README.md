# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![screenshot](./screenshot_doHoaSen.png)



### Links

- Solution URL: [solution URL](https://github.com/doHoaSen/challengeFrontend-testimonials-grid-section-main)
- Live Site URL: [live site URL](https://dohoasen.github.io/challengeFrontend-testimonials-grid-section-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned
- How to use CSS Grid and Flexbox
- How to insert SVG to background of div and control it
- Understand padding and margin more specific
- How to make reactive website by media query more specific


To see how you can add code snippets, see below:

```css
@media all and (min-width: 1024px) {
  .grid-container{
    display: inline-grid;
    grid-gap: 1rem;
    padding: 1rem;
    line-height: 1.3;
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: 1fr 1fr;
    grid-template-areas: "Daniel Daniel Jonathan Kira"
                         "Jeanette Patrick Patrick Kira";

  }
```

```css
.Daniel{
  grid-area: daniel;
  background-color: hsl(263, 55%, 52%);
  background-image: url("data:image/svg+xml,%3Csvg width='104' height='102' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M104 102V59.727H84.114c0-5.871.689-11.182 2.068-15.933 1.379-4.75 3.42-9.287 6.125-13.61C95.01 25.86 98.909 22.257 104 19.375V0c-9.758 4.27-17.712 9.874-23.864 16.813-6.151 6.939-10.712 14.545-13.681 22.818C63.485 47.904 62 59.941 62 75.74V102h42zm-62 0V59.727H22.114c0-5.871.689-11.182 2.068-15.933 1.379-4.75 3.42-9.287 6.125-13.61C33.01 25.86 36.909 22.257 42 19.375V0c-9.652 4.27-17.58 9.874-23.784 16.813C12.01 23.752 7.424 31.358 4.455 39.631 1.485 47.904 0 59.941 0 75.74V102h42z' fill='%23A775F1' fill-rule='nonzero'/%3E%3C/svg%3E");
  background-repeat: no-repeat;
  background-position: right top;
  color: white;
}



### Continued development

- Know details about CSS Grid and use it with Flex box to layout web pages.



## Author

- Website - [doHoaSen]https://github.com/doHoaSen)
- Frontend Mentor - [@doHoaSen](https://www.frontendmentor.io/profile/doHoaSen)

