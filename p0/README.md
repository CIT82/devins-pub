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