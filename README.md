# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

new .png
mobile device .png

### Links

- Solution URL: https://github.com/aboisam/3-column-preview-card-component.git
- Live Site URL: https://aboisam.github.io/3-column-preview-card-component/
## My process
1. structure the html layout 
2. add classes 
3. css 

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
-

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:


```html
I was corrected on how to used the <h1> element in the html tag, which some of the importantace of the <h1> element was listed by couple of the community that make comment on my iniatial post. so now i understand the important of the h1 and how the browser view the h1 one element 
<h1>Some HTML code I'm proud of</h1>
```
```
css
this css code for the container me to understand how to center div element horizontally and vertical center at the middle of the page. 
.container{
    flex-direction: row;
    margin: 250px;
    display: flex;
    border-radius: 10px;
    justify-content: center;
    align-items: center;
    font-size: 15px;
    clear: left;
    ----
}

```
the media query help understand how it will look like on different layout 
@media screen and (max-width: 425px) {
    .container{
        min-width: 87%;
        margin: 0;
        padding: 0;
        display: flex;
        flex-direction: column;
        
    }
    .cards{
        min-width: 5%;
        padding-bottom: 30px;
        align-items: center;
    }

}
```
### Continued development
I want to really understand the structure and layout of website very well 

### Useful resources
VScode, Pritter, GIT

## Author
twitter: @Sam_aboi
linkin: @sam-aboi
**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments
Frontend Mentor Challenge 
