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
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

### Screenshot

![](/assets/images/blog-preview.jpeg)

![](/assets/images/blog-preview-hovered.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/larryQuao/blog-preview-card.git)
- Live Site URL: [Add live site URL here](https://blog-preview-card-six-sigma.vercel.app)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS hover

### What I learned

I learned about box-shadow in css and also using the time element in HTML, which was interesting to learn.

To see how you can add code snippets, see below:

```html
<!-- Using the time elemet for the Date -->
<div class="small-heading">
          Published <time datetime="2023-12-21 0:00">21 Dec 2023</time>
        </div>
```
```css
/* Using the box-shadow property to provide the shadow of the container.*/
.container{
      background-color: #FFFFFF;
      width: 340px;
      padding: 24px;
      display: flex;
      flex-direction: column;
      gap: 24px;
      border: solid 1px #000000;border-radius: 20px;
      font-family: 'Figtree', sans-serif;
      box-shadow: 8px 8px #000000;
    }
```
```css
/* Applying the hover effect to the container */
.container:hover{
      box-shadow: 16px 16px #000000;
    }
```
### Continued development

I would like to learn more about about css selectors like the :active, :hover, :before, :after and so on. It would be nice to know this for building more interactive webpages

### Useful resources

- [Resource 1](https://www.w3schools.com/cssref/css_selectors.php) - This helped to have fair idea of css selectors and more details on the ```:hover``` and ```:active``` selectors  
- [Resource 2](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes) - This is an amazing article from MDN Documentation, which helped me finally understand Pseudo classes. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@larryQuao](https://www.frontendmentor.io/profile/larryQuao)
