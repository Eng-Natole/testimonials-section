# Frontend Mentor - Testimonials Grid Section Solution

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![desktop-screenshot](./images/desktop-screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

During this project, I improved my ability to create responsive layouts using **Flexbox** and **CSS Grid**. I also refined my understanding of **media queries** to ensure proper responsiveness.

Here is a snippet of a responsive layout I implemented:

```css
.container {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

@media (min-width: 1440px) {
  .container {
    flex-direction: row;
    max-width: 1500px;
  }
}
```

### Continued development

I plan to explore the following in future projects:

- Improving **accessibility** by implementing ARIA attributes.
- Using **CSS variables** more efficiently for better theme management.
- Experimenting with **CSS animations** to add subtle UI effects.

### Useful resources

- [CSS Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Helped me understand how to structure layouts using Flexbox.
- [MDN Web Docs - Responsive Design](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design) - A great reference for implementing responsive designs.

## Author

- Frontend Mentor - [@Eng-natole](https://www.frontendmentor.io/profile/@Eng-natole)

## Acknowledgments

Big thanks to the Frontend Mentor community for providing helpful feedback and inspiration on similar challenges!
