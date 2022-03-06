# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

  - [The challenge](#the-challenge)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Acknowledgments](#acknowledgments)


### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [Add solution URL here](https://github.com/macdeesh/NFT-card-component)
- Live Site URL: [Add live site URL here]( https://macdeesh.github.io/NFT-card-component/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to use svg in css as a decorative element without adding it in the html, and how to use the pseudo-element ::befor :

```css

.col-ETH::before {
  content: '';
  background: url("../images/icon-ethereum.svg") no-repeat;
  position: absolute;
  transform: translateX(-30%) translateY(28%);
  display: inline-flex;
  width: 100%;
  height: 100%;
}
```

I learned also how to use the pseudo-class :hover, like .NFT-image:hover::before, amd how to display properly a responsive image using :

```css

 .NFT-image {
  display: block;
  position: relative;
  max-width: 100%;
}
```

### Continued development

I will keep practicing css and specially positioning, and hovering elements with pseudo-elments and pseudo-class.

### Acknowledgments

I humbly express my gratitude towards Grace (https://github.com/grace-snow) for lending me an invaluable support and help to understand and fixe the issues that i encountered.

