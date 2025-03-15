# Interactive Cooking Guide

This project is an accessible, step-by-step cooking guide where users can navigate through each cooking step with a screen reader using only HTML and CSS.

## Features

- **Semantic HTML Structure**: Uses proper semantic elements like `<header>`, `<nav>`, `<main>`, `<section>`, etc.
- **Accessible Navigation**: Users can navigate through steps using keyboard controls and screen readers.
- **Dynamic Content Display**: Uses CSS `:target` selector to show/hide steps without JavaScript.
- **Pure CSS Implementation**: All functionality is implemented using only HTML and CSS, no JavaScript.
- **Responsive Design**: Adapts to different screen sizes.
- **High-Quality Images**: Features beautiful cooking images from Unsplash.
- **Dark Mode Support**: Toggle between light and dark themes with persistent preference saving.

## Accessibility Features

1. **Keyboard Navigation**: All interactive elements are focusable and have visible focus states.
2. **CSS-based Visibility Control**: Uses CSS to control which content is visible to screen readers.
3. **Skip Link**: Includes a skip-to-content link for keyboard users.
4. **Semantic Structure**: Clear heading hierarchy and semantic HTML elements.
5. **High Contrast**: Good color contrast for readability.
6. **Alt Text for Images**: All images include descriptive alt text for screen readers.
7. **Dark Mode**: Reduces eye strain in low-light environments with a toggle that announces changes to screen readers.
8. **Respects User Preferences**: Automatically applies the user's system preference for light/dark mode.

## How to Use

1. Open `index.html` in a web browser.
2. Start at the introduction and use the navigation buttons to move through each step.
3. You can navigate using:
   - Mouse clicks on the navigation buttons
   - Keyboard (Tab to focus on buttons, Enter to activate)
   - Screen reader (will announce the current step)
4. Toggle between light and dark mode using the theme button in the top-right corner.

## Technical Implementation

- Uses CSS `:target` selector to show the targeted step and hide others
- Implements a carousel-like navigation pattern using only CSS
- Leverages CSS visibility and display properties for accessibility
- Uses CSS variables for theming and color management
- Implements dark mode with localStorage for preference persistence
- Respects the user's system preference for color scheme
- All images are sourced from Unsplash and optimized for web display

## Image Credits

All images used in this project are from [Unsplash](https://unsplash.com/), a source for freely-usable images.
