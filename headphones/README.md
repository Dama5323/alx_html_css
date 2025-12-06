# 🎧 Headphones Webpage Implementation 

<div align="center">

![Headphones Hero](https://img.shields.io/badge/Headphones-Project-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Design-green)
![Accessibility](https://img.shields.io/badge/Accessibility-AAA-orange)

*A fully responsive webpage implementation built from scratch using only HTML5 and CSS3, based on a Figma design by Nicolas Philippot*

</div>

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Design Specifications](#design-specifications)
- [Features Implemented](#features-implemented)
- [Implementation Details](#implementation-details)
- [Getting Started](#getting-started)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Project Overview

A fully responsive webpage implementation built from scratch using only HTML5 and CSS3, based on a Figma design by Nicolas Philippot. This project demonstrates modern web development practices including responsive design, accessibility, and clean code architecture.


### 🚀 Quick Start
```bash
# Clone the repository
git clone https://github.com/yourusername/alx_html_css.git

# Navigate to the project directory
cd alx_html_css/headphones

# Open the final implementation
open 8-index.html  # or use your preferred browser
```


## Project Structure
```text
alx_html_css/headphones/
│
├── 📄 README.md                        # This file
│
├── 📁 images/                          # All image assets
│   ├── logo_headphones.png
│   ├── headphones_hero_1.jpg
│   ├── headphones_hero_2.jpg
│   └── ...
│
├── 📁 holberton_school-icon/           # Custom icon font
│   ├── style.css
│   ├── holberton_school-icon.eot
│   ├── holberton_school-icon.svg
│   ├── holberton_school-icon.ttf
│   └── holberton_school-icon.woff
│
├── 📁 fonts/                           # Custom fonts
│   ├── SourceSansPro-Regular.otf
│   ├── SourceSansPro-SemiBold.otf
│   ├── Spin-Cycle-OT.otf
│   └── ...
│
├── 📄 0-index.html                     # Task 1: Header/Hero section
├── 📄 0-styles.css
│
├── 📄 1-index.html                     # Task 2: + What We Do section
├── 📄 1-styles.css
│
├── 📄 2-index.html                     # Task 3: + Our Results section
├── 📄 2-styles.css
│
├── 📄 3-index.html                     # Task 4: + Contact Us section
├── 📄 3-styles.css
│
├── 📄 4-index.html                     # Task 5: + Footer section
├── 📄 4-styles.css
│
├── 📄 6-index.html                     # Task 6: Custom pentagons (no images)
├── 📄 6-styles.css
│
├── 📄 7-index.html                     # Task 7: Animated sections
├── 📄 7-styles.css
│
└── 📄 8-index.html                     # Task 8: + Hamburger menu (Final)
    📄 8-styles.css
    📄 8-script.js
```

### Design Specifications
## Typography

| Font | Usage | Weights |
|------|-------|---------|
| **Source Sans Pro** | Primary text | 300, 400, 600, 700 |
| **Spin-Cycle-OT** | Decorative elements | Regular |


## Color Palette
| Element | Color | Hex Code |
|---------|-------|----------|
| Primary Text | Dark Blue | `#071629` |
| Links Hover/Active | Coral Red | `#FF6565` |
| Background | White | `#FFFFFF` |
| Gradient | Custom | Linear gradients |

### Layout Specifications
- Maximum Content Width: 1000px (centered)

- Mobile Breakpoint: ≤ 480px

- Container Padding: 20px on all sides

- Desktop: Full responsive layout

- Mobile: Stacked layout with hamburger menu


### Features Implemented
1. Responsive Header & Hero Section ✅
- Full-screen hero with gradient overlay

- Navigation with hover effects

- Responsive logo and menu

- Call-to-action button with interactive states

2. "What We Do..." Section ✅
- Four service items with custom icon font

- Circular gradient backgrounds

- Responsive grid layout

- Consistent typography hierarchy

3. "Our Results" Section ✅
- Background image with overlay

- Custom pentagon shapes (implemented with CSS)

- Percentage display with labels

- Grid layout for results

4. Contact Form ✅
- Accessible form with proper labels

- Required field validation (HTML5)

- Submit button with hover effects

- Responsive form layout

5. Footer ✅
- Logo and navigation links

- Social media icons

- Copyright information

- Consistent styling with other sections

6. Advanced Features ✅
- CSS Pentagons: Custom shapes without image files

- Animations: Hover and scroll animations

- Hamburger Menu: JavaScript-powered mobile navigation

- Accessibility: ARIA labels, semantic HTML, keyboard navigation