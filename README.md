# Frontend Mentor - FAQ accordion solution

This is a solution to the [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- Hide/Show the answer to a question when the question is clicked
- Navigate the questions and hide/show answers using keyboard navigation alone
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![desktop view](./design/Screen%20Shot%202.png)
![Mobile view](./design/Screen%20Shot%20mobile%20view.png)

### Links

- Solution URL: [Solution URL](https://github.com/MohammedOnGit/FAQ_accordion)
- Live Site URL: [Live site URL](https://mohammedongit.github.io/FAQ_accordion/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow



### What I learned
Creating an accessible, responsive FAQ section that works seamlessly across devices is a game-changer for user experience. Using the :nth-of-type() selector brought new styling capabilities, while the details and summary tags ensured accessibility.

```html
<details>
        <summary>What is Frontend Mentor, and how will it help me?</summary>
        <p>
          Frontend Mentor offers realistic coding challenges to help developers
          improve their frontend coding skills with projects in HTML, CSS, and
          JavaScript. It's suitable for all levels and ideal for portfolio
          building.
        </p>
      </details>
```
```css
 details:nth-of-type(3) summary{
    padding-top: 1px;
  }
```

### Continued development
Responsive web design

### Useful resources

- [web.dev](https://web.dev/) - This helped me on the css view port new properties(lvw, svw, lvh, svh). I really liked this pattern and will use it going forward.


## Author

- Frontend Mentor - [@MohammedOnGit](https://www.frontendmentor.io/profile/MohammedOnGit)
- LinkedIn - [@Ibrahim Mohammed](https://www.linkedin.com/in/mohammed-ibrahim-02b3a7271/)
- Facebook - [@Ibrahim Mohammed](https://web.facebook.com/profile.php?id=100002964980399)





