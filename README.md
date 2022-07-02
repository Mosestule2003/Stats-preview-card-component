# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](C:\Users\user\Documents\Practice-3\design\Desktop-layout.png)
![](C:\Users\user\Documents\Practice-3\design\Mobile-layout.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)


## My process
- I started out with using a section element to stand as the parent for all the remaining components.
-I further used a div class of [body-content] to represent all the direct componets of the entire card.
- I used the div class of [content-1 and content-2] on a width of 50% do give an even layout to both the text used in the [body-content] and the image.
-Css is used to styles all the components of the parent element section. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

During the course of this project, I was able to understand more how css flexbox worked and also how to structure a HTML document in a more concise manner. Although I cam across a number of issues when trying to add a semi-transparent purple background to the image container using css;


```html
 <div class="content-2"><img src="images/image-header-desktop.jpg" alt="" width="100%" class="image">
```
```css
.content-2{
    width: 50%;
    border-radius:  0 15px 15px 0;
}
 /* Please can someone help with adding the semi-transparent background layer to the images section */
.image{
    border-radius: 0 15px 15px 0;
    background-color:  hsl(277, 64%, 61%);
    position: relative;
}
```
```

### Useful resources

- (https://www.w3schools.com/css/css_align.asp) - This helped me understand the dynamic nature of the css horizontal and vertical layout and how to efffectively use it in a in varring situations. I really liked this pattern and will use it going forward.
- (https://www.w3schools.com/html/html_responsive.asp) - This is an amazing website which helped me finally understand how to add responsiveness to my project. I'd recommend it to anyone still learning this concept.


## Author

- Email - (mosestule02@gmail.com)
- Frontend Mentor - [@Mosestule2003](https://www.frontendmentor.io/profile/Mosestule2003)

