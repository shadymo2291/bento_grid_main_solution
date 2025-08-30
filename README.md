## Table of contents

- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### Links

- Solution URL:https://github.com/shadymo2291/bento_grid_main_solution

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- selecting elements
- grid placement

### What I learned

in this project i used some CSS properties to help for responsive font size, such as @media, also i learned how to ordering the elements by useing order property.

To see how you can add code snippets, see below:

@media (max-width: 678px){
.container > div:nth-child(3) {
order: 3;
padding: 30px;
}
.container div:nth-child(3) p:first-child {
font-size: 25px;
margin-bottom: 30px;
letter-spacing: -2px;
font-weight: 500;
}
.container div:nth-child(3) p:last-child {
font-size: 18px;
text-align: center;
letter-spacing: -1px;
font-weight: 400;
padding: 10px;
}
.container div:nth-child(3) img {
max-width: 100%;
transform: translateX(0);
}
}

### Continued development

I want to learn more about responsive websites and other properties and CSS functions, such as the clamp() function.

### Useful resources

- [w3schools](https://www.w3schools.com/howto/howto_css_responsive_text.asp) - This helped me for Responsive Font Size.

## Author

- Frontend Mentor - [@shadymo2291](https://www.frontendmentor.io/profile/shadymo2291)

## Acknowledgments

I want to thank everyone who helped me to learn and to code, especially the Elzero Web School channel on YouTube
