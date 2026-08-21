# Agile Project Management & Resource Tracker

A lightweight web application built to streamline task tracking, resource allocation, and team velocity visualizer based on Google Project Management frameworks.

---

## Google Project Management Documentation

### 1. Project Charter
* **Project Name:** Agile Resource & Task Tracker
* **Objective:** Provide visual tracking for engineering teams to eliminate task bottlenecks and track sprint metrics.
* **In-Scope:** Task CRUD operations, Kanban status view, priority tagging, hour logging, workload distribution analytics.
* **Out-of-Scope:** External third-party integrations (Jira/Slack sync) in v1.0.

### 2. User Stories
* **As a** Scrum Master, **I want to** view resource workload allocation **so that** I can identify burnouts and bottlenecks.
* **As a** Developer, **I want to** log work hours and update status **so that** the board reflects live progress.
* **As a** Product Owner, **I want to** view task completion distribution **so that** I can measure release readiness.

### 3. Risk Matrix
| Risk Description | Severity | Likelihood | Mitigation Strategy |
| :--- | :--- | :--- | :--- |
| Resource Over-allocation | High | Medium | Monitor resource distribution chart during daily standups. |
| Database Concurrency (SQLite locks) | Medium | Low | Upgrade database engine to Supabase PostgreSQL for high traffic. |

---

## Tech Stack
* **Language:** Python 3.10+
* **Frontend/UI:** Streamlit, Plotly
* **Backend Data Layer:** SQLite3, Pandas
* **Deployment Platform:** Render

---

## Local Run Instructions

1. **Clone repository:**
   ```bash
   git clone <your-repo-link>
   cd project-tracker