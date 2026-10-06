# SAIF

### `.NET Backend Developer`

Building backend systems with a focus on **architecture · data · authorization · maintainability**

---

## `01` — ENGINEERING PROFILE

I am a software developer focused on **.NET backend engineering**.

My work revolves around building APIs and backend systems where **data integrity, authorization, architecture and business rules** matter as much as the code itself.

I prefer going deeper into a smaller technology stack rather than collecting technologies without connecting them.

### CURRENTLY

```text
ROLE
.NET Backend Developer

FOCUS
Backend Engineering
Database Design
Authorization
Architecture

PRIMARY SYSTEM
UniNet
```

---

## `02` — CORE STACK

### Backend
`C#` · `.NET` · `ASP.NET Core` · `Web API` · `REST` · `Dependency Injection` · `Async / Await`

### Data
`EF Core` · `SQL Server` · `T-SQL` · `LINQ` · `Fluent API` · `Migrations` · `Database Design`

### Engineering
`JWT` · `Claims` · `Authorization` · `FluentValidation` · `Repository` · `Unit of Work` · `GitHub Actions`

---

# `03` — FEATURED SYSTEM

<div align="center">

## 🟣 UniNet

### University Social & Academic Platform

*A backend-focused university system built around organizational hierarchy, academic data, authentication and resource-level authorization.*

</div>

### SYSTEM OVERVIEW

UniNet is the main system I am currently developing.

The architecture is divided into multiple projects with explicit dependency boundaries rather than relying only on folder organization.

The system includes concepts such as:

- Universities
- Colleges
- Departments
- Batches
- Students
- Employees
- Users & Roles
- Academic data
- Content
- Resource-level authorization

### SYSTEM

```text
STATUS
◉ Active Development

API
ASP.NET Core

DATABASE
SQL Server

ORM
EF Core

AUTH
JWT

AUTHORIZATION
Claims + Scope

CI
GitHub Actions
```

### Architecture

```text
                         ┌──────────────────┐
                         │     UniNet API   │
                         └────────┬─────────┘
                                  │
                 ┌────────────────┼────────────────┐
                 │                │                │
                 ▼                ▼                ▼
          ┌────────────┐   ┌────────────┐   ┌────────────┐
          │ Application│   │ Contracts  │   │   Domain   │
          └──────┬─────┘   └────────────┘   └──────┬─────┘
                 │                                  │
                 └────────────────┬─────────────────┘
                                  ▼
                         ┌──────────────────┐
                         │ Data Access Layer│
                         └────────┬─────────┘
                                  │
                                  ▼
                           ┌──────────────┐
                           │ SQL Server   │
                           └──────────────┘
```

### Engineering Highlights

| Area | Implementation |
|:---|:---|
| Authentication | JWT Bearer |
| Token Security | Refresh Token Rotation + SHA-256 at rest |
| Authorization | Claims-based scope + resource-based authorization |
| Data Access | EF Core + Fluent API |
| Querying | Projection + Expression Trees |
| Performance | `AsNoTracking` + explicit projections |
| Database | Composite / filtered indexes |
| Integrity | Computed columns + restrictive delete behavior |
| Validation | FluentValidation |
| CI | GitHub Actions |
| Build Discipline | `TreatWarningsAsErrors` |

<details>
<summary><b>▸ Why UniNet?</b></summary>

UniNet is intended to be more than a CRUD demonstration.

The system is used as a practical environment for exploring:

- backend architecture
- authorization boundaries
- database constraints
- domain behavior
- multi-tenant scope
- maintainability
- CI and engineering discipline

</details>

---

# `04` — ENGINEERING JOURNEY

```text
2025
 │
 │   DVLD
 │   └── Programming & Database Foundations
 │
 ▼
2026
 │
 │   WinSmartShope
 │   └── Desktop Architecture
 │       EF Core · SQL Server
 │
 ▼
 │
 │   BarshaiedAPI
 │   └── ASP.NET Core
 │       REST · JWT · Refresh Tokens
 │
 ▼
 │
 │   UniNet
 │   └── Backend System Engineering
 │       Architecture · Authorization
 │       Database Design · CI
 │
 ▼
NOW
```

| Project | Main Focus |
|:---|:---|
| **UniNet** | System architecture and backend engineering |
| **BarshaiedAPI** | ASP.NET Core backend development |
| **WinSmartShope** | Application architecture and data access |
| **DVLD** | Programming and database foundations |

---

# `05` — ENGINEERING INTERESTS

### `DATABASE`

I enjoy understanding how application logic and database constraints work together.

`EF Core` · `Query behavior` · `Indexing` · `Projections` · `SQL Server` · `Data integrity` · `Migrations`

### `AUTHORIZATION`

I am particularly interested in authorization as a system boundary, not simply as an attribute placed on controllers.

`JWT` · `Claims` · `Scope` · `Resource authorization` · `Hierarchical access` · `Refresh tokens`

### `ARCHITECTURE`

Architecture should solve an actual problem.

`Dependency boundaries` · `Separation of concerns` · `Domain behavior` · `Maintainability` · `Explicit business rules`

### `ENGINEERING`

Beyond writing features:

`Git workflows` · `CI` · `Build discipline` · `Documentation` · `Code review` · `Failure modes`

---

# `06` — HOW I THINK ABOUT SOFTWARE

<div align="center">

```text
       ┌───────────────────────┐
       │      REQUIREMENT      │
       └───────────┬───────────┘
                   │
                   ▼
       ┌───────────────────────┐
       │       DESIGN          │
       │ boundaries · data     │
       │ authorization         │
       └───────────┬───────────┘
                   │
                   ▼
       ┌───────────────────────┐
       │      IMPLEMENT        │
       └───────────┬───────────┘
                   │
                   ▼
       ┌───────────────────────┐
       │       VERIFY          │
       │ build · runtime · data│
       └───────────┬───────────┘
                   │
                   ▼
       ┌───────────────────────┐
       │       IMPROVE         │
       └───────────────────────┘
```

### `Understand → Design → Build → Verify → Improve`

</div>

---

# `07` — CURRENT FOCUS

```text
BACKEND
├── ASP.NET Core
├── API Design
├── Authentication
└── Authorization

DATABASE
├── SQL Server
├── EF Core
├── Query Behavior
└── Performance

ENGINEERING
├── System Design
├── Testing
├── Docker
└── Production Practices
```

---

# `08` — SELECTED WORK

| Project | Description | Stack |
|:---|:---|:---|
| 🟣 **UniNet** | University platform / Main Project | C# · ASP.NET Core · EF Core · SQL Server |
| 🔵 **BarshaiedAPI** | Inventory / POS API | C# · ASP.NET Core · EF Core · JWT |
| 🟢 **WinSmartShope** | Desktop application | C# · EF Core · SQL Server |
| ⚪ **DVLD** | Learning project / foundations | C# · SQL Server |

---

# `09` — PRINCIPLES

<div align="center">

### `DEPTH > BREADTH`

I would rather understand a smaller stack deeply than collect technologies without understanding their relationships.

### `MECHANISM > ABSTRACTION`

Before adding another abstraction, understand the mechanism underneath it.

### `SIMPLE > OVERENGINEERED`

Architecture should match the problem.

### `VERIFY > ASSUME`

A system is not finished because the code compiles.

</div>

---

# `10` — CONNECT

<div align="center">

<a href="https://github.com/saifwindow85-rgb">
<img src="https://img.shields.io/badge/GitHub-18181B?style=for-the-badge&logo=github&logoColor=white" />
</a>

&nbsp;

<!-- Replace # with your LinkedIn profile URL -->
<a href="#">
<img src="https://img.shields.io/badge/LinkedIn-18181B?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<br><br>

`C#` · `.NET` · `ASP.NET Core` · `EF Core` · `SQL Server`

<br>

<sub>Building systems · studying the mechanisms · improving one layer at a time.</sub>

</div>
