# Frontend Mentor - Recipe Page Solution

This is my solution to the [Recipe Page Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). This project helped me improve my CSS layout skills using Grid and Flexbox while following a mobile-first approach.

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Links

- Solution URL: [Github Repo](https://github.com/Enilolade/recipe-page)
- Live Site URL: [Recipe Live Site](https://enilolade.github.io/recipe-page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Flexbox
- Mobile-first workflow

### What I learned

During this project, I improved my understanding of CSS Grid for structuring layouts and Flexbox for aligning elements. I also practiced using media queries for responsiveness. Here’s an example of how I structured my grid layout:

```css
.container {
  display: grid;
  grid-template-rows: 10rem 1fr;
  grid-template-columns: 1fr;
  width: 100%;
}
```

Additionally, I refined my use of `background-image` to properly display the header image:

```css
.header-image {
  background-image: url(./assets/images/image-omelette.jpeg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
```

### Continued development

I want to further explore:

- Enhancing accessibility by improving contrast and adding ARIA attributes.
- Experimenting with more advanced CSS animations and transitions.
- Using CSS variables more effectively for easier theme management.

### Useful resources

- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - Helped me understand CSS Grid better.

## Author

- Frontend Mentor - [@Enilolade](https://www.frontendmentor.io/profile/Enilolade)
