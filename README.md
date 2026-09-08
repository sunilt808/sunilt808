<h1 align="center">Hi, I'm Sunil T 👋</h1>

<h3 align="center">Full-Stack Developer · Backend Engineer · CSE Undergraduate</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sunilt808&label=Profile%20Views&color=0e75b6&style=flat" alt="profile views" />
  <img src="https://img.shields.io/github/followers/sunilt808?label=Follow&style=social" alt="github followers" />
</p>

I'm a Computer Science & Engineering undergraduate at **Dayananda Sagar College of Engineering**, building practical software systems across the stack — with a growing focus on **backend engineer[...]

I like projects that force me to think about **data modeling, security, automation, correctness, and real-world workflows**.

* 🎓 B.E. CSE, Dayananda Sagar College of Engineering — **CGPA 8.38**
* 🧠 Currently deep in **DSA, System Design, and scalable backend architecture**
* 🏆 **Top 5, DSA Hackathon (BMSCE)** · 4+ hackathons including **RIFT National 2026 (PW)** · Participant, **Point Blank CTF**
* 📚 Sharpening DSA daily on [LeetCode](https://leetcode.com/u/Sunil_T808/) & [GeeksforGeeks](https://www.geeksforgeeks.org/profile/suniltso14h)

---

## 🛠️ Tech Stack

**Languages**

<p>
  <img src="https://skillicons.dev/icons?i=cpp,python,javascript,java" />
</p>

**Frontend**

<p>
  <img src="https://skillicons.dev/icons?i=react,html,css,vite" />
</p>

**Backend**

<p>
  <img src="https://skillicons.dev/icons?i=fastapi" />
</p>

**Databases**

<p>
  <img src="https://skillicons.dev/icons?i=mongodb,mysql,sqlite" />
</p>

**DevOps & Tools**

<p>
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,jenkins,git,github" />
</p>

**Core concepts I work with regularly:**
Data Structures & Algorithms · OOP · DBMS · REST API Design · JWT Authentication · RBAC · Multi-Tenant Architecture · Graph Algorithms · CI/CD · Containerization · MVC

---

# 🚀 Featured Projects

## 🔎 [TraceAcc1](https://github.com/sunilt808/TraceAcc1) — Enterprise AML & Money-Muling Detection Platform

**Graph theory meets financial investigation.**

TraceAcc1 is an **AML operations platform** that goes beyond simply flagging suspicious transactions. It connects **transaction analysis, graph-based detection, ML anomaly detection, investigation[...]

Transaction data is converted into a directed graph and analyzed using multiple complementary detection strategies:

* 🔄 **Cycle detection** for suspicious circular transaction flows
* 🕸️ **Fan-in / Fan-out analysis** for identifying transaction hubs
* 🔗 **Layering-chain detection** for tracing multi-hop movement through intermediary accounts
* ⚡ **Burst-activity detection** for identifying sudden transaction reactivation
* 🧠 **Behavioral and temporal analysis** over account activity
* 📊 **Community and centrality analysis** for graph-level risk signals
* 🤖 **Isolation Forest, LOF and DBSCAN** for unsupervised anomaly detection
* 🧬 **DC-LCG dual-view GNN** for graph-based anomaly analysis
* 🎯 Hybrid scoring producing a **0–100 risk score**

The important part is the workflow after detection: suspicious accounts become **alerts and findings**, which can move into investigation and case-management workflows rather than ending at an ML [...]

```text
Transaction Dataset
        ↓
Transaction Graph
        ↓
Pattern Detection + ML + GNN
        ↓
Hybrid Risk Engine
        ↓
Risk Score / Alerts / Findings
        ↓
Investigation & Case Management
        ↓
Admin Review
        ↓
SHA-256 Report Seal
        ↓
Controlled Client Release
```

The system separates **technical risk analysis from human investigation** while maintaining workflow, activity, and audit traceability across the investigation lifecycle.

<a href="https://deepwiki.com/sunilt808/TraceAcc1">
  <img src="https://deepwiki.com/badge.svg" alt="Ask DeepWiki about TraceAcc1">
</a>

**Stack:** `Python` · `FastAPI` · `NetworkX` · `Graph Theory` · `scikit-learn` · `PyTorch` · `React` · `Cytoscape.js` · `SQLAlchemy`

<p>
  <a href="https://github.com/sunilt808/TraceAcc1">
    <img src="https://img.shields.io/badge/🔍%20Explore%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Explore TraceAcc1 Repository">
  </a>
  <a href="https://deepwiki.com/sunilt808/TraceAcc1">
    <img src="https://img.shields.io/badge/🧠%20DeepWiki-5B5BD6?style=for-the-badge" alt="Explore TraceAcc1 with DeepWiki">
  </a>
</p>

---

## 🏥 [Noq](https://github.com/sunilt808/Noq-hospital) — Multi-Tenant Hospital Management System

**Hospital operations built around smart queues, isolated tenants, and role-specific workflows.**

Noq is a **multi-tenant hospital management platform** designed to handle the operational flow between **System Admins, Hospital Managers, Doctors, and Patients**.

The core idea is to combine appointment management with **digital queue and token management**, while keeping each hospital's data isolated and access controlled.

### What it handles

* 🏥 **Multi-hospital / multi-tenant architecture**
* 🎟️ **Digital queue management and live token tracking**
* 📅 Appointment scheduling and management
* 👨‍⚕️ Doctor workflows and availability
* 📋 Medical records and prescriptions
* 💳 Billing and hospital operations
* 🔔 Notifications and operational updates
* 🔐 JWT authentication and **role-based access control**
* 🧾 Audit-oriented workflows

### Architecture

```text
Patient / Doctor / Manager / Admin
                ↓
          React + Vite
                ↓
           JWT + RBAC
                ↓
          FastAPI REST API
                ↓
          MongoDB Atlas
```

The backend is organized around dedicated API routers and services for authentication, hospitals, departments, doctors, patients, appointments, queues, tokens, billing, notifications, and audit w[...]

The application is deployed with a decoupled frontend/backend architecture.

<p>
  <a href="https://github.com/sunilt808/Noq-hospital">
    <img src="https://img.shields.io/badge/🔍%20Explore%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Explore Noq Repository">
  </a>
  <a href="https://noq-hospital.vercel.app/signup">
    <img src="https://img.shields.io/badge/🚀%20Live%20Demo-2ea44f?style=for-the-badge" alt="Live Demo">
  </a>
  <a href="https://deepwiki.com/sunilt808/Noq-hospital">
    <img src="https://img.shields.io/badge/🧠%20DeepWiki-5B5BD6?style=for-the-badge" alt="Explore Noq with DeepWiki">
  </a>
</p>

**Stack:** `React` · `Vite` · `FastAPI` · `MongoDB Atlas` · `JWT` · `RBAC` · `Vercel` · `Render`

---

## 📡 [PlacementOS](https://github.com/sunilt808/Placement-os) — AI Placement Intelligence Monitor

**Turn messy placement announcements into structured opportunities automatically.**

PlacementOS is a **personal placement intelligence system** built around a real problem: placement information arrives through scattered Telegram messages, PDFs, DOCX files, Excel sheets, images,[...]

Instead of manually checking everything, PlacementOS builds an automated pipeline that **extracts, understands, matches, deduplicates, tracks, and notifies**.

### Intelligence Pipeline

```text
Telegram / PDFs / DOCX / Excel / Images
                  ↓
           Ingestion Pipeline
                  ↓
          Extraction + OCR
                  ↓
           NLP Processing
                  ↓
        Opportunity Engine
           ↙     ↓     ↘
   Eligibility  Dedup  Deadlines
     Matching   Merge   Tracking
           ↘     ↓     ↙
             MongoDB
                ↓
             FastAPI
                ↓
          React Dashboard
                ↓
         Telegram Alerts
```

### Key Engineering Features

* 📡 Telegram monitoring using **Telethon**
* 📄 PDF / DOCX / Excel extraction
* 👁️ **Tesseract OCR** for image-based announcements
* 🧠 Local-first NLP using **spaCy + dateparser + Regex**
* 🎯 Automated eligibility matching across **150+ CSE-family role patterns**
* ♻️ Duplicate detection and opportunity merging
* ⏰ Deadline extraction and tracking
* 📊 React dashboard for structured opportunities
* 🔔 Automated Telegram alerts
* 💾 MongoDB-backed opportunity storage
* 🛡️ Storage-quota guardian and operational safeguards

The system follows a **recall-first philosophy**:

> Missing a genuine opportunity is worse than producing an occasional false alert.

The core extraction pipeline can operate **without an AI API key**, with optional Gemini escalation when required.

<p>
  <a href="https://github.com/sunilt808/Placement-os">
    <img src="https://img.shields.io/badge/🔍%20Explore%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Explore PlacementOS Repository">
  </a>
  <a href="https://placement-os-rust.vercel.app/">
    <img src="https://img.shields.io/badge/🚀%20Live%20Demo-2ea44f?style=for-the-badge" alt="Live PlacementOS Demo">
  </a>
  <a href="https://deepwiki.com/sunilt808/Placement-os">
    <img src="https://img.shields.io/badge/🧠%20DeepWiki-5B5BD6?style=for-the-badge" alt="Explore PlacementOS with DeepWiki">
  </a>
</p>

**Stack:** `FastAPI` · `Telethon` · `spaCy` · `dateparser` · `Tesseract OCR` · `MongoDB Atlas` · `React 19` · `Vercel` · `Render`

---

## ✂️ [CutSlot](https://github.com/sunilt808/Cutslot-4) — Elite Salon Management System

**A salon management platform taken from UI to containerized deployment.**

CutSlot connects **Guests, Artisans, and Directorate/Admin users** through a unified booking and operations platform.

The project focuses heavily on **frontend craft and DevOps**, while the backend is built with FastAPI and SQLAlchemy.

### Platform Features

* 📅 Appointment booking and management
* 👤 Role-specific customer / worker / admin workflows
* 👨‍🔧 Worker assignment and dispatch
* 💰 Wallet functionality
* ⭐ Reviews
* 📊 Revenue and audit dashboards
* 🎨 Glassmorphic React UI
* ⚙️ FastAPI + SQLAlchemy backend

### DevOps Pipeline

```text
Developer Push
      ↓
    Jenkins
      ↓
 Docker Build
      ↓
 Container Image
      ↓
  Kubernetes
      ↓
 Deployment
```

Infrastructure and deployment configuration also include **Terraform**.

### Application Architecture

```text
React 19 + Vite
      ↓
 FastAPI API
      ↓
 SQLAlchemy ORM
      ↓
    SQLite
```

**Stack:** `React 19` · `Vite` · `FastAPI` · `SQLite` · `SQLAlchemy` · `Docker` · `Kubernetes` · `Jenkins` · `Terraform`

<p>
  <a href="https://github.com/sunilt808/Cutslot-4">
    <img src="https://img.shields.io/badge/🔍%20Explore%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Explore CutSlot Repository">
  </a>
  <a href="https://deepwiki.com/sunilt808/Cutslot-4">
    <img src="https://img.shields.io/badge/🧠%20DeepWiki-5B5BD6?style=for-the-badge" alt="Explore CutSlot with DeepWiki">
  </a>
</p>

---

## 📚 [BookSwap](https://github.com/sunilt808/BookSwap) — Android Book Exchange Platform

**A peer-to-peer campus book exchange application built around real exchange workflows.**

BookSwap allows students to **list, discover, borrow, donate, and exchange books** within their college community.

The application implements authentication, user/admin roles, book management, exchange requests, and owner approval using an MVC-based Android architecture.

```text
User
 ↓
Authentication
 ↓
Browse / Search / Manage Books
 ↓
Exchange Request
 ↓
Book Owner Approval
 ↓
Book Exchange
 ↓
Completed
```

```text
Activities / Controllers
        ↓
Adapters + Business Logic
        ↓
Models
        ↓
SQLite
```

**Stack:** `Android` · `Java` · `XML` · `SQLite` · `MVC` · `JWT` · `Android Studio`

<p>
  <a href="https://github.com/sunilt808/BookSwap">
    <img src="https://img.shields.io/badge/🔍%20Explore%20Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Explore BookSwap Repository">
  </a>
</p>

---

## 📚 Currently Learning

**Data Structures & Algorithms** · **System Design** · **Scalable Backend Architecture** · **DevOps & CI/CD** · **Cloud Deployment** · **ML-powered Software Systems**

---

## 🎯 Open To

Roles in **Backend Engineering**, **Full-Stack Development**, and **Distributed / Scalable Systems** — especially teams working on backend architecture, system design, DevOps, graph-based appli[...]

---

## 🤝 Let's Connect

Always up for talking about **backend systems, system design, DSA, hackathons, software engineering, or interesting open-source ideas.**

<p>
  <a href="https://github.com/sunilt808">
    <img src="https://img.shields.io/badge/GitHub-sunilt808-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
  <a href="https://leetcode.com/u/Sunil_T808/">
    <img src="https://img.shields.io/badge/LeetCode-Sunil__T808-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode">
  </a>
  <a href="https://www.geeksforgeeks.org/profile/suniltso14h">
    <img src="https://img.shields.io/badge/GeeksforGeeks-suniltso14h-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" alt="GeeksforGeeks">
  </a>
  <a href="https://github.com/sunilt808/sunilt808/blob/main/Sunil_T_RESUME.pdf">
    <img src="https://img.shields.io/badge/Resume-PDF-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Resume">
  </a>
  <a href="mailto:suniltsuni50@gmail.com">
    <img src="https://img.shields.io/badge/Email-suniltsuni50%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>
