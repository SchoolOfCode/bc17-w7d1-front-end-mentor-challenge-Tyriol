# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshots

Mobile View

<img src="./images/Screenshots/Screenshot 2024-08-11 120522.png" alt="Mobile View" width="300"/>

Desktop View

<img src="./images/Screenshots/Screenshot 2024-08-11 120534.png" alt="Desktop View" width="400"/>

Desktop View with active button

<img src="./images/Screenshots/Screenshot 2024-08-11 120545.png" alt="Desktop View Active button" width="400"/>

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Once you've completed the styling for a specific view (perhaps mobile), adjusting it for other sizes is pretty straightforward.
Using Grid and Flex is becoming a lot more intuitive as well now for me

```css
@media (max-width: 375px) {
  .container {
    height: auto;
    display: grid;
    grid-template-rows: 175px 1fr;
    width: 250px;
    margin: auto;
  }

  .desktop-img {
    display: none;
  }

  .mobile-img {
    width: 100%;
    border-top-left-radius: 0.5em;
    border-top-right-radius: 0.5em;
  }

  section {
    border-bottom-left-radius: 0.5em;
    border-bottom-right-radius: 0.5em;
  }
}
```

## Author

- Frontend Mentor - [@Tyriol](https://www.frontendmentor.io/profile/Tyriol)
- X - [@Kirisin](https://x.com/Kirisin)
