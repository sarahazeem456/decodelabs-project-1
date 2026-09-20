# decodelabs-project-1
A responsive, mobile-first skincare storefront built with semantic HTML5, CSS Grid, Flexbox, and client-side authentication for DecodeLabs Project 1.

# Aura Botanics — Responsive E-Commerce Frontend

A clean, mobile-first responsive frontend interface for a mindful skincare web application, built for DecodeLabs Full Stack Internship — Project 1.

This project implements modern web standards using pure fundamentals—crafted without third-party frameworks like Bootstrap or Tailwind to demonstrate core CSS layout engines, accessibility principles, and interactive client-side logic.

Key Features:
Mobile-First Responsive Architecture: Single-column base layout expanding gracefully via min-width media queries for Tablet (768px) and Desktop (1024px).
CSS Grid & Flexbox Hybrid System: 
  - 2D SS Grid for macro layout distribution (header, sidebar, main, footer).
  - Flexbox for micro components (navigation bars, cards, action controls).
- Interactive Product Catalog:
  - Live search input matching product names, descriptions, and key actives.
  - Sorting controls (Featured, Price: Low to High, Price: High to Low, Alphabetical A–Z).
  - Category sidebar filters (Hydration, Barrier Restore, Gentle Balance).
- Ingredient Inspector Modal: Detailed modal popups revealing key actives, complete INCI formulations, usage instructions, and customer reviews.
- Cart & Multi-Step Checkout Flow:
  - Slide-over bag modal with quantity adjustments and subtotal calculation.
  - Interactive multi-step checkout (Shipping → Payment → Order Confirmation with generated order IDs).
- Wishlist & User Authentication:
  - Saved favorites with heart toggle controls.
  - Client-side persistent authentication (Registration, Login, Session State) powered by browser localStorage.

Design System & Aesthetic Tokens:
Adheres strictly to the warm, grounded 2025 interface guidelines:

Token Value Role:
Mocha Mousse #A5856F Primary Brand & Stability Accent
Ethereal Blue #A0D4E0 Secondary Hydration & Active Highlights 
Moonlit Grey #F2F0EA Background Refinement Canvas 
Deep Earth #2A2826 High-contrast Typography & Borders 
Typography Montserrat(Headings) & Open Sans(Body) Clean modern hierarchy 

 Built With:
HTML5: Semantic landmarks (header, nav, aside, main, article, footer) for WCAG accessibility and screen-reader navigation.
CSS3: CSS Grid, Flexbox, Custom Properties (CSS Variables), clamp() fluid math, and media queries.
JavaScript (Vanilla ES6+): DOM state manipulation, modal controllers, filtering/sorting logic, and localStorage persistence.
