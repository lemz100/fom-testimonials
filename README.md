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

### Links

- Live Site URL: (https://ubiquitous-choux-10391c.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```css
.testimonials {
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        grid-template-rows: 1fr 1fr;
        max-width: 85%;
    }
    .testimonial {
        max-width: fit-content;
    }
    .purple {
        grid-column: 1 / 3;
    }
    .kira {
        grid-row: 1 / 3;
    }
    .jeanette, .darkblue {
        grid-row: 2 / 3;
    }
    .darkblue {
        grid-column: 2 / 4;
    }

  - max-width: 85% to constrain testimonial container
  - set testimonial grid placement using grid-row/grid-column.
```

### Continued development

Strengthen grid skills
Strengthen responsive design skills

## Author

- Frontend Mentor - [@lemz100](https://www.frontendmentor.io/profile/lemz100)
