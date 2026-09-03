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

### 🔗 [TraceAcc1](https://github.com/sunilt808/TraceAcc1) — Enterprise AML Operations & Money-Muling Detection Platform

*Graph intelligence meets governed financial investigation.*

TraceAcc Pro is an **AML operations platform** that connects client intake, technical AML analysis, investigation, report governance, and final client delivery through one controlled workflow. Instead of treating fraud detection as an isolated ML problem, the platform separates technical analysis from investigation while maintaining traceability across every handoff.

Clients submit investigation requests and transaction datasets through the Client Portal. Admins review and assign approved requests to **TraceLab**, where graph-based detection, behavioural and temporal analysis, anomaly detection, a 15-pattern suite, and the DC-LCG dual-view GNN generate risk intelligence and technical findings. Suspicious results can then be escalated into **InvoSpace**, where investigators manage cases, evidence, hypotheses, findings, account intelligence, and investigation reports. Admin review completes the workflow by sealing approved reports before they become visible to the client.

### 🔄 End-to-End Governed Workflow

```text
                              TRACEACC PRO
                                   │
                                   ▼
                              ┌─────────┐
                              │ CLIENT  │
                              └────┬────┘
                                   │
                         Request + Dataset
                                   │
                                   ▼
                              ┌─────────┐
                              │  ADMIN  │
                              │ Intake  │
                              └────┬────┘
                                   │
                         Accept / Reject
                         Assign Workspace
                                   │
                 ┌─────────────────┴─────────────────┐
                 ▼                                   ▼
          ┌──────────────┐                    ┌──────────────┐
          │   TRACELAB   │                    │  INVOSPACE   │
          │ AML Analysis │────── Alerts ─────►│ Investigation│
          └──────┬───────┘                    └──────┬───────┘
                 │                                   │
                 │                                   │
                 ▼                                   ▼
          Detection Engine                     Case Management
          Risk Intelligence                    Evidence
          Technical Findings                   Hypotheses
                                               Findings
                 │                                   │
                 └─────────────────┬─────────────────┘
                                   │
                                   ▼
                         Investigation Report
                                   │
                                   ▼
                              ┌─────────┐
                              │  ADMIN  │
                              │ Review  │
                              └────┬────┘
                                   │
                            SHA-256 Seal
                                   │
                                   ▼
                              FINAL REPORT
                                   │
                                   ▼
                              ┌─────────┐
                              │ CLIENT  │
                              │ Release │
                              └─────────┘
```

### 🧠 Detection & Risk Intelligence

```text
Transaction Dataset
        │
        ▼
Transaction Graph
(NetworkX DiGraph)
        │
        ▼
┌─────────────────────────────────────────┐
│          Detection & Analysis           │
│                                         │
│  Graph Heuristics                       │
│  • Cycle Detection                      │
│  • Fan-In / Fan-Out                    │
│  • Layering Chains                      │
│  • Burst Activity                       │
│                                         │
│  Behavioural / Temporal Signals         │
│  • Account Profiles                     │
│  • Velocity                              │
│  • Temporal Patterns                    │
│  • Community / Centrality / Motifs      │
│                                         │
│  ML Anomaly Detection                   │
│  • Isolation Forest                     │
│  • LOF                                  │
│  • DBSCAN                               │
│                                         │
│  15-Pattern Detection Suite             │
│                                         │
│  DC-LCG Dual-View GNN                   │
└──────────────────────┬──────────────────┘
                       │
                       ▼
                 Hybrid Engine
                   0 – 100
                       │
             ┌─────────┴─────────┐
             ▼                   ▼
           Alerts            Findings /
                              Technical
                               Report
             │                   │
             └─────────┬─────────┘
                       ▼
                   InvoSpace
```

### 🔐 Governance & Traceability

```text
Client Request
      ↓
Admin Acceptance
      ↓
Workspace Assignment
      ↓
TraceLab Analysis
      ↓
Risk Intelligence
      ↓
Alert Escalation
      ↓
InvoSpace Case
      ↓
Investigation
      ↓
Admin Review
      ↓
SHA-256 Report Seal
      ↓
Client Release
```

Every major workflow transition is tracked through the platform's workflow, activity timeline, and audit mechanisms. Technical analysis results are also persisted and connected to reports, alerts, cases, and the investigation workflow.

`Python` · `FastAPI` · `NetworkX` · `scikit-learn` · `PyTorch` · `React` · `Cytoscape.js` · `SQLAlchemy` · `SQLite/PostgreSQL`

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

The system is designed around isolated hospital data and role-specific access, allowing multiple hospitals to operate within the same platform while maintaining separation between their operational data.

### 🏥 Hospital Operations Flow

```text
                              NOQ HOSPITAL
                                   │
                                   ▼
                              ┌─────────┐
                              │ PATIENT │
                              └────┬────┘
                                   │
                         Select Hospital
                                   │
                                   ▼
                         Book Appointment
                                   │
                                   ▼
                           Digital Queue
                                   │
                          Live Token Status
                                   │
                                   ▼
                              ┌─────────┐
                              │ DOCTOR  │
                              └────┬────┘
                                   │
                         Consultation
                                   │
                     ┌─────────────┼─────────────┐
                     ▼             ▼             ▼
                Prescription   Medical Record   Billing
                                   │
                                   ▼
                         ┌────────────────┐
                         │ Hospital       │
                         │ Manager        │
                         └───────┬────────┘
                                 │
                    Hospital Operations
                    Doctors / Patients
                    Appointments / Queue
                                 │
                                 ▼
                         ┌────────────────┐
                         │ System Admin   │
                         │ Platform       │
                         │ Management     │
                         └────────────────┘
```

### ⚙️ Technical Foundation

```text
Patient / Doctor / Manager / Admin
                │
                ▼
        React + Vite Frontend
                │
          JWT + RBAC
                │
                ▼
          FastAPI Backend
                │
                ▼
          MongoDB Atlas
```

Built with a decoupled **React + FastAPI + MongoDB Atlas architecture**, with JWT authentication, role-based access control, and multi-tenant data separation.

`React` · `FastAPI` · `MongoDB Atlas` · `JWT` · `RBAC` · `Vercel` · `Render`

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

### 📡 Placement Intelligence Flow

```text
Placement Sources
      │
      ├── Telegram Messages
      ├── PDFs / DOCX
      ├── Excel Files
      ├── Images / OCR
      └── Google Forms
      │
      ▼
┌───────────────────────┐
│ Ingestion & Historical│
│ Import Pipeline       │
└───────────┬───────────┘
            │
            ▼
     Document / Media
       Extraction
            │
            ▼
      NLP Processing
   spaCy + Regex + Dates
            │
            ▼
    Opportunity Engine
            │
      ┌─────┼─────────────┐
      ▼     ▼             ▼
 Eligibility Dedup      Deadlines
 Matching    + Merge     Tracking
      │     │             │
      └─────┼─────────────┘
            ▼
       MongoDB Atlas
            │
            ▼
       FastAPI Backend
            │
            ▼
      React Dashboard
            │
            ▼
    Telegram Notifications
```

The system follows a **recall-first philosophy**: missing a genuine placement opportunity is treated as more costly than producing an occasional false alert. The core extraction and classification pipeline is designed to operate locally, with optional AI escalation where required.

`FastAPI` · `Telethon` · `spaCy` · `Tesseract OCR` · `MongoDB Atlas` · `React` · `Vercel` · `Render`

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

### ✂️ Salon Operations Flow

```text
                         CUTSLOT
                            │
          ┌─────────────────┼─────────────────┐
          ▼                 ▼                 ▼
   ELITE CLIENT       SKILLED ARTISAN    DIRECTORATE
      (Guest)              (Staff)          (Admin)
          │                 │                 │
          │                 │                 │
     Browse / Book      Receive Assignment   Manage Services
     Services           Floor / Queue        Manage Artisans
     Wallet             Perform Service      Revenue
     Subscription       Update Status         Analytics
     Feedback           Performance           Audit
          │                 │                 │
          └─────────────────┼─────────────────┘
                            │
                            ▼
                    Booking Lifecycle
                            │
                            ▼
                    Service Completion
                            │
                            ▼
                     Wallet / Revenue
                            │
                            ▼
                    Verified Feedback
```

### ⚙️ Technical Foundation

```text
Role-Based React Application
            │
            ▼
      FastAPI Backend
            │
       SQLAlchemy ORM
            │
            ▼
          SQLite
```

The project also includes a production-oriented DevOps workflow:

```text
Code
 ↓
Jenkins Pipeline
 ↓
Docker Build
 ↓
Container
 ↓
Kubernetes
 ↓
Deployment
```

`React 19` · `Vite` · `FastAPI` · `SQLite` · `SQLAlchemy` · `Docker` · `Kubernetes` · `Jenkins` · `Terraform`

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

BookSwap is an **Android-based book exchange platform designed for students to discover, list, borrow, donate, and exchange books within their college community**. It provides a simple digital marketplace for peer-to-peer book sharing while supporting authentication, user roles, and administrative control.

### 📚 Book Exchange Flow

```text
                         BOOKSWAP
                            │
                            ▼
                         USER
                            │
                    JWT Authentication
                            │
              ┌─────────────┴─────────────┐
              ▼                           ▼
        Browse / Search              Add / Manage
           Books                       Books
              │                           │
              └─────────────┬─────────────┘
                            │
                            ▼
                     Exchange Request
                            │
                            ▼
                       Book Owner
                            │
                     Accept / Manage
                            │
                            ▼
                     Book Exchange
                            │
                            ▼
                       Completed
                            │
                            ▼
                         ADMIN
                            │
              ┌─────────────┼─────────────┐
              ▼             ▼             ▼
           Users          Books         Reports
```

### 🏗️ MVC Architecture

```text
                  ┌──────────────┐
                  │     VIEW     │
                  │ XML Screens  │
                  │ RecyclerView │
                  │ Dialogs      │
                  └──────┬───────┘
                         │
                         ▼
                  ┌──────────────┐
                  │  CONTROLLER  │
                  │ Activities   │
                  │ Adapters     │
                  │ Auth Manager │
                  │ Exchange     │
                  │ Logic        │
                  └──────┬───────┘
                         │
                         ▼
                  ┌──────────────┐
                  │    MODEL     │
                  │ User         │
                  │ Book         │
                  │ Exchange     │
                  │ SQLite DB    │
                  └──────────────┘
```

`Android` · `Java` · `XML` · `SQLite` · `JWT` · `MVC` · `Android Studio`

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
