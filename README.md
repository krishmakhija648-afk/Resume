# Resume
# CSS Concepts Application - Resume Enhancement

**GitHub Link:** [(https://github.com/krishmakhija648-afk/Resume)]

## Overview
This write-up describes the updates made to my personal resume website to improve aesthetics, layout, and visual organization using modern CSS skills. By implementing concepts such as CSS Grid, Flexbox, robust selectors, and custom fonts, the site provides a much richer, premium user experience compared to default HTML styling.

## 1. Typography Improvements
- **Google Fonts Integration:** Two new font families from Google Fonts have been integrated (`Inter` for the body text, and `Outfit` for headings and navigation). This creates a modern, sleek reading experience. 
- **Font Hierarchy:** Adjusted variable font weights (e.g., `wght: 400`, `600`, `800`) to visually distinguish between regular paragraphs, subheadings, and main calls to action, drawing the user's attention seamlessly down the page.

## 2. Color Palette Strategy
- **Consistent Dark Theme:** Developed a bespoke color palette utilizing CSS variables (`:root`). The main background utilizes a deep `slate-navy` (`#0a192f`) accented by a stark neon `teal/emerald` (`#64ffda`).
- **Contrast & Readability:** Text colors are mapped to softer grays (`#8892b0` and `#ccd6f6`) rather than harsh pure whites, preventing eye strain and contributing to the premium aesthetic.

## 3. Advanced Layout & Positioning
- **Flexbox Navigation:** Evaluated `display: flex;` in the `<header>` element to achieve a sticky navigation bar with items spaced evenly via `justify-content: space-between`.
- **CSS Grid Structures:** Leveraged `display: grid;` for complex layouts such as the **Technical Expertise** (skills) section to effortlessly maintain flexible, responsive columns (`grid-template-columns: repeat(auto-fit, minmax(250px, 1fr))`).

## 4. Polished Selectors & Micro-Interactions
- utilized class target selectors, descendent selectors, and pseudoclasses (`:hover`, `::before`, `::after`) efficiently.
- **Hover Effects:** Embedded subtle CSS transitions, such as slight upward translations `transform: translateY(-8px)` combined with dynamic soft box-shadows on skill cards and buttons.
- A smooth scaling bar pseudo-element (`::before`) trick is used to highlight the side of feature project cards upon hover events.

## Summary
The combination of defined Design Tokens via CSS variables alongside modernized Flexbox and Grid layouts dramatically improved the usability, consistency, and visual layout of the original HTML content. The result is a fully cohesive, responsive portfolio.
