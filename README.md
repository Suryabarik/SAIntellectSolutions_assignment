# 🏥 JeevanMed AI ERP

## AI-Powered Medical Finance Management System

An AI-powered healthcare finance management system built using FastAPI, Streamlit, and Groq LLM APIs.

---

# 🚀 Features

- Patient Management
- Invoice Management
- Transaction Tracking
- Financial Analytics
- AI-Powered Recommendations
- JWT Authentication
- Role-Based Access Control
- Streamlit Dashboard

---

# 🤖 AI Decision Engine

The project integrates the **Llama-3.1-8B-Instant** model using the **Groq API** to generate intelligent financial recommendations.

AI Features:
- Financial risk analysis
- Pending invoice detection
- Smart payment recommendations
- AI-generated financial summaries

---

# 🧠 AI Workflow

Patient Data → Invoice Data → Financial Metrics → Groq API → AI Recommendations

---

# 📊 Example AI Output

## Raw Financial Data

```json
{
  "total_invoices": 5,
  "total_revenue": 13513,
  "total_pending_amount": 2399,
  "paid_invoices": 1,
  "partial_invoices": 2
}
```

## AI Metrics

```json
{
  "pending_ratio": 0.18,
  "payment_completion_rate": 0.2,
  "partial_ratio": 0.4
}
```

## AI Recommendations

- Send payment reminders for pending invoices
- Call overdue patients directly
- Offer payment plans to partial payers

---

# 🛠 Tech Stack

- FastAPI
- SQLAlchemy
- SQLite
- Streamlit
- JWT Authentication
- Groq API
- Llama-3.1-8B-Instant

---

# ⚙️ Setup Instructions

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Backend

```bash
uvicorn app.main:app --reload
```

## Run Frontend

```bash
cd frontend
streamlit run app.py
```

---

# 📡 API Endpoints

## Authentication
- POST /auth/signup
- POST /auth/token

## Patients
- POST /patients/
- GET /patients/

## Invoices
- POST /invoices/
- GET /invoices/

## Transactions
- POST /transactions/
- GET /transactions/

## Analytics
- GET /analytics/summary

## AI APIs
- GET /ai/financial-analysis
- POST /ai/recommendations

---

# 🔗 GitHub Repository

Repository Link:

https://github.com/Suryabarik/SAIntellectSolutions_assignment

---

# 👨‍💻 Author

Suryakanta Barik  
Python Developer | Backend Developer | AI/ML Enthusiast
