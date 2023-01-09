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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./images/Screenshot%202023-01-09%20at%205.31.40%20PM.png)
![](./images/Screenshot%202023-01-09%20at%205.31.54%20PM.png)

### Links

- Solution URL: [My GitHub](https://github.com/VSandwar74/vite-testimonials-cssgrid)
- Live Site URL: [My Live Site!](https://hilarious-pika-f500d0.netlify.app/)

## My process

### Built with

- Vite
- CSS custom properties
- CSS Grid

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned


To see how you can add code snippets, see below:

This was my first deep dive into CSS grid, etc.

```css
.grid {
  position: absolute;
  width: 80%;
  top: 15%;
  bottom: 15%;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr;
  grid-template-areas: 
    "dan dan jon kira"
    "jean pat pat kira";
  column-gap: 25px;
  row-gap: 25px;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [CSS Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - This was super helpful for my first exploration into css grid.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Frontend Mentor - [@VSandwar74](https://www.frontendmentor.io/profile/VSandwar74)

