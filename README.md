# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

I am attempting to recreate the product preview card with HTML and CSS.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](/product-preview-card-component-main/images/screenshot.jpeg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

1. I created a plan for how I would design my page. (went of script and wish I would have planned better.)
2. Set-up the html.
3. CSS
4. Mobile-Layout(Which I have since then realized should come first)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned I should design mobile first. I feel it helps with the flow of content. I did not use flex-box for the desktop design and I will definitely redo project using flex-box first. Display: none is a clever tool, it may be semanticly clunky but it really help me get a semblance of the design. I need to plan better. I will basically a chicken with its head cut off at certain points and better planning for css would have alleviated that issue.

```html
This was a clever way to get the paragraph to break how I wanted it.(clunky)
<p>
  A floral, solar and voluptuous<br class="br1" />
  interpretation composed by<br class="br2" />
  Olivier<br class="br3" />
  Polge, Perfumer-Creator<br class="br4" />
  for the House of<br class="br5" />
  CHANEL.<br class="br6" />
</p>
```

```css
Solved a major issue with the image resizing I was having. #img-div {
  display: none;
}
```

```



### Continued development
Page layout in general and flex-box. Mobile first design and Media-queiries in css.



### Useful resources
https://www.youtube.com/kepowob - Kevin's youtube page was a great and is still a great go to for me to understand css.
The book Web Design Playground by Paul McFedries - help with css as well especially with the mobile first approach and helped clear some flexbox issues I was having.



## Author

- Website - [https://www.linkedin.com/in/deshawnreid/
- Frontend Mentor - https://www.frontendmentor.io/profile/Earfworm
- Twitter - https://twitter.com/DeshawnReid88


## Acknowledgments

https://www.frontendmentor.io/profile/Badhrikr- I saw this page and was inspired to continue and finish through.
```
