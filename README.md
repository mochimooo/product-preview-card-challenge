# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![screenshot](./images/Screenshot%202023-02-03%20181348.png)

### Links

- Solution URL: [https://github.com/mochimooo/product-preview-card-challenge]
- Live Site URL: [https://mochimooo.github.io/product-preview-card-challenge]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties

### What I learned
```html
<link rel='stylesheet' type="text/css" href="sytle.css">
For this, I didn't include 'type' originally, and I thought just inputting 'css' instead of 'text/css' would work; it ended up stripping all the CSS codes. NEVER DO THAT AGAIN.
```
<s></s>
This one is a word strike tag that crosses the price number.

```css
.card {
    height: 32.125rem;
    width:700px;
    border-radius: 15px;
    background-color: hsl(0, 0%, 100%);
    margin: 0;
    position: absolute;
    top: 50%;
    left: 50%;
    -ms-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
 }

 h3 {
    line-height: 1.6;
}

#letter-spacing{
    letter-spacing: 0.5em;
}

row {
  display: flex
}
This one allows me to put two different texts in the same line; it also helped me put the picture and text side-by-side.

```
### Continued development

(Note: written on 2/3/2023 for the first finish)
-I need to practice more on how to use CSS selectors more efficiently. For example: the font style for both "Gabrielle Essence Eau De Parfum" and "$149.99" is the same, and the only difference is the color. I don't know how to use combination CSS selector to ditinguish the two.
- Learn how to make the card responsive to screen size. Currently the size of the card is static.
- Learn how to make the mobile version of this webpage.
- As of today (2/3/2023), I haven't learn how to make it so that user can see hover and focus states for interactive elements. This definitely would be something I need to learn.

### Useful resources

- [CSS line-height Property](https://www.w3schools.com/cssref/pr_dim_line-height.php) - I learned how to space out the description of the product by using line-height property.
- [letter-spacing](https://cssreference.io/property/letter-spacing/#:~:text=You%20can%20use%20pixel%20values.&text=letter%2Dspacing%3A%200.1em%3B,relative%20to%20the%20font%2Dsize.) - This page explains how to use letter-spacing.
- [How To-Cards](https://www.w3schools.com/howto/howto_css_cards.asp) - I still need to practice using this feature of CSS to make cards.
- [Deploying to GitHub Pages](https://www.codecademy.com/article/f1-u3-github-pages) - This website is helpful in explaining how to deploy more websites as you complete new challenge projects.

## Author

- Frontend Mentor - [@Mochimooo](https://www.frontendmentor.io/profile/Mochimooo)

## Acknowledgments

I'd like to thank @MelvinAguilar on FrontEnd Mentor for being the first person that gives me advice for my first-ever challenge project (Frontend Mentor QR code challenge). It motivated me to try more coding. I'd also like to thank my brother Benny and my friend Anh for encouraging me to start on this path.