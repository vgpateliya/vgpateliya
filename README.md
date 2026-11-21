# Vimal Pateliya

**Full-Stack Software Engineer | TypeScript, React, Next.js & Node.js | SaaS, Backend Systems & AI Integrations**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vimal--pateliya-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vimal-pateliya/)
[![Email](https://img.shields.io/badge/Email-vgpateliya27%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:vgpateliya27@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-vgpateliya-181717?style=flat&logo=github&logoColor=white)](https://github.com/vgpateliya)

---

Full-stack software engineer with 5+ years of experience designing, building, and operating production web applications, distributed backend services, and multi-tenant SaaS platforms. Specialized in modern TypeScript architectures across React, Next.js, and Node.js, with hands-on experience implementing high-concurrency booking workflows, Stripe billing lifecycles, and applied AI integrations.

---

## Selected Professional Engineering Work

> *These projects were delivered as part of professional client and enterprise engagements. Source code and client-specific implementation details are proprietary. The technical descriptions below highlight architectural decisions, systems design, and engineering contributions without disclosing confidential information.*
>
> ?? *In-depth architectural breakdowns, Mermaid sequence diagrams, and concurrency patterns are documented in [professional-engineering-case-studies](https://github.com/vgpateliya/professional-engineering-case-studies).*

### 1. Multi-Tenant Event & Conference Platform
- **Domain & Scope**: Distributed event ticketing and registration infrastructure powering multi-brand public event portals and a centralized organizer administrative platform.
- **Role & Contribution**: Lead developer, architecting shared API services, state-machine checkout flows, and organizer dashboards.
- **Key Technical Deliverables**:
  - **Ticketing & Checkout Engine**: Engineered Stripe checkout integration with temporary seat-hold expirations, automated tax/invoicing, waitlists, and dispute/refund workflows.
  - **On-Site Operations**: Secure dynamic QR-code ticket generation and offline-capable door check-in scanner with synchronization logs.
  - **Applied AI Assistant**: Multi-model in-app AI assistant built on the Model Context Protocol (MCP) with dynamic routing across Claude, OpenAI, and Gemini, including token budgeting and rate limiting.
  - **Security & Data Retention**: Role-based access control (RBAC), automated GDPR data retention jobs, and automated Playwright end-to-end test pipelines.
- **Tech Stack**: React, Vite, Next.js, TypeScript, Node.js, Express, PostgreSQL / Supabase, Redis, BullMQ, Stripe, Model Context Protocol (MCP), Playwright, Docker.

---

### 2. AI-Powered Business Development & Gamification SaaS
- **Domain & Scope**: Multi-tenant B2B platform driving enterprise business development through structured campaigns, task libraries, and performance gamification.
- **Role & Contribution**: Full-stack engineer owning conversational AI streaming, billing infrastructure, and tenant isolation.
- **Key Technical Deliverables**:
  - **Conversational Coaching Interface**: Streaming AI assistant providing contextual coaching actions, task suggestions, and conversation persistence.
  - **Gamification & Rewards**: Campaign orchestration, periodic skill assessment evaluation, and automated digital gift-card reward distribution via third-party APIs.
  - **Security & Tenant Scoping**: Cryptographic refresh-token rotation in httpOnly cookies, schema-level multi-tenant isolation, and atomic per-organization AI usage caps.
- **Tech Stack**: Next.js, React, TypeScript, MUI, Redux Toolkit, TanStack Query, Node.js, Express, Prisma ORM, PostgreSQL, Redis, BullMQ, OpenAI API, Stripe.

---

### 3. Event Management & Vendor Marketplace
- **Domain & Scope**: Two-sided marketplace connecting event organizers with verified service vendors across catering, photography, decor, and venue categories.
- **Role & Contribution**: Lead marketplace engineer leading architecture, high-concurrency discovery, and mobile client delivery.
- **Key Technical Deliverables**:
  - **Discovery Engine**: Multi-faceted search and category filtering tailored for multi-city vendor exploration.
  - **Media Delivery Optimization**: High-performance image loading pipeline optimized for visual vendor albums and trend portfolios.
  - **Real-Time Lead Alerts**: Bidirectional WebSocket notifications and push alerts delivering real-time quotation requests to vendors.
  - **Vendor Mobile App**: Cross-platform React Native mobile client enabling mobile lead management and profile configuration.
- **Tech Stack**: Next.js, TypeScript, Tailwind CSS, React Native, Node.js, Express, MongoDB, WebSockets.

---

### 4. Self-Drive Car Rental & Fleet Management
- **Domain & Scope**: Vehicle rental operations platform covering customer booking portals and real-time fleet operations.
- **Role & Contribution**: Independent full-stack developer engineering reservation lifecycles, admin dashboards, and concurrency safety.
- **Key Technical Deliverables**:
  - **Multi-City Fleet Discovery**: Real-time vehicle availability search, date filtering, tier pricing packages, and customer KYC document upload.
  - **Booking Concurrency Control**: Concurrency safety mechanisms designed to prevent race conditions and duplicate reservations during overlapping customer checkouts.
  - **Real-Time State Synchronization**: WebSocket infrastructure synchronizing vehicle reservation statuses between administrative web consoles and field Android apps.
  - **Role-Based Controls**: Tiered RBAC separating fleet operators, desk agents, and system administrators.
- **Tech Stack**: Next.js, TypeScript, Tailwind CSS, React Native, Node.js, Express, MongoDB, WebSockets.

---

### 5. E-Commerce Seller Analytics & Growth Platform
- **Domain & Scope**: Analytics and market intelligence SaaS platform built for e-commerce and TikTok Shop merchants.
- **Role & Contribution**: Full-stack engineer implementing recurring Stripe subscription tiers, product research filters, and analytical aggregation pipelines.
- **Key Technical Deliverables**:
  - **Billing & Subscription Lifecycle**: Automated recurring Stripe subscription billing, plan tier upgrades, and webhook event validation.
  - **Analytics Aggregation**: Indexed MongoDB aggregation pipelines computing store profitability, product pricing metrics, and sales trend analytics.
  - **Seller Calculators**: Real-time net profit and margin calculation tools helping sellers forecast pricing and marketplace fees.
- **Tech Stack**: React, Bootstrap, Node.js, Express, MongoDB, Stripe.

---

### 6. Manufacturing ERP & Shop-Floor Platform
- **Domain & Scope**: Manufacturing resource planning system modernizing shop-floor tracking, inventory movements, and statutory compliance.
- **Role & Contribution**: Full-stack engineer delivering shop-floor operational workflows, data schemas, and enterprise integrations.
- **Key Technical Deliverables**:
  - **Shop-Floor Visibility**: Operational tracking across work orders, raw material consumption, warehouse staging, and stage-gate approvals.
  - **Statutory Tax Compliance**: Automated GST e-invoicing and e-way bill generation conforming to statutory transport standards.
  - **Enterprise ERP Integration**: Data synchronization bridges interfacing with legacy QAD enterprise systems.
- **Tech Stack**: Vue.js, Nuxt 2, Node.js, Express, MongoDB.

---

## Engineering Strengths & Technical Domains

- **Distributed Architecture & Data Layering**: Strict boundary separation between client presentation, application controllers, and persistence layers. Domain modeling across relational (PostgreSQL, MySQL) and document (MongoDB) databases.
- **High-Concurrency Booking & Checkout**: Designing idempotent APIs, race-condition mitigation, temporary seat holds, and transactional state machines.
- **Multi-Tenant Security & RBAC**: Tenant schema isolation, JWT with refresh-token rotation, role-based permission matrices, and defense-in-depth API middleware.
- **Applied AI Engineering**: Production LLM integrations using tool calling, streaming responses, model routing, and Model Context Protocol (MCP) integrations with token budget governance.
- **Reliability & Automated Testing**: End-to-end and integration test automation using Playwright, Vitest, and Jest, supported by Docker containerization and GitHub Actions CI pipelines.

---

## Independent & Open-Source Projects

- **[Next.js Full-Stack AI Toolkit](https://github.com/vgpateliya/nextjs-fullstack-ai-toolkit)**  
  *Open-Source Agentic Engineering Toolkit · Cursor Rules · Claude Code · MCP · Husky*  
  A modular engineering toolkit providing structured agent rules, review skills, and pre-commit quality gates for Next.js full-stack applications. Enforces architectural boundaries (server/client isolation, data layering) and consistent workflows across Claude Code, Cursor, and Copilot.

---

## Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript, SQL |
| **Frontend** | React, Next.js, Vue.js / Nuxt, React Native, Tailwind CSS, Redux Toolkit, MUI |
| **Backend** | Node.js, Express, NestJS, REST APIs, WebSockets, BullMQ |
| **Databases & Caching** | PostgreSQL, Prisma ORM, MongoDB, Supabase, MySQL, Redis |
| **AI & LLM Integrations** | OpenAI API, Anthropic Claude, Google Gemini, Model Context Protocol (MCP), Tool Calling, Streaming |
| **Testing & Tooling** | Playwright, Vitest, Jest, Docker, GitHub Actions, Linux |

---

## Professional Experience

- **Software Development Engineer** — Zignuts Technolab  
  *January 2026 – Present*

- **Technical Lead** — Mighty Ventures LLP  
  *January 2025 – December 2025*

- **Full-Stack Developer** — Mighty Ventures LLP  
  *June 2024 – December 2024*

- **Full-Stack Developer** — Solution Squares  
  *October 2021 – June 2024*

---

## Connect

- **LinkedIn**: [linkedin.com/in/vimal-pateliya](https://www.linkedin.com/in/vimal-pateliya/)
- **Email**: [vgpateliya27@gmail.com](mailto:vgpateliya27@gmail.com)
- **GitHub**: [github.com/vgpateliya](https://github.com/vgpateliya)
