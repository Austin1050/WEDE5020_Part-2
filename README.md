# Dijong African Cuisine – Website Project

## Project Title
Dijong African Cuisine Website Development Project  
**Portfolio of Evidence (PoE) – Parts 1–2**

---

## Student Information
- **Student Name:** [Tokollo Austin Monama] 
- **Student Number:** [ST10502017]  
- **Module:** [WEDE5020 – Web Development]   

---

## Project Overview (complete)
Dijong African Cuisine is a South African restaurant that specialises in authentic African food. The restaurant offers a range of carefully curated packages (Standard, Gold, Premium, VIP, and Buffet-style) for individuals, families, events, and corporate clients.

This project involves the planning and eventual development of a modern, user-friendly website that replaces the current basic HTML structure. The website will allow customers to:
- View detailed food packages
- Place food orders online
- Submit enquiries for custom and bulk orders
- Learn about the brand and its services

**Existing pages used in the proposals:**
- index.html  
- about.html  
- services.html  
- standardpackage.html   
- vippackage.html   
- orders.html  
- enquiries.html  
- contact.html   

---

## Website Goals and Objectives
### Primary Goals
- Enable easy online ordering of African food packages
- Generate quality enquiries for custom and event orders
- Clearly showcase all package tiers
- Build trust and brand credibility through professional design and storytelling
- Improve mobile experience and conversion rates

### Key Performance Indicators (KPIs)
- Number of completed orders via orders.html
- Conversion rate from package pages to order/enquiry
- Number of enquiries submitted
- Average order value
- Website traffic and bounce rate
- Mobile conversion rate

---

## Key Features and Functionality
- Responsive Home page (index.html) with hero section and clear Calls-to-Action
- About page telling the brand story
- Services page outlining offerings
- Five individual package pages with detailed descriptions, pricing, images, and strong “Order Now” / “Enquire” buttons
- Dedicated Orders page (orders.html) with package selector and order form
- Enquiries page for custom and bulk requests
- Contact page with map, contact details, and form
- Consistent navigation with Packages dropdown
- WhatsApp click-to-chat integration
- Mobile-first responsive design
- Basic SEO optimisation on all pages
- Fast-loading, accessible layout (WCAG considerations)

---

## Timeline and Milestones
| Week   | Milestone                              | Deliverable                          |
|--------|----------------------------------------|--------------------------------------|
| 1–2    | Discovery & Planning                   | Content audit, sitemap, wireframes   |
| 3–4    | Design                                 | High-fidelity mockups + style guide  |
| 5–8    | Development                            | All 8 pages built and linked        |
| 9      | Functionality                          | Forms, navigation, content loaded    |
| 10–11  | Testing & Revisions                    | Cross-device testing & feedback      |
| 12     | Launch & Handover                      | Final QA, training & go-live         |

**Total planned duration:** 12 weeks

---

## Part 1 Details

### Part 1 Deliverables (Current Submission)
- Two complete Website Project Proposals
- Proposal 1: DIJONG AFRICAN CUISINE
- Proposal 2: BrightPath Learning Academy

---

## Part 2 Details (Design Phase – UI Styling, Responsiveness & Wireframes)

### Part 2 Deliverables (Current Submission)
Part 2 focuses on the visual design system, responsive UI styling, and wireframes for the Dijong African Cuisine website. The design decisions were implemented into a central stylesheet to ensure consistency across all pages.

**Deliverables included in Part 2:**
- Low-fidelity wireframes (mobile + desktop) for all pages
- Global CSS reset + base typography and layout rules
- Styled navigation bar (sticky header) with:
  - Logo area
  - Navigation links
  - Cart button + cart count badge
  - Hamburger menu for smaller screens
- Styled page sections and components:
  - Hero section (headline + outlined text effect + image hover/rotation)
  - Products grid + product cards (hover elevation/shadow)
  - About section (dark theme + rotated info box)
  - Events section (grid list with checkmark icons + hover effects)
  - Enquiry section (styled dropdown with custom arrow + focus states)
  - Contact form (inputs, textarea, button styling, validation states)
  - Contact info layout
  - Map section (iframe styling + hover effects)
  - Footer layout + socials styling
- Responsive design using defined breakpoints (768px, 480px, and large screens ≥1400px)

---

---

### Design System (Matches the CSS)
**Typography**
- Global font stack: `Segoe UI`, Arial, Helvetica, sans-serif (applied via universal selector)
- Large headline hierarchy used in hero and section headers (heavy weights for emphasis)

**Core Colours**
- Primary text / dark UI: `#111`
- Light background: `#fafafa`
- White surfaces/cards: `#ffffff`
- Borders: `#eee` and `#ddd`
- Muted text: `#555`, `#888`, `#999`
- Accent (gold for interaction emphasis): `#d4af37`
- Accent hover/darker gold: `#b8941f`
- Error (invalid fields): `#e74c3c`
- Success (valid fields): `#27ae60`

**Buttons**
- Primary button: `.btn-primary` (dark background `#111`, uppercase, bold)
- Secondary button: `.btn-secondary` (transparent with `#111` border)
- Add-to-cart: `.btn-add` (full-width CTA button)
- Contact form submit button overrides `.btn-primary` with gold styling (`#d4af37` → hover `#b8941f`)

**Cards & Surfaces**
- Product cards: white surface, subtle border, hover lift + shadow
- Events list items: left border emphasis + hover interaction
- About section: dark background with a rotated “info box” card

---

### Responsiveness (Matches Media Queries)
The site is responsive across mobile, tablet, and large screens using the following breakpoints:
- **≤ 768px:** hamburger menu appears, nav collapses, hero stacks, forms become mobile-friendly
- **≤ 480px:** reduced spacing and font sizes; map height reduced
- **≥ 1400px:** map iframe expands for large screens

---

### Accessibility & Usability Considerations (Implemented in CSS)
- Clear focus styling on form inputs and selects using accent colour + soft box-shadow
- Strong contrast for primary text (`#111` on light backgrounds)
- Touch-friendly spacing for form controls and buttons on mobile
- Validation feedback using `:invalid` (red) and `:valid` (green) borders once fields are filled

---

### File Location
- Main stylesheet: `styles.css`
---

## Sitemap
Dijong African Cuisine Website
│
├── index.html                  (Home)
├── about.html                  (About Us)
├── services.html               (Services)
├── Packages
│   ├── standardpackage.html
│   ├── vippackage.html
├── orders.html                 (Place an Order)
├── enquiries.html              (Custom Enquiries)
└── contact.html                (Contact Us)

---

## Changelog
All changes and improvements to the project will be tracked here.

### [2026-08-15] – Part 1 Initial Submission
- Created two full Website Project Proposals
- Structured proposals according to official requirements
- Mapped all features to existing HTML pages
- Converted all budgets to South African Rands (ZAR)
- Applied IIE Harvard Referencing Style
- Created professional README.md
- Added sitemap and project documentation
- Prepared repository for lecturer review and approval

### [2026-09-18] – Part 2 UI Styling, Responsive CSS & Wireframes
- Created low-fidelity wireframes (mobile + desktop) for all 11 pages
- Added global CSS reset and base typography (Segoe UI font stack)
- Implemented sticky navigation bar styling, cart button/badge, and hamburger menu responsive behaviour
- Designed and styled hero section (outlined heading effect + interactive hero image)
- Built responsive product grid and product card hover effects
- Styled About section (dark theme) with rotated highlight/info box
- Styled Events section with grid layout, check icons, and hover transitions
- Styled Enquiry dropdown with custom arrow icon and focus/hover states
- Styled Contact form inputs, textarea, submit button, and validation states
- Styled Map iframe section with hover effects and large-screen adjustments
- Added footer styling including socials hover behaviour
- Implemented responsive layouts for 768px and 480px breakpoints

### Future Updates (To be added)
- Part 3: Development Phase
- Any feedback changes from lecturer

---

## References
1. Baymard Institute. 2023. E-commerce UX research. [Online]. Available at: https://baymard.com/research [Accessed 10 August 2026]. 
2. xneelo. 2024. South African web hosting. [Online]. Available at: https://xneelo.co.za [Accessed 09 August 2026]. 
3. Afrihost. 2025. Web hosting packages. [Online]. Available at: https://www.afrihost.com [Accessed 10 August 2026]. 
4. W3Schools. 2025. HTML, CSS and JavaScript tutorials. [Online]. Available at: https://www.w3schools.com [Accessed 05 August 2026]. 
5. World Wide Web Consortium (W3C). 2023. Web Content Accessibility Guidelines (WCAG) 2.2. [Online]. Available at: https://www.w3.org/TR/WCAG22/ [Accessed 18 September 2026].

---

**End of README.md**
