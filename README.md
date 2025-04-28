# Odoo ERP - Multi-Company Distributor (Demo Project) - erp-multi-company-demo

## 🚀 About this project
This is a **demo** and **open-source** Odoo Community ERP setup simulating a real-world distribution company that operates under two fiscal entities but manages them operationally as one.

The project is currently **in progress**.  
Its goal is to showcase a complete, professional Odoo setup: installation, configuration, customization, and operational workflows using Odoo **18.2 Community Edition**.

> **Disclaimer:**  
> This is a portfolio sample project. It is not intended for production use without further adaptation.

---

## 🛠️ Technologies
- Odoo 18.2 Community Edition
- Python 3.13+
- PostgreSQL 14+
- Docker / Docker Compose
- Linux-based development environment

---

## 📦 Project Initialization

1. Clone the repository:
   ```bash
   git clone git@github.com:JPLFraccaro/erp-multi-company-demo.git
   cd odoo-multicompany-sample
   ```

2. Create an `.env` file (based on the provided `.env.example`):
   ```bash
   cp .env.example .env
   ```

3. Start the environment:
   ```bash
   docker-compose up -d
   ```

4. Access Odoo:
   ```
   http://localhost:8069
   ```

5. Default credentials (create a database at first launch):
   - Email: `admin@example.com`
   - Password: `admin`

---

## 📈 Roadmap

### Q2 2025

| Month | Hito | Estado |
|:------|:-----|:-------|
| **April** | Basic Dockerized Odoo 18.2 Environment + Base README | 🔥 Next step |
| **May** | Multi-Company Configuration + Custom Demo Data (Sales, Partners, Products) | ⏳ Planned |
| **June** | Basic Custom Modules: Sales Workflow Adjustment + Minimal Accounting Setup | ⏳ Planned |

---

## 📃 License
This project is licensed under the **GNU General Public License v3.0**.
