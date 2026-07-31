<h1 align="center">
  Hi there 👋
</h1>

<p align="center"><strong>Software Engineer · Mobile Developer</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/Location-Da%20Nang,%20Vietnam-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Focus-Backend Development-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Focus-Mobile Development-cyan?style=flat-square"/>
  <img src="https://img.shields.io/badge/Status-Internship%20%26%20Building-navy?style=flat-square"/>
</p>

---

## 🚀 About Me

I am an Information Technology student and Software Engineer Intern who loves building scalable backend systems. My expertise spans across server-side development, mobile app development, and system integration. I enjoy solving real-world problems with control logic, clean architecture, and low-level optimization.

### What I love working with:
- **Backend Development:** Nest.js, Express.js.
- **Frontend Development:** React.js/Next.js.
- **Databases & Caching**: PostgreSQL, MySQL/MariaDB, MongoDB, SQLite, Redis
- **Mobile Development:** Flutter cross-platform UI, Native Android (Kotlin + Jetpack Compose).

### Languages:
- **Vietnamese**: Native language.
- **English**: Working proficiency - able to read technical documentation and communicate effectively in the workplace.
- **Mandarin Chinese**: Currently studying HSK 3, with a strong commitment to achieving professional proficiency in Chinese.
---
## 🧰 Languages and Tools

<p align="center">
  <!-- Languages -->
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart"/>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin"/>

  <br/>

  <!-- Backend -->
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js"/>

  <br/>

  <!-- Frontend and Mobile -->
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose"/>

  <br/>

  <!-- Databases -->
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase"/>

  <br/>

  <!-- DevOps and Tools -->
  <img src="https://img.shields.io/badge/Cloudflare-FCC624?style=for-the-badge&logo=cloudflare&logoColor=orange" alt="Cloudflare"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
</p>

## 🛠️ Tech Stack

| Domain | Tools / Frameworks |
| ------------------- | ---------------------------------------------------------------------------- |
| **Mobile** | Flutter, Dart, BLoC / Provider, Firebase Cloud Messaging |
| **Frontend & Backend** | TypeScript, Node.js (NestJS, Express.js), Python (FastAPI), PHP (Laravel), React.js/Next.js |
| **Core Concepts** | Event-Driven, Microservices, Message Queue |
| **Cloud & DevOps** | GitHub Actions, Linux server management, Docker, RabbitMQ |

---

## ⭐ Personal Projects

### 💼 IT Job Board — AI-Powered Job Aggregation & Search Platform

An intelligent job-search platform that aggregates Vietnamese IT job postings from multiple sources and provides hybrid search with an AI-powered assistant.
- **Job Aggregation:** Crawls job postings from ITViec, TopDev, and JobOKO using browser automation with concurrent workers.
- **Data Processing:** Normalizes job titles, company names, locations, salaries, skills, job categories, and seniority levels.
- **Deduplication:** Detects duplicate postings within the same source while preserving listings from different job boards.
- **Hybrid Search:** Combines Elasticsearch BM25 search and Qdrant vector search using Reciprocal Rank Fusion and cross-encoder reranking.
- **AI Assistant:** Provides a retrieval-augmented chatbot that answers questions based only on available job postings with source citations.
- **Background Processing:** Uses Celery, RabbitMQ, and Redis for scheduled crawling, indexing, retries, locking, and maintenance tasks.
- **Dashboard:** Vue-based interface for browsing jobs, advanced filtering, semantic search, statistics, crawl history, and admin task management.
- **Tech:** FastAPI, Python, Vue 3, PostgreSQL, SQLAlchemy, Elasticsearch, Qdrant, Celery, RabbitMQ, Redis, Patchright, Sentence Transformers, Docker.

### ⚡ LoadService — Distributed Load & Resilience Testing Platform
An load-testing platform for evaluating the performance and resilience of user-controlled infrastructure.
*   **Resource Management:** Manages networks, worker servers, methods, duration, and concurrent slots.
*   **Access Control:** Supports JWT authentication, RBAC, permissions, roles, plans, and feature limits.
*   **Microservice Architecture:** Separates test and payment execution into an independent service.
*   **Message Queue Coordination:** Uses RabbitMQ to queue jobs and prevent worker slot conflicts.
*   **Backend Architecture:** Built with modular NestJS, repositories, migrations, filters, and interceptors.
*   **Dashboard:** Uses React to manage users, roles, plans, networks, servers, and test jobs.
*   **Tech:** NestJS, TypeScript, React, PostgreSQL, Drizzle ORM, Redis, RabbitMQ, JWT, Swagger, Docker.

### 💬 FastChat — Real-Time Communication Platform
A full-stack messaging application supporting real-time conversations, media sharing, push notifications, and audio/video calls.
*   **Backend:** Implements JWT authentication, private and group conversations, message reactions, participant roles, user blocking, media uploads, and password recovery.
*   **Real-Time Communication:** Uses **Socket.IO** for messaging and WebRTC signaling, with a self-hosted **Coturn** server for reliable call connectivity behind NAT and firewalls.
*   **Mobile App:** Built with Flutter using BLoC/Cubit architecture, persistent sessions, local notifications, media playback, message search, and file sharing.
*   **Deployment:** Set up CI/CD with GitHub Actions for automated Docker builds and SSH-based VM deployment.
*   **Tech:** NestJS, TypeScript, Flutter, Dart, MongoDB, TypeORM, Socket.IO, WebRTC, Firebase Cloud Messaging, S3-compatible storage, Docker.

### ⚙️ Chrome Remote Interface — Typed Async Chrome DevTools Protocol Client
A low-level asynchronous Python client for interacting with Chrome and Chromium through the Chrome DevTools Protocol (CDP).
- **Protocol Communication:** Connects to Chrome debugging targets over WebSocket using `asyncio`.
- **Type-Safe API:** Provides generated typed modules for CDP domains, commands, parameters, responses, events, payloads, aliases, and enums.
- **Event Management:** Supports typed event callbacks, awaitable one-shot listeners, and session-specific event filtering.
- **Browser Control:** Enables page navigation, JavaScript execution, network monitoring, target management, browser inspection, and runtime debugging.
- **Target & Session Support:** Connects to browser targets, creates and attaches to tabs, and supports flattened CDP sessions.
- **Protocol Generation:** Generates Python bindings from the CDP schema and supports protocol updates for newer Chrome versions.
- **Developer Tools:** Includes browser discovery helpers and a CLI for listing targets, creating pages, inspecting browsers, and fetching protocol descriptors.
- **Tech:** Python, AsyncIO, WebSockets, TypedDict, Chrome DevTools Protocol, JSON, Pyright, Ruff, Setuptools.

---

### 🔥 Streak Stats
[![GitHub Streak](https://streak-stats.demolab.com?user=il2dottore&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

---

## 🌐 Connect With Me
- **GitHub:** [il2dottore](https://github.com/il2dottore)
- **Email:** vongocbao1392005@gmail.com

---

Thanks for stopping by! 🚀
