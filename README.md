

# Overview

This project showcases a preview of my personal portfolio using HTML, CSS, and JavaScript. The portfolio features a collection of "book cards" representing different web projects, which are interactive and animated. The main technologies used are plain HTML, CSS for styling, and the GSAP library for animations.

## File Structure

- `index.html`: Main HTML file that structures the portfolio.
- `styles.css`: External CSS file for styling (though inline styles are heavily used).
- Images and external resources (e.g., Google Fonts, GSAP).

## Contents

### HTML Structure

- **Head Section**: Includes metadata, links to external CSS (Google Fonts), and the GSAP library.
- **Body Section**:
  - **Navbar**: A fixed position navbar with a frosted glass effect.
  - **Bookshelf**: A collection of book cards representing different web projects.
  - **Detail Card**: A personal detail card at the bottom.
  - **Smoke Effect**: An animated background smoke effect.

### CSS Styling

- **Fonts**: Custom fonts from Google Fonts (`Jersey 15`, `Platypi`).
- **Layout**:
  - Centered body with a background image.
  - Flexbox for aligning and spacing elements.
- **Book Cards**: Interactive 3D flip effect and hover animations.
- **Navbar**: A frosted glass effect using `backdrop-filter` and animations.
- **Smoke Effect**: A continuous animation to simulate rising smoke.

### JavaScript (GSAP Animations)

- **Book Cards Animation**:
  - Entrance animation for book cards.
  - Hover and click animations for flipping cards.
- **Bookshelf Animation**: A bumping effect on page load.
- **Detail Card Animation**: Fades in after the bookshelf animation.
- **Navbar Animation**: Slides in and out on page load.


## Dependencies

- **GSAP (GreenSock Animation Platform)**: For animations.
  - Included via CDN: `<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.10.4/gsap.min.js"></script>`
- **Google Fonts**: Custom fonts used in the project.
  - Included via CDN:
    ```html
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Jersey+15&family=Platypi:ital@0;1&display=swap" rel="stylesheet">
    ```


## Browser Compatibility

- Ensure modern browsers are used for full support of CSS features like `backdrop-filter` and GSAP animations.
