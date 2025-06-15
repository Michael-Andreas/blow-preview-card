# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS Flow Layout

### What I learned

I learned how to verticaly align an image and a span in the same line in flow layout without using flexbox

```html
<img
  src="./assets/images/image-avatar.webp"
  alt="avatar of author"
  class="avatar" />
<span>Greg Hooper</span>
```

```css
.avatar {
  display: inline-block;
  vertical-align: middle;
}

span {
  vertical-align: middle;
}
```

### Useful resources

- [Solution for the vertical alignment](https://stackoverflow.com/questions/9249359/vertically-align-text-within-a-div) - This helped me with my problem of aligning img and text on the same line without using flexbox.

## Author

- Website - [Michael Andreas](https://www.michaelandreas.de)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
