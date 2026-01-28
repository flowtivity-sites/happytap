# Happy Tap Plumbing - Website Rebuild

## Overview
This is a website rebuild for **Happy Tap Plumbing**, a trades business.

## Quick Start
```bash
npx create-next-app@latest . --typescript --tailwind --app --src-dir --no-eslint
npm run dev
```

## Design Direction
- **Aesthetic:** Gold Coast Professional
- **Display Font:** Bebas Neue
- **Body Font:** Work Sans
- **Primary Color:** #1e3a8a
- **Accent Color:** #f59e0b
- **Effects:** geometric shapes, bold shadows, decorative lines, subtle gradients

## Design Variations Available
This site has 4 unique design variations to choose from. The recommended variation is applied below, but you can switch by updating `selectedVariation` in prd.json.

### Gold Coast Professional (variation-1) - RECOMMENDED
- **Rationale:** This design reflects Happy Tap's commitment to professional service with a clean, trustworthy aesthetic. The navy and gold palette echoes the Gold Coast's premium coastal lifestyle while maintaining the reliability trades customers expect.
- **Palette:** Primary #1e3a8a, Accent #f59e0b
- **Fonts:** Bebas Neue / Work Sans
- **Mood:** professional, trustworthy, modern

### Industrial Strength (variation-2)
- **Rationale:** Emphasizes Happy Tap's expertise in both plumbing and roofing with a bold industrial aesthetic. The charcoal and teal combination conveys strength and water themes, perfect for a business that handles everything from emergency repairs to full installations.
- **Palette:** Primary #374151, Accent #0d9488
- **Fonts:** Oswald / Source Sans Pro
- **Mood:** industrial, reliable, bold, utilitarian

### Friendly Expert (variation-3)
- **Rationale:** Captures Happy Tap's 'local friendly expert' positioning with warm colors and approachable design. The forest green represents growth and reliability while yellow adds the friendly, approachable energy that matches their 'Happy' brand personality.
- **Palette:** Primary #065f46, Accent #fbbf24
- **Fonts:** Space Grotesk / DM Sans
- **Mood:** friendly, approachable, expert, warm

### Coastal Confidence (variation-4)
- **Rationale:** Designed specifically for Happy Tap's Gold Coast location, this variation uses ocean-inspired blues with vibrant orange accents. The bold typography and dynamic effects reflect confidence in handling any plumbing challenge while maintaining the coastal lifestyle appeal.
- **Palette:** Primary #1e40af, Accent #ea580c
- **Fonts:** Archivo Black / Inter
- **Mood:** confident, dynamic, coastal, energetic


## Business Information
- **Name:** Happy Tap Plumbing
- **Phone:** 0434 457 562
- **Email:** happytapplumbing@outlook.com
- **Address:** Gold Coast QLD, Australia
- **Hours:** Mon - Fri
8:00 am - 8:00 pm
Saturday
9:00 am - 7:00 pm
Sunday
9:00 am - 9:00 pm
- **Tagline:** WELCOME TO HAPPY TAP PLUMBING & ROOFING. YOUR LOCAL FRIENDLY GOLD COAST PLUMBING EXPERT

## Services
### Plumbing
Professional plumbing services

### Roofing
Professional roofing services

### Emergency Plumbing Repairs
Professional emergency plumbing repair services

### Appliance Installation
Professional appliance installation services

### Roofing Plumbing
Professional roofing plumbing services

### Guttering
Professional guttering services

### Bathroom
Professional bathroom services

### Leak Detection & Repair
Professional leak detection and repair services

### Appliance Installation & Repair
Professional appliance installation and repair services

### Blocked Drain Cleaning & Repair
Professional blocked drain cleaning and repair services

### Virtual Consultations
Virtual consultations for plumbing needs

## Available Images
**IMPORTANT:** Use these downloaded images from the original website. Do NOT use placeholder images.

- `assets/images/11062b_366f7fdbcafc4effaeddb0dba92014c1_mv2.png`
- `assets/images/11062b_60c5fc4a3ecd49f2a697206b09eeace1_mv2.png`
- `assets/images/11062b_681c6c82d3344ca09a024b18998e0f66_mv2.png`
- `assets/images/11062b_6e9638ad803e4099a6116eb750b5a584_mv2.png`
- `assets/images/7d46e0_5078480d8be3488c8cc18b9e4bc417de_mv2.png`
- `assets/images/Leaky_20Sink_20Drain_20Pipe.jpeg`
- `assets/images/Plumber_20at_20Work.png`
- `assets/images/Vaccum_20Cleaner.jpg`
- `assets/images/Washing_20Machine_20Maintenance.jpg`

## Content Files
- `content/pages.json` - Scraped page content
- `content/services.json` - Service offerings
- `content/about.json` - About/team information
- `content/metadata.json` - Business contact details
- `assets/images/` - Downloaded images from original website

## PRD Stories
Complete each story in `prd.json` in order. Mark `"passes": true` when done.

1. **Project setup: Next.js + Tailwind, Cloudflare config**
2. **Homepage: hero with images, services grid, trust signals, CTA**
3. **Services page with service images**
4. **About page with team/business images**
5. **Contact page: form, map, details**
6. **Design system: Apply vertical aesthetic**
7. **Motion & polish**
8. **AEO: LocalBusiness schema, meta tags, FAQ**
9. **Mobile responsive**
10. **Image optimization with next/image**
11. **Deploy to Cloudflare Pages**

## Deployment
```bash
npm run build
npx wrangler pages deploy ./out --project-name=happytap
```

Preview URL: `https://happytap.sites.flowtivity.com.au`

---
Generated by Website Factory
