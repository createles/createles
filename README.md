# Welcome! 👋

<div align="center">

[![English](https://img.shields.io/badge/README-English-blue.svg)](#) 
[![Japanese](https://img.shields.io/badge/README-日本語-red.svg)](./README.ja.md)

### Full-Stack Software Engineer | Node.js • Express • PostgreSQL • MongoDB • JavaScript / React
![English](https://img.shields.io/badge/ENG-green) ![Japanese](https://img.shields.io/badge/JP-red) ![Filipino](https://img.shields.io/badge/FIL-blue)



> *Building sense-provoking web experiences, interactive tools, and user immersive displays with a puzzle-solver's mindset.*

[🌐 Live Portfolio](https://github.com/createles) • [💼 LinkedIn](https://www.linkedin.com/in/jlc7/) • [✉️ Email](mailto:jlazcastillo@gmail.com)

</div>

---

## 💭 Profile & Engineering Approach

I’m a full-stack software engineer currently based in Osaka, Japan. When I’m not architecting web backends or building React interfaces, you’ll usually find me dissecting game mechanics in survival-horror titles or passing time working through complex logic puzzles.

Having spent years designing interactive learning tools & realia and facilitating professionals in multicultural communication, I've always been fascinated by the challenge of crafting experiences that engage one's curiosity. Today, I bring that exact mindset to web development by exercising the intersection between the art of puzzle-solving and providing fulfilling user outcomes. I love taking head-scratching technical problems, and structuring software in ways that turn them into responsive, felt experiences that stimulate one's own intuition along with task fulfillment.

---

## 🛠️ Technical Core

| Category | Skill Set |
| :--- | :--- |
| **Languages** | JavaScript (ES6+), TypeScript, Python, HTML5, CSS3, SQL |
| **Backend & APIs** | Node.js, Express.js, NestJS, Next.js, WebSockets (Socket.io), Asynchronous Daemons (Python / asyncio), RESTful APIs, Middleware Architecture, Auth / Sessions |
| **Database & Storage** | PostgreSQL, SQLite (WAL / Single-Writer), MongoDB, Prisma ORM, Supabase, Firebase Storage |
| **Frontend & Templating** | React, Tailwind CSS, EJS, Responsive Web Design, Dynamic DOM Interaction |
| **DevOps & Tools** | Git, GitHub, Docker, pnpm Workspaces, Nginx, Playwright, Pytest, Ruff, uv, Railway, Vercel, Netlify, Postman, Multer, Sharp |
| **AI Tooling & Workflows** | Claude Code, Gemini / Antigravity CLI, Cursor, GitHub Copilot |
| **Active Explorations** | IoT / Raspberry Pi Automation & Home Servers, Godot Engine (Game Logic & Systems Design) |

---

## ⭐️ Featured Spotlights

### 1. [CapsLoc — Game Localization & LQA Triage Hub](https://github.com/createles/capsloc) 🎮
> **Enterprise-Grade Real-Time Game Localization & LQA Triage Monorepo**

<div align="center">
  <a href="https://capsloc.up.railway.app/">
    <img src="https://github.com/createles/capsloc/releases/download/v1.0.0-assets/hero_cockpit.gif" alt="CapsLoc Cockpit Overview" width="680" />
  </a>
  <p align="center">
    <sub>🎮 16:9 Cockpit Preview — Real-time localization triage, slide-out string inspector, and character limit hazard gauges.</sub>
  </p>
</div>

* **Tech Stack**: `TypeScript (~6.0)` • `NestJS v12` • `React 19` • `Socket.io` • `PostgreSQL 16` • `Prisma 7` • `Tailwind CSS v4` • `Docker` • `pnpm Workspaces`
* **Architecture & Highlights**:
  * **Unified Monorepo**: Strict pnpm workspace sharing compile-time TypeScript DTOs and contracts between NestJS backend and React frontend.
  * **Real-Time Duplex Gateway**: Low-latency Socket.io triage messaging, presence tracking, and active typing indicators.
  * **Relational LocString Parsing**: Automated regex detection (`#LOC-*`, `$STR_*`) linking dialog and UI strings directly to PostgreSQL.
  * **Inspector Drawer & Hazard Gauges**: Dynamic character limit gauges preventing localized UI text clipping, sub-millisecond canonical glossary termbase, and strict RBAC approvals (`LOC_PM`, `SOLUTIONS_DEV`).
  * **Zero-Reflow Bilingual Engine**: Instant EN/JA toggle with 100% compile-time dictionary parity across 228 strictly-typed keys.
* 🚀 **[Explore Live Demo](https://capsloc.up.railway.app/)** • 📦 **[GitHub Repository](https://github.com/createles/capsloc)** • 🏛️ **[System Architecture](https://github.com/createles/capsloc/blob/main/docs/architecture.md)** • [日本語ドキュメント](https://github.com/createles/capsloc/blob/main/README.ja.md)

---

### 2. [Sennan City JETs Resource Portal](https://github.com/createles/sennan-jet-resources) 📢
> **Production Community Portal & Authenticated Marketplace**

| 🏛️ Portal Hub & Guidebook | 🛒 Community Marketplace (Live Triage) |
| :---: | :---: |
| <a href="https://sennan-jets.up.railway.app/"><img src="https://raw.githubusercontent.com/createles/sennan-jet-resources/main/assets/herobanner-section.png" alt="Sennan City JETs Portal Banner" width="100%" /></a> | <a href="https://sennan-jets.up.railway.app/"><img src="https://raw.githubusercontent.com/createles/sennan-jet-resources/main/assets/marketplace-section.gif" alt="Community Marketplace Live Demo" width="100%" /></a> |

<p align="center">
  <sub>📢 Left: Municipal information portal & guidebook • Right: Authenticated marketplace with on-the-fly Sharp image compression.</sub>
</p>

* **Tech Stack**: `Node.js` • `Express` • `EJS` • `PostgreSQL` • `Prisma ORM` • `Supabase Storage` • `Railway` • `Multer` • `Sharp`
* **Architecture & Highlights**:
  * **Production Deployment**: Active one-stop portal and verified marketplace serving municipal civil servants and foreign educators in Sennan City.
  * **In-Memory Image Optimization**: Automated `Multer` + `Sharp` compression pipeline processing uploads directly in server memory, slashing storage footprints by **70%+** without client-side lag.
  * **Relational Schema Integrity**: Prisma ORM managing user auth, item reservation lifecycles, and public community noticeboards.
* 🚀 **[Explore Live App](https://sennan-jets.up.railway.app/)** • 📦 **[GitHub Repository](https://github.com/createles/sennan-jet-resources)** • [English Documentation](https://github.com/createles/sennan-jet-resources/blob/main/README.md) • [日本語ドキュメント](https://github.com/createles/sennan-jet-resources/blob/main/README.ja.md)

---

### 🔧 Systems & Targeted Implementations

### 3. [JP PC Parts Price & Stock Watcher](https://github.com/createles/price-watcher) ⚡
> **Asynchronous E-Commerce Scraping & Event Daemon**
>
> * **Tech Stack**: `Python 3.12+` • `Playwright Async` • `Pydantic v2` • `SQLite (WAL)` • `Discord Webhooks` • `Pytest` • `uv`
> * **Engineering Highlight**: Architected an asynchronous event-driven daemon featuring decoupled strategy extractors for Japanese retail DOMs (Tsukumo, Dospara, PC One's) and an `asyncio.Queue` single-writer actor pattern preventing SQLite write locks. Validated with 160 hermetic tests running in <0.6s.
> * 📦 [GitHub Repository](https://github.com/createles/price-watcher) • [English Documentation](https://github.com/createles/price-watcher/blob/main/README.md) • [日本語ドキュメント](https://github.com/createles/price-watcher/blob/main/README.ja.md)

### 4. [Memoreat](https://github.com/createles/memoreat) 🍽️
> **Containerized Food Diary & Automated CI/CD Pipeline**
>
> * **Tech Stack**: `Next.js` • `TypeScript` • `React` • `PostgreSQL` • `Prisma ORM` • `Docker` • `GitHub Actions` • `Framer Motion`
> * **Engineering Highlight**: Packaged a full-stack Next.js application and relational database with Docker Compose, automated through GitHub Actions CI/CD to build and publish production images to GitHub Container Registry (GHCR).
> * 🚀 [Live App](https://memoreat-production.up.railway.app/) • 📦 [GitHub Repository](https://github.com/createles/memoreat) • [English Documentation](https://github.com/createles/memoreat/blob/main/README.md) • [日本語ドキュメント](https://github.com/createles/memoreat/blob/main/README.ja.md)

### 5. [Pass-n-Go Captcha Middleware](https://github.com/createles/pass-n-go) 🔐
> **Interactive Anti-Bot Visual Verification Middleware**
>
> * **Tech Stack**: `JavaScript (ES6+)` • `Express` • `React` • `HTML5/CSS3` • `MongoDB` • `Prisma ORM` • `Supabase` • `Railway`
> * **Engineering Highlight**: Built custom security middleware utilizing a dynamic 3x3 image grid system. Replaced static captcha checks with instant, stateful visual feedback to optimize user interaction while maintaining security integrity.
> * 🚀 [Live App](https://pass-n-go-captcha.up.railway.app/) • 📦 [GitHub Repository](https://github.com/createles/pass-n-go) • [English Documentation](https://github.com/createles/pass-n-go/blob/main/README.md) • [日本語ドキュメント](https://github.com/createles/pass-n-go/blob/main/README.ja.md)

### 6. [Gobble Drive](https://github.com/createles/gooble-drive) 🗃️
> **Cloud Storage & File Management Platform**
>
> * **Tech Stack**: `Node.js` • `Express` • `JavaScript (ES6+)` • `Database Storage` • `Railway`
> * **Engineering Highlight**: Designed a full-stack file management system supporting multipart file uploads, recursive folder hierarchy management, and dynamic database querying.
> * 🚀 [Live App](https://gobble-drive-production.up.railway.app/) • 📦 [GitHub Repository](https://github.com/createles/gooble-drive) • [English Documentation](https://github.com/createles/gobble-drive/blob/main/README.md) • [日本語ドキュメント](https://github.com/createles/gobble-drive/blob/main/README.ja.md)
---

## 💼 Professional Background

* **Interactive Learning Tooling & Digital Media** | *JET Programme (~5 yrs)*
  * **Automation & Tools**: Developed local interactive web applications & activities, programmable quiz tools, and digital-to-physical mapping assets that modernized lesson frameworks, leading to city-wide adoption across Japanese schools in the municipality.
  * **Project Leadership**: Spearheaded internationalization community initiatives (including an interactive puzzle-mystery activity for a 300+ participant event) and engineered objective-based programs focused on active problem-solving strategies.

* **Technical Program Delivery & Enterprise Solutions** | *Corporate Specialist (~3 yrs)*
  * **Client Solution Engineering**: Scoped and delivered custom technical training frameworks for enterprise clients (e.g., Accenture, Toyota), aligning complex operational requirements with strict SLA milestones.
  * **Data & Assessment Pipelines**: Managed standardized evaluation workflows and benchmarked diagnostic assessment data pipelines for 200+ corporate stakeholders.

---

## 🌐 Trilingual Capabilities

* **JLPT N2 Certified**: Capable in reading Japanese technical documentation, navigating local systems, and translating deliverables.
* **Native English & Filipino**: Full professional fluency in English and Filipino work environments. 
* **Cross-Cultural Technical Communication**: Experienced in facilitating requirement gathering, specification handoffs, and documentation reviews between English and Japanese teams.

---

<div align="center">
  <sub>Open for Full-Stack Software Engineering opportunities in Japan & Remote.</sub>
</div>