# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/images/screen.PNG)


### Links

- Solution URL: [Solution URL ](https://github.com/pnrmmt/frontendmentor-newbie4)
- Live Site URL: [Live site URL here](https://pnrmmt.github.io/frontendmentor-newbie4/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to create image overlay hover effects.


```css
.eq-img{
    position: relative;
}

.eq-img div{
    position: absolute;
    background-color:hsl(178, 100%, 50%, 75%); 
    width: 100%;
    height: calc(100% - 24px);
    z-index: 999;
    border-radius: 14px;
    top:0;
    opacity:0;
    transition: opacity 0.5s;
}
.eq-img div:hover{
  opacity: 1;
  cursor: pointer;
}
.eq-img div img{
   position: absolute;
   left:50%;
   top:50%;
   transform: translate(-50%,-50%);
}
```


## Author

- Frontend Mentor - [@pnrmmt](https://www.frontendmentor.io/profile/pnrmmt)


