# Bug Crawl Debugging Lab 🐞

This project was completed as part of the CodePath SITE Summer Internship's **Bug Crawl Lab**, where I practiced debugging common HTML and CSS layout issues using DevTools, CSS validators, and responsive design principles.

## ✅ Overview

The goal was to inspect, debug, and improve a pre-built but buggy web layout. I identified and fixed issues in the box model, Flexbox layout, responsiveness, and CSS inheritance.

---

## 🛠️ Fixes and Improvements Made

### 🔹 HTML Fixes
- Fixed incorrect or missing closing tags
- Ensured valid and semantic structure
- Applied proper nesting for all elements

### 🔹 CSS Fixes
- Corrected padding, margin, and borders to match intended box model behavior
- Explicitly set `box-sizing`, `display`, and `position` for layout clarity
- Added `.feature-item` and `.centered-text` classes to overlay text on images using:
  - `position: absolute`
  - `transform: translate(-50%, -50%)`
- Implemented responsive design with media queries:
  - Adjusted `.feature-container` to stack on small screens
  - Centered and resized text for mobile view
- Built a responsive **multi-column footer** using Flexbox:
  - Used `flex-wrap` for wrapping
  - Styled with spacing, alignment, and mobile adjustments

### 🔹 Layout Adjustments
- Made feature section images smaller using `width` and `max-width`
- Centered overlay text on images
- Cleaned up inconsistent spacing between boxes using DevTools

---

## 🖼️ Final Layout Preview

| Desktop View |  
|--------------|
| ![Final Layout](Screenshot%202025-06-05%20at%2012.07.27.png) |

*(Ensure the image file is saved in the same folder and named exactly as above.)*

---

## 🧰 Tools Used
- VS Code + Prettier for formatting
- Chrome DevTools for inspecting and live-editing styles
- W3C Validators (HTML & CSS)
- Flexbox for layout control
- Media queries for responsive design

---

## 📌 Lessons Learned
- How to debug layout issues with DevTools
- The power of `position: relative` and `absolute` for text overlays
- How `flex-wrap` and `flex-basis` affect responsiveness
- Practical understanding of the box model and margin collapsing
- The importance of semantic and accessible HTML

---

## 📁 How to Run
1. Clone or download this repo
2. Open `index.html` in a browser
3. View and resize window to test responsiveness

---

## ✨ Credit
Created by **Sarvesh Tiku** for the CodePath SITE Summer Internship Bug Crawl Lab.
