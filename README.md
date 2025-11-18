[🔗 View Live Preview](https://rylew0925.github.io/javascript20-projects/Light-Dark-Mode/)

# 🌗 Dark and Light Mode Toggle Project

This project demonstrates a dynamic theme toggle system with responsive layout, animated feedback, and a Matrix-style background effect in dark mode. Built from scratch with a focus on accessibility, usability, and contributor-level clarity.

---

## ✨ Features

- **Theme Toggle Switch**  
  Users can switch between light and dark modes using a custom toggle with animated icons and keyboard shortcut support.

- **Matrix Background Animation**  
  A green raining code effect appears in dark mode using a `<canvas>` element and JavaScript animation.

- **Dynamic Image Swapping**  
  SVG illustrations automatically switch between light and dark versions based on the selected theme.

- **Responsive Layout**  
  The About section adapts from horizontal to vertical stacking on smaller screens.

- **Accessible Design**  
  Semantic HTML, labeled inputs, and ARIA attributes ensure keyboard and screen reader compatibility.

- **Keyboard Shortcut**  
  Press `Ctrl + T` to toggle themes instantly without using the mouse.

- **Animated Feedback**  
  Toggle icons rotate on theme change for visual feedback.

---

## 🌗 Theme Toggle Implementation

The theme toggle is implemented using:

- A checkbox input (`#theme-toggle`)
- JavaScript logic to update:
  - `data-theme` attribute on `<html>`
  - Background colors for navigation and text box
  - Image sources based on theme state
  - Icon and label text
- Local storage to persist user preference across sessions
- Canvas animation triggered only in dark mode

```js
image1.src = `img/undraw_profile_${modeState}.svg`;
image2.src = `img/undraw_developer_activity_${modeState}.svg`;
image3.src = `img/undraw_feedback_${modeState}.svg`;
