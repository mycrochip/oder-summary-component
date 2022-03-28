# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![Product screenshot](images/osc-screenshot.jpg)


### Links

- Solution URL: [https://github.com/mycrochip/oder-summary-component](https://github.com/mycrochip/oder-summary-component)
- Live Site URL: [https://mycrochip.github.io/oder-summary-component/](https://mycrochip.github.io/oder-summary-component/)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I was so proud to be using a grid layout within a flex layout. Though, I could have gone with just grid; I don't want to pick sides yet in the never-ending grid/flex war.

```css
.flex-column {
    display: flex;
    flex-direction: column;
    justify-content: center;
    justify-items: center;
}

.grid-column {
    display: grid;
    grid-template-columns: 1fr 2fr 1fr;
    align-items: center;
    justify-items: center;
    grid-template-areas: "a b c";
}

.price {
    line-height: 1.5;
    grid-area: b;
    justify-self: start;
}
```

I also had my mind open after using the code below to solve one of my layout problems (overflow specifically).

```css
/* The hero image almost broke me */
.hero-container {
    border-radius: 1em 1em 0 0;
    -moz-border-radius: 1em 1em 0 0;
    height: auto;

    /*This saved me a lot of image problems
    ...and allowed the image to be clipped, 
    ...so as to inherit rounded corners*/
    overflow: hidden;
}
```

### Continued development

A usual, I will continue to take on more challenges on [FrontentMentor](https://www.frontendmentor.io). I am gaining a wealth of experience just imagining that I am delivering my projects to a client. I try to make them picture-perfect to the specifications.

### Useful resources

- [Ally 101](https://a11y-101.com/design/button-vs-link) - This helped me learn more about the use cases for buttons and links, though I'm not sure if I applied the knowledge appropriately in my project. I, however, appreciate such content because I value foolwing best coding practices and using semantic code (html, css).
- [W3Schools](https://www.w3schools.com) and [MDN](https://developer.mozilla.org) are constants for me.


## Author

- Frontend Mentor - [@mycrochip](https://www.frontendmentor.io/profile/mycrochip)
- Twitter - [@mycrochip_world](https://www.twitter.com/mycrochip_world)
