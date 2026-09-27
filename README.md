# Zaragoza Restaurant & Bar  
An authentic Spanish dining experience website with online reservations, event management, and an elegant admin dashboard — built for a premium restaurant in Cleveland, OH.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Dependencies](#dependencies)
- [Installation & Setup](#installation--setup)
- [Folder Structure](#folder-structure)
- [Contributions](#contributions)
- [How to Contribute](#how-to-contribute)
- [Contact](#contact)

---

## About the Project 
Zaragoza Restaurant & Bar is a modern, full-featured restaurant website designed to deliver an immersive digital experience that mirrors the warmth and sophistication of authentic Spanish cuisine. The site serves as both a marketing platform and an operational hub, offering diners seamless reservation booking, event browsing, gallery exploration, and direct communication — while empowering restaurant staff with a secure admin dashboard to manage content, orders, and guest inquiries.

---

## Project Overview  
This is a premium Next.js application built with TypeScript, Tailwind CSS v4, and Framer Motion for sophisticated animations. The website features a complete multi-page architecture with dynamic content management capabilities, a multi-step reservation system with form validation, and an admin panel protected by authentication. Designed for a real restaurant launching in May 2026 in Downtown Cleveland, Ohio.

---

## Key Features  
- **Multi-step Reservation System** — Intuitive booking flow with date/time selection, guest info, special requests, and confirmation
- **Admin Dashboard** — Secure authentication with session management; manage events, menu items, gallery photos, reservations, and messages
- **Dynamic Menu Display** — Categorized menu with smooth animations and responsive card layouts
- **Events Section** — Showcase upcoming events and private dining options
- **Photo Gallery** — Visual storytelling with curated image collections
- **Animated UI** — Framer Motion-powered scroll animations, transitions, and micro-interactions
- **Form Validation** — Zod-powered schema validation across all forms
- **Responsive Design** — Fully optimized for mobile, tablet, and desktop views
- **Toast Notifications** — Real-time feedback for user actions
- **SEO-Ready** — Semantic HTML structure with proper meta tags and layout hierarchy

---

## Tech Stack  
**Frontend:** React 19 · Next.js 16 · TypeScript  
**Styling:** Tailwind CSS v4 · PostCSS  
**Animations:** Framer Motion  
**Forms:** React Hook Form · Zod Validation  
**Icons:** Lucide React  
**Tooling:** ESLint · VS Code

---

## Dependencies
List required dependencies or major libraries:

```json
{
  "next": "16.1.6",
  "react": "19.2.3",
  "react-dom": "19.2.3",
  "typescript": "^5",
  "tailwindcss": "^4",
  "@tailwindcss/postcss": "^4",
  "framer-motion": "^12.37.0",
  "lucide-react": "^0.577.0",
  "react-hook-form": "^7.71.2",
  "@hookform/resolvers": "^5.2.2",
  "zod": "^4.3.6"
}
```

---

## Installation & Setup
1. Clone the repo and install dependencies:

```bash
git clone https://github.com/touhidcodes/zaragoza-restaurant-bar
cd zaragoza-restaurant-bar
pnpm install
```

2. Set up environment variables by creating a `.env.local` file in the root directory:

```env
NEXT_PUBLIC_ADMIN_PASSWORD=your_secure_password
```

3. Run the application:

```bash
pnpm dev
```

Open http://localhost:3000 to view the application.

---

## Folder Structure

```plaintext
zaragoza-restaurant-bar/
│
├── src/
│   ├── app/                    # Next.js App Router pages
│   │   ├── layout.tsx          # Root layout
│   │   ├── page.tsx            # Homepage
│   │   ├── about/
│   │   ├── contact/
│   │   ├── events/
│   │   ├── gallery/
│   │   ├── menu/
│   │   ├── private-dining/
│   │   ├── reservations/
│   │   └── admin/              # Admin dashboard (protected)
│   │       ├── login/
│   │       └── dashboard/
│   ├── components/             # Reusable UI components
│   │   ├── home/               # Homepage sections
│   │   ├── layout/             # Navigation, Footer
│   │   ├── menu/               # Menu-related components
│   │   ├── reservations/       # Reservation form steps
│   │   ├── admin/              # Admin dashboard components
│   │   └── ui/                 # Shared UI primitives
│   ├── data/                   # Static content data files
│   ├── hooks/                  # Custom React hooks
│   ├── lib/                    # Utilities, constants, validators
│   └── types/                  # TypeScript type definitions
│
├── public/                     # Static assets
├── package.json
└── tsconfig.json
```

---

## Contributions

| Name | Role | Contributions |
|------|------|---------------|
| G.M Asif Foisal | Lead Developer | Full project development, design, and implementation |

---

## How to Contribute

1. Fork the Project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---


## Contact

**Live URL:** [Zaragoza Live Site](https://zaragoza-restaurant-bar.vercel.app)  
**Email:** [asiffoisalaisc@email.com](mailto:asiffoisalaisc@email.com)  
**Portfolio:** [GitHub Profile](https://github.com/AsifFoisal)
