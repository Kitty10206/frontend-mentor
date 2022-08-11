# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover states for all interactive elements on the page (I did not fully succeed here)

### Screenshot

![Desktop version](https://github.com/Kitty10206/frontend-mentor/blob/Clipboard-landing-page/Clipboard%20landing%20page%20desktop.png?raw=true)


### Links

- Solution URL: [The CodePen link](https://codepen.io/HannahWillis/pen/eYMKyaa)
for some reason my CSS works to show the mobile version of the site on Codepen and nowhere else. I'm at a total loss on how to fix it, save from building it on something else. Next time, I'll try a different editor.

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- many chocolate biscuits


### What I learned

The mobile version took about 4 hours, and the media CSS for the desktop site took about 2-3 hours. However, an extra 3 hours minimum was spent trying to get the footer for the desktop site to work.

I managed to get my media queries to work! but only on codepen..

```html
<button class="ios-button"><h4>Download for iOS</h4></button>
```
I made buttons for the first time in ages.

```css
.ios-button {
  background-color: var(--strongcyan);
  border: solid 3px #2F9683;
  border-style: none none solid none;
  color: white;  
  width: 85%;
  border-radius: 35px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 10px 0px;
  cursor: pointer;
  box-shadow: 0px 8px 30px hsla(171, 66%, 44%, 0.5);
}
.ios-button:hover {
  background-color: hsla(171, 66%, 44%, 0.7);
  border-color: hsl(171, 66%, 44%, 0.9);
}
```
I enjoyed re-learning how to do :hover and button css. This and active links is something I want to tinker with more.



### Continued development

I really want to work out how to change the colour of an SVG, but by the time I got to the footer where I needed to do so, I was very burned out and gave up. In my next project with svgs I will try and work out how to do this because it seems very useful. This will probably help: (https://levelup.gitconnected.com/how-to-change-the-color-of-icons-with-css-f505ce8b9fdc).

### Useful resources

- [Floating images](https://www.inmotionhosting.com/support/website/website-design/align-float-images-css/) - I checked this out before deciding on grids for the logo in the footer.
- [Mozilla docs](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Box_Alignment_in_CSS_Grid_Layout) - I appreciate any and all resources about grids!
- [CSS tricks] (https://css-tricks.com/snippets/css/complete-guide-grid/) and (https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - I literally could not do anything without referring to these...

## Author

- Codepen - [Hannah Willis](https://codepen.io/HannahWillis)
- Frontend Mentor - [@Kitty10206](https://www.frontendmentor.io/profile/Kitty10206)


