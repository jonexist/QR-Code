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
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./images/QR%20code%20desktop.png)
![](./images/QR%20code%20mobile.png)

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://github.com/jonexist/qr-code)
- Live Site URL: [Add live site URL here](https://jonexist.github.io/qr-code/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox

### What I learned

I really want to learn how to write semantic html, but because of this project I gained a knowledge on how to do it on actuall coding activity and also I learned how to use flexbox while doing this projects

This code snippet is the main foundation of the page:

```html
<main class="container">
  <div class="wrapper">
    <img src="./images/image-qr-code.png" alt="QR code">
    <figcaption>Improve your front-end skills by building projects</figcaption> 
    <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
  </div>
</main>
```
```css
  .container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
.wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  background: hsl(0, 0%, 100%);
  width: min-content;
  height: 500px;
  padding: 0 15px;
  border-radius: 20px;
}
.wrapper img {
  width: 300px;
  height: 300px;
  border-radius: 0.60em;
  margin-bottom: 20px;
}
.wrapper figcaption {
  text-align: center;
  color: hsl(218, 44%, 22%);
  font-size: 25px;
  font-weight: 700;
  margin-bottom: 18px;
}
.wrapper p {
  text-align: center;
  color: hsl(220, 15%, 55%);
  font-weight: 400;
  padding: 0 2em;
}
```

### Continued development

I want to have a strong foundation of knowledge in HTML & CSS if I master this 2 I will now proceed to study JavaScript

### Useful resources

- [Writing Semantic HTML](https://www.w3schools.com/html/html5_semantic_elements.asp) - This help me to understand how to write semantic HTML.
- [Flexbox Layout](https://www.w3schools.com/css/css3_flexbox.asp) - I've also learned how to use flexbox in this site.

## Author

- Frontend Mentor - [jonexist](https://www.frontendmentor.io/profile/jonexist)
- Twitter - [jjonexist](https://www.twitter.com/jjonexist)
