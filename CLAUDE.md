# Happy Tap Plumbing - Claude Code Instructions

## Project Type
Next.js 14+ website with Tailwind CSS, deployed to Cloudflare Pages as static export.

## Tech Stack
- **Framework:** Next.js 14+ with App Router
- **Styling:** Tailwind CSS
- **Images:** next/image component
- **Fonts:** next/font/google
- **Export:** Static (output: 'export' in next.config.js)

## Design System

### Typography (use next/font)
```typescript
// app/layout.tsx
import { Bebas_Neue, Work_Sans } from 'next/font/google'

const displayFont = Bebas_Neue({
  subsets: ['latin'],
  weight: ['400', '700', '900'],
  variable: '--font-display'
})

const bodyFont = Work_Sans({
  subsets: ['latin'],
  weight: ['400', '500', '600'],
  variable: '--font-body'
})
```

### Colors (in globals.css)
```css
:root {
  --color-primary: #1e3a8a;
  --color-accent: #f59e0b;
  --color-surface: #f8fafc;
  --color-text: #1f2937;
  --color-text-muted: #6b7280;
}
```

### Effects to Include
- geometric shapes
- bold shadows
- decorative lines
- subtle gradients

## Available Images
**CRITICAL: Use these images from assets/images/ - do NOT use placeholder images!**

- 11062b_366f7fdbcafc4effaeddb0dba92014c1_mv2.png
- 11062b_60c5fc4a3ecd49f2a697206b09eeace1_mv2.png
- 11062b_681c6c82d3344ca09a024b18998e0f66_mv2.png
- 11062b_6e9638ad803e4099a6116eb750b5a584_mv2.png
- 7d46e0_5078480d8be3488c8cc18b9e4bc417de_mv2.png
- Leaky_20Sink_20Drain_20Pipe.jpeg
- Plumber_20at_20Work.png
- Vaccum_20Cleaner.jpg
- Washing_20Machine_20Maintenance.jpg

### How to use images:
```tsx
import Image from 'next/image'

// For images in public/assets/images/
<Image
  src="/assets/images/filename.jpg"
  alt="Description"
  width={800}
  height={600}
/>
```

## Required Pages (App Router)
1. `app/page.tsx` - Homepage
2. `app/services/page.tsx` - Services
3. `app/about/page.tsx` - About
4. `app/contact/page.tsx` - Contact

## Next.js Config for Static Export
```javascript
// next.config.js
/** @type {import('next').NextConfig} */
const nextConfig = {
  output: 'export',
  images: {
    unoptimized: true, // Required for static export
  },
}
module.exports = nextConfig
```

## Quality Checklist
- [ ] All images from assets/images/ used (NO placeholders)
- [ ] Lighthouse Performance > 90
- [ ] Mobile responsive (375px)
- [ ] LocalBusiness schema
- [ ] Distinctive design (NOT generic)
- [ ] Animations and hover states

## DO NOT
- Use Inter, Roboto, or Arial fonts
- Use placeholder images (unsplash, placeholder.com, etc.)
- Create cookie-cutter layouts
- Skip the design direction
- Use placeholder text (use scraped content)

## Workflow
1. Read prd.json for stories
2. Copy assets/images/ to public/assets/images/
3. Complete stories in order using the downloaded images
4. Mark "passes": true when done
5. Deploy when all stories pass
