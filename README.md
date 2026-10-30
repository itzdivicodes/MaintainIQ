# MaintainIQ

**Explainable AI Framework for Industrial Asset Health Intelligence and Maintenance Decision Support**

Youtube : https://youtu.be/82d4tuRMw7I

## Overview

MaintainIQ is an end-to-end platform that combines MongoDB-native time-series storage, LSTM Autoencoder anomaly detection, progressive degradation modeling, SHAP-based explainability, and natural language querying into a unified industrial asset health intelligence system.

## Architecture
MetroPT-3 → Sensor Reliability → MongoDB Time-Series → LSTM Autoencoder →
Progressive Degradation → DAHI → SHAP XAI → MAPE → Decision Engine →
Streamlit Dashboard + AMA

text

## Setup

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
Start MongoDB:

bash
net start MongoDB
Initialize schema:

bash
python -c "from src.database.schema import init_schema; init_schema()"
Import data:

bash
python src/database/import_data.py
Train model:

bash
python src/models/train.py
Run dashboard:

bash
streamlit run dashboard/app.py
Modules
Module	Description
DAHI	Dynamic Asset Health Index (0-100 score)
MAPE	Maintenance Action Prioritization Engine
EME	Explainable Maintenance Engine (SHAP)
AMA	Agentic Maintenance Assistant (NLP)
Technology Stack
Database: MongoDB 7.0+

Model: LSTM Autoencoder

Explainability: SHAP

Dashboard: Streamlit

Backend: Python 3.9+

text

---

## Summary

| File | Status |
|------|--------|
| `src/config.py` | ✅ Complete |
| `src/database/*` | ✅ Complete |
| `src/preprocessing/*` | ✅ Complete |
| `src/models/*` | ✅ Complete |
| `src/analytics/*` | ✅ Complete |
| `src/agent/*` | ✅ Complete |
| `dashboard/app.py` | ✅ Complete |
| `requirements.txt` | ✅ Complete |

---

**All files are complete. Start coding now!** 🚀
