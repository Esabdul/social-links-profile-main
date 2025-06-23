# Frontend Mentor - Social links profile solution

This is my solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

---

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

---

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover, active, and focus states for all interactive elements

### Screenshot

<-- Screenshot will be added soon-->

### Links

- **Solution URL:** [https://esabdul.github.io/social-links-profile-main/]
- **Live Site URL:** [https://esabdul.github.io/social-links-profile-main/]

---

## My process

### Built with

- Semantic **HTML5**
- **CSS custom properties** (variables)
- **Flexbox**
- **Responsive media queries**
- **Mobile-first workflow**
- **Accessible focus states**
- Plain **Vanilla CSS** (no frameworks)

### What I learned

This challenge helped me:

- Understand how to build **mobile-first responsive layouts**
- Use `:focus-within` and `:active` states effectively
- Improve accessibility with keyboard navigation support
- Structure CSS using custom variables for consistency

#### Example code

```css
.social-links li:hover {
  background-color: var(--color-green);
}

.social-links li:active {
  transform: scale(0.98);
}

.social-links li:focus-within {
  outline: 2px solid var(--color-green);
  outline-offset: 4px;
}
```
### Continued development

In future projects, I want to:

- Learn more about `:focus-visible` and accessibility best practices
- Improve transition/animation usage for smoother interactions
- Practice layout building using **CSS Grid**

---

### Useful resources

- [MDN Web Docs – CSS Pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes) – Clear explanations and examples for hover, focus, active, etc.
- [Kevin Powell on YouTube](https://www.youtube.com/kepowob) – Amazing CSS tutorials that helped reinforce my understanding of layout and responsiveness.
- [The Markdown Guide](https://www.markdownguide.org/) – Helped me structure and format this README.

---

## Author

- Frontend Mentor – [@Esabdul](https://www.frontendmentor.io/profile/Esabdul)
- GitHub – [@Esabdul](https://github.com/Esabdul)

---

## Acknowledgments

Thanks to [Frontend Mentor](https://www.frontendmentor.io/) for the challenge.
