# Care-AI – Behavioural Monitoring Support System

An AI-powered behavioural monitoring dashboard designed to assist
rehabilitation nurses by identifying patients who may require closer
observation based on behavioural pattern analysis.

## Overview

Care-AI is a decision-support system developed during a hackathon to
help rehabilitation nurses monitor patient behavioural patterns more
efficiently.

The system analyzes behavioural data over time, identifies deviations
from individual patient baselines, and highlights patients who may
require closer attention.

The goal is not to replace healthcare professionals, but to provide
nurses with clear, explainable insights that can support their
decision-making.

---

## Problem Statement

In rehabilitation centres, nurses may be responsible for monitoring
multiple patients simultaneously.

Continuous manual observation can make it difficult to identify subtle
changes in behaviour, potentially resulting in:

- Increased workload for healthcare staff
- Delayed identification of behavioural changes
- Missed early warning signs
- Difficulty prioritizing patients who require closer observation

---

## Proposed Solution

Care-AI acts as a behavioural monitoring and decision-support tool.

The system:

1. Collects patient behavioural data
2. Processes and validates the data
3. Analyzes behavioural patterns
4. Compares observations with individual baselines
5. Identifies unusual patterns or deviations
6. Highlights patients who may require closer observation
7. Presents the findings through an interactive Streamlit dashboard

The final decision remains with the healthcare professional.

---

## Key Features

### Behavioural Monitoring
Tracks behavioural indicators such as activity, sleep, food-related
scores, heart rate, stress levels, and therapy-related information.

### Baseline Analysis
Analyzes patient behaviour over time and identifies deviations from
their individual behavioural patterns.

### AI-Based Risk Analysis
Uses machine-learning-based analysis to identify behavioural patterns
that may require additional attention.

### Explainable Insights
Provides nurse-friendly information to help users understand why a
patient has been highlighted.

### Interactive Dashboard
A Streamlit-based dashboard allows rehabilitation staff to view
patient information and monitoring results in an accessible interface.

### Nurse Authentication
The system includes an authentication layer for accessing the
monitoring dashboard.

---

## Target Users

- Rehabilitation Nurses
- Healthcare Support Staff
- Rehabilitation Centre Administrators

---

## Technology Stack

| Technology | Purpose |
|------------|---------|
| Python | Core application and analysis |
| Pandas | Data processing and analysis |
| NumPy | Numerical operations |
| Scikit-learn | Machine learning and behavioural analysis |
| Streamlit | Interactive dashboard |
| Git & GitHub | Version control and collaboration |

---

## Project Structure

```text
Care-AI/
│
├── AIModel.py
├── DashBoard.py
├── auth.py
├── generateData.py
│
├── data/
│   ├── PatientData.csv
│   ├── nurses.csv
│   └── images/
│
├── .streamlit/
│   └── config.toml
│
├── README.md
└── requirements.txt
