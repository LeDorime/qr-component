# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](/screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5
- CSS

### What I learned

I learned how to properly use divs and sections within html and how nesting them can help with creating the desired layered effect.

```html
<section class="container">
	<div class="card">
		<div class="card-image qr_image"></div>

		<h2>Improve your front-end<br />skills by building projects</h2>

		<p>
			<br />Scan the QR code to visit Frontend<br />Mentor and take your coding
			skills to<br />the next level
		</p>
	</div>
</section>
```

```css
.card-image {
	background-color: aqua;
	height: 63%;
	background-size: cover;
	border-radius: 20px;
	border: 15px solid white;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [w3schools](https://www.w3schools.com/css/) - This helped me with creating certain parts of my css, like how to center and fit the image.

## Author

- Frontend Mentor - [@LeDorime](https://www.frontendmentor.io/profile/LeDorime)
