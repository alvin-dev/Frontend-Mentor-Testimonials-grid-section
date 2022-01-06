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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot


[Desktop](./design/screenshots/desktop.png) <br>
[Mobile](./design/screenshots/mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

- structure Grid layout
- grid-template-areas
- grid-area

```css
.container {
  display: grid;
  gap: 1.5rem 2rem;
  grid-template-columns: repeat(4,  1fr);
  grid-template-areas: 
    "daniel daniel jonathan kira"
    "jeanette patrick patrick kira"
    "footer footer footer footer";
}

.kira{
  grid-area: kira;
}
```

### Useful resources

- [origamid](https://www.origamid.com/projetos/css-grid-layout-guia-completo/) - Site about rules CSS Grid.
- [Desvendando o CSS Grid na prática](https://www.youtube.com/watch?v=HN1UjzRSdBk) - Video explaining CSS Grid building a layout.

## Author

- GitHub - [@alvin-dev](https://github.com/alvin-dev)
- Frontend Mentor - [@alvin-dev](https://www.frontendmentor.io/profile/alvin-dev)
- Instagram - [@alvaro_guedes_](https://www.instagram.com/alvaro_guedes_/)

