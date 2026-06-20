# WDD 331R Practice Site
**Student:** James Wright
**Semester:** Spring 2026
**Live Site:** [View Site](https://jamesrwri.github.io/wdd331-practice/)
## About
This repository is my Practice Site for WDD 331R: Advanced CSS.
Each week I add new pages and styles as I work through the course
assignments. The site deploys automatically to GitHub Pages on
every push to main.
## Purpose of This Site
The purpose of this site is to help me refine my advanced CSS skills, practice modern layout techniques, master design implementations, and build out a token-first pipeline using Lightning CSS.
## Pages
- [Home](index.html)
- [Custom Properties and Nesting](unit-1/custom-properties/index.html)
- [Layered Components](unit-2/layered-components/index.html)
- [Tailwind CSS](tailwind-awareness.html)
- [Custom Media](custom-media.html)
- [Visual Effects](visual-effects.html)
- [Blend Modes](blend-modes.html)
- [Unit 4 Assignment: Editorial Layout](grid-layouts/editorial.html) - Structural micro layout mapping zone components cleanly via responsive CSS Grid Named template areas.
- [Unit 4 Assignment: Fluid Card Grid System](grid-layouts/cards.html) - Scalable matrix configuration leveraging auto-fit generation configurations and custom nested column container min() clamp structures.
- [Container Query Component](./advanced/container-demo.html) - Context-aware interface cards altering their structural layout rules fluidly on the inline axis according to individual container limitations.
- [Sticky Sidebar Navigation Module](./advanced/sticky-demo.html) - Fixed layout components tracking viewport scroll lines with detailed diagnostic notations handling the ancestor overflow visible override rule.
## Typography Token Architecture

* **Token File Location:** All typography values are completely managed within `css/tokens/variables.css`.
* **Web Font Choice:** The site features **Lora** as a high-contrast serif typeface for all headings, paired with **Montserrat** as a clean system fallback stack for highly readable body copy blocks.
* **Font Display Optimization:** Configured using the native `display=swap` parameter method, ensuring the browser immediately renders text using safe system fallbacks while the remote font downloads, eliminating invisible layout shifting delays.
* **Fluid Scaling Scaling Range:** Built using a Major Third modular scale mapped into dynamic `clamp()` equations that scale font sizes fluidly from a minimum mobile screen width of 320px up to a maximum desktop layout boundary constraint of 1200px without utilizing media query breakpoints.