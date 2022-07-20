# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - QR code component solution](#frontend-mentor---qr-code-component-solution)
  - [Table of contents](#table-of-contents)
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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

A Horizontally and vertically aligned card containing a QR image, a heading and a paragraph.

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [Solution](https://github.com/felipec583/qr-code-page)
- Live Site URL: [Live site](https://felipec583.github.io/qr-code-page/)

## My process

- Starting out with the HTML markup: using divs to create a container and the card, which includes the Qr image, heading and paragraph.

- Create the card's children elements: img, h2 and p.

- Fill out the elements with the content showcased on the desktop design preview.

- Include a link element in the head element to add a style.css file and start styling the website.

- Assign a class to the container and card divs.

-  On the stylesheet:
   - Import the Outfit font.
   - Add :root pseudo element to create font variables and set the root font size.
   - Set body margin to 0 and the color background requested on the style guide.
   - Create a ruleset for the container class:
     - Position: absolute [Used to take the container out of the flow and relative to the body]
     - Top and left values at 50% to align the container's children.
     - Also, include the transform property and the translate values: X: -50% and Y-50% to align the card vertically and horizontally on the website.
   - Create a ruleset for the card class:
      - Add a bit of padding, the background color assigned on the style guide, width and border radius.
   - Create selectors for the h2 and p elements:
     - Set text-related properties: font-family, requested color, text-align, font-weight, font-size (rem)
   - Add a media query (max-width:400px)

### Built with

- HTML Markup
- CSS
- Absolute positioning (CSS)
- Transform property (CSS)
  



### What I learned

Absolute positioning coupled with the translate function turns out a good tool for aligning elements

```
{
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
}
```




### Continued development



### Useful resources

- [Stackoverflow article](https://stackoverflow.com/questions/14123999/center-a-div-horizontally-and-vertically) - This helped me find a way to align horizontally and vertically an element relative to the website.



## Author

- Website - [Felipe Castillo](https://github.com/felipec583)
- Frontend Mentor - [@felipec583](https://www.frontendmentor.io/profile/felipec583)
- Twitter - [@facl583](https://www.twitter.com/yourusername)



## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.


