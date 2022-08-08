 # Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Mobile version](https://github.com/Kitty10206/frontend-mentor/blob/testimonials-grid-section/Testimonials%20grid%20section%20mobile.png)
![Desktop version](https://github.com/Kitty10206/frontend-mentor/blob/testimonials-grid-section/Testimonials%20grid%20section%20desktop.png)

### Links

- Solution URL: [On Codepen, where I made this](https://codepen.io/HannahWillis/pen/gOeKWPv)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow
- Media queries that work for a change

### What I learned

This was a great way to experiment with CSS grids, which I reckon will become my new best friend (move over flexbox). I used OneNote on my phone to draw out the grids to make it easier to visualise, and I'll definitely keep doing that in the future.
Overall this took me from 6pm to 10.30pm when I stopped coding, including a total of 45 mins cuddling my cats. so, just about 4 hours of coding. I thought it'd take longer. For my next task, I'll write my estimate and time myself properly!

```html
<img src='https://github.com/Kitty10206/frontend-mentor/blob/testimonials-grid-section/image-daniel.jpg?raw=true' alt='Daniel Clifford' id='profile-photo' class="danielprofilephoto">
```
It's not really html but today I learned how to host images in github myself so I'm proud of that.

```css
#daniel {
  background: url(https://raw.githubusercontent.com/Kitty10206/frontend-mentor/8fe243a9ce3866e4967db89a84f07b5686388bff/bg-pattern-quotation.svg)
    no-repeat top right 15%;
  background-color: var(--moderateviolet);
  grid-column-start: first;
  grid-column-end: span third;
  grid-row-start: first;
  grid-row-end: second;
}
```
When I finally worked out how to put the quote marks in the right place, I shouted YES so loud I scared my cat. I had to put it in the background of the object, and put that CSS at the top.

```css
#kira {
  grid-column-start: fourth;
  grid-column-end: last;
  grid-row-start: first;
  grid-row-end: span last;
}
.....
 #container {
    display: grid;
    padding-top: 8%;
    justify-content: center;
    grid-template-columns: [first] 290px [second] 290px [third] 280px [fourth] 280px [last];
    grid-template-rows: [first] 320px [second] 305px [last];
  }
```
This was the first time I'd done grids this way, and when I eventually got it to work (by fixing my broken @media query) I was very excited.

### Continued development

Things I still need to fix:
- My issues with @media queries. It's partly forgetting the right way to write them, and partly assigning the wrong sizes for max/min-width. 
- I've not worked out how to host my own site on GitHub because it seems unnecessarily complex at 11.30 at night.
- id vs class! I wrote this in my last README but: **For class, I have to use "." and for id I have to use "#".**

Things I want to learn more about:
- Centering grids and flexboxes vertically in the viewfinder. I couldn't find anything online to help here.

### Useful resources

- [CSS Tricks Grid guide](https://css-tricks.com/snippets/css/complete-guide-grid/) - This is my new bible for grids, and CSS Tricks' other tutorials are super helpful as well. 
- [MDN Media queries](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Media_queries) - Found after googling "media queries for idiots" and it really helped. Definitely something to keep referring to!


## Author

- Codepen - [Hannah Willis](https://codepen.io/HannahWillis)
- Frontend Mentor - [@Kitty10206](https://www.frontendmentor.io/profile/Kitty10206)


## Acknowledgments

HUUUUGE thank you to Maritxx for explaining in my last submission why my @media queries were broken, it helped so much this time!
