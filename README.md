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
  - [Continued development](#continued-development)
- [Author](#author)


## Overview
A simple responsive product review card. resizes across multiple pages.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

<figure>
  <img alt="photo of desktop view implementation" src='./images/screenshot.png' height='250px' width='350px'>
  <figcaption>desktop view implementation</figcaption>
</figure>


<figure>
  <img src='./images/Screen Shot 2025-06-06 at 22.13.11.png' width="150px" height="350px">
  <figcaption>mobile view implementation</figcaption>
</figure>




### Links

- Solution URL: [Add solution URL here](https://github.com/NueloSE/product-preview-fm/tree/main)
- Live Site URL: [Add live site URL here](https://product-preview-fm.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I learnt using the <picture> tag to add different photo at different screen sizes

```html
  <picture>
      <source class="product" media="(min-width: 600px)"  srcset="./images/image-product-desktop.jpg" >
      <img class="product" src="images/image-product-mobile.jpg" alt="gabrielle chanel perfume and 2 leafs">
  </picture>
```
```css
:root {
    /* primary colors */
    --green: hsl(158, 36%, 37%);
    --dark-green: hsl(158, 42%, 18%);
}
```


### Continued development
Focus on improving on my responsive design techniques


## Author

- Frontend Mentor - [@nuelose](https://www.frontendmentor.io/profile/nuelose)
- Twitter - [@isnuelo](https://www.twitter.com/isnuelo)

