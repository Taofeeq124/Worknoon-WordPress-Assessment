# Worknoon WordPress Assessment

This project was built as a small but complete system — not just a landing page.

The goal was to combine WordPress development, SEO structure, and system thinking into something that reflects how real-world projects are handled.

---

## Overview

The project includes:

- A responsive landing page built with Elementor  
- Performance optimization for better load speed  
- Structured data (schema) to define the brand entity  
- SEO diagnosis and strategy documentation  
- A simple but clear system approach connecting everything together  

---

## Live Setup (How to Run)

1. Install WordPress locally or on a test server  
2. Install the required theme and plugins (listed below)  
3. Import the provided Elementor JSON files (page, header, footer)  
4. Activate the child theme  
5. Add the schema using Code Snippets or custom plugin  
6. Configure permalinks and basic settings  

---

## Tools & Technologies Used

- WordPress  
- Elementor + Elementor Pro  
- Hello Elementor (Child Theme)  
- Advanced Custom Fields (ACF)  
- Rank Math SEO  
- WP Rocket (for performance optimization)  

---

## Project Structure

- /theme-files → Child theme setup (elementor-json → Landing page, header, footer exports) and ACF JSON files
- /schema → JSON-LD schema files (Organization, Person, Website)
- ./ Strategy and SEO-related documentation


---

## How Everything Connects

This project was approached as a complete system rather than separate tasks.

- The landing page was built using Elementor with a focus on structure and conversion  
- Schema was written separately in JSON format to clearly define the Worknoon entity  
- The knowledge panel strategy explains how these signals work together for entity recognition  
- The SEO diagnosis shows how technical issues would be handled in a real scenario  

Together, this reflects a real workflow:

**Build → Structure → Optimize → Scale**

---

## Schema Approach

Instead of relying fully on a plugin, the schema was written manually in JSON-LD format.

This gives more control over what is sent to search engines and avoids unnecessary markup.

The schema aligns with the actual content on the site — including services, brand positioning, and contact information.

---

## Performance Optimization

The site was optimized using:

- Lightweight theme (Hello Elementor)  
- WP Rocket for caching and performance  
- Reduced unnecessary plugins  
- Clean layout structure  

The focus was to keep things fast without overcomplicating the setup.

---

## Challenges & Solutions

**1. Keeping things structured without over-engineering**  
Solution: Kept the setup simple but organized (separate schema, docs, and design files)

**2. Avoiding plugin dependency for schema**  
Solution: Wrote schema manually and documented implementation

**3. Balancing design and performance**  
Solution: Used Elementor carefully with a lightweight theme and caching

---

## SEO & System Thinking

This project was not treated as just a design task.

It includes:
- Entity-based SEO (schema + strategy)  
- Technical troubleshooting (indexing diagnosis)  
- Structured documentation for scalability  

The focus was to show how development and SEO work together, not separately.

---

## What I Would Improve

If this were a real production project, I would:

- Connect schema dynamically using PHP or ACF fields  
- Add real brand social profiles (sameAs links)  
- Expand internal linking structure  
- Set up tracking with Google Analytics or similar  
- Build out more structured content (e.g., services as custom post types)

---

## Notes

- Some schema fields (like social profiles and logo path) are placeholders and should be updated with real data  
- The setup is intentionally simple to focus on clarity and structure  

---

## Demo

A short walkthrough video is included showing:
- Page structure  
- Responsiveness  
- Schema setup  
- Project structure  
