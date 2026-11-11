# 🚀 HighLit — Developer Community Platform

<div align="center">

![Django](https://img.shields.io/badge/Django-5.x-092E20?style=for-the-badge&logo=django&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Ready-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-Channels-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)

**A modern developer community ecosystem designed for collaboration, project sharing, and real-time interaction.**  
*Graduation Project — Faculty of Information Technology.*

</div>

---

## 📌 About HighLit

**HighLit** is a comprehensive community platform built to connect developers, empower them to share student and professional projects, provide a dedicated portal for companies, and offer a smart filtering system for easy content and opportunity discovery. The project is engineered with production-ready best practices, robust security, and high performance.

---

## 🏗️ Tech Stack

| Layer | Technology | Description |
| :--- | :--- | :--- |
| **Backend API** | ![Django](https://img.shields.io/badge/-Django%20REST-092E20?logo=django&logoColor=white) + **Channels** | Core business logic, database management, and real-time WebSocket communication. |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white) | Primary relational database for development and production. |
| **Frontend** | ![Next.js](https://img.shields.io/badge/-Next.js%2014-black?logo=next.js&logoColor=white) + Tailwind CSS | High-performance, SEO-friendly, and responsive user interface. |
| **Admin Dashboard** | React + Vite | Separate administrative panel for managing platform content and users. |
| **API Documentation** | Swagger / OpenAPI | Interactive API endpoints documentation (available via backend). |

---

## 👥 The Team

| Name | Role / Focus |
| :--- | :--- |
| **Ahmad Abu-Mehsen** | Backend Developer (Django) & QA/QC |
| **Mohammed Qadan** | Team Lead & Backend Engineer (Django) |
| **Ahmad Al-Hamad** | Backend Developer (Django) |
| **Mostafa** | Admin Dashboard Developer (React / Vite) |
| **Fahmi** | Admin Dashboard Developer (React / Vite) |
| **Amjad Al-Zoubi** | Frontend & Quality Assurance |

---

## 📂 Repository Structure

```text
HighLit/
├── backend/            # Django REST API & WebSockets (Port: 8000)
├── frontend/           # Next.js User Interface (Port: 3000)
├── admin-dashboard/    # React + Vite Admin Panel
├── docs/               # Technical documentation, API contracts, and runbooks
├── .github/workflows/  # CI/CD automated workflows
├── .gitignore          # Strict ignore rules for secrets and virtual environments
└── README.md           # Project documentation