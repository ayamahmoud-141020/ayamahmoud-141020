# Aya Mahmoud Zaki

**Software Developer · AI & Automation · Python · TypeScript · .NET**
Giza, Egypt · open to remote work

<p>
  <a href="mailto:ayamahmoudzaki421@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
  <a href="https://linkedin.com/in/aya-mahmoud-zaki-180a30266"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/ayamahmoud-141020"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

## About Me

I turn business problems into working applications, integrations and automated workflows.

I use AI coding tools (Claude Code) every day to plan, build and debug. I treat AI output like a teammate's pull request: I read it, test it, and fix what breaks. Every project below ships with automated tests.

- Software Engineer at **ignteQ** (Jun 2025 – present)
- Full-Stack Developer at **Giza Power Industry** (Nov 2024 – Jun 2025)
- B.Sc. Computer Science, Helwan University (2024), GPA 3.67, Medical Informatics

---

## Work Projects

### HotelGate: B2B/B2C travel platform
*ignteQ · .NET 8 · SQL Server · Elasticsearch · Redis · RabbitMQ · Google Cloud (GKE, KMS)*

A Saudi travel platform for hotels, Umrah packages and Haramain train tickets, built from about 40 microservices.

- Built an automated notification and voucher workflow using a transactional outbox. Background workers retry with backoff and skip duplicates using idempotency keys, so booking emails are no longer lost.
- Shipped the Haramain train ticketing integration with a third-party provider.
- Worked on the search and orchestration services that combine results from several hotel providers: returned empty results instead of 500 errors, fixed fields dropped from the Redis cache, and added room grouping.
- Fixed a cancellation-policy time-zone bug that shifted refund tiers by 3 hours, backed by tests.
- Diagnosed an authentication-middleware bug, caused by dependency-injection scoping, that gave services the wrong user context.
- Made Elasticsearch index rebuilds zero-downtime with atomic alias swaps and rollback.
- Built hotel-inventory features in the Next.js supplier extranet.
- Coordinated UAT with partner companies and QA, and wrote documentation for supplier integration and pricing logic.

### Gental: Arabic-first AI agent builder
*ignteQ · .NET 10 · PostgreSQL + pgvector · Google Pub/Sub · Next.js · RAG · LLM tool-calling*

- Protected sign-up against abuse with a disposable-email blocklist that fails fast on bad configuration. Integration tests prove a refused sign-up saves nothing.
- Fixed an onboarding bug that left website crawls running with no owner by moving onboarding state into one atomic server-side command, covered by an atomicity test and Playwright end-to-end tests.

### Shamouly: holistic medicine platform
*ignteQ*

- Owned the specialist-side modules: Services, Medication Library, Settings and Courses.

### LearnKhana: B2B/B2C e-learning platform
*ignteQ · React · Next.js · Angular · Node.js · .NET*

- Delivered features end to end across React/Next.js frontends, Node.js and .NET APIs, and an Angular admin dashboard, covering course management, authentication and payments.

### HR & Payroll System
*Giza Power Industry · ASP.NET Core · React · TypeScript · Tailwind CSS · SQL Server*

- Replaced a legacy Visual Basic HR & Payroll desktop app with ASP.NET Core APIs and a React/TypeScript frontend.
- Redesigned the SQL Server schema and queries (15% faster) and built reporting dashboards with Chart.js.
- Integrated payroll with the company's existing ERP systems, and supported the ERP's production and inventory modules.

---

## Personal Projects

### [RxFlow: prescription intake automation](https://github.com/ayamahmoud-141020/rxflow)
*Python · FastAPI · PostgreSQL · React · TypeScript · Tesseract OCR · LLM · Docker · GitHub Actions*

Pharmacies retype faxed prescriptions by hand. RxFlow automates it end to end.

- **Intake:** file upload, or a cloud fax provider calls a signed (HMAC) webhook.
- **AI extraction with a safety net:** OCR, then an optional LLM extractor with strict JSON output. If the LLM fails, rules take over automatically.
- **Validation:** NPI/DEA checksums, fuzzy formulary matching for OCR typos, controlled-substance rules, and an eligibility API client with retries and exponential backoff.
- **Routing:** clean prescriptions are auto-approved; the rest go to a pharmacist review queue.
- **Security:** role-based access, JWT, append-only audit trail, PHI redaction in logs, secrets in environment variables.
- **Verified:** 34 pytest tests, run by GitHub Actions on every push.

### [Identity & Authentication Module](https://github.com/ayamahmoud-141020/identity-auth-module)
*NestJS · MongoDB · React · TypeScript · Zod · Docker · GitHub Actions*

- Sign-up, sign-in, and silent session refresh with token rotation and reuse detection.
- Passwords hashed with argon2id. One shared validation contract is used by the web forms, the API and the domain.
- Fully documented: API reference, security model and trade-offs.

### Deep Learning for Multiple Sclerosis Diagnosis (graduation project, team lead)
*Python · TensorFlow · Keras · DeepLabV3+*

- MRI classification and segmentation. Compared 16 models; EfficientNetB0 reached 97% accuracy (precision and recall above 0.96).
- Built a web interface where clinicians upload scans and get results with confidence scores.

---

## Tech Stack

**AI & Automation:** Claude Code · LLM APIs (structured output, RAG, tool-calling) · OCR · webhooks · background jobs and retries

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="C#"/>
  <img src="https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="SQL"/>
</p>

**Backend & APIs**
<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS"/>
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express"/>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET"/>
</p>

**Frontend**
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white" alt="Angular"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
</p>

**Data**
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="SQL Server"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white" alt="Elasticsearch"/>
</p>

**Deploy & Tools**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud"/>
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright"/>
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest"/>
</p>

---

## How I Work with AI

1. **Understand the problem first:** I turn the business need into clear requirements before writing code.
2. **Build with AI:** I use Claude Code to plan, scaffold and implement.
3. **Review everything:** I read and understand every change, then refactor what doesn't fit.
4. **Prove it works:** unit, integration and end-to-end tests, plus CI on every push.
5. **Protect data:** secrets in environment variables, role-based access, audit logs, no sensitive data in logs.
6. **Explain it:** READMEs, architecture diagrams, and plain-language updates for non-technical stakeholders.

---

## Education & Courses

**B.Sc. Computer Science**, Helwan University · 2020 – 2024 · GPA 3.67 · Specialization: Medical Informatics

- .NET Full Stack Development — Digital Egypt Pioneers Initiative (DEPI)
- Next.js, React.js & TypeScript Bootcamp — Codeawy
- Web Developer Challenger Track — EGFwd, Udacity
- AI Training Completion Certificate · Instant Data Science Certificate

---

## GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=ayamahmoud-141020&show_icons=true&hide_border=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ayamahmoud-141020&layout=compact&hide_border=true&langs_count=8" alt="Top Languages" height="165"/>
</p>
