# 🏥 ML Insurance Premium Prediction API

[![Python Version](https://img.shields.io/badge/python-3.9%2B-blue.svg)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi)](https://fastapi.tiangolo.com/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)](https://www.docker.com/)
[![Deployed on Render](https://img.shields.io/badge/Deployed_on-Render-46E3B7?style=flat&logo=render&logoColor=white)](https://ml-insurance-premium-api.onrender.com)

A Machine Learning-powered RESTful API that predicts insurance premiums based on user demographic and health data. Built with **FastAPI**, trained using **scikit-learn**, containerized with **Docker**, and continuously deployed on **Render**.

🚀 **Live API / Interactive Docs (Swagger UI):** [https://ml-insurance-premium-api.onrender.com/docs](https://ml-insurance-premium-api.onrender.com/docs)

---

## ✨ Features

- **Accurate ML Predictions:** Utilizes a pre-trained scikit-learn model to estimate insurance costs based on variables like age, BMI, smoking status, and more.
- **FastAPI Framework:** Extremely fast and efficient routing with automatic interactive documentation.
- **Data Validation:** Leverages Pydantic schemas to ensure all incoming request payloads are strictly validated before making predictions.
- **Containerized:** Fully reproducible environment using Docker.
- **Production Ready:** Configured for cloud deployment on platforms like Render.

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Framework:** FastAPI, Uvicorn
- **Machine Learning:** Scikit-Learn, Pandas, NumPy, Joblib
- **Validation:** Pydantic
- **Containerization:** Docker
- **Deployment:** Render

---

## 📂 Project Structure

```bash
├── config/              # Configuration files and environment variables
├── model/               # Serialized ML models (e.g., .pkl or .joblib files)
├── schema/              # Pydantic models for request/response validation
├── app.py               # FastAPI application entry point
├── Dockerfile           # Docker configuration for containerization
├── requirements.txt     # Python dependencies
├── .dockerignore        # Excluded files for Docker builds
└── .gitignore           # Excluded files for Git
