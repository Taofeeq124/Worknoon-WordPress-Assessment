# Worknoon WordPress Assessment – Theme Setup

This project is a lightweight, scalable WordPress setup built using Elementor and a custom child theme based on Hello Elementor Theme.

Instead of uploading a full WordPress backup, this repository uses an **Elementor JSON export + child theme structure** for portability, clarity, and better system-level understanding.

---

## Setup Instructions

Follow these steps to replicate the project:

### 1. Install WordPress
Set up a fresh WordPress installation (local or live environment).

---

### 2. Install Required Theme

- Install **Hello Elementor**
- Upload and activate the included **Child Theme** (`/theme/hello-child/`)
- Install ACF plugin and uplaod the Testimonials Post Type and Field Groups in Theme File.

---

### 3. Install Required Plugins

Install and activate the following plugins:

- Elementor (Required)
- Elementor Pro (Required)
- Advanced Custom Fields (Required)
- Rank Math SEO
- WP Rocket
- Safe SVG (Required)
- Solid Security Basic
- WPFront Scroll Top
- WPS Limit Login

---

### 4. Import Elementor Design

- Go to: Elementor → Tools → Import/Export
- Import the provided JSON file:
- Create a Menu and enable it from the header with Elementor.
- Assign it as the homepage

---

### 5. Configure Basic Settings

- Set homepage: Settings → Reading → Static Homepage
- Configure permalinks: `/post-name/`
- Connect analytics (if needed)

---

## Theme Architecture

This project uses:

- **Hello Elementor (Parent Theme)** – lightweight, performance-focused base
- **Custom Child Theme** – for safe overrides and scalability

### Why Child Theme?

- Prevents loss of changes during updates
- Allows custom styling and functions
- Supports scalable development

---

## Tools & Technologies Used

- WordPress (latest)
- Elementor + Elementor Pro
- Advanced Custom Fields (ACF)
- Rank Math SEO (for on-page optimization & schema support)
- WP Rocket (performance optimization)
- Safe SVG (secure SVG uploads)
- Solid Security (basic hardening)
- WPFront Scroll Top (UX enhancement)
- WPS Limit Login (security layer)

---

## Performance Optimization

The following optimizations were implemented:

- Lightweight theme (Hello Elementor)
- Minimal plugin usage (only essential tools)
- WP Rocket for:
  - Page caching
  - Minification
  - Lazy loading
- Optimized image handling
- Mobile-first responsive design

---

## Responsiveness

The landing page is fully responsive across:

- Desktop
- Tablet
- Mobile

Built using Elementor’s responsive controls and flexible layout system.

---

## System Thinking Approach

Instead of building a static page, this project was approached as a **scalable system**:

- Reusable Elementor sections
- Clean separation of design (Elementor) and logic (theme/plugins)
- Plugin-based extensibility
- SEO-ready structure

---

## Challenges & Solutions

### Challenge:
Ensuring portability without exporting full WordPress backup

### Solution:
Used Elementor JSON export + child theme + Testimonials ACF JSON to allow easy reconstruction without bloated files

---

### Challenge:
Balancing performance with design flexibility

### Solution:
Used Hello Elementor + WP Rocket to maintain speed while leveraging Elementor Pro features

---

## Future Improvements

If this project were extended:

- Convert sections into dynamic templates using ACF
- Implement Custom Post Types (e.g., Testimonials)
- Add schema injection via custom plugin
- Introduce CDN for global performance

---

## 📌 Notes

- This project intentionally avoids full backup exports to maintain clean version control and developer readability.
- Designed with scalability, SEO, and maintainability in mind.

