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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Screenshot of completed design](./design/Screenshot%20of%20Completed%20Frontend%20Mentor%20Testimonials%20Grid%20Section.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/Ankia-Fuls/fem-testimonial-grid)
- Live Site URL: [GitHub Pages](https://ankia-fuls.github.io/fem-testimonial-grid/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- SASS Styling

### What I learned

I practiced how to use CSS Grid to create the responsive bento grid layout.

I also set the tabindexes for the different sections to be more accessible and added screenreader only text in front of the names of the reviewers to make it read more fluidly for screenreaders.

```css
.sr-only {
    position: absolute;
    width: 1px;
    height: 1px;
    margin: -1px;
    padding: 0;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    white-space: nowrap;
    border: 0;
}
```

### Continued development

I would like to keep practicing how to make websites more reactive and more accessible as I go. Some of the colors and fonts in the design don't completely match the original design, so I would like to come back in the future to fix it.

### Useful resources

- [Screenreader Only code](https://dev.to/ibn_abubakre/hiding-elements-in-css-the-accessible-way-5h1b) - This helped me understand how to use screenreader only elements to add more accessibility into my websites.

## Author

- Frontend Mentor - [@Ankia-Fuls](https://www.frontendmentor.io/profile/Ankia-Fuls)
- GitHub - [@Ankia-Fuls](https://github.com/Ankia-Fuls)