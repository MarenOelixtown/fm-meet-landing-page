# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/assets/meet-landing-page_screenshot.png)

### Links

- Live Site URL: [Meet - Landingpage / Vercel deployment](https://fm-meet-landing-page-alpha.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

👉 First time that I used the 'background-image' with the linear-gradient and also first time I created a section devider like this.

👉 I liked using the picture-element in this way for the desktop media-query without css. Using the picture-element and the srcset attribute also ensures that only the necessary images are loaded depending on the screen size.

👉I tried to get a smooth transition between the different output sizes. With trial and error I came to the conclusion that if you give an element a max-width and centre it with margin-left and margin-right ‘auto’, you could already achieve a lot. In addition, clamp()-function helped me not only with font-sizes, but also with the scaling of images and spacing.

### Continued development

🔎 In the future, I would also like to learn more about tricks and tips for smooth transitions between different output devices to achieve a responsive design.

### Useful resources

- [background-image](https://developer.mozilla.org/en-US/docs/Web/CSS/background-image) - This helped me for designing the footer-background.
- [background-blend-mode](https://developer.mozilla.org/en-US/docs/Web/CSS/background-blend-mode) - I didn't use it this time, but saw the possibilities of the different effects.

## Author

- Frontend Mentor - [@Maren Oelixtown](https://www.frontendmentor.io/profile/MarenOelixtown)
