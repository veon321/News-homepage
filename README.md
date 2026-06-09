# Frontend Mentor - News homepage solution

This is a clean, responsive, and modern solution to the News homepage challenge on Frontend Mentor.

## Links

- Solution URL: [https://github.com/veon321/news-homepage](https://github.com/veon321/news-homepage)
- Live Site URL: [https://veon321.github.io/news-homepage/](https://veon321.github.io/news-homepage/)

## Built with

- **Semantic HTML5 markup**: Structured using appropriate layout elements (`<main>`, `<header>`, `<nav>`, `<article>`, `<aside>`, and `<section>`) to establish a clean DOM tree, ensuring optimal readability and semantic clarity for search engines and assistive technologies.
- **CSS Custom Properties (Variables)**: Implemented for strict adherence to the challenge's active design system, encapsulating the required HSL color tokens (`--soft-orange`, `--soft-red`, etc.) and typography parameters.
- **Flexbox Layout**: Employed as the core architecture to map the layout interface across a fluid system with explicit alignment control, managing both the structural multi-column layout and internal distribution within individual component cards.

## Features

- **Fluid Multi-Column Alignment**: Leverages explicit Flexbox property mappings (`flex: 0 0 68%`, `flex: 1`) to flawlessly position the primary content block and the high-contrast "New" sidebar side-by-side, achieving perfectly synchronized heights (`align-items: stretch`).
- **Adaptive Single-Column Reflow**: Utilizes responsive media queries to dynamically dissolve the multi-column desktop matrix into a streamlined, high-contrast vertical column on mobile viewports, restructuring navigation and card layouts to maintain ideal readability.
- **Optimized Asset Containment**: Controls asset rendering through strict bounding rules (`width: 100%`, `height: auto`, `display: block`), ensuring images scale proportionally without inducing structural layout shifts (CLS) across the viewport continuum.
