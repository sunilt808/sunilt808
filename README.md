<h1 align="center">Hi, I'm Sunil T 👋</h1>
<h3 align="center">Full-Stack Developer · Backend Engineer · CSE Undergraduate</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sunilt808&label=Profile%20Views&color=0e75b6&style=flat" alt="profile views" />
  <img src="https://img.shields.io/github/followers/sunilt808?label=Follow&style=social" alt="github followers" />
</p>

I'm a Computer Science & Engineering undergraduate at **Dayananda Sagar College of Engineering**, building practical software systems across the stack — with a growing focus on backend engineering, system design, and graph algorithms. I like projects that force me to think about data modeling and correctness under real-world mess, not just CRUD.

* 🎓 B.E. CSE, Dayananda Sagar College of Engineering — **CGPA 8.38**
* 🧠 Currently deep in DSA, System Design, and distributed/scalable backend architecture
* 🏆 Top 5, DSA Hackathon (BMSCE) · 4+ hackathons including **RIFT National 2026 (PW)** · Participant, **Point Blank CTF**
* 📚 Sharpening DSA daily on [LeetCode](https://leetcode.com/u/Sunil_T808/) & [GeeksforGeeks](https://www.geeksforgeeks.org/profile/suniltso14h)

---

## 🛠️ Tech Stack

**Languages**

<p><img src="https://skillicons.dev/icons?i=cpp,python,javascript,java" /></p>

**Frontend**

<p><img src="https://skillicons.dev/icons?i=react,html,css,vite" /></p>

**Backend**

<p><img src="https://skillicons.dev/icons?i=fastapi" /></p>

**Databases**

<p><img src="https://skillicons.dev/icons?i=mongodb,mysql,sqlite" /></p>

**DevOps & Tools**

<p><img src="https://skillicons.dev/icons?i=docker,kubernetes,jenkins,git,github" /></p>

**Core concepts I work with regularly:** Data Structures & Algorithms · OOP · DBMS · REST API design · JWT auth & RBAC · Multi-tenant architecture · Graph algorithms · CI/CD · Containerization · MVC

---

## 🚀 Featured Projects

### 🔗 [TraceAcc](https://github.com/sunilt808/TraceAcc) — Graph-Based AML & Money-Muling Detection Engine

*Graph theory meets fraud detection.* Transaction CSVs are parsed into a directed transaction graph, then run through a multi-heuristic detection pipeline — DFS-based cycle detection for fraud rings, fan-in/fan-out hub detection, layering-chain tracing through shell accounts, and burst-activity detection for mule reactivation — plus an unsupervised ML layer (Isolation Forest, Local Outlier Factor, DBSCAN) over per-account behavioral features. Every account gets a weighted 0–100 suspicion score, with results explored through a FastAPI backend and a React + Cytoscape.js investigation dashboard.

<a href="https://deepwiki.com/sunilt808/TraceAcc1"><img src="https://deepwiki.com/badge.svg" alt="Ask DeepWiki"></a>

`Python` · `FastAPI` · `NetworkX` · `Graph Theory` · `React` · `Cytoscape.js` · `scikit-learn`

---

### 🔗 [Noq](https://github.com/sunilt808/Noq-hospital) — Multi-Tenant Hospital Management System  [![Live Demo](https://img.shields.io/badge/Live-Demo-2ea44f?style=flat-square)](https://noq-hospital.vercel.app/signup)

A multi-tenant hospital management platform built around **smart queue and token-based appointment management**, with isolated hospital data and role-specific workflows for System Admin, Hospital Manager, Doctor, and Patient. The platform handles appointments, real-time token/queue tracking, billing, medical records, prescriptions, notifications, and hospital operations.

Built with a decoupled **React + FastAPI + MongoDB Atlas** architecture, using JWT authentication and RBAC to enforce tenant and role-level access. The backend is organized around dedicated API routers and services covering authentication, hospitals, departments, doctors, patients, appointments, queues, tokens, billing, notifications, and audit workflows.

<a href="https://deepwiki.com/sunilt808/Noq-hospital"><img src="https://deepwiki.com/badge.svg" alt="Ask DeepWiki"></a>

`React` · `FastAPI` · `MongoDB Atlas` · `JWT` · `Vercel` · `Render`

---

### PlacementOS — AI Placement Intelligence Monitor  ![Private](https://img.shields.io/badge/repo-private-lightgrey?style=flat-square)  [![Live Demo](https://img.shields.io/badge/Live-Demo-2ea44f?style=flat-square)](https://placement-os-rust.vercel.app/)

A self-hosted, single-user placement assistant that watches my college's placement Telegram group 24/7 and turns unstructured messages into structured, actionable opportunities. Repo is private since it's tuned to my own placement group and credentials, but the app is deployed and viewable live. Built on one guiding principle: **recall > precision — missing a real opportunity is worse than a false alert.** The core extraction loop runs fully offline, no AI API key required.

Pulls from a Telethon userbot + historical import, extracts from PDFs/DOCX/Excel/images (Tesseract OCR) and Google Forms, and runs local-first NLP (spaCy + dateparser + regex, with optional Gemini escalation) to match 150+ CSE-family roles, score eligibility, dedupe and merge same-company opportunities into one timeline, and track deadlines — with a React dashboard, storage-quota guardian, and automated Telegram alerts.

```
Telegram → Telethon/Bot API/Import → Message Pipeline → NLP + OCR + Extraction
→ Opportunity Engine → Dedup + Eligibility + Deadlines → MongoDB Atlas → FastAPI (REST/SSE) → React Dashboard → Telegram Alerts
```

`FastAPI` · `Telethon` · `spaCy` · `MongoDB Atlas` · `React 19` · `Vercel` · `Render`

---

### CutSlot — Elite Salon Management System  ![Private](https://img.shields.io/badge/repo-private-lightgrey?style=flat-square)

A premium, glassmorphic salon platform connecting Guests, Artisans (workers), and the Directorate (admins) — booking, worker dispatch, wallets, reviews, and revenue/audit dashboards. **Project focus is deliberately frontend craft + DevOps**, not backend depth: a FastAPI/SQLAlchemy backend exists and is fully wired up, but the real work here is the glassmorphic UI system and a complete Docker → Kubernetes → Jenkins CI/CD pipeline (Terraform included).

```
Model (SQLAlchemy + Pydantic) ← Controller (FastAPI, main.py) ← View (React, role-split by admin/worker/client/common)
```

`React 19` · `Vite` · `FastAPI` · `SQLite` · `SQLAlchemy` · `Docker` · `Kubernetes` · `Jenkins` · `Terraform`

---

### 🔗 [BookSwap](https://github.com/sunilt808/BookSwap) — Android Book Exchange Platform

An Android app for students to list, discover, borrow, and exchange books within their college community — JWT auth, user/admin roles, and a clean MVC structure over SQLite.

```
Activities/Controllers → Adapters + Logic → Models → SQLite
```

`Android` · `Java` · `SQLite` · `MVC` · `JWT`

---

## 📚 Currently Learning

Advanced DSA & Graph Algorithms · System Design · Scalable Backend Architecture · DevOps & CI/CD · Cloud Deployment · ML-powered Software Systems

## 🎯 Open To

Roles in **Backend Engineering**, **Full-Stack Development**, and **Distributed/Scalable Systems** — especially teams working on system design, DevOps, or graph-driven problems.

---

## 🤝 Let's Connect

Always up for talking backend systems, system design, DSA, hackathons, or open-source ideas.

[![GitHub](https://img.shields.io/badge/GitHub-sunilt808-181717?style=for-the-badge\&logo=github)](https://github.com/sunilt808)
[![LeetCode](https://img.shields.io/badge/LeetCode-Sunil__T808-FFA116?style=for-the-badge\&logo=leetcode\&logoColor=white)](https://leetcode.com/u/Sunil_T808/)
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-suniltso14h-2F8D46?style=for-the-badge\&logo=geeksforgeeks\&logoColor=white)](https://www.geeksforgeeks.org/profile/suniltso14h)
[![Resume](https://img.shields.io/badge/Resume-PDF-red?style=for-the-badge\&logo=adobeacrobatreader\&logoColor=white)](https://github.com/sunilt808/sunilt808/blob/main/Sunil_T_RESUME.pdf)
[![Email](https://img.shields.io/badge/Email-suniltsuni50%40gmail.com-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:suniltsuni50@gmail.com)
