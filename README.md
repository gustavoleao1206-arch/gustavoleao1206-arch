<p align="center">
  <img src="./assets/banner-en.png" alt="Gustavo Leão — full stack developer" width="100%">
</p>

<h2 align="center">Gustavo Leão · Full Stack Developer</h2>

<p align="center">
  AI-powered SaaS and automation for the legal sector
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/gustavo-leao-dev"><img src="https://img.shields.io/badge/LinkedIn-gustavo--leao--dev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.workana.com/freelancer/e374923f8c4b54cab1f5f7d6e4b1725b"><img src="https://img.shields.io/badge/Workana-freelance-4b2fd6?style=for-the-badge" alt="Workana"></a>
  <a href="https://leaoamorimtecnologia.com.br"><img src="https://img.shields.io/badge/Le%C3%A3o%20Amorim-Tecnologia-111827?style=for-the-badge" alt="Leão Amorim Tecnologia"></a>
</p>

---

## About me

I build web systems and SaaS products for law firms and legal departments that need to get off spreadsheets, automate repetitive work and keep their data in one place. Most of what I ship runs in production for real users, so I care as much about security, tests and maintainability as about features.

- **Now:** building legal SaaS products at Leão Amorim Tecnologia, and developing and automating internal HR (TOTVS) and legal systems at TV Gazeta de Alagoas
- **Education:** currently studying at UNINTER
- **Open to work:** full-time roles and freelance projects

## Tech stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS">
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white" alt="Unity">
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI">
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini">
</p>

## Featured projects

All of them are open source. The products serve Brazilian users, so their interfaces and code comments are in Portuguese; every repository has an English README.

### [LeoJuris](https://github.com/gustavoleao1206-arch/leojuris) · legal practice management
<a href="https://github.com/gustavoleao1206-arch/leojuris"><img src="./assets/leojuris.png" alt="LeoJuris" width="100%"></a>

Clients, cases, business-day deadlines, calendar, documents and fee splitting for a law firm, with court-gazette monitoring (DJEN) and case-status updates from DataJud/CNJ. AI reads PDFs and images, a person approves, and the system updates everything. Running in production at a Brazilian law firm.

**Highlights:** two-layer role-based access control, TOTP 2FA, audit trail, CSP without `unsafe-inline`, rate limiting, installable PWA, 967 automated tests.

**Stack:** Python · FastAPI · SQLAlchemy · PostgreSQL · vanilla JS

### [Prescrição Pro](https://github.com/gustavoleao1206-arch/prescricao-pro-saas) · legal SaaS with applied AI
<a href="https://github.com/gustavoleao1206-arch/prescricao-pro-saas"><img src="./assets/prescricao-pro-en.png" alt="Prescrição Pro" width="100%"></a>

Analyzes tax enforcement lawsuits from the case PDF and flags statute-of-limitations issues, with deterministic date checks, an AI-written report showing every calculation, and a draft petition. Credit-based subscription with payments through Asaas.

**Highlights:** idempotent credit ledger with refunds, field-level AES-256-GCM encryption, data-retention jobs, nonce-based CSP, 985 automated tests.

**Stack:** TypeScript · Next.js · Prisma · PostgreSQL · Docker · [live product](https://prescricaopro.com.br)

### [LA Miner](https://github.com/gustavoleao1206-arch/la-miner) · court-data intelligence
<a href="https://github.com/gustavoleao1206-arch/la-miner"><img src="./assets/la-miner-en.png" alt="LA Miner" width="100%"></a>

B2B prospecting SaaS that turns public Brazilian court data into qualified leads: incremental spreadsheet imports from the federal courts, contact enrichment through an external API with queues and scheduled jobs, a per-case CRM and KPI dashboards.

**Highlights:** multi-tenant API, refresh-token rotation with reuse detection, BullMQ workers, a CI gate that blocks deploys on vulnerable dependencies, 1,166 automated tests.

**Stack:** TypeScript · NestJS · Next.js · Prisma · PostgreSQL · Redis/BullMQ · [live product](https://laminer.com.br)

### [Kadosh Ops Platform](https://github.com/gustavoleao1206-arch/kadosh-ops-platform) · operations for a car-detailing business

One API, one database and one login serving a web back office and an Android app: clients and vehicles, service catalog with negotiated prices, scheduling and work orders, vehicle intake in a single transaction, and payments that can be reversed but never edited.

**Highlights:** login throttling by IP, by origin and by account, so a stranger cannot lock the owner out; 534 backend tests at 98% coverage, plus web and mobile suites.

**Stack:** Python · FastAPI · PostgreSQL · React · Flutter

### [Aethelgard](https://github.com/gustavoleao1206-arch/aethelgard) · Unity multiplayer game (source code)

A co-op action RPG for 1–4 players built with Unity 6 and Netcode for GameObjects, with a server-authoritative game loop: every gameplay request is validated on the server against the sender's own connection. The repository holds the code only; the licensed art is not included.

**Stack:** C# · Unity 6 · Netcode for GameObjects · URP

<sub>Screens show fictitious data.</sub>

## What I deliver

- Custom systems: web dashboard, role-based login, records and finance
- Applied AI: document reading, data extraction and assistants over your own data
- Automation: scheduled jobs, spreadsheet imports and document generation
- API integrations: payments, e-signature, courts and email
- Automated tests, deployment and user documentation

## Contact

Reach me on [LinkedIn](https://www.linkedin.com/in/gustavo-leao-dev) or [Workana](https://www.workana.com/freelancer/e374923f8c4b54cab1f5f7d6e4b1725b).
