Web and Scripting Programming Assignment 1

Student Name: Archer Keshtkar Bagheri
Student ID: 100914547 
Live GitHub Pages URL: https://bluejum.github.io/Assignment1/index.html
GitHub Repository URL: https://github.com/BlueJum/Assignment1

---

1. Responsive Viewport Layouts and Dimensions

This site implements a responsive design across three separate CSS stylesheets linked via HTML head media queries without using Flexbox:

Desktop / Laptop Viewport (full.css):

* Media Query: media="only screen and (min-width:960px)"
* Dimension Choice and Justification: Uses a fixed 960px centered wrapper (id wrapper). A width of 960px is the standard desktop grid width, ensuring comfortable line length and clean side-by-side floating sidebars on standard monitors.

Tablet Viewport (tablet.css):

* Media Query: media="only screen and (min-width:481px) and (max-width:960px)"
* Dimension Choice and Justification: Uses a fluid 95% wrapper width and converts the sidebar width to 35%. This range (481px to 960px) targets medium touchscreen devices (such as tablets in portrait and landscape modes), allowing content to expand and contract smoothly.

Mobile Phone Viewport (phone.css):

* Media Query: media="only screen and (max-width:480px)"
* Dimension Choice and Justification: Uses a 100% full-width wrapper with zero side margins and removes sidebar floats (float: none). Devices 480px and narrower have limited horizontal space; stacking content vertically in a single column ensures readability and tap-friendly navigation.

---

1. CSS3 Gradients Implementation

Angle Linear Gradient Application:

* Location: Applied to the body background to all four HTML pages (index.html, about.html, projects.html, and contact.html).
* CSS Code: background: 040620; background: -moz-linear-gradient(135deg, 040620 0%, 500C0C 100%); background: -webkit-linear-gradient(135deg, 040620 0%, 500C0C 100%); background: linear-gradient(135deg, 040620 0%, 500C0C 100%);
* Explanation: Uses a 135-degree angle linear gradient transitioning smoothly from Dark Navy (040620) at the top-left to Dark Burgundy (500C0C) at the bottom-right, fulfilling vendor-prefix cross-browser compatibility standards.

---

1. Adobe Color Scheme Palette

The color scheme was generated using Adobe Color (https://color.adobe.com/create) and applied consistently across all HTML pages and CSS stylesheets:

1. Color 1 (040620 - Dark Navy): Used for header background, footer background, linear gradient starting point, and main heading text.
2. Color 2 (500C0C - Dark Burgundy): Used for nav navigation bar background, linear gradient ending point, and form submit/reset buttons.
3. Color 3 (5F5D16 - Olive): Used for container borders, input field borders, and element drop shadows.
4. Color 4 (E4D281 - Gold): Used for border accents, aside sidebar background, and hover link highlight states.
5. Color 5 (F2E8C0 - Light Cream): Used as the primary wrapper background color and contrast text color for buttons and header text.

---

Code Sources and Citations
  Lecture Material: All HTML5 markup, semantic tags, form structures, media queries, and float-clearing techniques were written based on lectures 1-4.
  Personal coding knowledge
  External Code: 0% external code used from third-party frameworks or websites.
