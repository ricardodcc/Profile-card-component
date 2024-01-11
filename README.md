# Frontend Mentor - 3-column preview card component

This is a solution to the [Profile card component](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges helps you to improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)

## Overview

### Screenshot

![](design/desktop-preview.jpg)


### Links

- Solution URL: (https://www.frontendmentor.io/solutions/responsive-desktop-profile-card-wsass-CQaVj86BjF)
- Live Site URL: (https://ricardodcc.github.io/Profile-card-component/)

## My process
- First of all, I started this small project by organizing the Sass folder. In this folder, will be all the sass files that compose my style properties. So for that, I created:
  - A main file that contains all the imports of the other files;
  - A utils folder that contains such files as:
    - reset.scss + variables.scss + placeholder.scss + fonts.scss for the implementation and declaration of reset styles, variables, fonts that are used, and some placeholders that will be needed for the component implementation.     

- After that I created the index.html and the style.css file to write the HTML structure respecting the HTML5 "rules" and then just tipped ```scss --watch main.scss style.css``` and then when saving new info into any Sass it will automatically convert that into CSS language.

- In this challenge, I started by creating the background pattern and then I focused on the component. As i builted the HTML I tried to attribute classes to the elements with the BEM tipolegy.

### Built with

- Semantic HTML5 markup
- CSS custom properties, and variables
- SASS placeholders, reset, and variables