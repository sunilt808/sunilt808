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

### 🔗 [TraceAcc1](https://github.com/sunilt808/TraceAcc1) — Graph-Based AML & Money-Muling Detection Engine

*Graph theory meets fraud detection.* TraceAcc is an **AML operations and money-muling detection platform** that analyzes financial transactions as graphs to uncover suspicious account relationships and behavioral patterns. It combines graph-based detection with machine-learning techniques to generate risk intelligence and help investigators explore potentially suspicious transaction networks through an interactive dashboard.

Built with **FastAPI, NetworkX, scikit-learn, PyTorch, React, and Cytoscape.js**, bringing together graph algorithms, anomaly detection, and visual investigation into one system.

`Python` · `FastAPI` · `NetworkX` · `Graph Theory` · `scikit-learn` · `PyTorch` · `React` · `Cytoscape.js`

#### 🏗️ Architecture

```text
Transaction Data / CSV
        ↓
Data Parsing & Validation
        ↓
Transaction Graph
(NetworkX)
        ↓
┌───────────────────────────────┐
│ Graph-Based Detection         │
│ • Cycles                      │
│ • Fan-In / Fan-Out            │
│ • Layering Chains              │
│ • Burst Activity              │
└───────────────────────────────┘
        +
┌───────────────────────────────┐
│ ML Anomaly Detection          │
│ • Isolation Forest             │
│ • LOF                          │
│ • DBSCAN                       │
└───────────────────────────────┘
        ↓
Risk Intelligence / Scoring
        ↓
FastAPI REST API
        ↓
React + Cytoscape.js
Investigation Dashboard
```

<p>
  <a href="https://github.com/sunilt808/TraceAcc1">
    <img src="https://img.shields.io/badge/Explore%20Repo-181717?style=for-the-badge&logo=github&logoColor=white" alt="Explore Repository">
  </a>
  <a href="https://deepwiki.com/sunilt808/TraceAcc1">
    <img src="https://img.shields.io/badge/Ask%20DeepWiki-5B5BD6?style=for-the-badge" alt="Ask DeepWiki">
  </a>
</p>

---

### 🔗 [Noq](https://github.com/sunilt808/Noq-hospital) — Multi-Tenant Hospital Management System

Noq is a **multi-tenant hospital management platform built around smart appointments and digital queue management**. It replaces traditional waiting-line workflows with a role-based system where patients, doctors, hospital managers, and administrators can manage appointments, live queues, medical records, billing, and hospital operations from a unified platform.

The system is built around a **decoupled React + FastAPI + MongoDB Atlas architecture**, with **JWT authentication, RBAC, and isolated hospital data** designed to support multiple hospitals within the same platform.

`React` · `FastAPI` · `MongoDB Atlas` · `JWT` · `Vercel` · `Render`

#### 🏗️ Architecture

```text
                    React Frontend
                         ↓
                Authentication / RBAC
                         ↓
                  FastAPI REST API
                         ↓
              ┌────────────────────┐
              │ Application Logic  │
              │                    │
              │ Appointments       │
              │ Queue Management   │
              │ Medical Records    │
              │ Billing            │
              │ Notifications      │
              └────────────────────┘
                         ↓
                 MongoDB Atlas
                         ↓
              Hospital / Tenant Data
```

<p>
  <a href="https://github.com/sunilt808/Noq-hospital">
    <img src="https://img.shields.io/badge/Explore%20Repo-181717?style=for-the-badge&logo=github&logoColor=white" alt="Explore Repository">
  </a>
  <a href="https://noq-hospital.vercel.app/signup">
    <img src="https://img.shields.io/badge/Live%20Demo-2ea44f?style=for-the-badge" alt="Live Demo">
  </a>
  <a href="https://deepwiki.com/sunilt808/Noq-hospital">
    <img src="https://img.shields.io/badge/Ask%20DeepWiki-5B5BD6?style=for-the-badge" alt="Ask DeepWiki">
  </a>
</p>

---

### PlacementOS — AI Placement Intelligence Monitor

PlacementOS is a **personal placement intelligence system** that continuously monitors unstructured college placement information and turns it into structured, actionable opportunities. It combines Telegram monitoring, document extraction, OCR, NLP, eligibility matching, deadline tracking, and automated alerts to reduce the effort of manually searching through placement updates.

Built as a **local-first, self-hosted system** with a FastAPI backend, React dashboard, MongoDB Atlas, Telethon, spaCy, OCR, and an automated opportunity-processing pipeline.

`FastAPI` · `Telethon` · `spaCy` · `MongoDB Atlas` · `React 19` · `Tesseract OCR` · `Vercel` · `Render`

#### 🏗️ Architecture

```text
Telegram Groups / Historical Import
                ↓
          Ingestion Layer
       (Telethon + Imports)
                ↓
       Document / Media Extraction
        ┌───────┼────────┐
        ↓       ↓        ↓
      Text     PDF      Images
                ↓        ↓
           OCR / Parsers
                ↓
        Intelligence Layer
     ┌──────────┼──────────┐
     ↓          ↓          ↓
   spaCy      Regex     Optional Gemini
     └──────────┼──────────┘
                ↓
       CSE Role Classification
                ↓
       Opportunity Engine
     ┌──────────┼──────────┐
     ↓          ↓          ↓
 Deduplication Eligibility Deadlines
                ↓
          MongoDB Atlas
                ↓
          FastAPI REST API
                ↓
         React Dashboard
                ↓
       Telegram Notifications
```

<p>
  <a href="https://github.com/sunilt808/Placement-os">
    <img src="https://img.shields.io/badge/Explore%20Repo-181717?style=for-the-badge&logo=github&logoColor=white" alt="Explore Repository">
  </a>
  <a href="https://placement-os-rust.vercel.app/">
    <img src="https://img.shields.io/badge/Live%20Demo-2ea44f?style=for-the-badge" alt="Live Demo">
  </a>
  <a href="https://deepwiki.com/sunilt808/Placement-os">
    <img src="https://img.shields.io/badge/Ask%20DeepWiki-5B5BD6?style=for-the-badge" alt="Ask DeepWiki">
  </a>
</p>

---

### CutSlot — Elite Salon Management System

CutSlot is a **salon management platform connecting customers, workers, and administrators through a unified booking and operations system**. It brings together appointment management, worker assignment, wallets, reviews, and business reporting while focusing heavily on a polished, modern user experience.

The project combines a **glassmorphic React interface** with a FastAPI backend and a complete **Docker → Kubernetes → Jenkins CI/CD pipeline**, making it a project focused on both frontend engineering and DevOps practices.

`React 19` · `Vite` · `FastAPI` · `SQLite` · `SQLAlchemy` · `Docker` · `Kubernetes` · `Jenkins` · `Terraform`

#### 🏗️ Architecture

```text
                 React 19 SPA
                (Vite Frontend)
                       ↓
              Role-Based Routing
        ┌──────────┬──────────┬──────────┐
        ↓          ↓          ↓
      Admin      Artisan     Client
      Portal      Portal     Portal
        └──────────┬──────────┘
                   ↓
              FastAPI API
                   ↓
        ┌──────────────────────┐
        │ Controller / Routes  │
        │ Auth + Business Logic│
        └──────────┬───────────┘
                   ↓
        SQLAlchemy / Pydantic
                   ↓
                SQLite
                   ↓
          Docker Containers
                   ↓
              Kubernetes
                   ↓
          Jenkins CI/CD
                   ↓
            AWS EKS / IaC
             (Terraform)
```

<p>
  <a href="https://github.com/sunilt808/Cutslot-4">
    <img src="https://img.shields.io/badge/Explore%20Repo-181717?style=for-the-badge&logo=github&logoColor=white" alt="Explore Repository">
  </a>
  <a href="https://deepwiki.com/sunilt808/Cutslot-4">
    <img src="https://img.shields.io/badge/Ask%20DeepWiki-5B5BD6?style=for-the-badge" alt="Ask DeepWiki">
  </a>
</p>

---

### 🔗 [BookSwap](https://github.com/sunilt808/BookSwap) — Android Book Exchange Platform

BookSwap is an **Android-based book exchange platform designed for students to discover, list, borrow, and exchange books within their college community**. It provides a simple digital marketplace for peer-to-peer book sharing while supporting authentication, user roles, and administrative control.

The application follows a clean **MVC architecture** with Java and SQLite, keeping the project focused on structured Android development and local data management.

`Android` · `Java` · `SQLite` · `MVC` · `JWT`

#### 🏗️ Architecture

```text
             Android Application
                     ↓
          Activities / Controllers
                     ↓
             Adapters + Logic
                     ↓
                  Models
                     ↓
                 SQLite
                     ↓
          Local Application Data
```

<p>
  <a href="https://github.com/sunilt808/BookSwap">
    <img src="https://img.shields.io/badge/Explore%20Repo-181717?style=for-the-badge&logo=github&logoColor=white" alt="Explore Repository">
  </a>
</p>

---

## 📚 Currently Learning

Data Structures and Algorithms · System Design · Scalable Backend Architecture · DevOps & CI/CD · Cloud Deployment · ML-powered Software Systems

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
