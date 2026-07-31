# Premier Schools Exhibition - Landing Page

A highly responsive, accessible, and performant landing page built for the Premier Schools Exhibition. The project strictly follows modern web development best practices, utilizing semantic HTML5 and vanilla CSS without relying on heavy external frameworks or libraries.

## 🚀 Features

- **Custom CSS Architecture**: Built entirely with HTML and vanilla CSS using the BEM (Block Element Modifier) naming convention for highly maintainable and modular stylesheets.
- **Advanced CSS Animations**: Features performant, hardware-accelerated animations including an infinite dual-direction horizontal marquee for participating schools, and a staggered vertical looping gallery.
- **Flawless Responsiveness**: Meticulously optimized for all device sizes (Desktop, Tablet/iPad, Mobile). Includes conditional rendering logic (e.g., stripping the animated gallery on mobile to prioritize the lead-generation form and conversion metrics).
- **Accessibility (a11y) First**: Built towards WCAG 2.2 AA compliance standards. Features include:
  - `skip-link` for immediate keyboard navigation to main content.
  - Comprehensive ARIA roles and labels (`role="region"`, `aria-roledescription="carousel"`).
  - Keyboard focus states and traps for interactive elements.
  - `prefers-reduced-motion` media queries that automatically gracefully degrade or pause all continuous animations for sensitive users.
- **Touch-Optimized**: Implements native CSS `scroll-snap` for smooth, app-like horizontal swiping on mobile carousels and grid sections.

## 🛠 Tech Stack

- **HTML5**: Semantic, accessible markup.
- **CSS3**: Custom properties (variables), Flexbox/Grid layouts, Media Queries, and Keyframe animations.
- **Vanilla JavaScript**: Lightweight, minimal JS exclusively used for UI toggles and carousel scrolling logic, ensuring near-instant page load speeds.

## 📁 Project Structure

```
├── index.html          # Main entry point and semantic HTML structure
├── css/
│   ├── style.css       # Core styling, variables, layout, and animations
│   └── responsive.css  # Media queries and device-specific overrides
├── assets/             # Images, logos, and SVGs used in the UI
└── README.md
```

## ⚙️ Development Guidelines

1. **No Frameworks**: Do not introduce Bootstrap, Tailwind, jQuery, or other heavy dependencies. The goal is maximum performance and granular control via vanilla technologies.
2. **BEM Methodology**: All new CSS classes must adhere to the `block__element--modifier` structure to prevent scope bleed.
3. **Accessibility**: Any new interactive elements (buttons, sliders) must have proper `aria-labels`, visible `:focus-visible` states, and respect the reduced motion query.

## 🚀 Getting Started

Simply clone the repository and open `index.html` in your preferred modern web browser (Chrome, Firefox, Safari, Edge). No build step, bundling, or node modules required!
