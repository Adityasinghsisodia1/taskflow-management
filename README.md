# TaskFlow — Agile Project Management Dashboard

TaskFlow is an Agile task and resource management dashboard built with Python and Streamlit. It provides a visual interface for organizing tasks, tracking progress, and reviewing workload distribution.

> **Project note:** This repository is adapted from an existing open-source project. See the original repository in the Credits section for attribution.

## Features

* **Kanban workflow:** Organize tasks into To Do, In Progress, and Done stages.
* **Task management:** Create, update, and remove tasks.
* **Progress analytics:** Visualize task status and project progress.
* **Workload tracking:** Review task assignments and workload distribution.
* **Time tracking:** Record estimated and logged work hours.
* **Persistent storage:** Store task information using SQLite.
* **Interactive dashboard:** Explore project information through visual charts.

## Technology Stack

| Technology     | Purpose                         |
| -------------- | ------------------------------- |
| Python         | Application logic               |
| Streamlit      | Interactive web interface       |
| SQLite         | Database and persistent storage |
| Pandas         | Data manipulation               |
| Plotly Express | Interactive data visualization  |

## Project Structure

```text
taskflow-management/
├── app.py
├── database.py
├── requirements.txt
└── README.md
```

## Getting Started

### Prerequisites

* Python 3.10 or later
* pip

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/Adityasinghsisodia1/taskflow-management.git
   ```

2. Open the project directory:

   ```bash
   cd taskflow-management
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Start the Streamlit application:

   ```bash
   streamlit run app.py
   ```

5. Open the local URL displayed in the terminal.

## Learning Areas

This project provides an example of:

* Building interactive dashboards with Streamlit
* Managing application data with SQLite
* Visualizing project metrics
* Implementing task-management workflows
* Organizing a Python application into separate files

## Credits

This project is adapted from [Harshit-Tiwary/project-tracker](https://github.com/Harshit-Tiwary/project-tracker).

Please review the original repository's licensing and attribution requirements before redistributing or presenting a modified version.

## Disclaimer

The project has not been independently tested as part of this repository update. Installation, dependencies, and application behavior should be verified before describing the application as fully functional.
