# Frontend Mentor - Intro section with dropdown navigation solution
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
This challenge 

### The challenge

Users should be able to:

- View the relevant dropdown menus on desktop and mobile when interacting with the navigation links
- View the optimal layout for the content depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![desktop](https://i.imgur.com/0rxyhhG.png)
![mobile](https://i.imgur.com/IBDJcmO.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/AngeloMar98/MentorChallenge-13)
- Live Site URL: [Add live site URL here](https://mentor-challenge-13.vercel.app/)

## My process
The first thing to handle was the menus that pop-up in the navigation bar, I wanted to implement both a timer that deactivated them when you go away and leaving only one of them open. The rest of the page was easy, beside some figuring out the right size for the main heading, since the pop-up menus needed to be right above it. The grid is simply split into two equals section with a text and an image.

The part a bit more challenging was implementing the side menu for the mobile version, not as much implementing the side menu perse but more how to handle a different type of event for the pop menus. The pop menu are not anymore a floating element in the page but open up naturally in the navigation bar, using an hover effect for them didn't look right at all so I used a simple click event for them.

By using a window.matchMedia with the right query, the events are changed dynamically by assigning new ones and removing the old ones. The event only triggers when the query threshold is reached so it's really mostly for shows than anything, mobile users would never need to worry about that.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

Changing events dynamically with javascript-oriented media queries, I think this is far from the adequate scenario to use them but it was still fun figuring it out, assigning differents events might be useful when the layout change more drastically.

### Continued development

I want to make javascript and css fill each other's weaknesses more easily, sometime something hard in CSS barely requires any effort in Javascript

## Author

- Frontend Mentor - [@AngeloMar98](https://www.frontendmentor.io/profile/AngeloMar98)
  

