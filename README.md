# web-part-2
# Apex Auto Designs — Website

## Project Overview
Apex Auto Designs is a custom car design studio website built as part of the WEDE5020 Web Development module. The website showcases the studio's services, team, and contact information across four fully responsive pages.

---

## Pages
- `index.html` — Home page
- `about.html` — About the studio and team
- `services.html` — Full list of services and pricing
- `contact.html` — Contact form and studio information

---

## Technologies Used
- HTML5
- CSS3 (External Stylesheet — `styles.css`)
- JavaScript (Vanilla JS — `script.js`)
- Google Fonts — Bebas Neue, Cormorant Garamond, Barlow

---

## CSS Features Implemented
- CSS Variables (`:root`) for consistent colour scheme
- CSS Grid and Flexbox for layout structure
- `clamp()` for fluid typography
- Relative units (`rem`, `em`, `%`) throughout
- `:hover`, `:focus`, `:active` pseudo-classes
- `@keyframes` animations (shimmer, fadeUp, marquee, bounce)
- Media queries with breakpoints at 900px, 768px, and 480px
- Responsive images using `<picture>` and `srcset`

---

## Responsive Design Breakpoints
| Breakpoint | Target Device |
|---|---|
| 900px | Tablet landscape |
| 768px | Tablet portrait / Mobile |
| 480px | Small mobile |

---

## Colour Scheme
| Name | Hex |
|---|---|
| Black | `#080808` |
| Dark | `#0e0e0e` |
| Gold | `#D4AF37` |
| Gold Light | `#F0D060` |
| White | `#F5F0E8` |

---

## Changelog

### Part 2 Updates
- Added external stylesheet (`styles.css`) linked to all 4 HTML pages
- Implemented luxury black and gold colour scheme using CSS variables
- Added Google Fonts — replaced Arial with Bebas Neue, Cormorant Garamond, and Barlow
- Built CSS Grid layout for cards, services grid, team grid, and footer
- Built Flexbox layout for navigation, hero stats, and CTA sections
- Added responsive breakpoints at 900px, 768px, and 480px
- Added `:focus` styles on all form inputs with gold glow effect
- Added `:active` styles on all buttons
- Added `clamp()` for fluid font sizes across all headings
- Added `@keyframes` animations — shimmer, fadeUp, marquee, bounce
- Added full-bleed hero background image with dark overlay
- Added scrolling marquee bar
- Added responsive images using `<picture>` and `srcset` attributes
- Added process section, image strip section, and expanded footer

### Part 1 Fixes (Based on Feedback)
- Fixed duplicate HTML documents nested inside one file
- Removed broken `<img src="golfs">` tag
- Fixed hamburger menu — added `onclick="toggleMenu()"` and JavaScript toggle function
- Added missing `</head>` and `<body>` closing tags
- Replaced generic `Arial` font with professional Google Fonts
- Replaced `px` units with `rem`, `em`, `%`, and `clamp()`
- Replaced random clashing colours with cohesive design system
- Added CSS variables for consistent theming
- Added media queries for responsive design
- Added `:focus` and `:active` pseudo-classes
- Added CSS Grid and Flexbox layout structure

---

## References
[1] Mozilla Developer Network, "CSS Grid Layout," *MDN Web Docs*, 2024. [Online]. Available: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout. [Accessed: May 2026].

[2] Mozilla Developer Network, "Using media queries," *MDN Web Docs*, 2024. [Online]. Available: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries. [Accessed: May 2026].

[3] Mozilla Developer Network, "Responsive images," *MDN Web Docs*, 2024. [Online]. Available: https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images. [Accessed: May 2026].

[4] Google Fonts, "Bebas Neue," *Google Fonts*, 2024. [Online]. Available: https://fonts.google.com/specimen/Bebas+Neue. [Accessed: May 2026].

[5] W3Schools, "CSS Flexbox," *W3Schools*, 2024. [Online]. Available: https://www.w3schools.com/css/css3_flexbox.asp. [Accessed: May 2026].

[6] W3Schools, "HTML Responsive Web Design," *W3Schools*, 2024. [Online]. Available: https://www.w3schools.com/html/html_responsive.asp. [Accessed: May 2026].

---

## Author
**Ibanati Malingo**
WEDE5020 — Web Development (Introduction)
The Independent Institute of Education
2026
