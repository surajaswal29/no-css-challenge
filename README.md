# No CSS Challenge

A web development project demonstrating the power of pure HTML without any CSS
styling. This project showcases how to create a functional and structured
webpage using only HTML elements.

## Live Demo

[No CSS Challenge](https://surajaswal29.github.io/vanilla-HTML/nocss.html)

## Project Structure

```
vanilla-HTML/
├── index.html          # Blog homepage (pure HTML: no CSS, no JavaScript)
├── about.html          # About page
├── contact.html        # Contact page
├── services.html       # Services page
├── posts/             # Four tutorial posts on HTML
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

## The Quiet Web: the blog (no CSS, no JavaScript)

The blog at the root (`index.html`, `about.html`, `services.html`,
`contact.html` and `posts/`) uses **no CSS at all**: no `<style>`, no `style=""`
attributes, no stylesheets. It uses no JavaScript either. Everything below is
plain HTML (plus SVG markup):

| What you see | How it is built |
| --- | --- |
| Sage, mist and sand colour scheme | `bgcolor`, `text`, `link` and `vlink` on `<body>`, tables and rows |
| Serif reading type and sizes | `<font face>` and `<font size>` |
| Centred reading column that fits phones | A table cell with `width="720"` between two empty cells |
| Hairline card borders | A 1px `cellpadding` in the line colour around an inner table |
| Drifting clouds, a glowing sun, a breathing circle | SVG with SMIL animation (`<animate>`, `<animateTransform>`, `<animateMotion>`) |
| "Take a mindful minute" modal | `<dialog>` opened by `<button commandfor command="show-modal">` |
| Footnotes | `popover` + `popovertarget` |
| Accordions, one open at a time | `<details name>` |
| Exercise solutions revealed by a link | `hidden="until-found"` + a `#fragment` link |
| Live code previews | `<iframe srcdoc sandbox>` |
| "Download this page" | `<a download href="data:…">` |
| Soft data tables | `frame`, `rules`, `bordercolor`, `cellpadding`, `scope`, `<caption>` |
| Level and series progress | `<meter>` and `<progress>` |
| Form validation and demos that never leave the page | `required`, `pattern`, `minlength`, `<datalist>`, `method="dialog"` |
| Keyboard shortcuts | `accesskey` on the main navigation |
| Site search | `<search>` with a GET form to DuckDuckGo |

Attributes such as `bgcolor` and `<font>` are obsolete for authors, but the HTML
standard still defines how browsers render them, so they work in every browser.
SMIL animations don't follow the operating system's reduced-motion setting, so
all motion here is slow and subtle.

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/surajaswal29/vanilla-HTML.git
   ```
2. Open `index.html` in your web browser
3. Explore the HTML-only implementation

## Technologies Used

- HTML (the living standard), including `<dialog>`, `popover`, `<details name>` and `<search>`
- SVG with SMIL animation for illustrations and motion
- HTML tables and presentational attributes for layout and colour
- Semantic HTML elements

## License

This project is open source and available under the MIT License.

---

Made with ❤️ by Suraj Aswal
