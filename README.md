# Agile Project Management & Resource Tracker

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com)

An end-to-end, lightweight Agile task management and resource distribution dashboard built to eliminate engineering bottlenecks, track team velocity, and streamline sprint operations based on Google Project Management principles.

---

## Key Features

* Dynamic Kanban Board: Interactive task management separated into To Do, In Progress, and Done stages.
* Real-time Agile Analytics: Visual charts tracking task status distribution, estimated vs. logged hours, and completed sprint metrics.
* Resource Bottleneck Identification: Workload breakdown per developer/assignee to prevent burnout and uneven task allocation.
* Full Task CRUD Lifecycle: Easily add, edit status, log additional hours, or remove tasks on the fly.
* Persistent Storage: Built-in lightweight SQLite database engine with zero external configuration needed.

---

## Project Management Framework Documentation

### 1. Project Charter
* Project Name: Agile Resource & Task Tracker
* Project Sponsor: Engineering Operations Team
* Objective: Provide visual progress tracking and resource allocation metrics to reduce sprint blockers by 30%.
* In-Scope: Task creation, priority management, Kanban board, hour logging, workload analytics, deployment setup.
* Out-of-Scope: Third-party OAuth authentication, Slack/Jira webhook integration (Planned for v2.0).

### 2. User Stories
* As a Scrum Master, I want to view resource workload distribution so that I can identify burnouts and team bottlenecks early in the sprint.
* As a Developer, I want to log my work hours and change task states so that the team board reflects real-time progress.
* As a Product Owner, I want a high-level summary of total vs completed tasks so that I can measure release readiness and team velocity.

### 3. Risk Matrix
| Risk Event | Impact | Severity | Likelihood | Mitigation Strategy |
| :--- | :--- | :--- | :--- | :--- |
| Resource Over-allocation | High | High | Medium | Review workload bar charts during daily standups. |
| SQLite Database Lockouts | Medium | Low | Low | Migrate database layer to Supabase PostgreSQL for enterprise scale. |
| Data Loss on Server Restart | High | Medium | Low | Persistent volume storage mounting or cloud database integration. |

---

## System Architecture & Tech Stack

* Frontend Framework: Streamlit (Custom Web UI)
* Data Manipulation & Visualization: Pandas, Plotly Express
* Database Engine: SQLite3
* Language & Runtime: Python 3.10+
* Deployment Platform: Streamlit Community Cloud / Render

---

## Quickstart Guide (Local Setup)

### 1. Clone the Repository
git clone https://github.com/Harshit-Tiwary/project-tracker.git
cd project-tracker

### 2. Install Dependencies & Run
pip install -r requirements.txt
streamlit run app.py

---

## Cloud Deployment

This repository is pre-configured for one-click deployment on Streamlit Community Cloud:
1. Fork or push this repository to GitHub.
2. Log in to share.streamlit.io.
3. Select your repository, set main as the branch, and app.py as the main file path.
4. Click Deploy.

---

## Author
Developed as an Agile Engineering Portfolio Project demonstrating full-stack Python development, analytics integration, and Google PM principles.