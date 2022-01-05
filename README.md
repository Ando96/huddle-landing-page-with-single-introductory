# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](Capture.PNG)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [live site](https://ando96.github.io/huddle-landing-page-with-single-introductory/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I found out there is a shorthand property for declaring background properties.
```css
.body{
  background: var(--violet) url(images/bg-mobile.svg) no-repeat 0 top;
}
```

From looking at other peoples solutions I also found out you can declare fonts and font weights as variables.
```css
:root {
    --violet: hsl(257, 40%, 49%);
    --magenta: hsl(300, 69%, 71%);
    --white: #fff;

    --normal: 400;
    --bold: 600;

    --sans: 'Open Sans', sans-serif;
    --poppins: 'Poppins', sans-serif;
}
```


### Continued development

As with all my other readme files, I'm still working on improving my HTML and CSS skilss, I'll hopefully be moving onto Javascript soon.

### Useful resources

- [w3schools] https://www.w3schools.com/css/default.asp - Has everything you need when it comes to HTML and CSS basics
- [MDN] https://developer.mozilla.org/en-US/- Has a lot of useful and interesting information about the different HTML and CSS tags, I find a new attribute or tag every time I'm looking for something

## Author

- Frontend Mentor - [@Ando96](https://www.frontendmentor.io/profile/Ando96)
