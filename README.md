# Frontend Mentor - Article preview component solution

This is a solution to the [Article preview component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/article-preview-component-dYBN_pYFT). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See the social media share links when they click the share icon

### Screenshot

![](./screenshot.jpg)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Jquery


### What I learned
Improve my responsive design,
Knew what I need to focus on next(JS)


```html
   <div class="arrowDown"></div>
```
```css
.arrowDown{
    width: 0;
    height: 0;
    border-left: 18px solid transparent;
    border-right: 18px solid transparent;
    border-top: 18px solid var(--VeryDarkGrayishBlue);
    position: absolute;
    right: 245px;
    top: 375px;
   
}
```
```js
if(width>375){
        $(".authorRight").click(function(){
        if(x == 0){
          $(".shareBox").show();
          $(".arrowDown").show();
          x = 1;
        }
        else{
          $(".shareBox").hide();
          $(".arrowDown").hide();
          x = 0;
        }
      
      });
    }else{
      $(".authorRight").click(function(){
        if(x == 0){
          $(".shareBox").show();
          x = 1;
        }
        else{
          $(".shareBox").hide();
          x = 0;
        }
      
      });
    }
    
   

```





### Continued development

Event handling, responsive design and JS in general



### Useful resources

- [w3schools](https://www.w3schools.com) - I Use it for jquery syntax.



## Author

- Frontend Mentor - [@sandeshad100](https://www.frontendmentor.io/profile/sandeshad100)
- Linkedin - [@yourusername](https://www.linkedin.com/in/sandesh-adhikari-7877161a7/)


## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.


