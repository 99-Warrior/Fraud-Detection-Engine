# Fraud-Detection-Engine
Real-time scoring system- Fraud detection system build with FastAPI-Swagger UI
#Project Overview

Explain:

simulated transaction generation
ML fraud detection
FastAPI risk scoring
decision engine
fraud monitoring
Architecture Flow

Transaction Simulator
        ↓
Transaction Dataset
        ↓
Feature Engineering
        ↓
ML Fraud Model
        ↓
FastAPI Scoring API
        ↓
Risk Decision Engine
(ALLOW / OTP / BLOCK)

#Features


✅ transaction velocity detection
✅ device trust scoring
✅ geolocation anomalies
✅ risk scoring
✅ rule-based overrides
✅ ML classification
✅ API deployment

#Tech Stack

Python
PySpark
Databricks
FastAPI
Scikit-learn
Pandas
SQL

#API Example

{"amount": 95000,
  "velocity_24h": 8,
  "device_trust_score": 2,
  "location_mismatch": 1,
  "foreign_transaction": 1}

  Response
  {"risk_score": 94,
  "action": "BLOCK"}
