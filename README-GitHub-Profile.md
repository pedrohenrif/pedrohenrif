<div align="center">

# Pedro Henrique Furtado Santos

### Full Stack Developer · Backend & Integrations · AI Pipelines

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-henrique-furtado-santos)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pedro.henrique.furtado.santos@gmail.com)
[![Location](https://img.shields.io/badge/Curitiba%2C%20PR-00A859?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

## About me

Developer with 3+ years of experience building production-grade solutions across two parallel tracks:

- **@ Fellsky** — SaaS quality monitoring platform for call centers. Working with NestJS/TypeScript microservices, event-driven architecture (RabbitMQ), AI pipelines (OpenAI + ElevenLabs), and AWS cloud infrastructure.
- **@ GHR Tech** — IT consultancy for the healthcare sector. Python automations, RPA (Selenium), and integrations between legacy ERPs (Tasy/Oracle), payment gateways (Stone/Pagar.me), and state systems (GSUS/NF-e).

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Databases**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**AI & Automation**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)

---

## What I'm currently building

### Fellsky Platform
> Quality monitoring SaaS for call centers

A production ecosystem of **7 NestJS microservices** communicating via RabbitMQ:

| Service | What it does |
|---|---|
| `auth-service` | OAuth2 server (PKCE, token-exchange), JWT RS256, JWKS, AWS Cognito |
| `accounts-service` | Multi-tenant accounts, billing, usage limits |
| `monitories-service` | Monitoring CRUD, quiz engine, CSV batch import, AI retry (RFC-003) |
| `ai-analysis-service` | Call transcription (ElevenLabs) → LLM analysis (OpenAI) → vector embeddings |
| `conversations-service` | Calls & WhatsApp data hub, summaries |
| `files-service` | Multipart upload to S3, audio conversion (ffmpeg) |
| `copilot-service` | Conversational AI agent with 14 custom tools + Ably realtime |

---

## Notable Projects

### Healthcare & Hospital Systems (GHR Tech)

**Stone/Pagar.me → Tasy Oracle Integration**
Two-stage pipeline: Pagar.me V5 API → PostgreSQL staging → Oracle ERP with due-date rules (credit, debit, PIX, installments) and e-mail reporting.
`Python` `FastAPI` `SQLAlchemy` `cx_Oracle` `PostgreSQL`

---

**NF-e Multi-site Platform (ISMS)**
Restructured a monolith into 3 microservices + message queue for fiscal note processing across 4 healthcare facilities → Paraná State API.
`Python` `FastAPI` `React` `RabbitMQ` `Docker` `Oracle`

---

**Hospital Admission RPA (GA122)**
Extracts patients from Oracle Tasy and automates admission registration in GSUS (Paraná state system) via Selenium. Interchangeable Selenium/REST adapter architecture.
`Python` `Selenium` `cx_Oracle` `Firefox`

---

**Purchase Order RPA (GA108)**
Tasy Web automation for generating and organizing purchase order PDFs. Distributed as a standalone Windows executable.
`Python` `Selenium` `PyInstaller` `tkinter` `cx_Oracle`

---

**Ophthalmology Medical Record (Oftalmo2)**
FastAPI web app integrated with Tasy Oracle for ophthalmological records and custom PDF printing.
`Python` `FastAPI` `Jinja2` `cx_Oracle` `pdfkit`

---

**Status Report Automation**
Auto-generates client status reports from Google Sheets + Calendar data into Google Slides, published to Drive.
`Python` `Google APIs` `tkinter` `Service Account`

---

### Personal Projects

**AgroSync** — Full stack agricultural management platform with lot traceability and transactional inventory.
`Node.js` `React` `Prisma ORM` `DDD`

**Git Analyzer CLI** — CLI tool for analyzing code metrics across remote repositories.
`Python` `Typer`

---

## GitHub Stats

<div align="center">

![Pedro's GitHub stats](https://github-readme-stats.vercel.app/api?username=pedrohenrif&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=pedrohenrif&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff)

</div>

---

<div align="center">

*Open to discussing integrations, backend architecture, and healthcare tech.*

</div>
