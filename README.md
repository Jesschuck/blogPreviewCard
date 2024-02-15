# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- See hover states for all interactive elements on the page.

### Screenshot

![screenshot](/assets/images/image.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

For this project, I leveraged the `:hover` pseudo-class to provide users with a more interactive experience. By doing so, I was able to showcase clickable links and enhance the overall interactivity of the project.

I utilized the `:hover` pseudo-class on the **H1, button, and author's name** to enhance user interactivity and display clickable links.

```css
button:hover {
  background-color: var(--black);
  color: var(--yellow);
  cursor: pointer;
}

h1:hover {
  color: var(--yellow);
  cursor: pointer;
  caret-color: var(--black);
}

.author p:hover {
  color: var(--yellow);
  cursor: pointer;
}
```

### Continued development

I feel that there is still room for improvement in my understanding of certain concepts. Specifically, I would like to gain a better grasp on the Mobile-first workflow, CSS Grid Layout Module, and Flexbox, and incorporate more advanced techniques into my CSS usage.

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [@Jesschuck](https://www.frontendmentor.io/profile/Jesschuck)
