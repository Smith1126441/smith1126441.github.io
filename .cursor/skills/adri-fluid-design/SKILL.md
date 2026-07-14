---
name: adri-fluid-design
description: Guide the creation of clean, dark-themed, minimal web layouts inspired by adri-fluid-demo.squarespace.com. Use when designing user interfaces, creating web components, writing CSS/Tailwind, or styling dark mode websites.
---

# Adri Fluid Design System

## Quick Start
When asked to design a web page, component, or layout using this skill, apply the following "Adri Fluid" dark theme principles to create a highly polished, professional, and modern UI.

## Design Principles

### 1. Color Palette (Dark Theme)
- **Background (Primary):** Deep rich black (`#0A0A0A` or Tailwind `bg-neutral-950`).
- **Background (Secondary/Surface):** Dark charcoal for cards or alternating sections (`#171717` or `bg-neutral-900`).
- **Text (Primary):** High-contrast off-white (`#F5F5F5` or `text-neutral-50`).
- **Text (Muted):** Elegant light gray for secondary text and descriptions (`#A3A3A3` or `text-neutral-400`).
- **Accents:** Pure white or highly desaturated colors for borders, dividers, and primary buttons.

### 2. Typography
- **Headings:** Large, expressive, and clean. Use a sophisticated sans-serif (like Inter, Helvetica Now, or Roobert). 
  - Massive hero headlines should have tight tracking (letter-spacing).
- **Body Text:** Highly readable sans-serif with generous line-height (`leading-relaxed` or `1.6`).
- **Hierarchy:** Maintain a stark contrast in size and weight between section titles (H2) and body copy.

### 3. Layout & Spacing (Fluid & Minimal)
- **Whitespace:** Be incredibly generous with padding and margins (`py-24` or `py-32` for sections). Let the elements breathe.
- **Grids:** Use CSS Grid or Flexbox for structured, fluid layouts (e.g., bento boxes, asymmetric 2-column or 3-column layouts for case studies).
- **Dividers:** Use thin, subtle borders (`border-neutral-800`) to separate sections cleanly without adding visual clutter.

### 4. Component Styling
- **Buttons:** Minimalist. High contrast (e.g., White background, Black text for primary buttons). Sharp edges (`rounded-none`) or perfectly pill-shaped (`rounded-full`). Subtle hover transitions.
- **Images/Cards:** Use large, full-bleed images. Minimal text overlay or clean text positioned neatly beneath the image.
- **Navigation:** Clean and unobtrusive. Transparent background, minimal links, simple typography.

## Implementation Guidelines (Tailwind / CSS)

When generating code:
1. **Default to Dark Mode:** Apply the dark color palette unconditionally or setup standard dark mode preferences.
2. **Semantic HTML:** Structure the page logically with `<header>`, `<main>`, `<section>`, `<footer>`.
3. **Tailwind Classes Example:**
   ```html
   <section class="bg-neutral-950 text-neutral-50 py-24 px-6 md:px-12 lg:px-24">
     <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-16">
       <h2 class="text-4xl md:text-6xl font-medium tracking-tight">Collaborative & Iterative</h2>
       <p class="text-neutral-400 text-lg leading-relaxed">
         I believe in the power of collaboration to create exceptional websites...
       </p>
     </div>
   </section>
   ```
4. **Avoid Clutter:** Do not add unnecessary drop shadows, bright gradients, or complex animations unless specifically requested. Prioritize elegant typography and spacing.
