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

Testimonials grid section made using HTML and CSS with CSS Grid.

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](/screenshot.png)
![](/screenshot-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

1. Looking through the design example and start planning how to get my solution to look similar to the design
2. Write the structure of the page using HTML
3. Design the page each section from top to bottom in mobile screen size
4. Write media query for desktop screen size

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to use CSS grid. This is my second challenge using CSS Grid. Quite proud of how it turned out. I do encounter some difficulty especially positioning the whole container in the center.

Other thing that I'm still confused is what unit should i use to set the grid template.

```css
.main-container {
        margin: 0 auto;
        display: grid;
        grid-template-columns: 20% repeat(4, 1fr) 20%;
        grid-template-rows: 8rem 1fr 1fr 8rem;
        gap: 2rem;
}
```

### Continued development

Continue practicing CSS Grid.

### Useful resources

- [Interactive guide to CSS Grid](https://www.joshwcomeau.com/css/interactive-guide-to-grid/) - This amazing article helped me to understand the basic of CSS Grid. It is interactive so it's easier to understand.
- [CSS background position](https://developer.mozilla.org/en-US/docs/Web/CSS/background-position) - This helped me to set the background position of a background image.

## Author

- Website - [Nurika](https://github.com/nunu114)
- Frontend Mentor - [@nunu114](https://www.frontendmentor.io/profile/nunu114)