# Hi 👋 I'm Cimar Rodrigo

**Backend Developer** — I work mainly in **Go** and **Java**, and I'm comfortable taking a product across the full stack when it needs it.
Currently at **Banco Bisa S.A.** (La Paz, Bolivia), building backend services and internal applications for a production banking environment.

<img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExemVheWN3ejRhbzcxMTltOGJld29ydHdkcnBwMXdwb25lc2NpeHRvdiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/JqmupuTVZYaQX5s094/giphy.gif" width="400" alt="coding" />

---

### What I'm about

I care more about the shape of a problem than the syntax of the solution. Most of my work lives where correctness matters — payments, academic records, financial data — so I lean on clear boundaries, hexagonal architecture, and tests that actually fail when something breaks.

Right now I'm going deep on **Go**: concurrency, type internals, and designing services that stay readable as they grow.

---

### Tech Stack

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)

**Backend**

![Gin](https://img.shields.io/badge/Gin-008ECF?style=for-the-badge&logo=gin&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

**Frontend**

![Vue](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white)

---

### Featured

#### [plataforma-academica](https://github.com/CimarRodrigo/plataforma-academica) · `Vue` `Spring Boot` `Java`

My undergraduate thesis project — and the one I'm proudest of, because it actually shipped. It's a study-material sharing platform, built for and deployed at the Faculty of Humanities and Education Sciences at UMSA, where it runs on their intranet.

Students upload and share course material, comment on it, and vote it up or down. Weekly and global leaderboards surface whoever contributed the material people found most useful. Every user gets a profile listing their uploads, filterable by votes or date.

Where it got interesting was moderation. Anyone can report material or comments, which routes them into a review queue for users with the moderator role, who validate or block content that breaks the rules. Designing that meant thinking carefully about role-based access, content state transitions, and what happens to a ranking when a top-voted upload gets pulled.

Authentication runs on **Google OAuth2**, so students and staff sign in with the accounts they already have instead of one more password to forget. Spring Boot REST API on the backend, Vue on the front end.

Going from a thesis defense to something a faculty actually uses meant dealing with the unglamorous parts — real accounts, real uploads, real people telling me when something broke. I'd take that trade every time.

---

### Currently Building

**[go-finish-line-api](https://github.com/CimarRodrigo/go-finish-line-api)** · `Go` `Gin` `PostgreSQL`
Backend for a race registration platform: QR payment gateway integration with atomic transaction handling, and an OpenAPI-documented REST API.

**[go-payment-management-api](https://github.com/CimarRodrigo/go-payment-management-api)** · `Go` `Gin` `PostgreSQL`
Payment management API for residential building administration — income and expenses, co-owner dues, and outstanding debt tracking. Hexagonal architecture with DDD Lite and CQRS: domain entities and output ports at the core, GORM persistence models mapped at the edge, Gin handlers on top.

---

### Professional Work

Most of what I build day to day lives in private repositories, so here's the short version:

- **Internal banking application** — full-stack: **.NET** REST API on the backend, **Angular** on the front end, **Oracle** for persistence. Took it from requirements to production.
- **Internal automation services** — .NET and Java services that take manual, error-prone operational processes and turn them into something repeatable and auditable.

Happy to walk through architecture and decisions in a conversation.

---

### Also here

**[Aux-111](https://github.com/CimarRodrigo/Aux-111)** · `Java` — Teaching material I wrote as a TA for Intro to Programming at UMSA: fundamentals, algorithmic thinking, and clean coding habits for first-semester students.

---

### Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/cimar-rodrigo-morales)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rdo15072001@gmail.com?subject=Backend%20opportunity)

---
