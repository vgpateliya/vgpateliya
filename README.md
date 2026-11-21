# Vimal Pateliya

**Full-Stack Software Engineer | TypeScript, React, Next.js & Node.js | SaaS, Backend Systems & AI Integrations**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vimal--pateliya-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vimal-pateliya/)
[![Email](https://img.shields.io/badge/Email-vgpateliya27%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:vgpateliya27@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-vgpateliya-181717?style=flat&logo=github&logoColor=white)](https://github.com/vgpateliya)

---

Full-stack software engineer with 5+ years of experience designing, building, and maintaining production web applications, distributed backend services, and scalable SaaS platforms. Specialized in modern TypeScript architectures across React, Next.js, Node.js, and relational and document databases, with practical experience integrating LLM APIs and agentic workflows into production software.

---

## About & Technical Focus

- **Core Engineering**: 5+ years building full-stack applications with TypeScript, JavaScript, React, Next.js, Node.js, Express, PostgreSQL, Prisma, MongoDB, and Redis.
- **SaaS & Backend Systems**: Multi-tenant architectures, recurring subscription lifecycles with Stripe, background job orchestration with BullMQ, role-based access control (RBAC), and real-time data synchronization via WebSockets.
- **Applied AI & Agentic Workflows**: Production integrations with OpenAI, Anthropic Claude, and Google Gemini—implementing streaming assistant interfaces, structured output generation, tool calling, model routing, and Model Context Protocol (MCP) integrations.
- **Quality & Automated Testing**: End-to-end quality assurance across critical workflows using Jest, Vitest, and Playwright, paired with Docker containerization and automated CI/CD pipelines via GitHub Actions.
- **Technical Leadership**: Former Technical Lead at Mighty Ventures LLP—leading delivery coordination, architectural reviews, technical scoping and estimation, developer mentoring, and client-facing communication.

---

## Selected Professional Engineering Projects (Proprietary)

> *These projects were delivered as part of professional engagements. Source code and client-specific implementation details are proprietary. The descriptions highlight my engineering contributions without exposing confidential information.*

### 1. Multi-Tenant Event & Conference Platform
- **Overview**: Distributed multi-tenant ticketing and event management ecosystem powering customer-facing event websites and a centralized organizer administration portal.
- **Engineering Contribution**: Lead developer and top code contributor, architecting the shared API services, ticketing state machines, and administrative dashboards.
- **Key Technical Implementations**:
  - **Ticketing & Checkout**: End-to-end checkout pipeline with Stripe, temporary seat holds, automated invoicing, waitlist queuing, and dispute/refund workflows.
  - **On-Site Operations**: Secure dynamic QR-code ticket generation and offline check-in scanner capabilities for venue staff.
  - **Applied AI Integration**: Multi-provider AI assistant integrated via Model Context Protocol (MCP) with dynamic model routing for attendee support.
  - **Security & Compliance**: Granular role-based access control (RBAC), automated GDPR data retention policies, and automated end-to-end test suites using Playwright.
- **Tech Stack**: React, Next.js, TypeScript, Node.js, Express, PostgreSQL, Redis, BullMQ, Stripe, Model Context Protocol (MCP), Playwright.

---

### 2. AI-Powered Business Development & Gamification SaaS
- **Overview**: Multi-tenant B2B business development and employee gamification platform designed for professional services and corporate teams.
- **Engineering Contribution**: Full-stack engineering of conversational AI assistant workflows, core billing, user assessment engines, and tenant data isolation.
- **Key Technical Implementations**:
  - **Conversational AI Coaching**: Streaming chat interface providing real-time personalized guidance and structured actionable tasks via LLM APIs.
  - **Gamification Engine**: Configurable campaign workflows, reusable task libraries, periodic skill assessments, and automated achievement rewards.
  - **Reward Fulfillment**: Integration with third-party digital gift-card APIs for automated corporate reward distribution.
  - **Security & Resource Control**: Cryptographic refresh-token rotation, strict schema-level tenant isolation, and configurable per-organization AI token rate limits.
- **Tech Stack**: Next.js, React, TypeScript, Node.js, Prisma ORM, PostgreSQL, Redis, BullMQ, OpenAI API.

---

### 3. Event Management & Vendor Marketplace
- **Overview**: Two-sided event marketplace connecting event organizers with verified service vendors across multiple metropolitan regions.
- **Engineering Contribution**: Architected and led full-stack marketplace development, cross-platform mobile application, and high-concurrency search infrastructure.
- **Key Technical Implementations**:
  - **Scalable Discovery Engine**: Multi-facet search and filtering across city, category, and budget covering 10,000+ vendor listings.
  - **Media Delivery Optimization**: High-performance image and media delivery pipeline tailored for media-heavy vendor portfolios.
  - **Real-Time Lead Management**: Instant WebSocket notifications and push alerts alerting vendors to incoming client inquiries and quotation requests.
  - **Vendor Mobile App**: Cross-platform React Native client enabling on-the-go vendor profile, booking, and lead management.
- **Tech Stack**: Next.js, TypeScript, React Native, Node.js, Express, MongoDB.

---

### 4. Self-Drive Car Rental & Fleet Management
- **Overview**: Comprehensive vehicle rental and fleet operations platform spanning customer booking web portals and fleet manager administration.
- **Engineering Contribution**: Independently engineered customer booking flows, admin operations dashboard, and backend synchronisation services.
- **Key Technical Implementations**:
  - **Multi-City Fleet Discovery**: Real-time search, availability calendars, vehicle tier categorization, and dynamic pricing rules.
  - **Concurrency & Booking Safety**: Booking concurrency control algorithms preventing race conditions and double-booking during peak reservation windows.
  - **Real-Time Synchronization**: Bidirectional WebSocket channels synchronizing reservation status between web dashboards and Android devices.
  - **Role-Based Operational Controls**: Role-based access control (RBAC) separating customer service agents, fleet managers, and system administrators.
- **Tech Stack**: Next.js, TypeScript, React Native, Node.js, Express, MongoDB, WebSockets.

---

### 5. E-Commerce Seller Analytics & Growth Platform
- **Overview**: Subscription-based analytics and market intelligence SaaS platform built for e-commerce and TikTok Shop merchants.
- **Engineering Contribution**: Full-stack implementation of recurring subscription workflows, analytical aggregation pipelines, and profit calculation tooling.
- **Key Technical Implementations**:
  - **Subscription Lifecycle**: Automated recurring billing, tier upgrades/downgrades, and Stripe webhook lifecycle handling.
  - **High-Throughput Aggregation**: Optimized MongoDB aggregation pipelines querying 10,000+ data rows with sub-second response times.
  - **Seller Intelligence**: Real-time profitability calculators, pricing optimization tools, and sales revenue analytics.
- **Tech Stack**: React, Node.js, Express, MongoDB, Stripe.

---

### 6. Manufacturing ERP & Shop-Floor Platform
- **Overview**: Enterprise resource planning and shop-floor operations platform modernizing manufacturing tracking, inventory control, and compliance.
- **Engineering Contribution**: Engineering of operational workflows, database modeling, regulatory compliance integrations, and ERP system bridges.
- **Key Technical Implementations**:
  - **Shop-Floor Tracking**: End-to-end visibility into production stages, raw material consumption, and warehouse inventory movements.
  - **Regulatory Compliance**: Automated GST e-invoicing and e-way bill generation for tax and logistics compliance.
  - **Enterprise System Integration**: Reliable data synchronization bridges with QAD legacy enterprise systems.
- **Tech Stack**: Vue.js, Nuxt, Node.js, Express, MongoDB.

---

## Independent & Open-Source Projects

- **[Next.js Full-Stack AI Toolkit](https://github.com/vgpateliya/nextjs-fullstack-ai-toolkit)**  
  *Agentic Engineering · Cursor Rules · Claude Code · MCP · Next.js · Quality Gates*  
  A battle-tested governance and automation toolkit for Next.js full-stack teams using Claude Code, Cursor, and Gemini. Features strict architectural boundaries (server/client separation, data layering), pre-commit/pre-push quality gates via Husky, and structured agent workflows.

---

## Engineering Principles

- **Architecture & Boundaries**: Clear separation between presentation, application logic, and data access layers. Strict enforcement of server/client boundaries in modern React/Next.js architectures.
- **Security & Data Integrity**: Defense-in-depth principles—strict input validation, parameterized database queries, authenticated route middleware, principle of least privilege, and sanitized third-party webhook handling.
- **Reliability & Testing**: Automated testing at critical business boundaries (unit, integration, and E2E), graceful error degradation, and resilient background job retries.
- **Maintainability & DX**: Strong TypeScript typing across full client-server contracts, consistent linting/formatting standards, and clear documentation of architectural decisions.

---

## Tech Stack

| Category | Technologies |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript |
| **Frontend** | React, Next.js, Vue.js / Nuxt, React Native, Tailwind CSS, HTML5, CSS3 |
| **Backend** | Node.js, Express, NestJS, REST APIs, WebSockets, BullMQ |
| **Databases & Caching** | PostgreSQL, Prisma ORM, MongoDB, MySQL, Supabase, Redis |
| **AI & LLM Integrations** | OpenAI, Anthropic Claude, Google Gemini, Model Context Protocol (MCP), Tool Calling, Streaming APIs |
| **Testing & QA** | Jest, Vitest, Playwright |
| **DevOps & Cloud** | Docker, AWS, Vercel, GitHub Actions, Linux |

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
