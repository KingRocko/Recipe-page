# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)


## Overview

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: https://github.com/KingRocko/Recipe-page
- Live Site URL: https://kingrocko.github.io/Recipe-page/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- Using primitive and semantic custom properties takes some time to set up, but the effort really pays off when styling components.
- Small, seemingly minor details can be quite time-consuming, as there are often several possible approaches. During this project, I had some trouble styling the list bullet points with the correct indentation. Styling the table in the final section was also a bit challenging.
- Switching the padding from the content wrapper in the mobile view to the card wrapper in the desktop view really helped a lot and made things easier.
- @font-face: Being aware that an installed static version of a font might match but lack the full range of font weights (if a variable font is needed).
- Using em instead of px for media queries to make them relative to the browser’s initial font size (for accessibility reasons).
- I was using the following semantic HTML elements: main > article (for the card) and then div's inside the card as wrappers. Furthermore I used ul / ol / li and a table with th and td – as there's no real thead to be displayed, I used only th with scope="row".

### Continued development

– Definitely put more effort into establishing consistent naming conventions for custom properties. I still need practice and discipline to maintain consistency, as this really makes life easier in the long run.
– Pay closer attention to semantic HTML structure, particularly heading hierarchies and accessible table markup, to improve accessibility and ensure that the document structure is logical and meaningful.
– Continue improving my approach to responsive typography, especially by using relative units and exploring how font sizes, spacing, and layouts can adapt more naturally to different screen sizes and user preferences.
