# Christian Hamann

Senior UI/UX Architect and Software Developer. Founder of [visualfusion](https://www.visualfusion.de).

Based in Bavaria, Germany, and Tokyo, Japan — my second home, where I spend as much time as possible.

<p align="left">
  <img src="https://img.shields.io/badge/Swift-6.0-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift 6" />
  <img src="https://img.shields.io/badge/SwiftUI-iOS_%7C_iPadOS_%7C_macOS-007AFF?style=flat-square&logo=apple&logoColor=white" alt="SwiftUI" />
  <img src="https://img.shields.io/badge/React-18_%2F_19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Node.js-22-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/MCP-Model_Context_Protocol-8A2BE2?style=flat-square" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/Figma-Design_Systems-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="Figma" />
  <img src="https://img.shields.io/badge/Languages-DE_%7C_EN_%7C_JA-informational?style=flat-square" alt="German, English, Japanese" />
</p>

For over 25 years, I have worked as a design engineer and systems architect, bridging interface design in Figma with robust code. My work spans native Apple applications written in Swift, high-performance web applications with headless architectures, AI-ready services built on the Model Context Protocol, and independent, self-hosted infrastructure.

---

## Studio & Practice

**[visualfusion](https://www.visualfusion.de)** is my digital agency and software studio based in Traunstein, Germany. We design and engineer bespoke web platforms, native mobile applications, and holistic brand identities for clients across Europe, with an emphasis on typographic clarity, fluid interactions, and long-term maintainability.

---

## Selected Projects

| Project | Platform / Type | Status | Core Architecture | Links |
| :--- | :--- | :--- | :--- | :--- |
| **FeedKeeper** | Native App (iOS, iPadOS, macOS) & Server | Available on the App Store | Swift 6, SwiftUI, SQLite FTS5, WebKit, Node.js Core, MCP | [feedkeeper.cloud](https://feedkeeper.cloud) · [App Store](https://apps.apple.com/app/id6819176523) · [Open Source Core](https://github.com/visualfusion/feedkeeper) |
| **LumiGlass** | Native Smart Home Client (iOS, iPadOS, macOS) | In development | Swift 6, SwiftUI, Apple HomeKit, Home Assistant WebSockets | [lumiglass.app](https://lumiglass.app) · [Roadmap](https://www.visualfusion.de/lumiglass#roadmap) |
| **visualfusion** | Agency Website (DE / EN / JA) | Live | React 19, Vite 8 SSG, Three.js WebGL, Tailwind CSS v4, Umami | [visualfusion.de](https://www.visualfusion.de) |
| **Portfolio** | Headless SPA & Content Management (DE / EN / JA) | Live | React 18, Vite SSG, Craft CMS 5, GraphQL, Cloudflare Workers | [christianhamann.de](https://christianhamann.de) |

---

## Native Applications in Detail

### FeedKeeper
A high-end editorial RSS reader designed natively for the Apple ecosystem, available on the App Store for iPhone, iPad, and Mac.

[**Download on the App Store ↗**](https://apps.apple.com/app/id6819176523) &nbsp;·&nbsp; [**Visit feedkeeper.cloud ↗**](https://feedkeeper.cloud) &nbsp;·&nbsp; [**Open Source Server Core (GitHub) ↗**](https://github.com/visualfusion/feedkeeper)

- Built strictly with Swift 6 and SwiftUI, adhering to strict concurrency and zero external Swift package dependencies.
- Features a personalized editorial newspaper issue ("Deine Zeitung"), offline reading with delta synchronization, and sub-millisecond local full-text search powered by SQLite FTS5.
- Localized in German, English, and Japanese, including Japanese phrase-aware line breaking in the reader.
- Accompanied by a commercial cloud edition with AI curation that writes in the reader's language.

#### FeedKeeper Core (Open Source)

<p align="left">
  <a href="https://github.com/visualfusion/feedkeeper/releases"><img src="https://img.shields.io/github/v/release/visualfusion/feedkeeper?style=flat-square&label=release" alt="Latest release" /></a>
  <a href="https://www.npmjs.com/package/feedkeeper"><img src="https://img.shields.io/npm/v/feedkeeper?style=flat-square&logo=npm" alt="npm" /></a>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT License" />
  <img src="https://img.shields.io/badge/MCP-Streamable_HTTP-8A2BE2?style=flat-square" alt="MCP" />
</p>

A lightweight, MIT-licensed, self-hosted RSS server and remote MCP server built with Node.js, Express, and SQLite FTS5.

- Native, authenticated MCP endpoint with OAuth sign-in or personal access tokens, so Claude, ChatGPT, and other MCP clients can read, search, triage, and curate feeds directly.
- Listed in the official MCP Registry (`io.github.visualfusion/feedkeeper`) and verified in Claude's connector directory.
- Runs with Docker or without any setup via `npx feedkeeper`; your data stays in your own SQLite database.

### LumiGlass
A native smart home client unifying Apple HomeKit and Home Assistant into a cohesive Liquid Glass interface. Currently in development.

[**Visit lumiglass.app ↗**](https://lumiglass.app) &nbsp;·&nbsp; [**Roadmap & Architecture ↗**](https://www.visualfusion.de/lumiglass#roadmap)

- Built with Swift 6 and SwiftUI, leveraging Apple's native Liquid Glass APIs and modern concurrency, with a Mac Catalyst app for full HomeKit support on macOS.
- Hybrid mode running HomeKit (`HMHomeManager`) and Home Assistant (WebSocket API, local discovery, remote access) side by side, with duplicate devices and rooms merged automatically.
- Real-time controls for lighting, climate, shading, locks, and sensors, 24-hour history charts, plus on-device integrations for MusicKit, EventKit, WeatherKit, and AlarmKit.
- Localized in German, English, and Japanese.

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
- HomeKit (`HMHomeManager`), EventKit, WeatherKit, MusicKit, AlarmKit
- SQLite, FTS5, Data Protection Keychain
- App Store distribution with Xcode Cloud and TestFlight

### UI/UX Design & Frontend Architecture

<p align="left">
  <img src="https://img.shields.io/badge/Figma-Design_Systems-F24E1E?style=flat-square&logo=figma&logoColor=white" alt="Figma" />
  <img src="https://img.shields.io/badge/React-18_%2F_19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-v3_%2F_v4-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Three.js-WebGL_3D-000000?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/Vite-7_%2F_8-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
</p>

- Figma, Sketch, Adobe Creative Cloud, Affinity Suite
- Design systems, design tokens, responsive typography
- React 19 / 18, TypeScript, modern JavaScript, Tailwind CSS
- Three.js, WebGL, interactive 3D graphics
- Vite, build-time prerendering (SSG), Single Page Applications
- Multilingual interfaces (DE / EN / JA) with BudouX phrase breaking and dedicated Japanese typography
- Accessibility (WCAG 2.1 AA) and Core Web Vitals optimization

### Backend, APIs & Infrastructure

<p align="left">
  <img src="https://img.shields.io/badge/Node.js-22-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/MCP-Streamable_HTTP-8A2BE2?style=flat-square" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/PHP-8.4-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP 8.4" />
  <img src="https://img.shields.io/badge/Craft_CMS_5-GraphQL-E5422B?style=flat-square&logo=craftcms&logoColor=white" alt="Craft CMS 5" />
  <img src="https://img.shields.io/badge/Contao-Enterprise_CMS-F1592A?style=flat-square&logo=contao&logoColor=white" alt="Contao" />
  <img src="https://img.shields.io/badge/SQLite_FTS5-Full--Text_Search-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite FTS5" />
  <img src="https://img.shields.io/badge/Cloudflare_Workers-Edge_Proxy-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare Workers" />
  <img src="https://img.shields.io/badge/Docker-Containers-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

- Craft CMS 5 (Headless, GraphQL), Contao, WordPress
- Node.js, Express, PHP 8.4
- Model Context Protocol servers (Streamable HTTP, OAuth with PKCE, scoped access tokens)
- SQLite, MariaDB, MySQL
- Cloudflare Workers (Edge proxy and static delivery)
- Docker, Coolify, Debian Linux container administration
- Automated CI/CD pipelines via GitHub Actions and npm Trusted Publishing

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
- FeedKeeper on the App Store: [apps.apple.com/app/id6819176523](https://apps.apple.com/app/id6819176523)
- Open Source RSS & MCP Server: [github.com/visualfusion/feedkeeper](https://github.com/visualfusion/feedkeeper)
- LinkedIn: [linkedin.com/in/christian-r-hamann](https://linkedin.com/in/christian-r-hamann)
- Email: christian.hamann@visualfusion.de
