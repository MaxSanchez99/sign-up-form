# Sign-Up Form

A clean and visually appealing **sign-up form** built as part of *The Odin Project’s Intermediate HTML and CSS course*. This project demonstrates practical use of forms, layout structure, and styling techniques such as custom fonts, pseudo-classes, and background effects.

---

## Project Overview

This project replicates a sign-up form for an imaginary online service.  
The goal is to practice structuring a full web page, styling form elements, and handling user interactions using pure HTML and CSS.

---

## Features

- Clean, structured HTML layout  
- Custom background image with semi-transparent overlay  
- External font for the logo (e.g., *Norse Bold* or similar)  
- Styled input fields with:
  - **Default:** light border (`#E5E7EB`)
  - **Focus:** blue border and subtle shadow
  - **Invalid:** red border for incorrect password input  
- Styled “Create Account” button (`#596D48`) matching the page tone  
- Hover and focus states for inter

---

## Project Structure

.
├── index.html
├── style.css
├── images/
│ ├── plants.jpg
├── fonts/
| ├── Norse-Bold.otf
└── README.md


---

## Design Notes

- **Background Image:**  
  Custom image located in `/images/plants.jpg`  
  (original design used an Unsplash photo — remember to credit if used)

- **Logo:**  
  Odin logo sourced directly from The Odin Project’s curriculum:  
  `https://cdn.statically.io/gh/TheOdinProject/curriculum/.../odin-lined.png`

- **Font:**  
  Imported via `@font-face` from `/fonts/Norse-Bold.otf`  
  ```css
  @font-face {
      font-family: 'Norse';
      src: url('fonts/Norse-Bold.otf') format('opentype');
      font-weight: bold;
      font-style: normal;
  }

---

## 💡 Lessons Learned

- Using semantic HTML for forms and page structure  
- Styling input states with pseudo-classes (`:focus`, `:invalid`)  
- Enhancing readability using overlays and contrast  
- Maintaining consistent spacing, typography, and color themes  
- Building layouts with `flexbox`
