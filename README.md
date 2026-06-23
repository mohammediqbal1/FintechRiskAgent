# Fintech Risk Agent

**AI-Powered Autonomous Loan Risk Prediction & Explanation System**

This repository contains an end-to-end autonomous AI agent designed to inspect financial data, train machine learning models, evaluate performance, and generate explainable insights — all with minimal human intervention. It’s tailored for **credit risk assessment** in fintech and banking scenarios.

---

## 📌 Project Overview

Traditional ML workflows are often manual, repetitive, and hard to maintain. This project implements an **intelligent agent architecture** (Planner–Tool–Memory pattern) that can:

✔ Inspect dataset structure  
✔ Train a risk prediction model  
✔ Evaluate model performance on key metrics  
✔ Track state transitions autonomously  
✔ Generate explainable outputs for business needs  

---

## 🚀 Features

- 🤖 **Autonomous Workflow Engine**  
  Orchestrates data inspection, model training, evaluation, and explanation generation.

- 📊 **Data Profiling**  
  Automatically inspects dataset dimensions and field characteristics.

- 🧠 **Machine Learning Integration**  
  Uses Scikit-learn for model training and evaluation.

- 📈 **Performance Metrics Computation**  
  Computes accuracy, precision, recall, and confusion matrix.

- 🧳 **Memory System**  
  Tracks task states (e.g., `inspected`, `trained`, `evaluated`) to guide future decisions.

- 📦 **Model Persistence**  
  Saves trained models for reuse and future deployment.

---

## 🗂️ Folder Structure

fintech-risk-agent/
│
├── agent/
│ ├── agent.py # Core agent loop
│ ├── planner.py # Decision logic
│ └── memory.py # Memory state tracking
│
├── tools/
│ ├── data_tool.py # Data inspection utilities
│ ├── train_tool.py # Model training logic
│ ├── eval_tool.py # Evaluation metrics
│ └── explain_tool.py # Explanation generator
│
├── models/ # Saved models
│ └── risk_model.pkl
│
├── data/ # Dataset files
│ └── loan_data.csv
│
├── logs/ # Prediction and audit logs
│
└── main.py # Entry point script


---

## 📥 Getting Started

### 1. Clone the repository

```
git clone https://github.com/mohammediqbal1/FintechRiskAgent.git
cd FintechRiskAgent/fintech-risk-agent
```

### 2. Create a Python virtual environment

```
python -m venv venv
source venv/bin/activate        # Linux / macOS
venv\Scripts\activate           # Windows
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

## 🧪 Example Output

```
→ Inspecting dataset...
→ Model trained and saved
→ Evaluation: accuracy 0.9566
→ Explanation generated for risk decision
→ Agent workflow completed
```
