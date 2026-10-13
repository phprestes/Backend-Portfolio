# ⚙️ Backend Engineering Portfolio

Welcome to my backend engineering repository! This portfolio aggregates the projects where the core of the work is the server side: designing APIs, modeling data, and keeping state consistent. It spans a bootcamp project, event projects, and course assignments developed while pursuing my **B.S. in Computer Science** at the **University of São Paulo (USP) - ICMC**.

The portfolio is organized by area. Each project includes a brief description, core techniques, technology stack, and an interactive repository card.

> See also: [Data Science Portfolio](https://github.com/phprestes/Data-Science-Portfolio), [Data Engineering Portfolio](https://github.com/phprestes/Data-Engineering-Portfolio) and [Undergraduate Projects Portfolio](https://github.com/phprestes/Undergraduate-ICMC-USP).

---

## 📌 Quick Navigation
- [REST APIs & Services](#-rest-apis--services)
- [Full-Stack Web Applications](#-full-stack-web-applications)

---

## 🔹 REST APIs & Services

## 📚 Bootcamp QI Tech 2026
* **Project Name:** Digital Bank API — Bootcamp QI Tech 2026
* **Description:** An API for a digital bank covering customer registration, a linked account, deposits, transfers with a fee, and a paginated statement. Built as a layered monolith with a mocked external service, money stored in cents, and balances kept in a column guarded by a lock, backed by black-box HTTP tests and documented architecture decision records. The repository is also written to be AI-friendly, with an `AGENTS.md` and skills for coding agents.
* **Techniques:** Layered Architecture (Middlewares, Schemas, Resources, Controllers, Repositories, Models), REST API Design, Transactional Integrity (Balance Column with Lock), Money as Integer Cents, Pagination, Black-Box Integration Testing, Architecture Decision Records, Containerized Environments (Docker Compose), AI-Friendly Repository Documentation.
* **Stack:** `Python 3.11`, `FastAPI`, `PostgreSQL 16`, `Docker`, `MockServer`, `pytest`, `Makefile`
* **Repository:**

  <a href="https://github.com/phprestes/Bootcamp-QI-Tech">
    <img src="https://gh-card.dev/repos/phprestes/Bootcamp-QI-Tech.svg" alt="Repo Card" />
  </a>

## 💡 Event Project — SEMCOMP
* **Project Name:** Donation Stock Exchange API (SEMCOMP)
* **Description:** A REST API built within SEMCOMP to streamline the event's fundraising, run as a "stock exchange" of donations. Donation items belong to tiers whose value multiplier decays along a polynomial as donations accumulate, items are demoted to the next tier once their quantity limit is reached, and the service renders charts of how item values evolve over time.
* **Techniques:** REST API Design, Document Modeling (MongoDB), Polynomial Decay Pricing, Tier Demotion Logic, Input Validation, Server-Side Chart Rendering.
* **Stack:** `JavaScript`, `Node.js`, `Express.js`, `MongoDB`, `Mongoose`, `Chart.js`
* **Repository:**

  <a href="https://github.com/phprestes/API-Arrecadacao-Semcomp">
    <img src="https://gh-card.dev/repos/phprestes/API-Arrecadacao-Semcomp.svg" alt="Repo Card" />
  </a>

---

## 🔹 Full-Stack Web Applications

## 📚 Introduction to Web Development
* **Project Name:** Poções e Soluções — Full-Stack E-Commerce
* **Description:** A complete web application for the fictional "Poções e Soluções" store, covering product catalog, cart, user accounts, and an administrative area. Split into a React SPA front-end and a REST API back-end with a relational persistence layer through an ORM.
* **Techniques:** Single Page Applications (SPA), Component-Based UI, REST API Design, ORM Modeling & Migrations, Client-Side Routing, Authentication & Authorization, Responsive Layout.
* **Stack:** `JavaScript`, `React`, `Vite`, `Node.js`, `Express.js`, `SQLite`, `Sequelize`, `CSS`
* **Repository:**

  <a href="https://github.com/phprestes/Pocoes-e-Solucoes">
    <img src="https://gh-card.dev/repos/phprestes/Pocoes-e-Solucoes.svg" alt="Repo Card" />
  </a>

## 📚 Introduction to Web Development
* **Project Name:** Farol das Artes — Art Platform
* **Description:** A full-stack web platform built as the final assignment of the course, pairing a React front-end with a Go REST API, a PostgreSQL database, and MinIO object storage for media. The whole environment is orchestrated with Docker Compose and driven by a Makefile.
* **Techniques:** REST API Design (Gin + GORM), Object Storage for Media Assets, Relational Data Modeling, Containerized Development Environments, Build Automation, Front-End/Back-End Integration.
* **Stack:** `Go`, `Gin`, `GORM`, `JavaScript`, `React`, `Vite`, `PostgreSQL`, `MinIO`, `Docker`, `Makefile`
* **Repository:**

  <a href="https://github.com/pedrohpd/Farol_da_Arte">
    <img src="https://gh-card.dev/repos/pedrohpd/Farol_da_Arte.svg" alt="Repo Card" />
  </a>

---
