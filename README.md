# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Links

- Solution URL: (https://github.com/KrisvHeij/recipe-page-main)
- Live Site URL: (https://krisvheij.github.io/recipe-page-main/)

## My process

I started this project with a mobile-first approach. First I wrote all of the html in the index.html file and from there on I began with styling the whole page section by section.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The most difficult part of this project was getting the bullet points from the different lists right. I couldn't figure out how to style them correctly. So I replaced some of them with pseudo elements as you can see here:

.prep li:before {
content: "";
width: 4px;
height: 4px;
background-color: var(--c-brown-800);
border-radius: 50%;
}

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/)

## Author

- Website - [Kris van Heijningen](https://github.com/KrisvHeij)
- Frontend Mentor - [@KrisvHeij](https://www.frontendmentor.io/profile/KrisvHeij)
