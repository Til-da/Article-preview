# Frontend Mentor - Article preview component solution

This is a solution to the [Article preview component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/article-preview-component-dYBN_pYFT). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See the social media share links when they click the share icon

### Links

- Live Site URL: [Add live site URL here](https://680a09b0cc383f7556ab6562--tourmaline-arithmetic-70df0b.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Media queries
- Google fonts [Manrope](https://fonts.google.com/specimen/Manrope)
- Javascript
- DOM manipulation


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:


```js

mobileShareBtnContainer.addEventListener("click", function(){

    mobileAuthorArea.style.display = "none"
    mobileSocialSharingBar.style.display = "flex"
})

const mobileShareBtn = document.querySelector(".mobile-social-share-btn")

mobileShareBtn.addEventListener("click", function(){
    mobileAuthorArea.style.display = "flex"
    mobileSocialSharingBar.style.display = "none"
})

```


### Continued development

- DOM Manipulation
- Javascript


## Author

- Frontend Mentor - [@Til-da](https://www.frontendmentor.io/profile/Til-da)

