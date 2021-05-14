# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- Build out the project to the designs provided

### Links

- Solution URL: [Solution on Frontend Mentor]()
- Live Site URL: [Github Pages Link]()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

In this project, I learned how to select the nth item in css. I used a lot of flexbox, and the design changed a lot from mobile to desktop.

```html
<div class="card">
  <div class="card-header">
    <img src="./images//image-colton.jpg" alt="" class="profile" />
    <div class="name-contain">
      <div class="name">Colton Smith</div>
      <div class="verified">Verified Buyer</div>
    </div>
  </div>
  <p class="card-paragraph">
    "We needed the same printed design as the one we had ordered a week prior.
    Not only did they find the original order, but we also received it in time.
    Excellent!"
  </p>
</div>
```

```css
.card {
  margin-right: 25px;
}
.card:nth-child(1) {
  margin-top: 0px;
  margin-bottom: 40px;
}
.card:nth-child(2) {
  margin-top: 20px;
  margin-bottom: 20px;
}
.card:nth-child(3) {
  margin-top: 40px;
  margin-bottom: 0px;
}
```

### Useful resources

- [Blog for centering css grid](https://coryrylan.com/blog/how-to-center-in-css-with-css-grid) - This helped me center my content in css grid.
- [W3 Schools, nth child css](https://www.w3schools.com/cssref/sel_nth-child.asp) - This helped me select the nth child.
- [css tricks, grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This helped me use css grid in general.

## Author

- Website - [Landon Schlangen](https://www.landonschlangen.com)
- Frontend Mentor - [@Landon345](https://www.frontendmentor.io/profile/Landon345)
- LinkedIn - [Profile](https://www.linkedin.com/in/landon-schlangen-a3989a16b/)

## Acknowledgments

I completed this one on my own in about 1.5 hours.
