# SQL Query Optimizer Assistant ⚡

**AI-powered SQL tuning tool** that analyzes query performance, suggests optimizations, and ensures compatibility with modern database features using Baseline data.

![SQL Optimizer Demo](docs/screenshot1.png)

---

## 📋 Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Built With](#built-with)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## 📖 About the Project

Manual SQL tuning is slow, inconsistent, and often opaque. Developers waste hours reading execution plans, guessing at indexing strategies, and rewriting joins.

**SQL Query Optimizer Assistant** solves this by:
- Automating query analysis and optimization.
- Providing **explainable AI suggestions** developers can trust.
- Integrating **Baseline web feature data** to ensure forward-compatible syntax.

---

## ✨ Features
- Accepts raw SQL queries via UI or CLI.
- Parses execution plans and detects inefficiencies.
- Suggests indexes, join rewrites, and query restructuring.
- Predicts performance gains with estimated execution time.
- Logs every suggestion with reasoning for auditability.

---

## 🛠 Built With
- **Languages:** Python, SQL (PostgreSQL), JavaScript
- **Frameworks & Libraries:** Pandas, SQLAlchemy, psycopg2, Flask
- **Platforms:** GitHub, AWS S3 (for logs)
- **Databases:** PostgreSQL
- **APIs & Data Sources:** Baseline `web-features` npm package, PostgreSQL EXPLAIN/ANALYZE
- **Tools:** VS Code, Git, Docker, Markdown, LaTeX

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- PostgreSQL (local or cloud instance)
- Git

### Installation
1. **Clone the repo**
   ```bash
   git clone https://github.com/Ashokkumar-Ganesan/sql-query-optimizer-assistant.git
   cd sql-query-optimizer-assistant
