# 🧩 ShadowScore – AI Creditworthiness Engine

**ShadowScore** is an AI-powered credit scoring system that leverages alternative data (like digital behavior, mobile usage, and social signals) to predict a numeric credit score (0–1000). It is privacy-first, explainable, and supports token-based access to empower users with secure control over their data.

---

## 🚀 Features

- 🔢 **Predicts a Credit Score (0–1000)** using machine learning
- 🔐 **PII Masked** — personal data is hashed and anonymized
- 📊 **Explainable AI** — shows feature importance using SHAP
- 🛢️ **PostgreSQL Integration** — stores user scores securely
- 🔑 **Token-Based Access** — users can generate secure tokens to share their scores
- 🌐 **Streamlit Interface** (Bonus) — interactive UI for score viewing and token sharing

---

## 🧠 Core Problem Statement

Build an AI creditworthiness engine that:
- Predicts a score using **alternative (non-financial) data**
- Ensures **privacy and anonymity**
- Offers **transparency** via explainability
- Stores results in a **scalable DB**
- Allows **controlled sharing** of data

---

## 🗂️ Folder Structure



shadowscore/
├── data/ # Sample or synthetic datasets
├── models/ # Trained model artifacts
├── app/ # FastAPI or Flask backend
├── utils/ # Helper scripts for masking, scoring, etc.
├── streamlit_app/ # Streamlit frontend code
├── requirements.txt # Python dependencies
├── README.md
└── main.py # Entry point





---

## 🛠️ Tech Stack

| Layer            | Tech Used              |
|------------------|------------------------|
| ML Model         | XGBoost / RandomForest |
| Explainability   | SHAP                   |
| Privacy Layer    | Hashlib (SHA256)       |
| Backend API      | FastAPI / Flask        |
| DB Storage       | PostgreSQL             |
| UI               | Streamlit              |
| Token Access     | UUID / JWT             |

---

## 📥 How to Run

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/shadowscore.git
   cd shadowscore


