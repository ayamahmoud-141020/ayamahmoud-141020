<h1 align="center">Hi 👋, I'm Aya Mahmoud Zaki</h1>
<h3 align="center">Software Developer · AI &amp; Automation · Python · TypeScript · .NET</h3>

<p align="center">
  <img src="https://media1.tenor.com/m/Ug6cbVA1ZsMAAAAd/developer.gif" height="200" alt="developer gif" />
</p>

<p align="center">
  <a href="mailto:ayamahmoudzaki421@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
  <a href="https://linkedin.com/in/aya-mahmoud-zaki-180a30266"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/ayamahmoud-141020"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/%2B20%201055973408-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Phone"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ayamahmoud-141020&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views"/>
</p>

---

## 🙋‍♀️ About Me

I turn business problems into working applications, integrations and automated workflows.

I use **AI coding tools (Claude Code)** every day to plan, build and debug. I treat AI output like a teammate's pull request: I read it, test it, and fix what breaks. Every project below ships with automated tests and CI.

- 💼 **Software Engineer at ignteQ** (Jun 2025 – present): HotelGate (travel platform, ~40 .NET microservices) and Gental (Arabic-first AI agent builder with RAG and LLM tool-calling)
- 🎓 B.Sc. Computer Science, Helwan University (2024), GPA 3.67, Medical Informatics
- 🌍 Giza, Egypt · open to remote work

---

## 🚀 Featured Projects

### 💊 [RxFlow: prescription intake automation](https://github.com/ayamahmoud-141020/rxflow)
`Python` `FastAPI` `PostgreSQL` `React` `TypeScript` `OCR` `LLM` `Docker` `GitHub Actions`

Pharmacies retype faxed prescriptions by hand. RxFlow automates it end to end:

- **Intake:** file upload, or a cloud fax provider calls a **signed (HMAC) webhook**
- **AI extraction with a safety net:** OCR, then an optional LLM extractor with strict JSON output. **If the LLM fails, rules take over automatically.**
- **Validation:** NPI/DEA checksums, fuzzy formulary matching for OCR typos, controlled-substance rules, and an eligibility API client with retries and exponential backoff
- **Routing:** clean prescriptions are auto-approved; the rest go to a pharmacist review queue
- **Security:** role-based access, JWT, append-only audit trail, PHI redaction in logs, secrets kept in environment variables
- **Verified:** 34 pytest tests, run by GitHub Actions on every push

### 🔐 [Identity & Authentication Module](https://github.com/ayamahmoud-141020/identity-auth-module)
`NestJS` `MongoDB` `React` `TypeScript` `Zod` `Docker` `CI`

Sign-up, sign-in, and silent session refresh with **token rotation and reuse detection**. Passwords are hashed with argon2id, and one shared validation contract is used by the web forms, the API and the domain. Fully documented: API reference, security model and trade-offs.

### 🧠 Deep Learning for Multiple Sclerosis Diagnosis (graduation project, team lead)
`Python` `TensorFlow` `Keras` `DeepLabV3+`

MRI classification and segmentation. Compared 16 models; EfficientNetB0 reached **97% accuracy** (precision and recall > 0.96). Includes a web interface where clinicians upload scans and get results with confidence scores.

---

## 💼 What I Build at Work

**ignteQ — HotelGate** (.NET 8, SQL Server, Elasticsearch, Redis, RabbitMQ, Google Cloud)
- Automated notification and voucher workflow (transactional outbox, background workers, retries, idempotency keys), so booking emails are no longer lost
- Haramain train ticketing integration with a third-party provider; multi-provider hotel search
- Fixed production bugs end to end, each backed by tests (time-zone refund rules, auth middleware context, search error handling)
- Coordinated UAT with partner companies and QA, and wrote technical documentation

**ignteQ — Gental** (.NET 10, PostgreSQL + pgvector, Pub/Sub, Next.js, RAG, LLM tool-calling)
- Sign-up abuse protection, plus an atomic onboarding fix covered by integration and Playwright end-to-end tests

**Giza Power Industry** (Nov 2024 – Jun 2025)
- Replaced a legacy Visual Basic HR & Payroll app with ASP.NET Core and React/TypeScript; made queries 15% faster; integrated it with the company's ERP systems

---

## 🛠️ Tech Stack

**AI & Automation:** Claude Code · LLM APIs (structured output, RAG, tool-calling) · OCR · webhooks · background jobs & retries

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

## 🧪 How I Work with AI

1. **Understand the problem first:** I turn the business need into clear requirements before writing code.
2. **Build with AI:** I use Claude Code to plan, scaffold and implement.
3. **Review everything:** I read and understand every change, then refactor what doesn't fit.
4. **Prove it works:** unit, integration and end-to-end tests, plus CI on every push.
5. **Protect data:** secrets in environment variables, role-based access, audit logs, no sensitive data in logs.
6. **Explain it:** READMEs, architecture diagrams, and plain-language updates for non-technical stakeholders.

---

## 🎓 Education & Courses

**B.Sc. Computer Science**, Helwan University · 2020 – 2024 · GPA 3.67 · Specialization: Medical Informatics

- ✅ .NET Full Stack Development — Digital Egypt Pioneers Initiative (DEPI)
- ✅ Next.js, React.js & TypeScript Bootcamp — Codeawy
- ✅ Web Developer Challenger Track — EGFwd, Udacity
- ✅ AI Training Completion Certificate · Instant Data Science Certificate

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ayamahmoud-141020&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ayamahmoud-141020&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ayamahmoud-141020&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages"/>
</p>

---

<p align="center">
  <a href="https://linkedin.com/in/aya-mahmoud-zaki-180a30266">LinkedIn</a> •
  <a href="https://github.com/ayamahmoud-141020">GitHub</a> •
  <a href="mailto:ayamahmoudzaki421@gmail.com">Gmail</a>
</p>
