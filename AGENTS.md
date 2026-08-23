# 🤖 AGENTS.md — Developer Profile & System Context

This file serves as the system memory and context for AI coding assistants working with **Shivansh Mishra**.

---

## 👤 Developer Profile & Vision

- **Name:** Shivansh Mishra
- **Location:** Lucknow, India
- **Education:** B.Tech CSE (Cloud Computing & Machine Learning) @ BBD University (3rd Year)
- **Target Role:** Backend / AI Engineering Internship (India or Remote)
- **Portfolio:** [resume-webpage-ashy.vercel.app](https://resume-webpage-ashy.vercel.app/)
- **LinkedIn:** [linkedin.com/in/shivansh-mishra-132b97358](https://www.linkedin.com/in/shivansh-mishra-132b97358/)
- **Contact:** tgsmishra@gmail.com

### Core Engineering Philosophy
> *"No vibe-coding. No shortcuts. Every line committed must be explainable and written to survive a senior engineer's code review."*

- Shifted from passive tutorial-following to building production systems from scratch.
- Prioritizes deep foundational understanding over framework chasing.
- All code must include proper type hints, clean modular structure, custom exceptions, and test assertions.

---

## 🛠️ Tech Stack & Working State

| Category | Primary Stack | Verification Status |
|:---|:---|:---:|
| **Language** | Python 3.11+ | ✅ 85% Core Mastered |
| **Data & Files** | `pathlib`, JSON, CSV, Context Managers | ✅ 70% Mastered |
| **Relational DB** | SQL (SQLite, PostgreSQL), JOINs | 🔄 30% Active Learning |
| **API Framework** | FastAPI + Pydantic v2 | 🔄 5% Initial Setup |
| **ORM & Migrations**| SQLAlchemy (Async), Alembic | 🔄 5% Initial Setup |
| **Vector DB / RAG** | ChromaDB, Text Embeddings | ⏳ Planned |
| **AI Integration** | Google Gemini API (Structured Outputs) | ⏳ Planned |
| **DevOps** | Git/GitHub, Docker, GitHub Actions | 🔄 CI Workflows Configured |

---

## 🚀 Active Flagship Project: AI Resume Analyzer

A production-grade, full-stack AI system analyzing resume PDFs against job requirements with structured gap analysis.

```
[ User PDF Upload ] ──► [ FastAPI Backend ] ──► [ Pydantic v2 Validation ]
                              │            │
                              ▼            ▼
                   [ PostgreSQL + Alembic ]   [ Gemini API (Scoring & JSON Output) ]
                                                   │
                                                   ▼
                                           [ ChromaDB (RAG Matching) ]
```

### Key Modules & Requirements
1. **FastAPI Backend:** JWT Authentication, OAuth2 Password Flow, rate limiting.
2. **Database:** Async PostgreSQL with SQLAlchemy & Alembic migrations.
3. **AI Engine:** Structured output parsing via Google Gemini API.
4. **Vector Search:** Semantic gap matching using ChromaDB embeddings.
5. **Testing & Deployment:** `pytest` + `httpx`, Dockerized container, GitHub Actions CI.

---

## 🧭 Instructions for AI Agents & Pair Programmers

1. **Do Not Hallucinate Progress:** Keep skill mastery levels strictly grounded in verifiable code from `Python-Learning-Journey`.
2. **Encourage First-Principles Coding:** Avoid generating boilerplate without explaining the underlying mechanism.
3. **Enforce Type Hints:** Use explicit typing (`Optional`, `Union`, `Callable`, `Generator`, generics).
4. **Error Handling Standards:** Always use custom exception hierarchies with informative `__str__` representations.
