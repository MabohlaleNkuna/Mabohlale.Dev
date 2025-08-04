# Project README: Personal Portfolio Website

## Overview

This project is a **responsive personal portfolio website** built with HTML, CSS, and some external icon libraries. It showcases various sections such as About, Education, Programming Languages, Projects, and Contact, all within a single-page layout with smooth navigation.

---

## Project Structure

- `index.html` — Main HTML file containing the entire webpage markup.
- `styles.css` — Main stylesheet for the site’s styles.
- `experience.css` — Additional CSS for specific sections (e.g., Education).
- `assets/` — Folder containing images and downloadable files like the CV PDF.
- External icons are used via **Bootstrap Icons CDN**.

---

## Features & Functionality

### 1. Single Page Layout with Section Anchors

The page is divided into multiple **sections** identified by `id`s:

- `#about` — About Me section
- `#education` — Educational Background
- `#languages` — Programming Languages
- `#projects` — Projects portfolio
- `#contact` — Contact details and form

Each section is clearly marked in the HTML with `<section id="...">` to allow direct navigation.

---

### 2. Navigation

#### Bottom Navigation Bar

- A fixed navigation bar at the bottom of the viewport contains icons linking to each main section.
- Uses `<nav class="bottom-nav">` with anchor tags `<a href="#section-id">` to jump to each section.
- Each nav icon has a `title` attribute and uses Bootstrap Icons for visuals.

**How navigation works:**

- Clicking a navigation icon triggers a jump to the corresponding section via anchor scrolling.
- The `href` attributes correspond directly to the section IDs on the page.
- This creates smooth user experience on both desktop and mobile devices.

#### Scroll-Down Arrow in Header

- On the hero/header section, a scroll-down arrow (`&#x21e3;`) links specifically to the Contact section (`#contact`).
- Clicking it smoothly scrolls the user down to the contact form.

---

### 3. Section Details

#### About Me Section

- Displays a profile image alongside a short bio paragraph.
- Uses a two-column layout with an image on one side and text on the other.

#### Educational Background

- Lists educational history as cards in a grid layout.
- Includes a **Download CV** button linking to a PDF file in the assets.

#### Programming Languages

- Displays cards with icons and language names.
- Icons are styled using Bootstrap Icons with specific colors.

#### Projects Section

- Displays a grid of project cards.
- Each card contains:
  - Project image
  - Project title and description
  - Technologies used
  - Links to GitHub repo and live demo (open in new tab)

#### Contact Section

- Contains multiple contact methods:
  - WhatsApp contact card with a direct message link
  - LinkedIn profile card with a connect link
  - Contact form powered by Formspree for email submissions

---

### 4. Responsive Design

- The layout adjusts for mobile and desktop screen sizes.
- Navigation and content grids reorganize to ensure readability and usability on all devices.

---

## How to Run the Project Locally

1. **Clone the repository:**

   ```bash
   git clone # Project README: Personal Portfolio Website

## Overview

This project is a **responsive personal portfolio website** built with HTML, CSS, and some external icon libraries. It showcases various sections such as About, Education, Programming Languages, Projects, and Contact, all within a single-page layout with smooth navigation.

---

## Project Structure

- `index.html` — Main HTML file containing the entire webpage markup.
- `styles.css` — Main stylesheet for the site’s styles.
- `experience.css` — Additional CSS for specific sections (e.g., Education).
- `assets/` — Folder containing images and downloadable files like the CV PDF.
- External icons are used via **Bootstrap Icons CDN**.

---

## Features & Functionality

### 1. Single Page Layout with Section Anchors

The page is divided into multiple **sections** identified by `id`s:

- `#about` — About Me section
- `#education` — Educational Background
- `#languages` — Programming Languages
- `#projects` — Projects portfolio
- `#contact` — Contact details and form

Each section is clearly marked in the HTML with `<section id="...">` to allow direct navigation.

---

### 2. Navigation

#### Bottom Navigation Bar

- A fixed navigation bar at the bottom of the viewport contains icons linking to each main section.
- Uses `<nav class="bottom-nav">` with anchor tags `<a href="#section-id">` to jump to each section.
- Each nav icon has a `title` attribute and uses Bootstrap Icons for visuals.

**How navigation works:**

- Clicking a navigation icon triggers a jump to the corresponding section via anchor scrolling.
- The `href` attributes correspond directly to the section IDs on the page.
- This creates smooth user experience on both desktop and mobile devices.

#### Scroll-Down Arrow in Header

- On the hero/header section, a scroll-down arrow (`&#x21e3;`) links specifically to the Contact section (`#contact`).
- Clicking it smoothly scrolls the user down to the contact form.

---

### 3. Section Details

#### About Me Section

- Displays a profile image alongside a short bio paragraph.
- Uses a two-column layout with an image on one side and text on the other.

#### Educational Background

- Lists educational history as cards in a grid layout.
- Includes a **Download CV** button linking to a PDF file in the assets.

#### Programming Languages

- Displays cards with icons and language names.
- Icons are styled using Bootstrap Icons with specific colors.

#### Projects Section

- Displays a grid of project cards.
- Each card contains:
  - Project image
  - Project title and description
  - Technologies used
  - Links to GitHub repo and live demo (open in new tab)

#### Contact Section

- Contains multiple contact methods:
  - WhatsApp contact card with a direct message link
  - LinkedIn profile card with a connect link
  - Contact form powered by Formspree for email submissions

---

### 4. Responsive Design

- The layout adjusts for mobile and desktop screen sizes.
- Navigation and content grids reorganize to ensure readability and usability on all devices.

---

## How to Run the Project Locally

1. **Clone the repository:**

   ```bash
   git clone https://github.com/MabohlaleNkuna/Mabohlale.Dev