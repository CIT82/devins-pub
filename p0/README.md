# Project 0: Template Analysis (Part 1)
**Template Name:** AdminHMD
**Bootstrap Version:** v5.3.8

---

## Section 1: `<head>` Analysis
- **External CSS:**
  - [Bootstrap CSS](./assets/css/bootstrap.min.css) is used for responsive design.
  - [Bootstrap Icons](./assets/vendors/bootstrap-icons/bootstrap-icons.css) is used to add icons in a element.
- **Custom CSS:** [Main CSS File](./assets/css/style.css) styles the main elements.

## Section 2: Site Inventory (Top Half)

### Navigation (Admin Navbar)
**Line Numbers:** 93-145
**Top-Level Classes:** `navbar admin-navbar navbar-expand bg-white`
**Research:** The classes set the background color to white and text color to black. A backdrop-filter is added to set a blur of 14px. A transition is set for visual effect for color and box-shadow. The `.admin-navbar` makes the position sticky to the top of the page when scrolling down.

### Navigation (Hamburger Menu)
**Line Numbers:** 29-78
**Top-Level Classes:** `.sidebar-nav`
**Research:** The class turns the display into grid. Instead of the elements being compact, they're spaced out.

### Main Content
**Line Numbers:** 147-356
**Top-Level Classes:** `.dashboard-content`
**Research:** It calculate and set the minimum height of the page which is `calc(100vh - 132px)`

### Dashboard (Section 1)
**Line Numbers:** 161-217
**Top-Level Classes:** `row g-3 mt-1`
**Research:** The margin spaces the section out of its siblings. The gap is used to add spaces between the boxes inside the section.

## Section 3: Site Inventory (Bottom Half)

### Sale Performance (Section 2)
**Line Numbers:** 219-257
**Top-Level Classes:** `row g-3 mt-1`
**Research:** The classes adds a gap between the sections so the interface does not look cluttered.

### Recent Users (Section 3)
**Line Numbers:** 259-354
**Top-Level Classes:** `panel mt-3`
**Research:** The `mt-3` adds a gap to separate it from the section above it. The `panel` is used for pseudo class `:hover` to add a tiny detail when hovering over the section box.

### The Footer
**Line Numbers:** 358-363
**Top-Level Classes:** `admin-footer`
**Research:** It overwrite the style to set font size and color. It also add a padding to add a gap at the bottom of the page.