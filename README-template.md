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
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./images/Screenshot%202024-03-21%20at%2010.50.19 PM.png)

### Links

- Solution : [GitHub Repo](https://github.com/tacostrash/qrCode)
- Live Site : [Vercel Link](https://qr-code-challenge.vercel.app/)

## My process

I was trying to divide it into parts. I made three different `divs` and make three `class` as well at first. I realized that the image needed to be in somewhere in between so i plaved it in the middle `div` I was having trouble. I then reset everything and decided to do it one by one and it worked out very well.

### Built with

- HTML
- CSS
- Mobile-first workflow

### What I learned

I learned so much. I learned how wveyrthing is connected when using `class`. I learned I need to put in a size of the image so it will appear. I figured out that I needed to resize the picture itself to get the white space I needed so it could look like the final result. I got the custom font to be assigned to the project. I really enjoyed working on this project because I completed it by googling and it felt nice to see it come together.

````html
<body>
  <!-- Made a class named card to work on the card itself -->
  <div class="card">
    <!-- Image of the QR Code -->
    <img
      src="images/image-qr-code.png"
      alt="This is a QR code"
      class="center"
    />

    <!-- This is the text for each and has it's own class name -->
    <strong class="top-text">
      Improve your front-end skills by building projects
    </strong>
    <p class="bottom-text">
      Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level.
    </p>
  </div>
</body>
```` 
  
  ```css 

/* The page as a whole */
body {
  background-color: hsl(220, 100%, 94%);
}

/* This is the styling for the image */
.center {
  border-radius: 23px;
  margin: 10px 0 10px 0;
  width: 90%;
  display: block;
  margin-left: auto;
  margin-right: auto;
  margin-top: 4%;
  margin-bottom: 7%;
}

/* This code below is the card as a whole */
.card{
  box-shadow: 0 4px 8px 0;
  max-width: 350px;
  margin: auto;
  text-align: center;
  background-color: white;
  border-color: white;
  border-radius: 23px;
  border-style: solid;
}

/* The two below is for the text within the card.  */
.top-text{
  font-size: 27px;
  font-weight: 700;
}

.bottom-text{
  color: grey;
  font-size: 20px;
  font-weight: 400;
  background-color: white;
  border-radius: 23px;
}
 
/* This is the font for everything */
* {
font-family: 'Outfit';
}
````
### Continued development

I want to focus more on the JavaScript when tackling these projects. I really love HTML and CSS but I would like to develop my JS even more than what I know.

## Author

- LinkedIn - [Carlos Marin](https://www.linkedin.com/in/carlos-fragoso-marin/)
- Frontend Mentor - [@tacostrash](https://www.frontendmentor.io/profile/tacostrash)
- Github - [@Carlos Marin](https://github.com/tacostrash)

## Acknowledgments

Worked on this like a real programmer and googled every problem I had very thankful to make this and actually learning to code better.
