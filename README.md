# Frontend Mentor - Stats preview card component solution

This is CKodes's solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:s

- View the optimal layout depending on their device's screen size

### Screenshot

#### Desktop Screenshot

<img width="1680" alt="Desktop" src="https://user-images.githubusercontent.com/78678795/124386608-d2730a00-dd0d-11eb-83ad-f18a27b2a11a.png">

#### Mobile Page 1 Screenshot

<img width="362" alt="MobilePg1" src="https://user-images.githubusercontent.com/78678795/124386617-d737be00-dd0d-11eb-8529-bf9f081bb40c.png">

#### Mobile Page 2 Screenshot

<img width="362" alt="MobilePg2" src="https://user-images.githubusercontent.com/78678795/124386622-dbfc7200-dd0d-11eb-8965-838fd7f840b3.png">

### Links

- [Frontend Mentor Solution Page](https://www.frontendmentor.io/solutions/stats-preview-card-component-qlCE8TBSN)
- [Live Site](https://ckodes.github.io/FEM.StatsPreviewCardComponent/)

## My process

### Built with

- HTML | CSS
- Bootstrap 4.0 (card, responsive grid)

### What I learned

- Using Media Queries

For **media queries** I created two values.

**max-width: 1190px** was used to reduce the font-size of the _.stats-para_ class for viewport widths which were in-between mobile and desktop.
This is to ensure the string characters _(COMPANIES, TEMPLATES, QUERIES)_ did not overflow for in-between widths.

**max-width: 1024px** was used to format and style the design to fit mobile and in-between widths.
Most of the changes were for centering texts.

- Centering

The bulk of the centering came from the _.mainholder_ and _.cardholder_ classes where **flexbox CSS properties** were used.

- CSS Background Values

I learnt how to add **url, color, and blend modes** for background properties to add the image and its purple hue to the _.right_ class.

### Continued development

- Add dark mode toggle

### Useful resources

[Another Frontend Mentor Solution Submission](https://www.frontendmentor.io/solutions/stats-preview-card-component-using-css-flexbox-jOXbIxBxh)

- This helped me for the **CSS Background Values** that I added to the _.right_ class.

[Bootstrap](https://getbootstrap.com/)

[MDN Web Docs](https://developer.mozilla.org/en-US/)

[Codeply](https://www.codeply.com/)

[Codepen](https://codepen.io/)

[Markdown Guide](https://www.markdownguide.org/)

## Author

- Frontend Mentor Profile [@CKodes](https://www.frontendmentor.io/profile/CKodes)

## Acknowledgments

Thank you to Dr. Angela Yu of [The App Brewery](https://www.appbrewery.co/) for [The Complete 2021 Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp/) course and for introducing Frontend Mentor as a means to hone FE dev skills. This is my first Frontend Mentor challenge, and it was attempted after completing Lecture 84 - Media Query Breakpoints.
