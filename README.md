# Frontend Mentor - Sunnyside landingpage solution


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview
This project required me to build a fully responsive landing page to the designs provided. I used Bootstrap, along with CSS to customize navigation feature in mobile view. 

### The challenge

Users should be able to:

-View the optimal layout for the site depending on their device's screen size
-See hover states for all interactive elements on the page


### Links

- Solution URL: https://github.com/sansanthi/sunnyside-bootstrap
- Live Site URL: https://sunnyside-fmentor.netlify.app/


### Built with

- Semantic HTML5 markup
- Bootstrap
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I have built this landing page with bootstrap.Firstly, I learned how to set up bootstrap with CDN. I used mainly navbar component and columns. And learned how to override bootstrap component with custom css properties. Also I knew how to build down arrow and half triangle with css pesudo element.


To see how you can add code snippets, see below:

```down arrow css
.down-arrow {
  height: 110px;
  background-color: #fff;
  position: relative;
}
.down-arrow,
.down-arrow::before,
.down-arrow::after {
  display: block;
  width: 7px;
  background-color: #fff;
  border-radius: 10px;
}
.down-arrow::before,
.down-arrow::after {
  content: '';
  position: absolute;
  height: 30px;
  bottom: -3px;
}
.down-arrow::before {
  left: -10px;
  transform: rotate(-45deg);
}
.down-arrow::after {
  right: -10px;
  transform: rotate(45deg);
}
```
```half triangle css
 .navbar-collapse::before {
    content: '';
    border-width: 15px;
    border-style: solid;
    position: absolute;
    top: -28px;
    right: 0px;
    border-left-color: transparent;
    border-top-color: transparent;
    border-right-color: #fff;
    border-bottom-color: #fff;
  }
```

### Continued development
In this challenge there are issues with navbar collapse with toggler. I have to fix navbar toggler action. And need to learn Bootstrap.


### Useful resources

- https://stackoverflow.com/


**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments
Google search and https://stackoverflow.com/
