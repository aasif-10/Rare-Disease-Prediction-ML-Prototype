# 🧠 AI Diagnosis Platform  
![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)

A web-based **AI + Rule-Based hybrid system** to predict diseases instantly from symptoms (text or visual). The platform generates actionable reports with probable diagnoses, confidence levels, and suggested doctor guidance, helping reduce delays in treatment.

---

## 🚀 Features

- **Hybrid Prediction**  
  Combines rule-based logic with a machine learning model for accurate predictions.

- **Multi-Modal Input**  
  Accepts text, images, or videos of patient symptoms.

- **Instant Reports**  
  Generates detailed diagnosis reports within minutes.

- **Accurate & Accessible**  
  Designed for use in hospitals, clinics, and homes.

- **Prescription Suggestions**  
  Provides guidance for doctors, especially in resource-limited settings.

---
---

## ⚙️ Setup & Installation

```bash
# Clone Repository
git clone https://github.com/yourusername/Hybrid-Disease-Predictor.git
cd Hybrid-Disease-Predictor

# Create Virtual Environment
python -m venv .venv

# Activate Virtual Environment

# Windows
.venv\Scripts\activate

# Linux / Mac
source .venv/bin/activate

# Install Dependencies
pip install -r requirements.txt

# Train ML Model (optional if pretrained model included)
python scripts/train_model.py

# Test Hybrid Predictor
python scripts/test_hybrid.py
```

## 📁 Project Structure

Hybrid-Disease-Predictor/
│
├── data/                      # Dataset CSV files
├── models/                    # Saved ML models and label encoders
├── scripts/
│   ├── train_model.py         # Train ML model
│   └── test_hybrid.py         # Test hybrid predictor
│
├── hybrid_predictor.py        # Hybrid prediction code
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation


🌍 How It Solves Real Problems
1. Report Delay - Provides instant diagnostic predictions so doctors can start treatment immediately.
2. Overwhelmed Doctors - Assists clinicians with a confidence-ranked list of possible diseases and suggested prescriptions.
3. Accessibility - Can be deployed in clinics, hospitals, and homes globally.
