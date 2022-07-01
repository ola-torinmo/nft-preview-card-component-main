
## ETH NFT CARD



## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [solution](https://github.com/ola-torinmo/nft-preview-card-component-main)
- Live Site URL: [live url](https://ola-torinmo.github.io/nft-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned
i learned how to manipulate html structure positioning with the css position property.
using the hover effect to change the image in the image div to turn on the colored opacity of the image



code snippets, see below:

```html

<div class="container">
          <div class="image">
            <a href=""><img src="images\image-equilibrium.jpg" alt=""></a>
          </div>
```
```css
.image a{
    width: 325px;
    
    margin: 15px 25px;
    align-self: center;
    /* background-image: no-repeat; */
    display: block;
    position: relative;
    

}
.image a img{
    width: 100%;
    border-radius: 5%;
    justify-content: space-around;
    display: block;
    
    
    
}
/* made the image opaque with transition */
.image a img:hover{
    opacity: 0.25;
    transition: 0.5s;


}
/* made the container holding the image turn teal to give the image a colored opacity */
.image a:hover{
    
  
    background-color: teal;
    border-radius: 5%;
    background-image: url("images/icon-view.svg");
    background-repeat: no-repeat;
    background-position: center;

}

```





### Useful resources

- [w3schools](https://www.w3schools.com) - This helped me for dealing with the colored opacity feature. I really liked this pattern and will use it going forward.


## Author


- Frontend Mentor - [@ola-torinmo](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@olatorinmo](https://www.twitter.com/yourusername)


## Acknowledgments

My roommate was a really great help when we were completing this challenge.
