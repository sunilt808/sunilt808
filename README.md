<h1 align="center">Hi, I'm Sunil T 👋</h1>
<h3 align="center">Full-Stack Developer · Backend Engineer · CSE Undergraduate</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sunilt808&label=Profile%20Views&color=0e75b6&style=flat" alt="profile views" />
  <img src="https://img.shields.io/github/followers/sunilt808?label=Follow&style=social" alt="GitHub followers" />
</p>

<p align="center">
  Building practical software systems with a focus on backend engineering, APIs, data modeling, authentication, graph-based analysis, and DevOps.
</p>

---

## 👨‍💻 About Me

I'm a Computer Science & Engineering undergraduate at **Dayananda Sagar College of Engineering**, interested in building software systems that go beyond basic CRUD applications.

My current focus is on **Data Structures & Algorithms, backend engineering, system design, and DevOps**, while working on projects involving real-world workflows, security, data processing, and graph analytics.

* 🎓 B.E. Computer Science & Engineering — **CGPA: 8.38**
* 🧠 Currently focusing on **DSA, System Design, Backend Architecture & DevOps**
* 🏆 **Top 5 — DSA Hackathon, BMSCE**
* 🏆 Participated in **4+ hackathons**, including **RIFT National 2026**
* 🔐 Participant — **Point Blank CTF**
* 💻 Practicing DSA on [LeetCode](https://leetcode.com/u/Sunil_T808/) and [GeeksforGeeks](https://www.geeksforgeeks.org/profile/suniltso14h)

---

## 🛠️ Tech Stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=cpp,python,javascript,java" />
</p>

### Frontend

<p>
  <img src="https://skillicons.dev/icons?i=react,html,css,vite" />
</p>

### Backend

<p>
  <img src="https://skillicons.dev/icons?i=fastapi" />
</p>

### Databases

<p>
  <img src="https://skillicons.dev/icons?i=mongodb,mysql,sqlite" />
</p>

### DevOps & Tools

<p>
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,jenkins,terraform,git,github" />
</p>

### Core Concepts

`Data Structures & Algorithms` · `OOP` · `DBMS` · `REST APIs` · `JWT Authentication` · `RBAC` · `Multi-Tenant Architecture` · `Graph Algorithms` · `CI/CD` · `Containerization` · `MVC`

---

# 🚀 Featured Projects

## 🔍 TraceAcc — Graph-Based AML & Money-Muling Detection

[![GitHub](https://img.shields.io/badge/GitHub-TraceAcc-181717?style=flat-square\&logo=github)](https://github.com/sunilt808/TraceAcc)

A graph-based **Anti-Money Laundering (AML) and money-muling detection system** that analyzes transaction relationships and identifies suspicious financial behavior through graph algorithms, rule-based detection, and machine-learning techniques.

### Key Capabilities

* 🔄 Transaction graph construction and analysis
* 🕸️ Graph-based suspicious-pattern detection
* 🔁 Cycle detection for potential transaction rings
* 📡 Fan-in / fan-out analysis for suspicious hubs
* ⛓️ Layering-chain analysis
* ⚡ Burst-activity detection
* 🤖 Unsupervised anomaly detection
* 📊 Account-level suspicion scoring
* 🔎 Interactive graph-based investigation

### Architecture

```text
Transaction Data
       ↓
Graph Construction
       ↓
Graph Analysis + Detection Pipeline
       ↓
ML Anomaly Detection
       ↓
Risk / Suspicion Scoring
       ↓
FastAPI Backend
       ↓
React Investigation Dashboard
```

`Python` · `FastAPI` · `NetworkX` · `scikit-learn` · `React` · `Cytoscape.js` · `Graph Algorithms`

<a href="https://deepwiki.com/sunilt808/TraceAcc1">
  <img src="https://deepwiki.com/badge.svg" alt="Ask DeepWiki" />
</a>

---

## 🏥 Noq — Multi-Tenant Hospital Management System

[![GitHub](https://img.shields.io/badge/GitHub-Noq--Hospital-181717?style=flat-square\&logo=github)](https://github.com/sunilt808/Noq-hospital)
[![Live Demo](https://img.shields.io/badge/Live-Demo-2ea44f?style=flat-square)](https://noq-hospital.vercel.app/signup)

A **multi-tenant hospital management platform** built around appointment, queue, token and hospital-operation workflows.

### Key Features

* 🏥 Multi-tenant hospital architecture
* 🎫 Appointment and token management
* ⏱️ Queue and token lifecycle management
* 👨‍⚕️ Doctor and patient workflows
* 💰 Billing workflows
* 📋 Medical records and prescriptions
* 🔔 Notifications
* 🛡️ JWT authentication
* 🔐 Role-based access control
* 📝 Audit logging

### Roles

```text
System Admin
     ↓
Hospital Manager
     ↓
Doctor
     ↓
Patient
```

The application uses a decoupled **React frontend + FastAPI backend + MongoDB Atlas** architecture.

`React` · `Vite` · `FastAPI` · `MongoDB Atlas` · `JWT` · `PBKDF2` · `RBAC` · `Vercel` · `Render`

<a href="https://deepwiki.com/sunilt808/Noq-hospital">
  <img src="https://deepwiki.com/badge.svg" alt="Ask DeepWiki" />
</a>

---

## 📡 PlacementOS — AI Placement Intelligence Monitor

![Private](https://img.shields.io/badge/repository-private-lightgrey?style=flat-square)
[![Live Demo](https://img.shields.io/badge/Live-Demo-2ea44f?style=flat-square)](https://placement-os-rust.vercel.app/)

A personal placement intelligence system that transforms unstructured college placement updates into **structured, actionable opportunities**.

The system monitors placement communications, extracts job information from messages and documents, evaluates eligibility, tracks deadlines, and reduces duplicate announcements.

### Processing Pipeline

```text
Telegram / Documents
        ↓
Message & File Processing
        ↓
OCR + NLP + Extraction
        ↓
Opportunity Detection
        ↓
Eligibility Matching
        ↓
Deduplication + Deadline Tracking
        ↓
MongoDB
        ↓
FastAPI
        ↓
React Dashboard + Telegram Alerts
```

The system follows a **recall-first approach**, prioritizing the discovery of potential opportunities before filtering them.

`FastAPI` · `Telethon` · `spaCy` · `Tesseract OCR` · `MongoDB Atlas` · `React 19` · `Vercel` · `Render`

---

## 💇 CutSlot — Elite Salon Management System

![Private](https://img.shields.io/badge/repository-private-lightgrey?style=flat-square)

A salon management platform connecting **Guests, Artisans and Directorate/Admins** through role-specific workflows.

The project focuses on **frontend engineering, application architecture and DevOps**, with a React interface, FastAPI backend and containerized CI/CD pipeline.

### Key Features

* 📅 Appointment booking
* 👤 Role-based dashboards
* 👨‍🔧 Artisan management
* 💳 Wallet workflows
* ⭐ Reviews
* 📊 Revenue and audit dashboards
* 🐳 Docker
* ☸️ Kubernetes
* 🔄 Jenkins CI/CD
* 🏗️ Terraform

### Architecture

```text
React Frontend
       ↓
FastAPI Controllers
       ↓
SQLAlchemy Models
       ↓
SQLite
```

`React 19` · `Vite` · `FastAPI` · `SQLAlchemy` · `SQLite` · `Docker` · `Kubernetes` · `Jenkins` · `Terraform`

---

## 📚 BookSwap — Android Book Exchange Platform

[![GitHub](https://img.shields.io/badge/GitHub-BookSwap-181717?style=flat-square\&logo=github)](https://github.com/sunilt808/BookSwap)

An Android application designed for students to **list, discover, borrow and exchange books** within their college community.

### Key Features

* 📚 Book listing and management
* 🔍 Book discovery
* 🔄 Exchange workflows
* 👤 User management
* 🛡️ Admin functionality
* 🔐 Authentication
* 🗄️ Local database storage

### Architecture

```text
Activities / Controllers
          ↓
Application Logic
          ↓
Models
          ↓
SQLite
```

`Java` · `Android` · `XML` · `SQLite` · `JWT` · `MVC`

---

# 📚 Currently Learning

* Data Structures & Algorithms
* System Design
* Backend Architecture
* Database Design
* DevOps & CI/CD
* Cloud Deployment
* Machine Learning for Software Systems

---

# 🎯 Open To

I'm interested in opportunities involving:

**Backend Engineering · Full-Stack Development · Software Engineering · System Design · DevOps**

I particularly enjoy working on problems involving **APIs, data processing, authentication, graph algorithms and complete end-to-end systems.**

---

# 🤝 Let's Connect

Always interested in discussing **backend systems, DSA, system design, hackathons and software projects.**

<p>
  <a href="https://github.com/sunilt808">
    <img src="https://img.shields.io/badge/GitHub-sunilt808-181717?style=for-the-badge&logo=github" />
  </a>
  <a href="https://leetcode.com/u/Sunil_T808/">
    <img src="https://img.shields.io/badge/LeetCode-Sunil__T808-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" />
  </a>
  <a href="https://www.geeksforgeeks.org/profile/suniltso14h">
    <img src="https://img.shields.io/badge/GeeksforGeeks-suniltso14h-2F8D46?style=for-the-badge&logo=geeksforgeeks&logoColor=white" />
  </a>
  <a href="https://github.com/sunilt808/sunilt808/blob/main/Sunil_T_RESUME.pdf">
    <img src="https://img.shields.io/badge/Resume-PDF-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" />
  </a>
  <a href="mailto:suniltsuni50@gmail.com">
    <img src="https://img.shields.io/badge/Email-suniltsuni50%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>
