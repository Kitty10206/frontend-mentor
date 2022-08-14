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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![Mobile version](https://github.com/Kitty10206/frontend-mentor/blob/huddle-landing-page/Huddle%20landing%20page%20mobile.png?raw=true)
![Desktop version](https://github.com/Kitty10206/frontend-mentor/blob/huddle-landing-page/Huddle%20landing%20page%20desktop.png?raw=true)


### Links

- Solution URL: [Codepen](https://codepen.io/HannahWillis/full/BarOgjP)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Columns


### What I learned

This took me way way way too long because I couldn't get the icons to center properly and I must have spent half a day trying different combinations of things before resorting to a close approximation of the effect. The rest of it took 1-2 hours for the mobile version plus 2 hours for the desktop css, so a huge proportion of my time was wasted on this.


```html
<a href="/" rel="noreferrer"><div class="socials"><i class="fa-brands fa-facebook-f"></i></div></a>
```
```css
button:hover h3 {
  color: white;
}
```
Here was how I made my button text colour change as I hovered over the button, because for whatever reason it was only changing when I hovered directly on the text.


### Continued development

I routinely have to check things like columns, grids, and flexboxes. Hopefully at some point I will progress past this...

### Useful resources

- [StackOverflow](https://stackoverflow.com/questions/4502633/how-to-affect-other-elements-when-one-element-is-hovered) - This showed me how to make the text color change when I hovered over the large button
- [W3Schools](https://www.w3schools.com/howto/howto_css_two_columns.asp and https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_two_columns_unequal) - This helped me make the columns as floating the image wasn't working.
- [Free Code Camp](https://www.freecodecamp.org/news/how-to-center-anything-with-css-align-a-div-text-and-more/) I routinely refer back to this on centering anything.

## Author

- Codepen - [Hannah Willis](https://codepen.io/HannahWillis)
- Frontend Mentor - [@Kitty10206](https://www.frontendmentor.io/profile/Kitty10206)

## Acknowledgments

I heavily relied on a comment on a previous project written by @phoenixdev22 (https://www.frontendmentor.io/solutions/nft-card-with-floats-and-fading-in-with-hover-OS3UfTLIJZ#comment-62f65d1583876a172edf9ebe) for pointers on what not to miss. This was an incredibly helpful comment, and I hope I managed to get everything. One thing I was confused with though was here (https://stackoverflow.com/questions/50709625/link-with-target-blank-and-rel-noopener-noreferrer-still-vulnerable) it says I don't need to use the rel tags instead of no_target.
