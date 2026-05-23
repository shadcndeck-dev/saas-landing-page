# ChatDeck — Free SaaS Landing Page Template



**A free, open-source SaaS landing page template built with Shadcn UI, Next.js, and Tailwind CSS. Launch and validate your product faster — without starting from scratch.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
![Next.js](https://img.shields.io/badge/Next.js-15-black?logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-CSS-38bdf8?logo=tailwindcss)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-components-black)

---

<!-- Replace with your actual screenshot -->
[![ChatDeck Preview](<img width="5000" height="2625" alt="OG Images-04 jpg" src="https://github.com/user-attachments/assets/a6201e20-3900-4dad-98c1-8618ac4bbef9"/>)](https://www.shadcndeck.com/templates/chatdeck-saas-landing-page)

---

## ⚡ Live Demo

**[View Live Demo →](saas-landing-page-ten-teal.vercel.app)**

---

## Why ChatDeck?

Most [shadcn landing page templates](https://www.shadcndeck.com/templates) are either too generic or too opinionated. ChatDeck gives you a clean, conversion-focused foundation that works for any SaaS product.

- ✅ No paid tier. No restrictions. Fully open source.
- ✅ Built with the tools you already use — Next.js, Shadcn UI, TypeScript, Tailwind
- ✅ Every section is independently editable — no tangled dependencies
- ✅ Designed for real launches, not just portfolios

---

## Sections Included

| Section | Description |
|---|---|
| **Hero** | Clean hero with social proof and a clear value proposition |
| **Navigation** | Sticky nav with smooth scrolling to all sections |
| **Video** | Dedicated section for product demos or walkthroughs |
| **Social Proof** | Trusted companies section with smooth scroll animations |
| **Features** | Icon-based feature grid using Lucide icons |
| **Team** | Team cards with social links |
| **Testimonials** | Auto-scrolling marquee with user feedback |
| **Pricing** | Animated pricing with monthly/yearly toggle |
| **FAQ** | Accordion FAQ section to handle objections |

---

## Tech Stack

| Technology | Purpose |
|---|---|
| [Next.js](https://nextjs.org/) | React framework with App Router & SSR |
| [React](https://react.dev/) | UI library with latest patterns |
| [TypeScript](https://www.typescriptlang.org/) | Type-safe development |
| [Tailwind CSS](https://tailwindcss.com/) | Utility-first styling |
| [shadcn/ui](https://ui.shadcn.com/) | Accessible, composable components |
| [Lucide React](https://lucide.dev/) | Clean, consistent icon library |
| [Motion](https://motion.dev/) | Smooth, performant animations |

---

## Getting Started

### Prerequisites

- Node.js 18+
- npm, yarn, pnpm, or bun

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/chatdeck.git

# Navigate into the project
cd chatdeck

# Install dependencies
npm install
```

### Run Locally

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Customization

### Update Content

All section content lives in clearly labeled components inside `/components`. Each section is self-contained — edit one without breaking others.

### Update Colors & Theme

ChatDeck uses Tailwind CSS with Shadcn UI's CSS variables. Update your brand colors in:

```
app/globals.css
```

### Add or Remove Sections

Each section is an individual component. Import or remove them from `app/page.tsx`:

```tsx
// app/page.tsx
import Hero from "@/components/sections/Hero";
import Features from "@/components/sections/Features";
import Pricing from "@/components/sections/Pricing";
// Add or remove as needed
```

---

## Project Structure

```
chatdeck/
├── app/
│   ├── globals.css        # Global styles & CSS variables
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Main page — import sections here
├── components/
│   ├── sections/          # Individual page sections (Hero, Features, etc.)
│   └── ui/                # Shadcn UI components
├── public/                # Static assets
└── tailwind.config.ts     # Tailwind configuration
```

---

## Deploy

### Deploy to Vercel (Recommended)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/your-username/chatdeck)

### Other Platforms

ChatDeck works on any platform that supports Next.js:

- [Netlify](https://docs.netlify.com/frameworks/next-js/)
- [Railway](https://railway.app/)
- [Render](https://render.com/)

---

## Who Is This For?

- **Indie Hackers** — Launching a new SaaS and need a conversion-ready page fast
- **Startup Founders** — Validating an idea before building the full product
- **Developers** — Building an MVP and skipping the design phase
- **Teams** — Need a shared, open-source starting point for a product site
- **Creators** — Want a clean layout that drives signups without heavy customization

---

## Contributing

Contributions are welcome! If you find a bug, want to improve a section, or add a feature:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## License

This project is licensed under the **MIT License** — free to use, modify, and distribute for personal and commercial projects.

See [LICENSE](./LICENSE) for full details.

---

## Acknowledgements

Built with:

- [shadcn/ui](https://ui.shadcn.com/) by [@shadcn](https://twitter.com/shadcn)
- [Next.js](https://nextjs.org/) by Vercel
- [Tailwind CSS](https://tailwindcss.com/) by the Tailwind team

---

**If ChatDeck saved you time, consider giving it a ⭐ — it helps others find it.**
