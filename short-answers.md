# Short Answers

## 1. Difference between Google Knowledge Graph and Knowledge Panel

The Knowledge Graph is the system Google uses to store and understand entities (people, companies, things) and how they relate to each other.

The Knowledge Panel is just the visual result of that — what users see on the search page.

In simple terms:
- Knowledge Graph = the data layer  
- Knowledge Panel = the display layer  

---

## 2. How Google Determines Entity Identity

Google builds entity identity by combining multiple signals, not just one.

From what I implemented in this project, the key ones are:
- Structured data (schema)
- Consistent brand name and description
- Website content (especially About page)
- External mentions and backlinks
- Social profiles (sameAs)

It’s basically about consistency — the more aligned these signals are, the easier it is for Google to confidently recognize the entity.

---

## 3. When to Create Custom Post Types Instead of Pages

Custom Post Types are better when the content needs structure and scalability.

For example:
- Case studies  
- Courses  
- Listings  

If the content has repeatable fields (like title, description, image, metadata), then a Custom Post Type makes more sense.

Regular pages are fine for static content like:
- Home  
- About  
- Contact  

In this project, if it were extended, services or testimonials could easily be turned into structured post types.

---

## 4. Recommended Plugins for Speed Optimization and Why

From experience, I prefer tools that actually reduce load time without breaking the site.

- WP Rocket → handles caching, file optimization, and improves load time quickly  
- Image optimization (ShortPixel or Smuch) → reduces image size without losing quality  
- Lightweight theme (Hello Elementor) → avoids unnecessary bloat  

In this project, performance was handled with a combination of a lightweight theme and caching, rather than stacking too many plugins.

---

## Lastly

The goal across all of this is not just to use tools, but to keep things simple, controlled, and scalable — especially when combining WordPress, SEO, and structured data.
