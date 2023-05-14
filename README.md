# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Desktop preview image for 3-column preview card challenge](/images/desktop-preview.png "Desktop preview")
![Mobile preview image for 3-column preview card challenge](/images/mobile-preview.png "Mobile preview")

### Links

- Solution URL: [Solution](https://github.com/ag7621/fem-3-column-preview)
- Live Site URL: [Live site](https://ag7621.github.io/fem-3-column-preview/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

When building the mobile view I ran into an issue where my design matched the challenge, but the white space at the bottom did not. I thought using `margin-bottom` on the container div would solve the issue, but it did not. I still have yet to figure out what in my code did not work, but did come up with a solution to use padding instead along with `border-radius` on specific cards. The reason is I used `border-radius` and `overflow:hidden` on the container div is so I didn't have to declare `border-radius` on the individual cards, but in the end had to do it anyways when mobile view came into play.

Perhaps I'll revisit it later when I've acquired more experience, but for now I've left it as is.

### Continued development

The use of BEM and proper responsiveness is something always on my list of continued development. I do enjoy these more simple challenges to reinforce practices, and to become more familiar with building for specific layouts. Overall I have a lot of fun doing these ones and look forward to building more complex designs!

### Useful resources

- [Josh W Comeau CSS reset](https://www.joshwcomeau.com/css/custom-css-reset/) - A CSS reset referred to in a video by Kevin Powell.

## Author

- Frontend Mentor - [@ag7621](https://www.frontendmentor.io/profile/ag7621)