# AI-Powered Digital Farming Mentor
> **Ancient Wisdom, Modern Farming — Reviving Our Roots Back Through Technology.**

## Overview
The **AI-Powered Digital Farming Mentor** is an intelligent agricultural guidance platform designed to preserve and share the practical knowledge of experienced Indian farmers. 

Rather than relying solely on generic internet data or standard AI outputs, the platform gathers authentic farming practices, traditional techniques, and natural remedies directly from experienced farmers across different regions of India[cite: 1]. This practical wisdom is structured into a centralized knowledge repository and combined with machine learning models to deliver actionable, personalized farming guidance.

---

## Tech Stack

### Frontend & Backend
* **Frontend:** React.js, Next.js (for SEO & performance optimization), Tailwind CSS
* **Backend:** FastAPI, SQLAlchemy
* **Authentication:** JWT (JSON Web Tokens)
### Machine Learning & APIs
* **ML Models:** XGBoost, Random Forest, LightGBM
* **External APIs:** Soil Data API, WeatherAPI

### Cloud & Infrastructure (AWS)
* **Compute & Containerization:** Amazon ECS (Backend hosting), AWS Lambda (Serverless processing)
* **Database & Storage:** Amazon RDS (PostgreSQL / MySQL), Amazon S3 (Simple Storage Service)
* **Monitoring:** Amazon CloudWatch

---

## Project Structure (Recommended)

```text
Ai-Farming/
├── backend/
│   ├── app/
│   │   ├── api/            # API endpoints & routes
│   │   ├── core/           # Config and JWT security settings
│   │   ├── models/         # SQLAlchemy database models
│   │   ├── schemas/        # Pydantic schemas
│   │   └── services/       # Weather & Soil API integration
│   ├── requirements.txt    # FastAPI, SQLAlchemy, etc.
│   └── main.py
│
├── frontend/
│   ├── src/
│   │   ├── components/     # UI building blocks
│   │   ├── pages/          # React / Next.js views
│   │   └── styles/         # Tailwind CSS styling
│   └── package.json
│
├── ml/
│   ├── data/               # Regional farming datasets & traditional practices
│   ├── models/             # Trained XGBoost, LightGBM, Random Forest models
│   └── train.py            # Model training & inference scripts
│
├── .gitignore
└── README.md
