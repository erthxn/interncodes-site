# interncodes-site

**Personal portfolio & professional site for Majek Ay (erthxn)**  
Live at: **[https://interncodes.xyz](https://interncodes.xyz)**

---

## Table of Contents

- [Overview](#overview)
- [Who This Is For](#who-this-is-for)
- [About Majek Ay](#about-majek-ay)
- [What the Site Does](#what-the-site-does)
- [Site Structure & Sections](#site-structure--sections)
  - [Navigation](#navigation)
  - [Hero](#hero)
  - [Services](#services)
  - [Process](#process)
  - [Selected Work](#selected-work)
  - [About](#about)
  - [Contact](#contact)
  - [Footer](#footer)
- [Selected Projects in Detail](#selected-projects-in-detail)
  - [SpinMi](#spinmi)
  - [GiftTrove](#gifttrove)
  - [cSIM Rate](#csim-rate)
- [Technical Architecture](#technical-architecture)
- [Design System](#design-system)
- [Interactive Features](#interactive-features)
- [SEO & Structured Data](#seo--structured-data)
- [File Structure](#file-structure)
- [How to Run Locally](#how-to-run-locally)
- [Deployment](#deployment)
- [Customization Notes](#customization-notes)
- [Contact & Socials](#contact--socials)
- [License](#license)

---

## Overview

`interncodes-site` is a single-page, fully static personal website for **Majek Ay**, a Web3 **Community Architect** who designs, builds, and operates Telegram and Discord infrastructure for crypto and blockchain projects.

The site serves as both a professional portfolio and a service landing page. It clearly communicates:

- What Majek does
- How he works
- Proof of shipped work
- How to get in touch

It is intentionally lightweight, fast, and framework-free -- pure HTML, CSS, and a small amount of vanilla JavaScript.

---

## Who This Is For

This site is aimed at:

- Web3 founders and teams who need serious Telegram/Discord infrastructure
- Projects that have outgrown basic community setups and need proper architecture, moderation systems, and engagement loops
- Teams looking for someone who not only designs communities but also **runs** them day-to-day
- People who value "build in public" documentation and long-term operational ownership over short-term campaign work

---

## About Majek Ay

**Majek Ay** (also known as **erthxn**, Earth Intern, Intern, or Interncode) is a community architect specializing in Telegram and Discord ecosystems for Web3 projects.

His work sits at the intersection of:

- Community design & culture
- Technical infrastructure (bots, roles, channels, Mini Apps)
- Day-to-day moderation and operations
- Public building and audience growth

He focuses on creating digital spaces that can actually hold up under real user growth -- not just look good on launch day.

**Aliases / identities used on the site:**
- Majek Ay
- erthxn
- Earth Intern
- Intern
- Interncode

---

## What the Site Does

The website is a complete self-contained presentation of Majek's professional identity and services. It:

1. **Positions** him clearly as a Community Architect
2. **Explains** the four main service areas he offers
3. **Shows** his operating process (Diagnose -> Architect -> Launch -> Operate)
4. **Showcases** real shipped work with metrics and links
5. **Provides** multiple direct contact channels
6. **Establishes** credibility through structured data, clean design, and concrete project examples

It is not a blog, not a multi-page marketing site, and not a complex web application. It is a high-signal, single-page professional presence.

---

## Site Structure & Sections

### Navigation

- Fixed top navigation that becomes semi-transparent with backdrop blur after scrolling
- Desktop links: Services Â· Process Â· Work Â· About
- Primary CTA: "Work with me"
- Mobile: full-screen animated hamburger menu with staggered link reveals
- Brand mark uses the profile avatar

### Hero

**Headline:**  
> "I design the room. Then I run it."

**Subcopy:**  
Telegram and Discord infrastructure, moderation systems, and engagement tools for teams that need their community to hold up under real growth -- not just look good on day one.

Two primary CTAs:
- "Work with me ->"
- "See the work"

The hero uses soft radial gradients and a subtle noise texture for depth.

### Services

Section title: **"Infrastructure for communities that actually hold up."**

Four service cards:

| #  | Service                    | Description |
|----|----------------------------|-----------|
| 01 | **Community Architecture** | Telegram and Discord servers designed from the ground up -- role structures, channel logic, moderation systems, and onboarding flows that scale. |
| 02 | **Engagement Systems**     | Custom bots and mechanics (XP, ranks, quests, gated access) built to keep a community active between announcements. |
| 03 | **Growth Infrastructure**  | Mini Apps and utility tools (price tracking, username sniping, etc.) that give a project something genuinely useful. |
| 04 | **Build in Public**        | Documenting the process primarily on X so the project builds trust and audience alongside the product. |

### Process

Section title: **"Four stages, one operator."**

| Stage        | Focus |
|--------------|-------|
| **Diagnose** | Audit the current community (or the gap where one should be) -- where people drop off and what's missing. |
| **Architect**| Design the structure: roles, channels, moderation logic, and the mechanics that keep people coming back. |
| **Launch**   | Build and ship bots, servers, and assets that match the brand and are ready for real traffic on day one. |
| **Operate**  | Moderate, iterate, and grow the community day to day -- the part most agencies skip. |

This section emphasizes that Majek owns the full lifecycle rather than handing off after launch.

### Selected Work

Three projects are featured:

1. **SpinMi** (featured case study with large media treatment)
2. **GiftTrove** (card with interactive image swap)
3. **cSIM Rate** (text-focused card)

### About

Short biographical section with circular avatar treatment and supporting tags:

- Community Architect
- Telegram & Discord
- Creator
- Blockchain
- VibeCoding

Core message: true community building blends culture and code to create spaces people actually want to stay in.

### Contact

Dark section with the headline:  
> "Let's build something that holds up."

Four contact cards linking to:
- Email
- Telegram
- X (Twitter)
- Discord

### Footer

- Brand + avatar
- Quick navigation links
- Aliases line
- "Buy me a coffee" tip link

---

## Selected Projects in Detail

### SpinMi

**Status:** Live & actively moderated  
**Type:** Telegram Mini App + Community  
**Metric highlighted:** 6,000+ MAU

**What it is:**  
SpinMi lets users create custom spinning animated coin spin emojis in under 60 seconds -- no 3D software or video editing required. Users design the emoji, the system renders it, and it appears ready to use in chat.

**Majek's involvement:**
- Day-to-day community moderation
- Hosted a last-one-standing elimination reward event
- Created 120+ spin emojis to help push SpinMi into memecoin buybot communities

**Links:**
- Mini App: [t.me/spinmibot/open](https://t.me/spinmibot/open)
- Community: [t.me/spinmicommunity](https://t.me/spinmicommunity)

### GiftTrove

**Status:** Built but currently paused  
**Type:** Telegram Mini App

**What it is:**  
A tool for scouting collectible gifts across multiple marketplaces (Telegram, Fragment, MarketApp, Thermos).

**Technical notes (from site copy):**
- Multilingual React frontend
- Python / Flask backend
- Premium plan + detail modals

The card on the site includes an interactive image swap (overview <-> in-app preview) controlled by a circular button.

### cSIM Rate

**Status:** Built for the ChainSIM community  
**Type:** Utility tool

**What it is:**  
A floor-price tracker and digit-value estimator that helps ChainSIM community members quickly assess rarity and pricing.

---

## Technical Architecture

This is a **zero-build, zero-dependency** static site.

| Layer         | Technology |
|---------------|----------|
| Markup        | Semantic HTML5 |
| Styling       | Vanilla CSS (custom properties + extensive media queries) |
| Interactivity | Vanilla JavaScript |
| Fonts         | Google Fonts (Newsreader, Inter, JetBrains Mono) |
| Assets        | Served via jsDelivr CDN from this repository |
| Hosting       | GitHub Pages (or any static host) via `CNAME` |

There is no React, Vue, Svelte, Next.js, or any other framework. The entire site lives in a single `index.html` file with embedded CSS and JS.

### Key Implementation Details

- **Scroll reveals** use `IntersectionObserver` with staggered delays
- **Mobile menu** is a full-viewport overlay with CSS transitions
- **Nav scroll state** is toggled via a passive scroll listener
- **GiftTrove image swap** is a pure CSS + JS class toggle
- **Responsive breakpoints** at 380px, 560px, 640px, 860px, 1024px, and 1280px
- Reduced-motion preference is respected

---

## Design System

### Color Palette (CSS Custom Properties)

```css
--ink: #100E1C;
--ink-soft: #211D38;
--indigo: #4B3FD1;
--periwinkle: #6E6FE3;
--periwinkle-mid: #8A8FE8;
--lavender: #C6C1F2;
--lavender-light: #E6E4FA;
--mist: #F5F3FC;
--paper: #FFFFFF;
--gray: #65627C;
```

### Typography

- **Headings:** Newsreader (serif)
- **Body:** Inter
- **Labels / Eyebrows:** JetBrains Mono (uppercase, tracked)

### Spacing & Radius

- Large radius: `24px`
- Medium radius: `16px`
- Small radius: `10px`
- Content max-width: `1180px`

The overall aesthetic is clean, slightly soft, and professional with a distinctive indigo/lavender accent system.

---

## Interactive Features

1. **Scroll-triggered reveals** -- Elements fade and slide up (or scale) as they enter the viewport
2. **Sticky navigation** -- Gains background blur and border after a small scroll threshold
3. **Mobile menu** -- Animated hamburger -> X, full-screen overlay with staggered link animations
4. **GiftTrove image crossfade** -- Button toggles between two screenshots with caption updates
5. **Hover states** -- Cards lift slightly and gain colored shadows; links change color

All interactions are lightweight and respect `prefers-reduced-motion`.

---

## SEO & Structured Data

The page includes:

- Proper `<title>` and meta description
- Canonical URL pointing to `https://interncodes.xyz/`
- JSON-LD `Person` schema with:
  - Name + alternate names
  - Job title
  - Email
  - Description
  - Social profile links (`sameAs`)

This helps search engines and knowledge graphs understand who the site represents.

---

## File Structure

```
interncodes-site/
â”œâ”€â”€ index.html              # Complete single-page application (HTML + CSS + JS)
â”œâ”€â”€ CNAME                   # Domain configuration -> interncodes.xyz
â”œâ”€â”€ README.md               # This file
â””â”€â”€ web_assets/
    â”œâ”€â”€ erthxn.PNG          # Profile / avatar image
    â”œâ”€â”€ spinmi.PNG          # SpinMi project screenshot
    â”œâ”€â”€ gifttrove.PNG       # GiftTrove main screenshot
    â”œâ”€â”€ gifttrove_preview.PNG # GiftTrove alternate/in-app view
    â””â”€â”€ majek.PNG           # Additional profile asset
```

Assets are referenced via the jsDelivr GitHub CDN pattern:

```
https://cdn.jsdelivr.net/gh/erthxn/interncodes-site@main/web_assets/...
```

---

## How to Run Locally

Because the site has no build step:

```bash
# Clone the repository
git clone https://github.com/erthxn/interncodes-site.git
cd interncodes-site

# Open in any static server or simply open index.html in a browser
# Example with Python:
python3 -m http.server 8000

# Then visit http://localhost:8000
```

No package managers, no `npm install`, no bundlers required.

---

## Deployment

The repository is configured for **GitHub Pages**:

1. The `CNAME` file sets the custom domain to `interncodes.xyz`
2. Pushing to the `main` branch (or the configured Pages branch) deploys the site
3. Because everything is static and self-contained, the same files can be dropped onto any static host (Netlify, Cloudflare Pages, Vercel static, S3, etc.)

---

## Customization Notes

If you fork or adapt this site:

- All major content lives in `index.html` -- search for section comments (`<!-- ===== SERVICES ===== -->` etc.)
- Colors and spacing are controlled via CSS custom properties at the top of the `<style>` block
- Project images live in `/web_assets/` and are loaded via jsDelivr for performance and caching
- The JSON-LD block in `<head>` should be updated if the identity or social links change
- The mobile menu and reveal system are pure vanilla JS -- easy to extend or remove

---

## Contact & Socials

| Platform     | Handle / Link |
|--------------|---------------|
| **Email**    | majek.erthxn@gmail.com |
| **Telegram** | [@erthxn](https://t.me/erthxn) |
| **X**        | [@erthxn](https://x.com/erthxn) |
| **Discord**  | Majek Ay (user ID linked on site) |
| **Website**  | [interncodes.xyz](https://interncodes.xyz) |

---

## License

This repository currently has no explicit license file. All rights to the design, content, and assets remain with Majek Ay / erthxn unless otherwise stated.

---

**Built by Majek Ay (erthxn)**  
Community Architect for Web3 -- designing the room, then running it.
