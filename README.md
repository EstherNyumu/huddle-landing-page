# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview
This is a project done usig HTML and CSS coding languages as a practice to improve my skills.

### The challenge
In my page one can tell the elements that act as links and the layout is simple and can adjust to different screens.

### Screenshot
C:\Users\user\OneDrive\Documents\WEB DEV\huddle-landing-page-with-single-introductory-section-master\Screenshot (4).png

### Links
- Solution URL: [https://www.frontendmentor.io/solutions/huddle-landing-page-using-html-and-css-Wkr_kUVwYm]
- Live Site URL: [https://esthernyumu.github.io/huddle-landing-page/]

## My process
I started by addding all the required contents in the page using HTML.
I then started styling the elements such as the buttons, icons, texts and added the images.
I styled using CSS adding the appropriate colours.

### Built with
- Semantic HTML5 markup
- CSS custom properties
- CSS lists
- CSS pseudo-classes
- imported google fonts(https://fonts.googleapis.com/css2?family=Open+Sans&family=Poppins:wght@400;600&display=swap)

### What I learned
This project has helped me learn an easier way to add icons on your page in a way you can style them altogether without interfering with the other contents of the page. The code snippet for this part is:
```html
<ul class="social-list" role="list" aria-label="Social links">
  <li>
    <a aria-label="facebook" href="#"
    ><svg class="social-icon">
      <use xlink:href="images2/social.svg#logo-facebook"></use></svg
    ></a>
  </li>
  <li>
    <a aria-label="twitter" href="#">
      <svg class="social-icon">
        <use xlink:href="images2/social.svg#logo-twitter"></use></svg
      ></a>
  </li>
  <li>
    <a aria-label="instagram" href="#">
      <svg class="social-icon">
        <use xlink:href="images2/social.svg#logo-instagram"></use></svg
      ></a>
  </li>
</ul>
  ```
  ```css
  ul[role="list"],
ol[role="list"] {
  list-style: none;
  padding: 0;
}

.social-list {
  display: flex;
  align-items:flex-end;
  justify-content: flex-end;
  gap: 0.5rem;
}

.social-icon {
  fill: #fff;
  display: flex;
  border: 1.6px solid #ddd;
  border-radius: 16px;
  padding: 5px;
  width: 1rem;
  height: 1rem;
}

.social-list a:is(:hover, :focus) .social-icon {
  fill:  hsl(300, 69%, 71%);
  border-color: hsl(300, 69%, 71%) ;
}
  ```

### Continued development
I would like to improve in my skills of styling as I found myself googling on how to do most of the things.I want
to also focus on getting to know more and better HTML elements.
I would also like to improve in mobile design.

## Author
- Website - [Esther Nyumu](https://www.your-site.com )
- Frontend Mentor - [Esther Nyumu](https://www.frontendmentor.io/profile/EstherNyumu)
- Twitter - [Esther Nyumu](https://twitter.com/NyumuEsther)

## Acknowledgments
I have a friend who would help me out in this project especially in the styling. W3Schools was also a great help in guiding me about the html and css elements.

