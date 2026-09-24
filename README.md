# No CSS Challenge

A web development project demonstrating the power of pure HTML without any CSS
styling. This project showcases how to create a functional and structured
webpage using only HTML elements.

## Live Demo

[No CSS Challenge](https://surajaswal29.github.io/vanilla-HTML/nocss.html)

## Project Structure

```
vanilla-HTML/
├── index.html          # Main blog homepage
├── about.html          # About page
├── contact.html        # Contact page
├── services.html       # Services page
├── posts/             # Directory containing blog posts
├── portfolio/         # Business and product portfolio: HTML + CSS, zero JavaScript
└── css-miracles/      # The opposite challenge: pure CSS, zero JavaScript
```

## CSS Miracles

The flip side of the challenge. Open `css-miracles/index.html` for a gallery of
designs built with only HTML and CSS: no JavaScript, no images, no libraries.

| Piece | Highlights |
| --- | --- |
| `cube.html` | Nested 3D cubes over a synthwave grid (`preserve-3d`, `perspective`) |
| `solar-system.html` | Animated orrery on a tilted orbital plane |
| `landscape.html` | A day-to-night cycle driven by animated `@property` colours |
| `interactive.html` | Dark mode, tabs, star rating, flip card, accordion and a counting checklist, all powered by `:checked` and `:has()` |
| `neon.html` | Flickering neon sign and a glitch headline |
| `aurora.html` | Glassmorphism card with a rotating conic-gradient border |
| `loaders.html` | Twelve loading indicators |
| `coffee.html` | CSS illustration with rising steam and latte art |
| `breathe.html` | Guided box breathing; the text cue itself is animated with `content` |
| `ocean.html` | Moonlit sea with layered rolling waves and a shimmering reflection |
| `rain.html` | Rainy window: bokeh lights, fogged glass, sliding drops |
| `fireflies.html` | Dusk meadow with fireflies, each on its own path and rhythm |
| `lava-lamp.html` | Gooey metaball lava lamp (`filter: contrast()` + `blur()`) |
| `hypnosis.html` | Phyllotaxis sunflower with `sqrt()`, pendulum wave, twisting tunnel |
| `patterns.html` | Twelve seamless single-background patterns |
| `scroll.html` | Scroll-driven animations with `animation-timeline` (Chrome / Edge) |

## Portfolio: a real site with no JavaScript

`portfolio/` is a four-page business and product portfolio for a fictional
studio, built to show that a normal company website does not need JavaScript to
feel modern. Each page is one HTML file plus one shared stylesheet: no scripts,
no image files and no web fonts. The largest page is about 11 KB gzipped
including the CSS, and the stylesheet is cached after the first visit.

| Feature | Built with |
| --- | --- |
| Mobile menu | `popover` + `popovertarget`, placed with CSS anchor positioning |
| Product quick views and booking modal | `<dialog>` opened by `<button commandfor command="show-modal">`, `closedby="any"` |
| Dialog fade in and out | `@starting-style` + `transition-behavior: allow-discrete` |
| Product filter and case-study tabs | Radio buttons read with `:has()` |
| Monthly / yearly pricing | A checkbox switch read with `:has()` |
| FAQ accordion | `<details name>` (one open at a time), animated with `::details-content` |
| Testimonials carousel | Scroll snap, with `::scroll-marker` dots where supported |
| Form validation | `required`, `type="email"`, `minlength`, `<datalist>`, messages via `:user-invalid` |
| Light and dark themes | `color-scheme` + `light-dark()` |
| Page-to-page animation | Cross-document view transitions (`@view-transition`) |
| Instant navigation | Speculation rules (a JSON block, not script) prerender pages on hover |
| Product artwork | CSS gradients and pseudo-elements, no image downloads |

Every feature is progressive: older browsers still get a working, readable site.
The contact form uses `mailto:` because a static site has no server; point its
`action` at a form service to collect submissions.

## Features

- Pure HTML implementation with no CSS dependencies
- Responsive layout using HTML tables
- Interactive navigation menu
- Blog post listing with thumbnails
- SVG-based illustrations and graphics
- Contact form implementation
- Semantic HTML structure for better accessibility

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/surajaswal29/vanilla-HTML.git
   ```
2. Open `index.html` in your web browser
3. Explore the HTML-only implementation

## Technologies Used

- HTML5
- SVG for graphics and illustrations
- HTML Tables for layout
- Semantic HTML elements

## License

This project is open source and available under the MIT License.

---

Made with ❤️ by Suraj Aswal
