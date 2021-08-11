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
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![desktop screenshot](./design/screenshot-desktop.png)

### Links

- [Solution URL] (https://github.com/akshaymagrani/webDev-n15-Stats-preview-card-component-main)
- [Live Site URL] (https://web-dev-n15-stats-preview-card-component-main.vercel.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Grid
- Mobile-first workflow

### What I learned

Recap over some of your major learnings while working through this project.

```css
/*Use of CSS grid*/
.card {
  display: grid;
  grid-template-columns: 540px 1fr;
  grid-template-rows: 1fr 30px;
  max-width: 1080px;
  position: relative;
  transform: translateY(50%);
}
.written-content {
  grid-row: 1/2;
  grid-column: 1/2;
  text-align: left;
  padding: 4em;
  border-bottom: 4px solid var(--pic-accent);
}
.image-div {
  grid-row: 1/2;
  grid-column: 2/3;
  border-top-right-radius: 10px;
  border-top-left-radius: 0;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

Techniques I found useful that I want to refine and perfect:

- Transitions before and after pages load.
- Libraries to make animation easier.
- Difference between different display styles and associated position values.

## Author

- Website - [Akshaykumar I. Magrani](https://www.your-site.com)
- Frontend Mentor - [@akshaymagrani](https://www.frontendmentor.io/profile/akshaymagrani)
- Twitter - [@magraniakshay](https://www.twitter.com/akshaymagrani)
