# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#Links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](./images/screenshot1.JPG)
![](./images/screenshot2.JPG)


### Links

- [Solution URL](https://github.com/frank-itachi/Web-Development/tree/master/3-column-preview-card-component)
- [Live Site URL](https://frank-itachi.github.io/Web-Development/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- BootStrap Grid
- BootStrap d-flex utility
- BootStrap cards

### What I learned

Fir this challenge I also used the bootstrap card components but the difference here was that I had to use the card group feature in order to put the cards  together. The “card-group” class comes with a pre-defined set of styles so I adjusted some of them to achieve the  resulting design.
I also learned how to use ranges in CSS media queries. 

```html
<div class="card-group">
  ...
</div>
```

```css
@media (min-width: 576px) and (max-width: 991px){
    .main-col {
        margin-left: 0;
    }

}
```


### Useful resources

- [BootStrap](https://getbootstrap.com/docs/5.3/components/card/) 
- [BootStrap](https://getbootstrap.com/docs/5.0/layout/grid/)
- [BootStrap](https://getbootstrap.com/docs/5.0/utilities/flex/)

## Author

- GitHub - [Francisco Carrillo](https://github.com/frank-itachi)
- Frontend Mentor - [@frank-itachi](https://www.frontendmentor.io/profile/frank-itachi)