# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshots/Screenshot%202025-02-18%20at%2011-25-11%20Frontend%20Mentor%20Blog%20preview%20card.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/gabriel-de-azevedo/blog-preview-card-main)
- Live Site URL: [GitHub Page](https://gabriel-de-azevedo.github.io/blog-preview-card-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I used `em` as the main unit for all my sizes, paddings and gaps.

I heard that it was a good idea but never experienced the advantages before. Mainly when it comes to components, it makes resizing the whole design a lot easier. I managed to resize the whole card with a single property:

```css
@media (max-width: 25rem) {
  .article-card {
    font-size: 0.8rem;
  }
}
```

Pretty neat!

## Author

- GitHub - [gabriel-de-azevedo](https://github.com/gabriel-de-azevedo)
- LinkedIn - [gabriel-marques-de-azevedo](https://www.linkedin.com/in/gabriel-marques-de-azevedo/)
- Frontend Mentor - [@gabriel-de-azevedo](https://www.frontendmentor.io/profile/gabriel-de-azevedo)
