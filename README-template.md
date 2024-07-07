# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

[(./screenshot(2).png)]

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned

I got experience on how to make a page responsive.

 code snippets, see below:

```html
<div class="instructions">
      <p id="sub-heading">Instructions</p>
      <ol class="items2">
        <li><span id="thick-content"> Beat the eggs:</span>
          In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed. 
          You can add a tablespoon of water or milk for a fluffier texture.</li>
          <li><span id="thick-content">Heat the pan:</span>Place a non-stick frying pan over medium heat and add butter or oil.
          </li>
          <li><span id="thick-content">Cook the omelette:</span>Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to ensure 
            the eggs evenly coat the surface.</li>
          <li><span id="thick-content">Add fillings (optional):</span>When the eggs begin to set at the edges but are still slightly runny in the 
            middle, sprinkle your chosen fillings over one half of the omelette.
          </li>
          <li><span id="thick-content">Fold and serve:</span>As the omelette continues to cook, carefully lift one edge and fold it over the 
            fillings. Let it cook for another minute, then slide it onto a plate.</li>
          <li><span id="thick-content">Enjoy: </span>Serve hot, with additional salt and pepper if needed.</li>
      </ol>
      <hr>
    </div>
```
```css
.proud-of-this-css {
  @media screen and (max-width: 375px) {
    .slide{
        max-width: 375px;
        height: fit-content;
        padding: unset;
        margin: unset;
        box-sizing: content-box;
    }

    body{
        padding: 0;
        margin: 0;
    }
}
}
```

### Continued development

I hope to improve in uses of css selectors and pseudo-selectors


### Useful resources

- [Example resource 1](https://www.w3schools.com) - This helped me use some elents. I really liked the way it explains elements and will use it going forward.


## Author

- Frontend Mentor - [@Thelma6002](https://www.frontendmentor.io/profile/Thelma6002)
- Twitter - [@dhaperla](https://www.twitter.com/dhaperla)


## Acknowledgments

I would like to acknowledge the significant impact Irvine has had on my work, and thanks for the inspiration and support .

