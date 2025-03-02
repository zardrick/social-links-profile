# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Desktop View](./design/desktop-design.jpg)  
![Mobile View](./design/mobile-design.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/zardrick/social-links-profile)
- Live Site URL: [Live Demo](https://zardrick.github.io/social-links-profile/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

One of the key things I practiced in this challenge was centering a div using `display: flex` and utilizing `object-fit: cover` for the profile image. Here’s an example:

```css
.profile-picture img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

This ensures the image fits nicely within the circular frame without distortion.

### Continued development

In future projects, I want to focus more on:
- Improving accessibility for screen readers.
- Enhancing responsiveness using CSS Grid and Flexbox together.
- Using CSS animations for better user experience.

### Useful resources

- [CSS Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me understand flexbox better and apply it efficiently.
- [MDN Web Docs - Object Fit](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit) - Helped me ensure images are properly fitted inside their containers.

## Author

- Frontend Mentor - [@Zardrick](https://www.frontendmentor.io/profile/Zardrick)

## Acknowledgments

Shoutout to the Frontend Mentor community for the inspiration and motivation to complete this challenge!

