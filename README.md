# Christian Hamann

Senior UI/UX Architect and Software Developer. Founder of [visualfusion](https://www.visualfusion.de).

Based in Bavaria, Germany, and Tokyo, Japan — my second home, where I spend as much time as possible.

<p align="left">
  <img src="https://img.shields.io/badge/Swift-6.0-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift 6" />
  <img src="https://img.shields.io/badge/SwiftUI-iOS_%7C_iPadOS_%7C_macOS-007AFF?style=flat-square&logo=apple&logoColor=white" alt="SwiftUI" />
  <img src="https://img.shields.io/badge/Apple_HomeKit-IoT-FF9500?style=flat-square&logo=apple&logoColor=white" alt="Apple HomeKit" />
  <img src="https://img.shields.io/badge/Home_Assistant-WebSockets-41BDF5?style=flat-square&logo=homeassistant&logoColor=white" alt="Home Assistant" />
  <img src="https://img.shields.io/badge/React-18_%2F_19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Three.js-WebGL-000000?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/Vite-5_%2F_6-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Figma-Design_Systems-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="Figma" />
  <img src="https://img.shields.io/badge/Node.js-22-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/PHP-8.4-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP 8.4" />
  <img src="https://img.shields.io/badge/Craft_CMS_5-GraphQL-E5422B?style=flat-square&logo=craftcms&logoColor=white" alt="Craft CMS 5" />
  <img src="https://img.shields.io/badge/Contao-CMS-F1592A?style=flat-square&logo=contao&logoColor=white" alt="Contao" />
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" alt="GraphQL" />
  <img src="https://img.shields.io/badge/SQLite_FTS5-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/Docker-Containers-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

For over 25 years, I have worked as a design engineer and systems architect, bridging interface design in Figma with robust code. My work spans native Apple applications written in Swift, high-performance web applications with headless architectures, and independent, self-hosted infrastructure.

---

## Studio & Practice

**[visualfusion](https://www.visualfusion.de)** is my digital agency and software studio based in Traunstein, Germany. We design and engineer bespoke web platforms, native mobile applications, and holistic brand identities for clients across Europe, with an emphasis on typographic clarity, fluid interactions, and long-term maintainability.

---

## Selected Projects

| Project | Platform / Type | Core Architecture | Links |
| :--- | :--- | :--- | :--- |
| **FeedKeeper** | Native App (iOS, iPadOS, macOS) & Server | Swift 6, SwiftUI, SQLite FTS5, WebKit, Node.js Core | [feedkeeper.cloud](https://feedkeeper.cloud) · [Open Source Core](https://github.com/visualfusion/feedkeeper) |
| **LumiGlass** | Native Smart Home Client (iOS, iPadOS, macOS) | Swift 6, SwiftUI, Apple HomeKit, Home Assistant WebSockets | [visualfusion.de/lumiglass](https://www.visualfusion.de/lumiglass) · [Roadmap](https://www.visualfusion.de/lumiglass#roadmap) |
| **visualfusion** | Agency Web Application | React 19 SSR, Three.js 3D WebGL, Tailwind CSS v4, Umami | [visualfusion.de](https://www.visualfusion.de) |
| **Portfolio** | Headless SPA & Content Management | React 18, Vite SSG, Craft CMS 5, GraphQL, Cloudflare Workers | [christianhamann.de](https://christianhamann.de) |

---

## Native Applications in Detail

### FeedKeeper
A high-end editorial RSS reader designed natively for the Apple ecosystem.
- Built strictly with Swift 6 and SwiftUI, adhering to strict concurrency and zero external Swift package dependencies.
- Features a personalized editorial newspaper issue ("Deine Zeitung"), offline reading with delta synchronization, and sub-millisecond local full-text search powered by SQLite FTS5.
- Accompanied by a standalone, MIT-licensed open-source server core and a commercial cloud edition with automated AI curation.

### LumiGlass
A native smart home client unifying Apple HomeKit and Home Assistant into a cohesive Liquid Glass interface.
- Built with Swift 6 and SwiftUI, leveraging Apple's native Liquid Glass design language and modern concurrency.
- Dual-mode architecture communicating directly with HomeKit accessories via `HMHomeManager` and with Home Assistant over WebSockets.
- Real-time controls for lighting, climate, and shading, with 24-hour historical sensor telemetry and cross-platform scene execution.

---

## Technical Disciplines

### Native Apple Ecosystem

<p align="left">
  <img src="https://img.shields.io/badge/Swift-6.0-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift 6" />
  <img src="https://img.shields.io/badge/SwiftUI-Apple_Platforms-007AFF?style=flat-square&logo=apple&logoColor=white" alt="SwiftUI" />
  <img src="https://img.shields.io/badge/Xcode-27+-147EFB?style=flat-square&logo=xcode&logoColor=white" alt="Xcode" />
  <img src="https://img.shields.io/badge/HomeKit-HMHomeManager-FF9500?style=flat-square&logo=apple&logoColor=white" alt="HomeKit" />
  <img src="https://img.shields.io/badge/Home_Assistant-WS_API-41BDF5?style=flat-square&logo=homeassistant&logoColor=white" alt="Home Assistant" />
  <img src="https://img.shields.io/badge/WebKit-Native_Integration-000000?style=flat-square&logo=safari&logoColor=white" alt="WebKit" />
</p>

- Swift 6, SwiftUI, Swift Concurrency
- AppKit, Mac Catalyst, StoreKit 2, WebKit
- HomeKit (`HMHomeManager`), EventKit, WeatherKit
- SQLite, FTS5, Data Protection Keychain

### UI/UX Design & Frontend Architecture

<p align="left">
  <img src="https://img.shields.io/badge/Figma-Design_Systems-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="Figma" />
  <img src="https://img.shields.io/badge/React-18_%2F_19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-v3_%2F_v4-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Three.js-WebGL_3D-000000?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/Vite-Tooling-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
</p>

- Figma, Sketch, Adobe Creative Cloud, Affinity Suite
- Design systems, design tokens, responsive typography
- React 19 / 18, TypeScript, modern JavaScript, Tailwind CSS
- Three.js, WebGL, interactive 3D graphics
- Vite, build-time prerendering, Single Page Applications
- Accessibility (WCAG 2.1 AA) and Core Web Vitals optimization

### Backend, APIs & Infrastructure

<p align="left">
  <img src="https://img.shields.io/badge/Node.js-22-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/PHP-8.4-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP 8.4" />
  <img src="https://img.shields.io/badge/Craft_CMS_5-GraphQL-E5422B?style=flat-square&logo=craftcms&logoColor=white" alt="Craft CMS 5" />
  <img src="https://img.shields.io/badge/Contao-Enterprise_CMS-F1592A?style=flat-square&logo=contao&logoColor=white" alt="Contao" />
  <img src="https://img.shields.io/badge/SQLite_FTS5-Full--Text_Search-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite FTS5" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-Edge_Proxy-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare Workers" />
  <img src="https://img.shields.io/badge/Docker-Containers-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

- Craft CMS 5 (Headless, GraphQL), Contao, WordPress
- Node.js, Express, PHP 8.4
- SQLite, MariaDB, MySQL
- Cloudflare Workers (Edge proxy and static delivery)
- Docker, Coolify, Debian Linux container administration
- Automated CI/CD pipelines via GitHub Actions

---

## Spoken Languages

- German: Native
- English: Fluent
- Japanese: Advanced (intercultural background; Tokyo is my second home)
- Italian: Basic

---

## Background & Selected Brands

As a certified Digital Media Specialist (*Geprüfter Medienfachwirt Digital IHK*), I have architected and engineered platforms, digital campaigns, and user interfaces across diverse sectors.

Selected brands and institutions:
- Automotive & Retail: Porsche Holding, Porsche Bank, XXXLutz
- Consumer Goods & FMCG: Procter & Gamble, Nestlé, Pampers, Unilever, Nivea (Beiersdorf)
- Media & Culture: Bertelsmann Group, Disney Channel, Salzburg Easter Festival

---

## Principles

- Native ergonomics: Native platforms deserve genuine system design, fluid physics, and platform conventions instead of web-wrapper abstractions.
- Privacy by design: No commercial tracking cookies, no surveillance analytics, and strict data boundaries at all system edges.
- Durability: Readable, strictly typed code with minimal third-party dependencies built for long-term maintainability.

---

## Connect

- Website & Portfolio: [christianhamann.de](https://christianhamann.de)
- Studio: [visualfusion.de](https://www.visualfusion.de)
- Open Source RSS Server: [github.com/visualfusion/feedkeeper](https://github.com/visualfusion/feedkeeper)
- LinkedIn: [linkedin.com/in/christian-r-hamann](https://linkedin.com/in/christian-r-hamann)
- Email: christian.hamann@visualfusion.de
