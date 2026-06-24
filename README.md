<p align="center">
  <img src="./danhino-banner.svg" alt="danhino" width="100%"/>
</p>

Technical Program Manager and full-stack builder with ~20 years in mortgage and financial services technology. I ship end-to-end — from backend APIs and databases to mobile apps and AI-powered tools. Currently job hunting in Houston, TX while building independently on the side.

> 🔭 **Currently building:** [AI Transparent Notes V2](https://github.com/danhino/ai-transparent-notes-v2)

---

### 📝 AI Transparent Notes V2

> **A true OS-level transparent notes app for Windows, built with AI writing tools baked in.**

| Layer | Tech |
|---|---|
| 🖥️ Desktop Shell | Tauri 2.0 |
| ⚛️ UI | React 19 + TypeScript |
| 🎨 Editing | Multi-pane, up to 8 tabs, CodeMirror 6 syntax highlighting for 15+ languages |
| 🤖 AI Tools | Contextual writing assistance and format toolbars |
| 📦 Distribution | NSIS `.exe` and `.msi` installers |

🔗 **[github.com/danhino/ai-transparent-notes-v2](https://github.com/danhino/ai-transparent-notes-v2)**

--

### 🛠️ Fuerza Home Services

> **A bilingual marketplace app connecting homeowners with trade professionals across six service categories.**

| Layer | Tech |
|---|---|
| 📱 App | React Native + Expo Router |
| ⚙️ Backend | Node.js, Express, TypeScript |
| 🗄️ Data | Prisma + PostgreSQL |
| 🔄 Realtime | Socket.io, Zustand |
| 💳 Payments | Stripe PaymentSheet + Connect Express |
| ☁️ Storage | Cloudflare R2 |
| 🔔 Notifications | Firebase Admin SDK |
| 🌐 i18n | Bilingual English + Spanish |

🔗 **[github.com/danhino/fuerza-home-services](https://github.com/danhino/fuerza-home-services)**

--

### ☀️ 100 Miles of Summer

> **A PWA-ready fitness tracker to log and gamify a summer running goal — no framework, no backend, no cost.**

| Layer | Tech |
|---|---|
| 🏗️ Structure | HTML5 semantic markup |
| 🎨 Styling | CSS3, responsive dark mode via `@media prefers-color-scheme` |
| ⚡ Logic | Vanilla JavaScript, no frameworks |
| 📊 Charts | Chart.js — activity breakdown visualization |
| 💾 Storage | Browser `localStorage` — offline-first, data stays on device |
| 📤 Export | `Blob` + `FileReader` APIs — JSON import/export for backups |
| 🌐 Hosting | GitHub Pages |

🔗 **[github.com/danhino/100-miles-of-summer](https://github.com/danhino/100-miles-of-summer)**

--

### 🤖 AI Resume Agent

> **A chatbot that answers questions about my professional background, deployed as both a full page and a floating widget on my portfolio.**

| Layer | Tech |
|---|---|
| 🌐 Proxy | Cloudflare Worker |
| 🔒 Security | CORS lock + IP-based rate limiting via KV |
| 🧠 System Prompt | Embedded professional profile context |

🔗 **[danhino.com](https://danhino.com)**

--

### 🏥 AI Claims Processor

> **A production-ready ERA/EOB analyzer that ingests ANSI 835 EDI files and ERA PDFs, extracts CPT, CAS, and RARC codes, and reports which claims are eligible for Independent Dispute Resolution (IDR).**

| Layer | Tech |
|---|---|
| 🖥️ Language | Python 3.11+ |
| 🌐 UI | Streamlit — file upload, results grid, code management |
| 📄 Parsing | Custom ANSI 835 tokenizer and segment parser (CLP, SVC, CAS, LQ) |
| 📑 PDF Extraction | PyPDF2 with Tesseract OCR fallback for scanned documents |
| 🤖 AI Enhancement | OpenAI, Claude/Anthropic, or Ollama — optional, gracefully degrades |
| 🔒 HIPAA | PHI redaction layer before any AI call; Ollama runs fully local (no BAA required) |
| 🗄️ Storage | SQLite for code reference data; PHI held in session state only |
| 📤 Reports | CSV, JSON, and HTML/PDF audit reports |
| 🧪 Tests | pytest with coverage via `pytest-cov` |

🔗 **[github.com/danhino/ai-claims-processor-idr-eligibility-analyzer](https://github.com/danhino/ai-claims-processor-idr-eligibility-analyzer)**

---

## ⚙️ Tech Stack

**Languages & Frameworks**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-CE422B?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**AI & Agents**

![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-4A90D9?style=for-the-badge&logoColor=white)

**Mobile & Desktop**

![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=for-the-badge&logo=tauri&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)

**Infrastructure**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)

---

## 🧬 What I Build

🤖 **AI-powered tools** — desktop apps with embedded AI writing assistants, AI chatbots, automated claims processing

📱 **Mobile marketplace apps** — bilingual, payment-integrated, with realtime backends

🌐 **Personal AI agents** — resume agents, portfolio chat widgets, Cloudflare-deployed proxies

🚀 **Full-stack delivery** — solo, from database schema to mobile UI to deployment

---

## 🔗 Connect

[![Portfolio](https://img.shields.io/badge/danhino.com-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://danhino.com)
[![Cookie Business](https://img.shields.io/badge/Dan's_Cookie_Jar-8B5E3C?style=for-the-badge&logo=cookiecutter&logoColor=white)](https://danscookiejar.com)
