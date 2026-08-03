# Portfolio

**Author:** Neev Modi  
**Course:** Full Stack Development (Assignment 1)  
**Institution:** National Institute of Technology, Warangal  

---

## Design 
The portfolio is designed with a modern, warm neutral palette using WCAG AA-compliant contrast ratios to ensure maximum accessibility and visual clarity. The layout prioritizes a minimalist developer identity, highlighting core technical skills, academic background, and key project achievements. Smooth scrolling, subtle hover micro-interactions, and fade-in keyframe animations provide intuitive user feedback without compromising site performance.

## Layout Technique Justification
- **Flexbox:** Used for one-dimensional structural components, including the header, sticky navigation menu, skills tags, contact form layout, and footer links. Flexbox ensures precise alignment, effortless vertical/horizontal centering, and flexible element wrapping across varied screen resolutions.
- **CSS Grid:** Employed specifically in the Projects section using `grid-template-columns: repeat(auto-fit, minmax(260px, 1fr))`. This approach creates a two-dimensional layout that dynamically reflows project cards into multi-column or single-column grids based on available viewport width, minimizing hardcoded media query overrides.

## Known Limitations
- The contact form is built as a pure static HTML5 structure and does not send live network requests.
- Dark theme styling custom properties are structured in CSS variables but currently lack a JavaScript toggle control.

## AI & Tooling Disclosure
Assistance from AI tools was limited to debugging HTML validation syntax, verifying WCAG color contrast levels, and reviewing responsive CSS layout behavior.
