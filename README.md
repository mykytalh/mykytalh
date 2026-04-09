# Hi, I’m Mykyta 👋

Software engineer focused on backend + full-stack systems — especially **auth, data flows, storage, and production infrastructure**.

- 🎓 Informatics + Data Science @ UW  
- 🧩 Building production systems: authentication, multi-tenant data separation, ingestion pipelines  
- 🛠️ Stack: FastAPI, Postgres, AWS, React/Next.js, TypeScript  
- 📫 Reach me: mykyta@ethosphere.ai  
- 🔗 LinkedIn: [Mykyta Lepikash](https://www.linkedin.com/in/mykytlh/)

---

## What I do (recent)

### Ethosphere — Software Engineer

I work on backend + full-stack systems used in **production environments and live demos**.

**What I shipped / owned:**
- Built an **Admin UI system end-to-end** (backend APIs, auth, DB flows, CI/CD checks)
- Implemented **microphone-based login/auth** (registration + session handling + improved request flow)
- Designed **multi-tenant storage and data isolation**
- Extended system into **NRF Manager + Associate UI** (full-stack integration)
- Bootstrapped deployments using **AWS CDK + Vercel**

**Impact:**
- Reliable end-to-end system: **auth, sessions, and data integrity remained consistent**
- Stable for repeated demo usage (NRF) and continued iteration
- Built **extensible patterns** to avoid per-client rewrites

---

## Capstone Project — Automated Peer Reviewer Matching (ITHS)

**Type:** UW Informatics Capstone (Team Project)  
**Status:** In Progress  

### Overview
Building a system that **automatically identifies relevant peer reviewers for research abstracts**.

The system uses an **LLM-driven pipeline + OpenAlex API** to retrieve researchers whose work aligns with a given abstract, reducing manual effort and improving consistency in reviewer selection.

---

### Current System (MVP)

**Pipeline:**
1. User submits a research abstract  
2. LLM (Opus) generates structured search queries  
3. Queries are sent to the OpenAlex API  
4. Relevant researchers are returned  

---

### My Contributions
- Designed and improved the **abstract → query → retrieval pipeline**
- Worked on **LLM prompt engineering** for structured, relevant queries
- Integrated **OpenAlex API** into the workflow
- Improved **result quality and reduced noise**
- Debugged issues with:
  - overly broad queries  
  - inconsistent or irrelevant results  
- Applied backend thinking to ensure:
  - consistent data flow  
  - predictable outputs  
  - extensibility  

---

### Key Challenges
- Translating **unstructured abstracts → effective search queries**
- Handling **noisy and inconsistent external data**
- Balancing:
  - recall (more results)  
  - vs precision (relevant results)  
- Designing beyond “demo-quality” systems  

---

### Next Steps
- Improve **UI for reviewer exploration**
  - Show publications, affiliations, relevance  
  - Enable easier comparison  

- Move logic into a **FastAPI backend**
  - Centralize LLM + OpenAlex pipeline  
  - Improve reliability  

- Add a **PostgreSQL database**
  - Store abstracts, queries, and results  
  - Enable caching and analytics  

- Implement **reviewer ranking/scoring**
  - Relevance, recency, publication signals  

- Deploy to **AWS**
  - Backend (EC2 or containers)  
  - Database (RDS)  
  - Logging/monitoring  

- Build full **production infrastructure**
  - Infrastructure as Code (CDK/Terraform)  
  - CI/CD pipelines  
  - Dev / prod environments  

---

## Projects (personal / school)

### Husky-Connect

**Type:** Personal / School Project  
**Status:** Completed  

**Source code:**
- Frontend: https://github.com/mykytalh/husky-connect  
- Backend: https://github.com/mykytalh/husky-connect-backend  

---

### Overview
Husky-Connect is a student networking application that connects users based on shared majors and classes, with a strict onboarding flow that enforces complete profile data before access.

---

### Goals
- Ensure every user completes their profile before using the app  
- Maintain clean, consistent user data  
- Build a scalable foundation for student matching  

---

### My Role
- Built the project **end-to-end as a solo developer**
- Developed frontend using **Next.js**
- Implemented **Firebase authentication + session handling**
- Built **gated onboarding and protected routes**
- Designed **Firestore data model and access logic**

---

### Problem
Many student platforms allow incomplete profiles, leading to poor matching and unreliable data.

---

### Solution
- Enforced **mandatory profile completion**
- Blocked access until onboarding is finished
- Separated **auth data from profile data**
- Built structured data flows for consistency  

---

### Outcome
- Fully functional onboarding system  
- All users have validated, complete profiles  
- Stable auth, routing, and data flows  

---

### Takeaways
- Designing **auth-driven access control systems**
- Enforcing **data integrity beyond UI constraints**
- Building onboarding as a **core system feature**

---

## Skills

**Languages:** Python, TypeScript/JavaScript, SQL  
**Backend:** FastAPI, REST APIs, auth/session flows, async processing  
**Data:** PostgreSQL, Firestore, multi-tenant modeling  
**Cloud/Infra:** AWS (S3/IAM/CDK), CI/CD, Vercel  
**Frontend:** React, Next.js (mostly admin/internal tooling)
