<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=190&section=header&text=Erfan%20Mohammadi&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Backend%20%26%20Database%20Developer%20%C2%B7%20Software%20Engineer&descSize=17&descAlignY=58&animation=fadeIn" alt="Erfan Mohammadi" />

**I build enterprise web systems end to end: database, API and UI. Then I deploy them and keep them running.**

[![Website](https://img.shields.io/badge/erfanmohammadi.ir-667eea?style=for-the-badge&logo=googlechrome&logoColor=white)](https://erfanmohammadi.ir)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/erfan-mohammadi77/)
[![Email](https://img.shields.io/badge/Email-764ba2?style=for-the-badge&logo=gmail&logoColor=white)](mailto:erfan.mohammadi.alv77@gmail.com)

</div>

---

## About me

- **Software Developer & Database Specialist at Alvan Paint & Resin** since July 2022. I design and ship the company's internal platforms (recruiting, IT operations, management reporting, maintenance, and an AI sales tool), and I administer and tune its SQL Server databases.
- **Founder of [Houshiva](https://houshiva.ir)**, where I build custom software for businesses: management systems, SaaS products and automation.
- **Strongest in** Python/Django back ends, SQL Server (T-SQL, performance tuning, legacy schemas), and BI with Power BI and SSIS. On the front end I use React.
- Based in **Tehran, Iran**. Open to new projects and collaboration.

### What I bring to a team

| | |
|---|---|
| 🧱 **End-to-end delivery** | Data model → REST API → React UI → tests → production deployment, all by one person |
| 🗄️ **Deep SQL Server** | Query tuning, stored procedures, full-text search, and building new systems on top of legacy ERP schemas |
| 🔗 **Integration with what already exists** | Syncing users from the ERP, single sign-on between internal apps, rewriting VB.NET/WinForms modules as web apps without touching the original database |
| 🚀 **Production on real infrastructure** | Docker, nginx and Windows services on on-premise servers, with obfuscated (PyArmor) builds for the code that ships |
| 🌐 **Persian / RTL products** | Fully right-to-left interfaces, Jalali dates, locally bundled fonts for offline corporate networks |

---

## Featured work

> Most of my production work is for my employer or for clients, so those repositories are **private**. Code walkthroughs and live demos are available on request.

### 📋 RezumeBan: recruiting & applicant tracking system (ATS)

A complete hiring platform, in use at Alvan: job requisitions and approval → job postings → drag-and-drop **Kanban pipeline** → interviews with **weighted scorecards** and calendar (.ics) invites → **offers** → funnel and source-effectiveness **reports**. It also handles résumé import with duplicate detection and merging, side-by-side candidate comparison, candidate sourcing from the GitHub, Stack Overflow and dev.to APIs, and a `Ctrl+K` command palette.

`Django 6` `DRF` `JWT` `React 19` `Vite` `Tailwind CSS 4` `Framer Motion` `Recharts` · 31 automated tests

<table>
<tr>
<td width="50%"><img src="assets/rezumeban-dashboard.png" alt="RezumeBan dashboard" /></td>
<td width="50%"><img src="assets/rezumeban-pipeline.png" alt="RezumeBan hiring pipeline" /></td>
</tr>
</table>

### 🧭 Software Knowledge Center: internal IT operations platform

The IT team's daily workspace. It covers documentation, tasks and issues, a phone directory and live user presence. It also does **access control and auditing across three SQL Server instances** (who can see what, copying access between users, segregation-of-duties checks), runs a **SQL query console** and a database audit, and is the **single sign-on hub** for the other internal apps.

`Django` `DRF` `React` `MUI` `SQL Server` `Docker` `nginx`

### 📊 Alvan management dashboard: company-wide analytics

One dashboard over the ERP data for management, with modules for **HR** (headcount, attrition, age pyramid, accidents, contracts), **accounting** (ledger, trial balance, balance sheet, income statement), **assets**, **inventory**, **cash and cheques**, **maintenance** and **market pricing**. Domain chatbots for HR and quality questions are built in, and access is controlled per module.

`React` `Ant Design` `Recharts` `Python` `SQL Server`

### 🎨 Alvan Color Visualizer: AI wall-color preview

A sales tool. The customer uploads a photo of a room or building. The app detects the walls with **Mask2Former semantic segmentation** and repaints them in colors from the company catalogue, keeping the original light, shadows and texture (Lab color space, guided-filter edges, linear-light compositing). All models run **locally**, so there is no per-use API cost.

`Python` `FastAPI` `PyTorch` `Transformers` `Mask2Former` `OpenCV` `JavaScript`

### 🛠️ More systems I have built

| Project | What it is | Stack |
|---|---|---|
| **PM Factory** | Maintenance-management (CMMS) rewrite of the ERP's VB.NET/WinForms module as a web platform, with ERP user sync and server-side PDF reports | Django · DRF · React · TypeScript · PostgreSQL · Ant Design |
| **Alvan Market Intelligence** | Collects, normalizes and matches competitor product and price data, with an *evidence chain* that traces every dashboard number back to its raw source | Django · Celery · Redis · PostgreSQL · React · TypeScript |
| **Avana** *(Houshiva)* | Multi-tenant, white-label SaaS for language schools: courses, attendance, online exams, tuition, video store, certificates, subscriptions, SMS login | Django REST Framework · React |
| **Houshiva Asset** *(Houshiva)* | Configurable asset and custodianship management, installable as a PWA | Django 5.2 · DRF · React · PostgreSQL |
| **Karnama** *(Houshiva)* | Mobile-first PWA for job seekers: searches several job sites at once, Persian résumé builder, application tracking | React · PWA |

### 🌍 Public repositories

| Repository | Description |
|---|---|
| [**portfolio**](https://github.com/erfanmohammadi1998/portfolio) | My portfolio, live at [erfanmohammadi.ir](https://erfanmohammadi.ir). It's an interactive architecture map plus an API console you can query (`GET /projects`, `whoami`). Trilingual (fa / en / de) and RTL-aware |
| [**ticket-management-system**](https://github.com/erfanmohammadi1998/ticket-management-system) | Full-stack support-ticket system with role-based access and a dashboard, built with Django REST Framework, React and SQL Server |
| [**ip_killswitch**](https://github.com/erfanmohammadi1998/ip_killswitch) | Small Python utility that closes chosen apps when your public IP changes, e.g. when a VPN drops. Fail-safe by design |

---

## Tech stack

<p>
<img src="https://skillicons.dev/icons?i=python,django,fastapi,react,ts,js,tailwind,vite,postgres,mysql,docker,nginx,git,github,gitlab,linux&perline=16" alt="Tech stack icons" />
</p>

| Area | Tools |
|---|---|
| **Backend** | Python, Django, Django REST Framework, FastAPI, JWT auth, OpenAPI/Swagger, Celery |
| **Databases** | Microsoft SQL Server & T-SQL (performance tuning, stored procedures, full-text search), PostgreSQL, MySQL |
| **BI & reporting** | Power BI, SSIS, data warehousing, Crystal Reports, Stimulsoft Reports |
| **Frontend** | React, TypeScript, JavaScript, Vite, Tailwind CSS, MUI, Ant Design, Recharts |
| **AI & automation** | PyTorch / Mask2Former, OpenCV, OCR & document processing, web scraping, Selenium / Playwright |
| **DevOps** | Docker & Compose, nginx, Windows Server services (NSSM), GitLab, GitHub Actions, Linux |

---

## Experience & education

**Software Developer & Database Specialist**, Alvan Paint & Resin · *Jul 2022 – present*
Internal enterprise systems end to end · SQL Server design, administration and tuning · Power BI / SSIS reporting · Docker deployments · data-driven automation

**Founder & Developer**, Houshiva · *present*
Custom software for businesses: management systems, SaaS, CRM and automation, with direct client work and long-term support

**Associate Degree in Computer Software**, Imam Sadegh Technical College · *2015 – 2017*

**Training:** SQL Server Performance & Tuning (75 h) · Business Intelligence (90 h) · Advanced T-SQL: window functions & columnstore · Power BI Desktop · Advanced Python · Data Analysis

---

## Activity

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/erfanmohammadi1998/erfanmohammadi1998/gh-pages/github-contribution-grid-snake-dark.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/erfanmohammadi1998/erfanmohammadi1998/gh-pages/github-contribution-grid-snake.svg" />
</picture>
</p>

---

<div align="center">

**Let's build something reliable.**
[erfanmohammadi.ir](https://erfanmohammadi.ir) · [LinkedIn](https://www.linkedin.com/in/erfan-mohammadi77/) · [erfan.mohammadi.alv77@gmail.com](mailto:erfan.mohammadi.alv77@gmail.com)

</div>
