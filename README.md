
# DronaUI

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Sass](https://img.shields.io/badge/Sass-^1.32.0-ff69b4)
![License](https://img.shields.io/badge/license-MIT-green)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Contributions](https://img.shields.io/badge/contributions-welcome-orange)

DronaUI is a modern, lightweight CSS framework inspired by popular frameworks like Bootstrap. It focuses on performance, scalability, and ease of use, providing developers with powerful tools to build responsive, customizable, and beautiful user interfaces.

## Features

- **Responsive Grid System**: Easy to create flexible layouts.
- **Customizable Components**: Buttons, forms, cards, modals, and more.
- **Sass-Powered**: Fully customizable with variables and mixins.
- **Lightweight**: Minimal footprint and optimized for performance.
- **Cross-Browser Support**: Works seamlessly in modern browsers.

## Installation

You can easily install DronaUI using npm:

```bash
npm install dronaui
```

Or include it directly via CDN:

```html
<link rel="stylesheet" href="https://cdn.dronaui.com/1.0.0/dronaui.min.css">
```

## Usage

To start using DronaUI, include the CSS file in your HTML file:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <link rel="stylesheet" href="dronaui.min.css">
</head>
<body>
  <div class="container">
    <h1>Hello, world!</h1>
    <button class="btn btn-primary">Click me</button>
  </div>
</body>
</html>
```

## Customization

DronaUI is built with Sass, allowing easy customization. Modify the existing Sass variables to change the design:

```scss
$primary-color: #4CAF50;
$secondary-color: #FFC107;

@import "dronaui.scss";
```

## Development

To contribute or modify DronaUI, clone the repository and install dependencies:

```bash
git clone https://github.com/Ravikisha/DronaUI.git
cd DronaUI
npm install
```

Compile the Sass files by running:

```bash
npm run build
```

## Works TODO

- [x] Padding
- [x] Margin
- [ ] Space Between
- [x] Responsive
- [ ] Text Format
- [ ] Colors
  - [ ] Text Color
  - [ ] Background Color
- [ ] Font
  - [ ] Font Size
  - [ ] Font Family
  - [ ] Font Style
- [ ] Image Styles
- [ ] Animations
- [ ] Border
- [ ] Shadows
- [ ] Buttons
- [ ] Forms
- [ ] Cards
- [ ] Modals
- [ ] Alerts
- [ ] Navbars
- [ ] Dropdowns
- [ ] Tabs
- [ ] Pagination
- [ ] Progress Bars
- [ ] Tooltips
- [ ] Notifications
- [ ] Accordions
- [ ] Carousels
- [ ] Sliders
- [ ] Tables
- [ ] Grid System
- [ ] Flexbox
- [ ] Utilities
- [ ] Accessibility
- [ ] JavaScript Utilities

## Roadmap

- [ ] Add additional UI components (e.g., tooltips, notifications).
- [ ] Improve accessibility features.
- [ ] Add JavaScript utilities for interactive components.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes you would like to make.

## License

DronaUI is licensed under the [MIT License](LICENSE).