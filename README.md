# Responsive Website

A simple responsive website built from scratch using HTML and SCSS without external frameworks or libraries. The layout adapts seamlessly to mobile, tablet, and desktop viewports.

## Features

- **Responsive Design**: Implements a fluid grid and media queries for three breakpoints:
  - Mobile (<600px)
  - Tablet (600px–1023px)
  - Desktop (>=1024px)
- **Consistent Spacing**: Uniform spacing controlled by a single SCSS variable.
- **Typography**: Base font size of 16px, page title at 32px, section titles at 24px.
- **Sticky Footer**: Footer sticks to the bottom when content height is short, otherwise follows the content naturally.
- **SCSS Usage**: Demonstrates variables, nesting, and imports; easily extendable for mixins and loops.

## Getting Started

### Prerequisites

- [Sass (Dart Sass)](https://sass-lang.com/)
- Node.js (for using `npx sass`)

### Compilation
1. **Compile SCSS to CSS**:
   ```bash
   npx sass --watch scss/style.scss:css/style.css
   ```
2. **Open** `index.html` in your browser to view the site.

## Project Structure

```
responsive-website/
├── index.html          # Main HTML file
├── scss/               # Source SCSS files
│   ├── _reset.scss     # Browser reset
│   ├── _variables.scss # SCSS variables and breakpoints
│   └── style.scss      # Main styles and media queries
├── css/                # Compiled CSS files
│   └── style.css
├── images/             # Assets (e.g., logo.png)
└── README.md           # Project documentation
```

## Usage

- **Customize Variables**: Edit `_variables.scss` to change colors, spacing, and breakpoints.
- **Extend Styles**: Add mixins, functions, or loops in `style.scss` for more dynamic styling.
