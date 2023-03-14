# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

This is how the desktop solution looks like 

![](/images/product-preview-solution-desktop.png)

This is how the mobile solution looks like 

![](/images/product-preview-solution-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid

### What I learned

I learned how to use the property <picture> to replace the image of the product depending on the size of the screen

- Here is the code with the most significant thing I've learned doing this challenge 

```html
<div id="productImage">
  <picture>
    <source media="(min-width: 700px)" srcset="images/image-product-desktop.jpg">
    <source media="(max-width: 700px)" srcset="images/image-product-mobile.jpg">
    <img id="image" src="images/image-product-desktop.jpg" alt="">
  </picture>
</div>
```

### Useful resources

- [Converting Colors](https://convertingcolors.com/) - Particullarly I like to call the colors on my CSS code by its HEX code (not always the best choice though). This website converts the code for you from any format you have to any format you like. By now, it is my favorite.

## Author

- Frontend Mentor - [@itsale-o](https://www.frontendmentor.io/profile/itsale-o)
- LinkedIn - [alessandra-santos-oliveira](https://www.linkedin.com/in/alessandra-santos-oliveira/)
- Twitter - [@itsale_o](https://twitter.com/itsale_o) (I don't talk about work there but feel free to follow me)