# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: (https://github.com/JulianIfesiokwu/Testimonials-grid-Project)
- Live Site URL: (https://julianifesiokwu.github.io/Testimonials-grid-Project/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- CSS Flex
- Mobile-first workflow
- BEM methodology
- SCSS

### What I learned

I learnt the basics of BEM and SASS in this project and how to use a mixin to include a media query.
```css
@include media-md {
    main {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr;
        grid-template-rows: 1fr 1fr;
    }

    .testimonial--purple {
        grid-column: 1 / span 2;
        grid-row: 1 / span 1;
    }

    .testimonial--grey {
        grid-column: 3 / span 1;
        grid-row: 1/2;
    }

    .testimonial--dark {
        grid-column: 2/4;
        grid-row: 2/3;
    }

    .white--one {
        grid-column: 4 / span 1;
        grid-row: 1 /span 2;
    }

    .white--two {
        grid-column: 1 / span 1;
        grid-row: 2 /span 1;
    }
}
```

### Continued development

I intend to continue my development on CSS Grid, BEM and SASS because I wish to use these methodolgies for all my future projects.

### Useful resources

- (https://www.w3schools.com/css/css_background_repeat.asp) - This helped me to put the quotation marks in the background of a testimonial.

- (https://www.w3schools.com/css/css_background_shorthand.asp) - This helped me shorten my css background property.When using the shorthand property the order of the property values is:
 background-color
 background-image
 background-repeat
 background-attachment
 background-position

-(https://falkus.co/2017/05/using-lighten-and-darken-in-sass/) - This helped me understand and use the lighten and darken property in SASS.

-(https://www.w3schools.com/cssref/pr_background-position.asp) - This enabled me understand you can use percentages to position a background image. I use this property to properly align the quotation marks in the first testimonial section.

-(https://www.w3schools.com/css/css_grid.asp) - This was particularly useful in creating the desktop view grid.

## Author

- Frontend Mentor - [@egbuna09]("https://www.frontendmentor.io/profile/egbuna09")

