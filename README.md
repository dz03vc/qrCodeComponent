# Frontend Mentor - Order summary card solution

This is a solution to the [QR Code Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H); 
Solution by [Guilherme](https://github.com/dz03vc).

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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- See and scan the QR Code both on desktop and mobile;
- Click the attribution links.

### Screenshot

- Desktop:

![Desktop Version](https://github.com/dz03vc/orderSummaryComponent/blob/main/screenshotOrderSummaryDesktop.png?raw=true)

- Mobile:

![Mobile Version](https://github.com/dz03vc/orderSummaryComponent/blob/main/screenshotOrderSummaryMobile.png?raw=true)

### Links

- [Solution URL](https://github.com/dz03vc/orderSummaryComponent)
- [Live Site URL](https://dz03vc.github.io/orderSummaryComponent/)

## My process

### Built with

- HTML5
- Pure CSS 
- Flexbox
- SVG

### What I learned

- Mainly how to scructure the HTML while focused on the way I would style the CSS coding;
- The different ways of working with, and scaling, SVG;
- How to work with flexbox;

```html
<div class="planColumn">
        <data class="plan">Annual Plan</data>
        <data class="price">$59.99/year</data>
      </div>
```
```css
.planContainer {
      display: flex;
      background-color: hsl(225, 100%, 98%);
      padding-left: 1.65rem;
      padding-right: 1.65rem;
      padding-top: 1.5rem;
      padding-bottom: 1.5rem;
      border-radius: 1rem;
      margin-top: 0.5rem;
      margin-bottom: 0.25rem;
    }

    .planColumn {
      display: flex;
      flex-direction: column;
    }
```

### Continued development

- I learned a lot about flex and svg with this challenge, but I definetely need to continue exploring the different ways of working with it;
- I'm planning on doing the HTML/CSS QR code challenge before starting the Colt Steele's JavaScript section.

### Useful resources

- [Kevin Powell - YouTube](https://www.youtube.com/@KevinPowell) - His Channel helped me a lot with his CSS/SVG related videos.
- [MDN - Flex](https://developer.mozilla.org/en-US/docs/Web/CSS/flex) - MDN structures/Syntaxes/Instructions always helping.
- [Colt Steele's Web Dev Bootcamp](https://www.udemy.com/course/the-web-developer-bootcamp/) - Colt Steele's bootcamp that I'm enrolling right now.

## Author

- Website - [Guilherme @ Github](https://github.com/dz03vc)
- Frontend Mentor - [Guilherme @ Frontend Mentor](https://www.frontendmentor.io/profile/dz03vc)
- Linkedin - [Guilherme @ LinkedIn](https://www.linkedin.com/in/guilherme-pinto-1b998b22/)


## Acknowledgments

- A big thanks to M and V that helped me with this challenge!
- [M's GitHub](https://github.com/studentiyot)
- [V's GitHub](https://github.com/Vishisht-Dwivedi)

