# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

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

![](./images/screenshot1.PNG)
![](./images/screenshot2.JPG)


### Links

- [Solution URL](https://github.com/frank-itachi/Web-Development/tree/master/stats-preview-card-component)
- [Live Site URL](https://frank-itachi.github.io/Web-Development/stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- BootStrap Grid
- BootStrap d-flex utility
- BootStrap cards

### What I learned

Something that I really liked and learned was that I was able to implement bootstrap cards components with the help of the documentation. I learned how to use nested rows with the Boostrap grid system.

```html
<div class="col-md-6 col-card-content">
                                    <div class="card-body">
                                    <h1 class="card-title">Get <span>insights</span> that help your business grow.</h1>
                                    <p class="card-text">Discover the benefits of data analytics and make better decisions regarding revenue, customer 
                                        experience, and overall efficiency.</p>
                                    <div class="row g-0 card-body-row">
                                        <div class="col-12 col-md-3">
                                            <h2>10k+</h2>
                                            <p class="text-uppercase">companies</p>
                                            </div>
                                        <div class="col-12 col-md-4">
                                            <h2>314 </h2>
                                            <p class="text-uppercase">templates</p>
                                        </div>
                                        <div class="col-12 col-md-5">
                                            <h2 class="text-uppercase">12m+</h2>
                                            <p class="text-uppercase">queries</p>
                                            </div>
                                    </div>
                                    </div>
                                </div>
```

### Useful resources

- [BootStrap](https://getbootstrap.com/docs/5.3/components/card/) 
- [BootStrap](https://getbootstrap.com/docs/5.3/utilities/flex/#align-items)
- [BootStrap](https://getbootstrap.com/docs/5.0/layout/grid/)

## Author

- GitHub - [Francisco Carrillo](https://github.com/frank-itachi)
- Frontend Mentor - [@frank-itachi](https://www.frontendmentor.io/profile/frank-itachi)