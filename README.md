# Frontend Mentor - Profile card component solution

https://github.com/Djokaras/profile-card-component.git Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- Build out the project to the designs provided

### Screenshot

![](./design/desktop-preview.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/flexbox-Q9vD-8rPa/](https://www.frontendmentor.io/solutions/flexbox-Q9vD-8rPa/)
- Live Site URL: [https://djokaras.github.io/profile-card-component/](https://djokaras.github.io/profile-card-component/)

## My process

Started with mobile first approach. Had some trouble with background image positioning. Flexbox for card layout.

### Built with

- HTML
- CSS flexbox
- Absolute positioning for profile picture

### What I learned

Learned how to position background image in the body. Had troubles untill I realised that body element had no height.

```css
body {
	background-position: right 45vw bottom 60vh, left 55vw top 30vh;
	background-repeat: no-repeat;
	background-color: hsl(185, 75%, 39%);
	height: 100vh;
}
```

### Continued development

Should work more on HTML as I feel like here is overcomplicated.

### Useful resources

https://www.youtube.com/watch?v=3T_Jy1CqH9k&t=508s&ab_channel=KevinPowell

## Author

- Website - [Djordje Stevic](https://www.your-site.com)
