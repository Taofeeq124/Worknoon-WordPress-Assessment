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
- A simple system approach connecting everything together  

---

## Setup Instructions

1. Install WordPress (local or live environment)  
2. Install required plugins (listed below)  
3. Activate Hello Elementor theme + child theme  
4. Import Elementor JSON files (page, header, footer)  
5. Add schema using Code Snippets or custom plugin  
6. Configure permalinks and basic settings  

---

## Tools & Technologies Used

- WordPress  
- Elementor + Elementor Pro  
- Hello Elementor (Child Theme)  
- Advanced Custom Fields (ACF)  
- Rank Math SEO  
- WP Rocket  

---

## Project Structure

- /theme-files → Child theme setup (elementor-json → Landing page, header, footer exports) and ACF JSON files
- /schema → JSON-LD schema files (Organization, Person, Website)
- ./ Strategy and SEO-related documentation

---

## System Thinking & Project Reflection

### 1. Problem Overview

The task was not just to build a landing page, but to demonstrate how WordPress, SEO, and system thinking can work together.

The challenge was to create something simple on the surface, but structured in a way that reflects how a real project would be built and scaled.

---

### 2. Approach to the Solution

I approached this in layers:

- **Design Layer** → Built the landing page using Elementor with clear structure and responsiveness  
- **Performance Layer** → Optimized using a lightweight theme and caching  
- **SEO Layer** → Added structured data and created supporting SEO documentation  
- **System Layer** → Organized everything into reusable and scalable components (schema, docs, structure)  

Instead of treating each task separately, the focus was on how they connect.

---

### 3. Key Decisions and Why

- **Elementor + Hello Theme**  
  Chosen for speed, flexibility, and clean structure without unnecessary bloat  

- **Manual Schema (JSON-LD)**  
  Instead of relying fully on plugins, I wrote schema manually to have better control and clarity  

- **Separate Schema Files**  
  Keeps things organized and easier to scale or reuse  

- **Minimal Plugin Usage**  
  Avoided stacking plugins to keep performance stable  

---

### 4. Tradeoffs Considered

- Using Elementor improves speed of development but can introduce performance overhead  
  → Managed this with a lightweight theme and caching  

- Using plugins for schema is faster but less flexible  
  → Chose manual schema for better control  

- Keeping the project simple vs over-engineering  
  → Focused on clarity and structure instead of adding unnecessary complexity  

---

### 5. Challenges & How They Were Resolved

**Challenge:** Keeping the project structured while using a visual builder  
→ Solution: Separated logic (schema, docs) from design (Elementor)

**Challenge:** Avoiding plugin dependency for core SEO features  
→ Solution: Implemented schema manually and documented the approach

**Challenge:** Balancing performance with design flexibility  
→ Solution: Used Hello Elementor and WP Rocket for optimization

---

### 6. Affiliate Tracking / Onboarding Systems

This project did not include a live affiliate system, but the structure supports it.

If implemented, I would:

- Use a tool like FirstPromoter or similar  
- Integrate tracking scripts via WordPress hooks or header scripts  
- Create dedicated onboarding pages (custom post types or templates)  
- Track conversions through events and form submissions  

The idea is to keep tracking separate from design, while still integrated into the system.

---

### 7. Experience with Tools like FirstPromoter

I have not directly implemented FirstPromoter in this project, but I understand how these systems work:

- Tracking user referrals  
- Managing affiliate links  
- Connecting conversions to users  

In WordPress, this would typically be handled via:
- Script integration  
- API/webhook connections  
- Custom tracking events  

---

### 8. What I Would Improve

If this were a production project, I would:

- Make schema dynamic using PHP or ACF fields  
- Add real brand assets (logo, social profiles)  
- Expand internal linking and content structure  
- Set up analytics tracking (Google Analytics or similar)  
- Convert sections like services into Custom Post Types  
- Improve automation (e.g., onboarding flows, tracking systems)  

---

## SEO & Schema

Schema was created in JSON-LD format to define:

- Organization  
- Person  
- Website  

This supports entity recognition and aligns with the knowledge panel strategy included in the project.

---

## Final

This project reflects how I approach real work:

Not just building pages, but thinking in terms of structure, systems, and long-term scalability.
















