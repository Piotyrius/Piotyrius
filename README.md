<h1 align="center">Hi, I'm Piotyrius 👋</h1>

<p align="center">
  <b>Full-stack product engineer.</b> Django &amp; DRF on the back, React &amp; TypeScript on the front, AWS underneath.<br>
  I take products from an empty repo to a paying customer — schema, API, UI, pipeline, and the on-call docs that come with it.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS">
</p>

---

## 🔭 What I'm building

**[invu](https://invu.ge)** — a digital invitation platform. A host picks a template, edits it in a
browser canvas, sends it to a guest list, and collects RSVPs, photos and gift claims.

It's four codebases I own end to end:

| Piece | Stack | Scale |
|---|---|---|
| **API** | Django 5.2 · DRF 3.16 · PostgreSQL 17 · Firebase auth | 179 routes, 66 models, 8 apps |
| **Web app** | React · TypeScript · Vite · SCSS · Zustand · React Query | canvas editor built on Fabric.js |
| **Mobile** | React Native · Expo · React Navigation | shares the same API |
| **QA suite** | pytest + DRF `APIClient` · Cucumber/RestAssured | PR gate + nightly regression |

Running on AWS `eu-central-1` — Lightsail containers, RDS, S3 + CloudFront, Secrets Manager,
CloudWatch — across three environments, each with its own GitHub Actions deploy pipeline.

---

## 🛠️ What I work with

**Backend**  
`Python` `Django` `Django REST Framework` `FastAPI` `SQLAlchemy (async)` `Celery` `Redis` `PostgreSQL` `Prisma`

**Frontend**  
`TypeScript` `React` `Next.js (App Router)` `Vite` `Tailwind` `SCSS` `Zustand` `TanStack Query` `Fabric.js` `GSAP` `i18next`

**Mobile**  
`React Native` `Expo` `EAS`

**Infrastructure & ops**  
`AWS (Lightsail · RDS · S3 · CloudFront · Secrets Manager · CloudWatch)` `Google Cloud (Run · Cloud Build · GCS · Secret Manager)` `Docker` `Docker Compose` `GitHub Actions` `gunicorn` `WhiteNoise`

**Testing & quality**  
`pytest` `pytest-django` `Vitest` `Testing Library` `MSW` `Cucumber / Gherkin` `RestAssured` `k6 load testing`

**Integrations**  
`Firebase Auth` `Flitt payments` `Resend` `Sentry` `Prometheus` `OpenAPI / Swagger` `Leaflet` `WeasyPrint / ReportLab` `QR codes`

---

## 💡 How I work

- **Docs ship with the change.** Every backend change updates the doc that describes it, in the same
  commit. Architecture decisions get an ADR — *"Redis is optional; here's why"* beats rediscovering it
  six months later.
- **Environments are explicit.** Develop, staging and production are separate accounts, separate
  databases, separate pipelines. Nothing gets verified on the box it was written on.
- **I audit my own work.** Pre-sales security review, a first-customer readiness pass, a structural
  audit of the Django app layout — each one written up with findings, owners and evidence.
- **Measure before optimising.** A load test found a ~5 req/s ceiling that looked like an
  undersized box. It was one serializer. Fixing it gave 2.5× throughput.
- **Georgian-first products.** Georgian and Russian localisation, local payment rails, local DNS.
  i18n isn't a phase-two ticket.

---

## 📦 Selected repositories

| Project | What it is | Stack |
|---|---|---|
| **[Academy-CRM](https://github.com/Piotyrius/Academy-CRM)** | Full CRM for a private academy — admissions, attendance, grading, PDF certificates with QR verification, audit logging | Django 5.1 · DRF · Celery · Redis · PostgreSQL |
| **[acade-portal](https://github.com/Piotyrius/acade-portal)** | The student/lecturer portal on top of it, Georgian &amp; Russian | React · TypeScript · Vite · Tailwind |
| **[zmanculatori](https://github.com/Piotyrius/zmanculatori)** | Rule-based garment pattern engine — a deterministic DAG that drafts parametric 2D sewing patterns from body measurements and exports SVG | FastAPI · async SQLAlchemy · Celery · pure-Python engine |
| **[ZmanculatorFront](https://github.com/Piotyrius/ZmanculatorFront)** | Its control surface and SVG pattern viewer | Next.js · TypeScript · React Query |
| **[sabaCRM](https://github.com/Piotyrius/sabaCRM)** | Sales CRM with a three-level org hierarchy and hierarchical RBAC | Next.js 14 · Prisma · Tailwind |
| **[greenstart-back](https://github.com/Piotyrius/greenstart-back)** | CO₂ removal platform — plantation tracking, absorption maths, generated certificates on GCS | Django · DRF · Google Cloud |
| **[agro-AI](https://github.com/Piotyrius/agro-AI)** | Early LLM experiment — a Flask chat UI in front of a self-hosted model server | Python · Flask |

*A few of the biggest ones — invu's API, web app, mobile app and QA suite — are private.*

---

## 📊 By the numbers

<p align="center">
  <img src="https://img.shields.io/badge/repositories-14-0A66C2?style=flat-square" alt="14 repositories">
  <img src="https://img.shields.io/badge/commits%20authored-~2%2C300-2EA043?style=flat-square" alt="~2,300 commits">
  <img src="https://img.shields.io/badge/primary%20languages-Python%20%C2%B7%20TypeScript-8957E5?style=flat-square" alt="Python and TypeScript">
  <img src="https://img.shields.io/badge/since-2023-6E7681?style=flat-square" alt="Since 2023">
</p>

---

<p align="center">
  <sub>💬 Ask me about Django at the API boundary, canvas editors, or getting a Lightsail deploy to behave.</sub>
</p>
