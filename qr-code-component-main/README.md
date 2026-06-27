# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### Screenshot

![](../qr-code-component-main/images/Screenshot%202026-06-27%20151105.png)

*(Note: Replace `./screenshot.png` with the actual path to your screenshot image once you take it).*

### Links

- Solution URL: [Add your Frontend Mentor solution URL here]
- Live Site URL: [Add your GitHub Pages live URL here]

## My process

### Built with

- Semantic HTML5 markup (using `<main>` for better accessibility)
- CSS custom properties (variables)
- Flexbox for centering and layout
- Mobile-first approach (Fluid design without media queries)
- Google Fonts (Outfit)

### What I learned

During this project, I focused on breaking the habit of using meaningless `<div>` tags and started writing **Semantic HTML**. I also deepened my understanding of how **Flexbox** works to perfectly center elements on a page.

One of the most valuable lessons was understanding the difference between `padding` and `margin`, and utilizing the `gap` property in Flexbox for cleaner spacing instead of relying on paddings.

Here is a snippet of the CSS I used to perfectly center the card and create breathing room:

```css
body {
    background-color: hsl(212, 45%, 89%);
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    min-height: 100vh;
    gap: 20px; /* Modern way to separate the main card and footer */
}