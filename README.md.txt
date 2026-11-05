# GlowCare – Skincare Landing Page

**OASIS INFOBYTE Web Development & Designing Internship**
**Level 1 · Task 1: Landing Page**

## Project Overview

GlowCare is a responsive, static landing page for a fictional skincare brand. It uses an e-commerce style layout with product cards, prices, ratings and "Add to Cart" buttons. The product bottles and jar are drawn with pure CSS, so the page uses no images.

## Technologies Used

- HTML5 (semantic elements: `header`, `nav`, `main`, `section`, `footer`)
- CSS3 (custom properties, Flexbox, Grid, media queries)
- Google Fonts: DM Serif Display and Poppins
- No JavaScript (the cart is built with CSS only)

## Task Checklist

| Requirement | Where |
|---|---|
| Sticky navbar with at least 3 links | Five links: Home, About, Products, Why GlowCare, Contact |
| Hero with headline, subheadline and CTA | "Skincare made for your natural glow" with Shop Now and Discover GlowCare buttons |
| At least 2 content sections | About, Products, Why GlowCare and a CTA band |
| Footer with contact and social links | Quick Links and Contact columns |
| Consistent colour palette | Rose, cream and brown tokens defined in `:root` |
| Responsive layout | Grid and Flexbox with breakpoints at 1000px and 700px |
| No element overlap | `box-sizing: border-box` and deliberate spacing |
| Clear typography | Serif headings, sans-serif body text |

## Accessibility

- Visible keyboard focus on every interactive element
- Accent text darkened to meet contrast guidelines
- Decorative CSS illustrations hidden from screen readers
- Animations disabled for users who prefer reduced motion

## Project Structure

```text
WebDev-L1-LandingPage/
├── index.html
├── style.css
├── README.md
└── screenshots/
```

## How to Run

Open `index.html` in any modern browser. No build step or server is needed.

## Working Add to Cart (CSS only)

The cart works without any JavaScript, using hidden checkboxes and CSS counters:

- Clicking **Add to Cart** marks the product as added and the button changes to "✓ Added"
- Clicking it again removes the product
- The Cart button shows how many products are added
- Clicking **Cart** opens a side panel listing the products with a running total
- Each product can be removed from the panel

The cart resets when the page is refreshed, and checkout is a demo only.