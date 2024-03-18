# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

- [Overview](#overview)
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

**Desktop Version:**

![1710779631935](images/1710779631935.png)

**Mobile Version:**

![1710779707113](images/1710779707113.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: https://ubiquitous-peony-5136d7.netlify.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

While perusing the challenge, I knew I had to use flexbox in CSS to put all the elements on the page together. However, prior experience with flexbox was limited, which forced me to revise the custom variables I had to use. I also got to know how to use **rem** and **vh** in addition to **px** as units in various custom variables.

```css
body    {
    font-family: "Outfit","sans-serif";
    font-size: 15px;
    background-color: var(--light-gray);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: calc(100vh-1px);
    margin: 1.25rem;
}
```

```css
.card      {
    background-color: var(--white);
    padding: 1.25rem;
    border-radius: 0.625rem;
    box-shadow: 5px 5px 5px rgba (0,0,0,0.05);
    margin-bottom: 2rem;
}
```

### Continued development

I would like to use this as a template in case I need to use a QR Code in any of my future projects or as a way to share personal contact info.

### Useful resources

- [Flexbox Froggy](https://flexboxfroggy.com/) - This site helped me to revise the custom variables used in flexbox in a fun manner.

## Author

- Website - S Yashwanth
- Frontend Mentor - [@yashwanth-srinivasa](https://www.frontendmentor.io/profile/yashwanth-srinivasa)
