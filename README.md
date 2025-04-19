# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Overview

This project is part of the Frontend Mentor challenge, which aims to create a responsive Four Card Feature Section. In this challenge, you will create a layout with four cards that display an image, title, and a short description of the feature or service offered. These cards must be able to adapt to different screen sizes (responsive), and have an interactive effect when hovered by the user.

### The Challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![MObile Version](<./images/Screenshot (29).png>)

![Desktop Version](<./images/Screenshot (30).png>)

### Links

- Live Site URL: [Github Pages](https://haese-hks.github.io/four-card-feature-section/)

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/responsive-four-card-feature-using-css-grid---vanilla-css-S_gzqG9vTa)

### My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I Learned

what i learned in this project is how to use css grid and pseudo ::before

```css psuedo ::before
.card::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  height: 4px;
  width: 100%;
  border-top-left-radius: 0.5rem;
  border-top-right-radius: 0.5rem;
  background-color: var(--blue);
}
```
```css grid
  .feature-cards {
    max-width: 100%;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
  }
```

### Continued Development

next i will improve the ::before and ::after psuedo because this is very important for css animations

### Useful Resources

- [freeCodeCamp](https://www.freecodecamp.org/):
  
- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
  
- [W3Schools - CSS](https://www.w3schools.com/css/)

- [Frontend Mentor - Blog Preview Card Challenge](https://www.frontendmentor.io/challenges/blog-preview-card-ryaPa2l8M)

- [Google Fonts](https://fonts.google.com/)

- [CSS-Tricks - Transform](https://css-tricks.com/almanac/properties/t/transform/)

- [GitHub Pages Documentation](https://docs.github.com/en/pages)

### Author

- Git Hub: [@haese-hks](https://github.com/haese-hks)
- Frontend Mentor: [@haese-hks](https://www.frontendmentor.io/profile/haese-hks)
- X - [@haese_hks](https://x.com/haese_hks)

### Acknowledgments

- Thanks to [Frontend Mentor](https://www.frontendmentor.io) for providing the challenge and design files.
- Big thanks to the [freeCodeCamp](https://www.freecodecamp.org) community for all the learning resources and tutorials.
- Special thanks to [CSS-Tricks](https://css-tricks.com) for their helpful guides and tutorials on CSS.
- Shout out to the [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS) for being an incredible resource for understanding web technologies.
