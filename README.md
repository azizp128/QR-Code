# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

![Design preview for the QR code component coding challenge](./design/desktop-preview.jpg)

### Screenshot

![SCREENSHOT](./screenshot/full-page.png)

### Links

- Solution URL: [SOLUTION](https://www.frontendmentor.io/solutions/responsive-qr-code-component-using-css-properties-and-flexbox-lKD3zI6GdU)
- Live Site URL: [LIVE SITE](https://azizp128.github.io/QR-Code/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox

### What I learned

I learned new properties such as min-width, box-shadow, align-items, and transition. Most of the properties are from CSS Flexbox.

The code snippets are below:

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 5%;
}
```

```css
.card {
  max-width: 285px;
  background-color: white;
  border-radius: 20px;
  box-shadow: 5px 15px hsl(217, 8%, 61%, 0.05);
  padding: 13px;
}
```

```css
.card-img {
  max-width: 100%;
  border-radius: 10px;

  background: #2c7dfa;
  transition-duration: 1s;
  transition-property: background, transform;
  transition-timing-function: cubic-bezier(1, 0.11, 22, 1.41);
}

.card h1:hover {
  color: #2c7dfa;
}

.card p:hover {
  color: black;
}

.card-img:hover {
  transform: rotate(90deg);
}
```

### Continued development

I'm going to improve my Layout and Flexbox skills first and then move to learn about CSS Grid.

## Author

- Frontend Mentor - [@azizp128](https://www.frontendmentor.io/profile/azizp128)
- Twitter - [@azizprbw](https://www.twitter.com/azizprbw)
