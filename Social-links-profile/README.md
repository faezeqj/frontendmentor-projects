# Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ).

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](images/destkop-design.jpg)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

**Building without a Figma file**

This challenge only came with JPG mockups, no Figma file. I learned that you can still get pretty close to pixel-accurate by guessing, testing, and comparing against the reference images directly — then leaning heavily on DevTools' inspector to fine-tune spacing, font sizes until they matched.

**Making the card responsive**

I originally gave `.box` a fixed `width: 400px`, which broke on smaller screens — the card would either overflow or get squished by its flex parent, causing text to wrap oddly. Switching to a fluid width with a max-width cap fixed it and removed the need for extra media queries just to resize the box:

```css
.box {
    width: 100%;
    max-width: 384px;
}
```

### Continued development

- **Responsive layout without a design file** — I got the mobile and desktop versions working 
  by guessing and testing, but I want to get faster and more confident at judging spacing/sizing 
  by eye, so I rely less on trial and error and more on instinct.

## Author

- [LinkedIn](https://www.linkedin.com/in/faezeqj)
- [Frontend Mentor](https://www.frontendmentor.io/profile/faezeqj)