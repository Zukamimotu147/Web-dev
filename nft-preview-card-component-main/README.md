# Frontend Mentor - NFT preview card component

![Design preview for the NFT preview card component coding challenge](./design/desktop-preview.jpg)

# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Live Site URL: [Vercel Site](https://nft-preview-project.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS positions

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
.time::marker {
    content: url(images/icon-clock.svg);
}

.etherium::marker {
    content: url(images/icon-ethereum.svg);
}

.card-image-overlay {
    position: absolute;
    top: 30%;
    left: 50%;
    transform: translate(-50%, -50%); 
    visibility: hidden;
    border-radius: 10px;
    background-color: hsla(178, 100%, 50%, 0.5);
    height: 300px;
    width: 300px;
}

.card-image:hover .card-image-overlay {
    visibility: visible;
}
```

### Continued development

I want to continue learning CSS positions because the overlay part of the challenge is the hardest to me.


## Author

- GitHub - [Zukamimotu147](https://github.com/Zukamimotu147?tab=repositories)
- Frontend Mentor - [@Zukamimotu147](https://www.frontendmentor.io/profile/Zukamimotu147)

