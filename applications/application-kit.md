# Application Kit — Mamoon Khan

Ready-to-paste answers and cover letters for the job applications in `job-search-plan.md`.
Everything here comes from the resume (`resume/Mamon Khan SE Resume.pdf`) and the plan's reference details. Nothing is made up. Leave any field these don't cover (e.g. CNIC) for the user to fill in.

## Standard form answers

| Field | Answer |
|---|---|
| Full name | Mamoon Khan |
| Email | mamoonofficial01@gmail.com |
| Phone | +92-311-6993072 |
| LinkedIn | linkedin.com/in/mamoon-khan |
| GitHub | github.com/Moon-Khan |
| Current location | Lahore, Pakistan |
| Current employer / title | CodingCops — Software Engineer (Dec 2024 – Present) |
| Total experience | 2 years (incl. Support Engineer at Agrilift, intern at TenX) |
| Education | BS Computer Science, FAST-NUCES |
| CGPA (only if asked) | 2.47 |
| Notice period | 1 month |
| Current salary | PKR 170,000/month |
| Expected salary (Pakistan) | PKR 250,000/month (negotiable upward) |
| Expected salary (UK/US) | Market rate for the role; for UK sponsored roles, at least the Skilled Worker floor (£38,700) or the role's going rate |
| Shift flexibility | Yes, comfortable with evening shifts (e.g. 1:00 PM–10:00 PM PKT) |
| Visa (UK/US onsite) | Will require visa sponsorship |
| Visa (remote) | No sponsorship needed; can work as a remote employee or contractor from Pakistan |
| CNIC | Not stored here; user supplies it |

## Short self-ratings (for skill questionnaires)

Base these on what the resume shows. Don't inflate them.
- Strong: React, TypeScript/JavaScript, Node.js, Express, NestJS, REST APIs, PostgreSQL, MongoDB, JWT/RBAC
- Solid: ASP.NET Core, C#, EF Core, SQL Server, GraphQL (Federation), Redis, Docker, GitHub Actions
- Working knowledge: Next.js, AWS EC2, Microservices, Socket.IO

## Common screening answers

**Why are you looking for a change?**
I've spent two years shipping full-stack features end-to-end at CodingCops and want a role with a larger product scope, stronger engineering practices, and more ownership of backend architecture and security.

**Describe a challenging backend problem you solved.**
On the BBB Smart System, I load-tested a NestJS/GraphQL Federation dispatcher service at 19,000+ requests (35 concurrent users) and found a reporting endpoint pushing database CPU to 98%. I fixed it by adding targeted indexes, rewriting N+1 queries as joins, and adding connection pooling with query and statement timeouts. The service then held a 0.02% error rate.

**Experience with authentication/security?**
I've implemented JWT auth with refresh-token rotation and reuse detection (a replayed token revokes its whole family), RBAC through global guards, PostgreSQL Row-Level Security for tenant isolation, and per-tenant Redis rate limiting with atomic Lua scripts. On MyValueApp I also built SSO and subscription billing with GoHighLevel.

**Testing / CI experience?**
I wrote 32 Jest unit tests and 23 Supertest e2e tests against real Postgres/Redis containers, run in GitHub Actions (lint, build, test). I added 12 automated test suites to a ~35K-line production codebase.

## Cover letters

### A. Node.js / MERN / NestJS roles

> Dear Hiring Team,
>
> I'm applying for the {ROLE} position at {COMPANY}. I'm a full-stack engineer with two years of production experience in React, TypeScript, Node.js, Express and NestJS, currently at CodingCops in Lahore, where I own features from idea to production.
>
> Recent work that matches your stack:
> - Built a multi-tenant NestJS + PostgreSQL backend with Row-Level Security, JWT refresh-token rotation with reuse detection, RBAC, and per-tenant Redis rate limiting, covered by 55 unit/e2e tests in GitHub Actions CI.
> - Architected a NestJS GraphQL Federation microservice, load-tested it at 19,000+ requests with a 0.02% error rate, and fixed a 98% DB-CPU hotspot through indexing, join rewrites and connection pooling.
> - Built the backend for a real-time chat app (Express, MongoDB, Socket.IO), deployed on Vercel.
>
> {ONE SENTENCE ON WHY THIS COMPANY/PRODUCT.}
>
> My resume is attached. I'd welcome the chance to talk.
>
> Best regards,
> Mamoon Khan
> mamoonofficial01@gmail.com · +92-311-6993072 · linkedin.com/in/mamoon-khan · github.com/Moon-Khan

### B. .NET + React roles

> Dear Hiring Team,
>
> I'm applying for the {ROLE} position at {COMPANY}. I'm a full-stack engineer with two years of experience building React frontends with ASP.NET Core and Node.js backends, currently at CodingCops in Lahore.
>
> On the MyValueApp platform (React + Node.js + ASP.NET Core 8), I owned 24 API modules end-to-end, built subscription billing and SSO integration from scratch, resolved 98+ production bugs, and added 12 automated test suites to keep a ~35K-line codebase stable through weekly releases. I also optimise SQL Server and PostgreSQL queries, indexes and connection pooling for APIs under concurrent load, and I'm comfortable with EF Core, LINQ, Clean Architecture and CQRS.
>
> {ONE SENTENCE ON WHY THIS COMPANY/PRODUCT.}
>
> My resume is attached. Thank you for your consideration.
>
> Best regards,
> Mamoon Khan

### C. International remote / UK / US roles

> Hi {NAME / Hiring Team},
>
> I'm a full-stack engineer (React, TypeScript, Node.js/NestJS, PostgreSQL; plus ASP.NET Core) based in Lahore, applying for {ROLE}. I've spent two years shipping production features for international clients and I'm comfortable working overlapping hours (up to 10 PM PKT, which covers UK afternoons and US East Coast mornings).
>
> Highlights: a multi-tenant SaaS backend with Postgres RLS, refresh-token rotation and Redis rate limiting; a GraphQL Federation microservice load-tested at 19K+ requests with a 0.02% error rate; and 24 API modules owned end-to-end on a React/Node/.NET product.
>
> {FOR ONSITE: I would require visa sponsorship. / FOR REMOTE: I can start as a remote employee or contractor, with no sponsorship needed.}
>
> Resume attached. Happy to do a technical screen at your convenience.
>
> Mamoon Khan
