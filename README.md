# Backend .NET Developer Training Roadmap — Advanced C# to API

> **6 Sprints · 68 Days**

## Overview

| Sprint | Topic | Project / Milestone | Days | Duration |
|:------:|-------|---------------------|:----:|:--------:|
| 1 | Advanced C# + Exception Handling | Job Application Tracker (Console) | 1–14 | 14 days |
| 2 | LINQ | Sales Data Analytics Dashboard (Console) | 15–28 | 14 days |
| 3 | Entity Framework Core | Library Management System (EF Core) | 29–42 | 14 days |
| 4 | Web API Foundation — Setup, Domain & Data Access | E-Commerce API — Milestone 1: Foundation | 43–52 | 10 days |
| 5 | Web API Core — Products, Errors, Logging & Caching | E-Commerce API — Milestone 2: Products & Basket | 53–59 | 7 days |
| 6 | Security & Orders | E-Commerce API — Milestone 3: Auth & Orders (Final) | 60–68 | 9 days |

---

## Sprint 1 — Advanced C# + Exception Handling

**Day 1–14 · 14 Days**

### Core Topics

- [ ] Collections — `List`, `Dictionary`, `Queue`, `Stack`, `HashSet`
- [ ] Generics (Classes, Methods, Constraints)
- [ ] Delegates (`Func`, `Action`, `Predicate`)
- [ ] Events + Event Handlers
- [ ] Lambda Expressions + Anonymous Methods
- [ ] Async/Await (Concepts, Task, Patterns)
- [ ] File Handling (Streams, Read/Write)
- [ ] Exception Handling
  - **Easy:** `try/catch/finally` & `TryParse`
  - **Medium:** Custom exceptions
  - **Hard:** Exception filters (`when`) & `throw` vs `throw ex`
  - `using` / `IDisposable`
  - `AggregateException`

### 🎯 Sprint Project

**Job Application Tracker (Console)**

---

## Sprint 2 — LINQ

**Day 15–28 · 14 Days**

### Core Topics

- [ ] **Execution Concepts** — Deferred vs Immediate, Method vs Query Syntax, `IEnumerable` vs `IQueryable`
- [ ] **Filtering** — `Where`
- [ ] **Projection** — `Select`, `SelectMany`
- [ ] **Ordering** — `OrderBy`, `ThenBy`, `Reverse`
- [ ] **Paging / Partitioning** — `Skip`, `Take`
- [ ] **Grouping** — `GroupBy`
- [ ] **Joining** — `Join`, `GroupJoin`
- [ ] **Aggregation** — `Sum`, `Count`, `Average`, `Min`, `Max`
- [ ] **Quantifiers** — `Any`, `All`, `Contains`
- [ ] **Element Operators** — `First`, `FirstOrDefault`, `Single`, `SingleOrDefault`
- [ ] **Set Operations** — `Distinct`, `Union`, `Intersect`, `Except`

### 🎯 Sprint Project

**Sales Data Analytics Dashboard (Console)**

---

## Sprint 3 — Entity Framework Core

**Day 29–42 · 14 Days**

### Core Topics

- [ ] **Setup** — `DbContext` + Entities, Code First + Migrations
- [ ] **Modeling**
  - Relationships (One-to-Many, Many-to-Many)
  - Fluent API (`MaxLength`, `Precision`)
  - Enums as label
  - Owned Entities
- [ ] **Data** — Data Seeding, CRUD Operations
- [ ] **Patterns** — Repository Pattern Basics *(Unit of Work is covered in Sprint 4)*
- [ ] **Loading** — Eager Loading (`Include` / `ThenInclude`); Explicit Loading *(bonus)*
- [ ] **Performance & Transactions**
  - `AsNoTracking`
  - `IEnumerable` vs `IQueryable`
  - Transactions (Commit / Rollback)

### 🎯 Sprint Project

**Library Management System (EF Core)**

---

## Sprint 4 — Web API Foundation: Setup, Domain & Data Access

**Day 43–52 · 10 Days · Modules 1–3**

| Module | Title | Days | Duration |
|:------:|-------|:----:|:--------:|
| 1 | Setup, HTTP & Routing | 43–44 | 2 days |
| 2 | Domain & Data Layer | 45–48 | 4 days |
| 3 | Repository, UoW & Specification | 49–52 | 4 days |

### Module 1 — Setup, HTTP & Routing *(Day 43–44)*

- [ ] HTTP Fundamentals (Methods, Status Codes)
- [ ] Routing (Conventional vs Attribute) + Middleware
- [ ] Onion / Clean Architecture (4 projects) + Swagger

### Module 2 — Domain & Data Layer *(Day 45–48)*

- [ ] Entities + `DbContext`, Fluent API
- [ ] Code First Migrations + Seeding
- [ ] DI Lifetimes + Async/Await Deep Dive

### Module 3 — Repository, UoW & Specification *(Day 49–52)*

- [ ] Repository Pattern + Unit of Work
- [ ] Specification Pattern + Result Pattern
- [ ] `AsNoTracking` for read paths

### 🎯 Milestone

**E-Commerce API — Clean Architecture solution up and running with the data layer in place**

---

## Sprint 5 — Web API Core: Products, Errors, Logging & Caching

**Day 53–59 · 7 Days · Modules 4–6**

| Module | Title | Days | Duration |
|:------:|-------|:----:|:--------:|
| 4 | Products API | 53–55 | 3 days |
| 5 | Error Handling & Logging | 56–57 | 2 days |
| 6 | Basket & Redis Caching | 58–59 | 2 days |

### Module 4 — Products API *(Day 53–55)*

- [ ] DTOs + AutoMapper
- [ ] Controllers + Action Results
- [ ] Filtering, Search, Sorting, Paging

### Module 5 — Error Handling & Logging *(Day 56–57)*

- [ ] Result / Error pattern + Exception Middleware
- [ ] Validation (Data Annotations / FluentValidation)
- [ ] Logging (Built-in + Serilog)

### Module 6 — Basket & Redis Caching *(Day 58–59)*

- [ ] Redis — Basket Storage
- [ ] Action Filters vs Middleware
- [ ] Response Caching (`[RedisCache]` attribute)

### 🎯 Milestone

**E-Commerce API — Products endpoints, centralized error handling, logging, and Redis-backed basket**

---

## Sprint 6 — Security & Orders

**Day 60–68 · 9 Days · Modules 7–8**

| Module | Title | Days | Duration |
|:------:|-------|:----:|:--------:|
| 7 | Authentication & Authorization | 60–63 | 4 days |
| 8 | Orders | 64–68 | 5 days |

### Module 7 — Authentication & Authorization *(Day 60–63)*

- [ ] JWT Authentication (ASP.NET Identity)
- [ ] Authorization (Roles, Policies)

### Module 8 — Orders *(Day 64–68)*

- [ ] Order domain + specifications

### 🎯 Final Project

**E-Commerce API — Clean Architecture (complete)**
