# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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

- View the optimal layout for the section depending on their device's screen size


### Links

- Solution URL: (https://www.frontendmentor.io/solutions/responsive-page-using-flexbox-and-grid-kEW5aqPt7n)
- Live Site URL: (https://doileo.github.io/social-proof/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

For this challenge I wanted to use intentionally Grid for the desktop layout. Here I needed to use the grid-template-areas to establish the cells in the grid. 

To see how you can add code snippets, see below:

```css
.description-container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr;
    grid-template-areas: "top-left top-right";
    grid-area: description-container;
   }
```

### Continued development

I realize that time from time the use of Grid System is understimated compared to Flexbox. One of the benefit of Grid System is being versatile, and adaptabile in varying combinations of rows and columns. Not to mention that is ideal for responsive layouts.


### Useful resources

- [Example resource](https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-areas) - This is an amazing article which helped me finally understand grid areas. I'd recommend it to anyone still learning this concept.


## Author

- Website - [Doina](https://doileo.github.io/portfolio/)
- Frontend Mentor - [@Doileo](https://www.frontendmentor.io/profile/yourusername)
- LinkedIn - (https://www.linkedin.com/in/doinaleovchindeveloper/)
