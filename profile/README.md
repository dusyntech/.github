<div align="center">

# Dusyn Technologies

### Next-Generation Unified Cloud Ecosystem & Developer Infrastructure

[![Website](https://img.shields.io/badge/Website-dusyn.in-blue?style=for-the-badge&logo=google-chrome&logoColor=white)](https://dusyn.in)
[![Organization](https://img.shields.io/badge/GitHub-dusyntech-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dusyntech)
[![Enquiries](https://img.shields.io/badge/Enquiries-hello%40dusyn.in-2ea44f?style=for-the-badge&logo=gmail&logoColor=white)](mailto:hello@dusyn.in)
[![Architecture](https://img.shields.io/badge/Ecosystem-16%2B_Cloud_Apps-8a2be2?style=for-the-badge)](https://dusyn.in)

</div>

---

### 🌐 About Dusyn Technologies

**Dusyn Technologies** develops an all-in-one, privacy-centric cloud productivity ecosystem and cutting-edge developer tooling. From centralized **Master SSO Identity** to 16 specialized satellite cloud micro-apps and AI-driven video engines, we craft high-performance software engineered for speed, privacy, and modern developer workflows.

---

### 🏛️ Ecosystem Architecture: Master SSO & Satellite Apps

At the core of the Dusyn ecosystem lies a unified distributed architecture:
- **Master Account Hub (`account`)**: Centralized identity provider issuing asymmetric RS256 JWT tokens with global Redis revocation and Cloudflare Turnstile protection.
- **Unified Satellites**: 16 dedicated cloud productivity applications running with independent databases, shared design tokens, and seamless one-click single sign-on across `*.dusyn.in`.

---

### 📦 The Dusyn Cloud Suite

| Category | Service | Description | Core Stack |
| :--- | :--- | :--- | :--- |
| **Identity** | **Dusyn Account** | Master Identity, multi-profile switcher, OAuth, and central session manager. | Next.js 15, RS256 JWT, Redis |
| **Productivity** | **Dusyn Drive** | Secure cloud file storage, folder hierarchy, and media preview pipeline. | Next.js 15, Go / Node.js, MongoDB |
| **Productivity** | **Dusyn Docs** | Collaborative document editor with rich markdown and formatted export. | Next.js 15, WebSocket, MongoDB |
| **Productivity** | **Dusyn Sheets** | Cloud spreadsheet engine with real-time formula computation and grid views. | Next.js 15, Canvas, Node.js |
| **Productivity** | **Dusyn Notes** | Instant, distraction-free markdown note-taking and idea organizer. | Next.js 15, TypeScript, MongoDB |
| **Productivity** | **Dusyn Tasks** | Kanban boards, project management, and automated todo workflows. | Next.js 15, REST API, MongoDB |
| **Productivity** | **Dusyn Calendar** | Interactive event scheduling, time-blocking, and calendar coordination. | Next.js 15, Go, MongoDB |
| **Media & Comms**| **Dusyn Chat** | Real-time team messaging channels with low-latency pub/sub pipelines. | Next.js 15, WebSocket, Redis Pub/Sub |
| **Media & Comms**| **Dusyn Meet** | WebRTC-powered virtual meetings, screen sharing, and peer-to-peer rooms. | Next.js 15, WebRTC, MediaServer |
| **Media & Comms**| **Dusyn Photos** | High-resolution cloud photo gallery, intelligent tagging, and albums. | Next.js 15, S3-compatible Blob, Node.js |
| **Media & Comms**| **Dusyn Music** | Lossless audio streaming, interactive player, playlists, and audio engine. | Next.js 15, Web Audio API, Go |
| **Media & Comms**| **Dusyn Video** | Cloud video hosting, adaptive HLS streaming, and playback studio. | Next.js 15, FFmpeg, Cloudflare Stream |
| **Utilities** | **Dusyn PDF** | PDF utility suite: merge, split, annotate, compress, and document conversion. | Next.js 15, WebAssembly, Node.js |
| **Utilities** | **Dusyn Resume** | Interactive CV and resume builder with modern ATS-compliant templates. | Next.js 15, React-PDF, TailwindCSS |
| **Utilities** | **Dusyn Contacts** | Global address book, contact categorization, and cross-app sync. | Next.js 15, Go, MongoDB |
| **Utilities** | **Dusyn Calculator** | Scientific, financial, and precision mathematical computation suite. | Next.js 15, Math Engine |
| **Utilities** | **Dusyn Age Calc** | Precision date difference, countdown chronometer, and milestone tracker. | Next.js 15, TypeScript |

---

### ⚡ Developer Tooling & Open Source

- **[Reelcraft](https://github.com/dusmamud/reelcraft)**: Open-source CLI that turns codebases and GitHub repos into beat-synced 9:16 vertical shorts in 30 seconds using Hyperframes, kinetic code typing, and auto-generated narration.

---

### 🛠️ Technology Stack & Engineering Standards

- **Web Frontend**: Next.js 15+ (App Router), React 19, TypeScript, Tailwind CSS v4, Lucide Icons.
- **Mobile Apps**: Native Android (Kotlin, Jetpack Compose, Dagger Hilt, Retrofit).
- **Backend Services**: Go (Chi / Gin), Node.js (Express, Mongoose), REST & WebSocket microservices.
- **Databases & Caching**: MongoDB, CockroachDB / PostgreSQL, Redis (session management & token blacklisting).
- **Security & Infra**: RS256 JWT validation, Cloudflare Turnstile bot protection, Docker, GitHub Actions CI/CD.

---

### 📬 Connect & Enquiries

- **Official Website:** [dusyn.in](https://dusyn.in)
- **General & Business Enquiries:** [hello@dusyn.in](mailto:hello@dusyn.in)
- **Support & Security:** [dusmamud0@gmail.com](mailto:dusmamud0@gmail.com)
- **Founder Profile:** [@dusmamud](https://github.com/dusmamud)
