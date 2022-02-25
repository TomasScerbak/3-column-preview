# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size (project was build only for 375px and 1440px)
- See hover states for interactive elements

### Links

- Live Site URL: (https://tomasscerbak.github.io/3-column-preview/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- BEM convention
- Mobile-first workflow
  
### What I learned
```HTML
Semantic TAGs
    <main></main>

Using BEM convention
          <div class="box box--one">
            <img class="card__image" src="Images/icon-sedans.svg" alt="car" />
            <h1 class="card__heading">Sedans</h1>
            <div>
```

```CSS
How to use FLEXBOX
            .container {
              display: flex;
              flex-direction: column;
              align-items: center;
              justify-content: center;
              margin: 5rem 2rem;
            }

New border box properties for individual boxes
             .box--one {
               background-color: var(--color-bright-orange);
               border-top-left-radius: 10px;
               border-top-right-radius: 10px;
              }
```

### Continued development

I will keep practicing HTML best practicies, learning and sorting accessibility issues. Continue learning FLEXBOX capabilities.

## Author

- Website - [Tomas Scerbak](https://tomasscerbak.github.io/tomas-scerbak-portfolio/)
- Frontend Mentor - [@Potato](https://www.frontendmentor.io/profile/TomasScerbak)
