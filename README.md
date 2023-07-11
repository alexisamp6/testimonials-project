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
Your challenge is to build out this testimonials grid section and get it looking as close to the design as possible.

You can use any tools you like to help you complete the challenge. So if you've got something you'd like to practice, feel free to give it a go.

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](![Screenshot of my testimonials grid section coding challenge](<images/ Frontend-Mentor-Testimonials/screenshot.jpg>)

### Links

- Solution URL: [Solution for the challenge](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Web-first workflow

### What I learned

```css
.card:nth-of-type(1) {
  grid-column: 1 / 3;
}

.card:nth-of-type(4) {
  grid-column: 2 / 4;
  grid-row: 2 / 3;
}
.card:nth-of-type(5) {
  grid-column: 4 / 5;
  grid-row: 1 /3;
}

@media (max-width: 768px) {
  .testimonials {
    grid-template-columns: 1fr;
    width: 100%;
  }
  .card:nth-of-type(1) {
    grid-column: 1 / 2;
  }

  .card:nth-of-type(4) {
    grid-column: 1;
    grid-row: 4;
  }
  .card:nth-of-type(5) {
    grid-column: 1;
    grid-row: 5;
  }
}
```

### Continued development
I have just recently started learning these topics, but I want to work on more projects that use flexbox,grid, and responsive design to strengthen my knowledge of them. 

## Author
- Frontend Mentor - [@alexisamp6](https://www.frontendmentor.io/profile/alexisamp6)
