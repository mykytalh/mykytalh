# Hi, I’m Mykyta 👋

Software engineer focused on backend + full-stack systems (auth, data flows, storage, deployment).

- 🎓 Informatics + Data Science @ UW
- 🧩 Mostly building production systems: authentication, multi-tenant data separation, ingestion flows
- 🛠️ Current stack: FastAPI, Postgres, AWS, React/Next.js, TypeScript
- 📫 Reach me: mykyta@ethosphere.ai | LinkedIn: [Mykyta Lepikash](https://www.linkedin.com/in/mykytlh/])

---

## What I do (recent)

### Ethosphere — Software Engineer
I work on backend + full-stack systems used in production and live demos.

**Concrete stuff I shipped / owned:**
- Admin UI system end-to-end: core features, backend endpoints, auth, DB flows, CI/CD checks
- Microphone login/auth: registration + session handling + improved request flow
- Multi-tenant storage + client separation (data stays in the right tenant)
- Extended system into NRF Manager + Associate UI (full-stack integration)
- Bootstrapped deployments: infra via AWS CDK + frontend on Vercel

**What mattered (results):**
- Reliable end-to-end system: auth + sessions + data integrity stayed consistent
- Stable enough for repeated demo usage (NRF) and continued iteration
- Extensible patterns so we’re not rewriting everything per client

---

## Projects (personal / school)

Husky-Connect

Type: Personal / School Project
Status: Completed
URL(s):

Live app: not applicable, it was taken due to maintability costs 

Source code: 
- frontend https://github.com/mykytalh/husky-connect
- backend https://github.com/mykytalh/husky-connect-backend

Project Overview

Husky-Connect is a student networking application that connects users based on shared majors and classes, with a strict onboarding flow that enforces complete profile data before access is granted.

Goals

Ensure every user completes their profile before using the app

Maintain clean, consistent user data

Build a scalable foundation for student matching features

My Role

I was the sole developer and built the project end-to-end:

Frontend with Next.js

Firebase authentication and session handling

Gated onboarding and protected routes

Firestore data model and access logic

Problem / Opportunity

Many student platforms allow users to enter with incomplete profiles, leading to poor matching and unreliable data. This project enforces profile completeness as a system-level requirement.

Process & Solution

Implemented Firebase Auth for secure login

Built a mandatory profile setup flow after first sign-in

Blocked access to the main app until profile completion

Designed Firestore schemas to separate auth data from profile data

Outcome

Fully functional gated onboarding system

All users have validated, complete profiles

Stable auth, routing, and data flows

Takeaways

Designing auth-driven access control

Enforcing data integrity beyond the UI

Building clean onboarding flows as part of the core system
---

## Skills

**Languages:** Python, TypeScript/JavaScript, SQL  
**Backend:** FastAPI, REST APIs, auth/session flows, async processing  
**Data:** PostgreSQL, Firestore, multi-tenant modeling  
**Cloud/Infra:** AWS (S3/IAM/CDK), CI/CD, Vercel  
**Frontend:** React, Next.js (mostly admin/internal tooling)

