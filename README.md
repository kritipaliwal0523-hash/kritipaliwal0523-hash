<h1 align="center">Hi, I'm Kriti 👋</h1>

<p align="center">
  CS undergrad (Class of 2027) building AI-powered full-stack apps and ML systems.<br>
  I like projects where the output has to be <b>reliable</b>: validation, real metrics.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kriti-paliwal-565b38370"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:kritipaliwal0523@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

## 🛠️ What I build with

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

**Databases**
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

**AI / ML**
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat&logo=googlegemini&logoColor=white)

---

## 🚀 Projects (click to expand)

<details>
<summary><b>🤖 AI Code Review Assistant</b> — GitHub PR reviewer powered by Gemini</summary>
<br>

Listens to GitHub webhooks, fetches the PR diff, runs a 2-pass LLM review (bugs/security, then smells/style) and posts the result as a PR comment.

- Webhook signature verification + queue (BullMQ/Redis with in-memory fallback), so GitHub gets a response in seconds
- Per-file diff chunking so the model never sees half a change
- Retry + fallback comment on failure, every review logged to MongoDB
- React dashboard with review history and metrics

**Stack:** Node.js · Express · React · MongoDB · GitHub API · Gemini API · Jest

🔗 [View repo](https://github.com/kritipaliwal0523-hash/ai-code-review-assistant)
</details>

<details>
<summary><b>📋 Employee Task Manager</b> — role-based task management for small teams</summary>
<br>

Separate admin and employee workflows with task assignment, Kanban/table views, comments, notifications and activity logs.

- Firebase Auth + backend token verification, role-based middleware (roles are never trusted from the frontend)
- 23 REST endpoints across 7 modules
- Dashboards with Recharts for both admins and employees

**Stack:** React · Express · Firebase Auth · Firestore · Tailwind CSS

🔗 [View repo](https://github.com/kritipaliwal0523-hash/Employee-Task-Manager)
</details>

<details>
<summary><b>🛡️ CrediShield AI</b> — buyer risk prediction for MSMEs</summary>
<br>

Predicts which B2B buyers are likely to pay late, scores their reliability, and drafts a collections message that a human reviews before sending.

- Logistic Regression: **85.5% accuracy, 0.92 ROC-AUC** on a held-out set (572 transactions, 50 buyers)
- Buyer-history features built only from data available before each invoice, to avoid leakage
- Gemini drafts the message; the risk score comes from the model, not the LLM
- Falls back to a rule-based template if the API is down

**Stack:** React · FastAPI · SQLAlchemy · scikit-learn · JWT · Gemini API

🔗 [View repo](https://github.com/kritipaliwal0523-hash/credi-shield-ai)
</details>

<details>
<summary><b>🏦 Banking Customer & Data Intelligence</b> — data analytics project</summary>
<br>

Cleaning and validation pipeline over customer, account and transaction data, with SQL analysis, RFM segmentation and a 4-page Power BI dashboard. Data is synthetic.

**Stack:** Python · Pandas · SQL · Power BI · Excel

🔗 [View repo](https://github.com/kritipaliwal0523-hash/banking-customer-data-intelligence)
</details>

<details>
<summary><b>🎟️ Event Management System</b> — Java desktop app</summary>
<br>

Java Swing + MySQL application for managing events and participants using JDBC.

🔗 [View repo](https://github.com/kritipaliwal0523-hash/event-management-system-java)
</details>

---

## 🌱 Currently

- 🔭 Building more full-stack projects and deploying them
- 💬 Ask me about: webhooks, REST API design, ML evaluation

---

<p align="center">
  <i>Thanks for stopping by! Check out the repos above and feel free to reach out.</i>
</p>
