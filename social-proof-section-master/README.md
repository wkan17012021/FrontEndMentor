# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

This challenge was less complicated than the previous. It still took 3-4 hours to complete, not sure why the efficiency isn't improving per challenge! I find i am still spending time researching common css qwerks (getting the profile pic to align with their name and 'Verified Buyer') and looking up properties and their use cases on W3 / MDN. Overall, a nice challenge as i had been watching a lot of coding videos lately.

### The challenge

Users should be able to:

- View the optimal layout for the section depending on their device's screen size

## My process

1. From mobile, start to conceptualise how the card component can be divvied up i.e. what separate group containers and nested containers will be needed.
2. Revise conceptual model based on desktop version. Consider what layout will be necessary to facilitate the rearrangment of the star reviews and testimonial sections.
3. Use normal flow box model for mobile view. For some nested content, flexbox.
4. The desktop template is more involved imo. Use a combination of flex row/column to get the overall positioning. I wasn't sure the most effective way to implement the staggered effect- I ended up hacking it somewhat with negative margins. Perhaps grid display would be best here.
5. The background image effects I haven't quite got the hang of. Room for improvement here.

### Built with

- HTML5 markup
- SCSS
- Flexbox
- Mobile-first workflow

### What I learned

I noticed an efficiency improvement in manipulating elements with the box model principles which historically has been a labourious trial and error challenge in itself. Also, I quite like this staggered effect and would like to implement this in my personal projects.

### Continued development

Multiple positioned background-images. I haven't tackled these at all before FEM so some time investment is needed. It seems without the figma design, getting the images to match the jpeg is time consuming trial and error process.

### Useful resources

General SO and W3 searches on flex manipulation.

## Author

The Dogue 🐕

## Acknowledgments

TheCoderGuru - tweaked the gap between the testimonial cards in desktop version. Thanks
Trey willeto - advised on the background svgs display. Thanks
