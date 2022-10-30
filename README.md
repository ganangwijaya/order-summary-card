# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

The challenge is to build out this order summary card component and get it looking as close to the design as possible.

### Screenshot

![](https://github.com/ganangwijaya/order-summary-card/blob/main/screenshoot.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/ganangwijaya/order-summary-card)
- Live Site URL: [Live site URL on GitHub Pages](https://ganangwijaya.github.io/order-summary-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [Tailwind CSS](https://tailwindcss.com/) - CSS Framework


### What I learned

In this challenge I learned a lot about using flexbox and also using color variables by configuring `theme.extend.colors` in Tailwind CSS.
To see how you can add code snippets, see below:

Here's that part of my code:

```html
<button class="w-full bg-brightblue hover:bg-desaturatedblue font-black text-xs text-gray-200 rounded-lg py-2.5 drop-shadow-xl">Proceed to Payment</button>
<button class="w-full mt-5 font-black text-xs text-desaturatedblue hover:text-darkblue">Cancel Order</button>
```
```js
<script>
  tailwind.config = {
    theme: {
      fontFamily: {
        'sans': ['Red Hat Display', 'sans-serif']
      },
      extend: {
        colors: {
          paleblue: 'hsl(225, 100%, 94%)',
          brightblue: 'hsl(245, 75%, 52%)',
          verypaleblue: 'hsl(225, 100%, 98%)',
          desaturatedblue: 'hsl(224, 23%, 55%)',
          darkblue: 'hsl(223, 47%, 23%)',
        }
      }
    }
  }
</script>
```
## Author

- Github - [@ganangwijaya](https://github.com/ganangwijaya)
- Frontend Mentor - [@ganangwijaya](https://www.frontendmentor.io/profile/ganangwijaya)
