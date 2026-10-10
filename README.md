# Assignment #3 — Responsive Web Design
## Student information
- **Name:** Akshit Khokher
- **Group:** Replace with your group
- **Course:** Front-End Development
- **Topics:** CSS Media Queries and Bootstrap 5 Grid

> Before submitting, replace the group and contact details in `index.html` and this README with your real information.

## Project overview
This project completes the five tasks in Assignment #3. It uses basic HTML and CSS plus Bootstrap 5. The page is designed to adjust to mobile, tablet, and desktop screens.

## How to run
1. Download or clone this project.
2. Open `index.html` in a browser. An internet connection is needed to load Bootstrap from its CDN.
3. Resize the browser or use Developer Tools → device toolbar to test mobile, tablet, and desktop sizes.

## Part 1 — Media Queries

### Task 0: Responsive Typography
The page has headings and paragraphs. CSS media queries change heading and paragraph sizes at mobile, tablet, and desktop widths.
- Mobile: up to 575.98px
- Tablet: 576px–991.98px
- Desktop: 992px and wider

**Screenshot:** Save a screenshot showing the typography on a mobile screen as `screenshots/task-0-mobile.png`, and optionally add tablet/desktop versions.

### Task 1: Responsive Layout with Media Queries
Three boxes are created using CSS Grid, without Bootstrap:
- Desktop: three boxes in one row.
- Tablet: two boxes in the first row and the third on the next row.
- Mobile: boxes stack vertically.


## Part 2 — Bootstrap Grid System

### Task 2: Bootstrap Responsive Columns
The three columns use Bootstrap's 12-column grid:
- `col-12`: one full-width column on mobile.
- `col-md-6`: two half-width columns per row on tablet.
- `col-lg-4`: three equal columns on desktop (4 + 4 + 4 = 12).



### Task 3: Bootstrap Navigation Bar
The navbar uses Bootstrap 5 components. The logo is on the left and links are on the right on larger screens. The navbar toggler collapses the links into a hamburger menu on smaller screens. Bootstrap's JavaScript bundle powers the menu.


## Part 3 — Combined Project

### Task 4: Responsive Portfolio Page
The portfolio combines:
1. A Bootstrap navigation bar.
2. A main area with project cards on the left and student information/contact sidebar on the right on desktop.
3. A footer across the bottom.
4. Bootstrap grid classes for project cards.
5. Custom media queries for font sizes, spacing, and small-screen visibility.

On small screens the columns stack, spacing is reduced, and the decorative menu explainer icon is hidden on very narrow screens.


## Summary of work process
First, I created the HTML structure for each assignment task. Next, I added CSS media queries for responsive typography and the CSS-only three-box layout. I used Bootstrap 5's 12-column grid for the three responsive columns, then created a collapsible navbar. Finally, I combined these components into a portfolio page with project cards, a student-information sidebar, and a footer. I tested the layout by resizing the browser and checking the mobile, tablet, and desktop breakpoints.

## Files
- `index.html` — page structure and Bootstrap components.
- `style.css` — styling and responsive media queries.
- `screenshots/` — add screenshots for each task here.

