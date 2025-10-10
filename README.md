# Intelligent Freight Network Optimization
Decision Intelligence System integrating Machine Learning and Linear Optimization (Pyomo + CBC) to minimize freight cost and delays across 37 logistics hubs in the Northeastern U.S.
# 🚛 Intelligent Freight Network Optimization

### A Decision Intelligence System for Freight Logistics in the Northeastern U.S.

This project builds a **Decision Intelligence System** that integrates machine learning and optimization to improve freight network performance.  
It simulates 180k+ shipments across 37 logistics hubs, predicts operational metrics, and optimizes routing decisions using Pyomo + CBC.

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Pyomo](https://img.shields.io/badge/Pyomo-CBC%20Solver-brightgreen)
![Machine Learning](https://img.shields.io/badge/ML-XGBoost-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)


---

## 🧠 Architecture

**1. Data Intelligence (EDA)**  
- Cleaned and visualized operational data.  
- Identified correlations (Cost–Distance: 0.77, Delay independence, etc.).

**2. Predictive Intelligence (XGBoost)**  
- Predicted shipment cost (R² ≈ 0.78)  
- Predicted delay probability (R² ≈ 0.31)  
- Predicted fuel consumption (R² ≈ 0.99)

**3. Prescriptive Intelligence (Pyomo + CBC)**  
- MILP model minimizing `0.7 × Cost + 0.3 × Delay`  
- Service-level ≥95%, delay ≤3 hrs  
- 13% total composite cost reduction

---

## 📊 Results
| Metric | Baseline | Optimized | Improvement |
|--------|-----------|------------|--------------|
| Composite Cost (Cost + Delay Weighted) | 572,817 | 498,886 | **12.9% ↓** |

---

## 🛠️ Tech Stack
Python · Pandas · Seaborn · Scikit-Learn · XGBoost · Pyomo · CBC Solver

---

## 🗺️ Key Files
| File | Description |
|------|--------------|
| `Intelligent_Freight_Network_Optimization.ipynb` | Full analysis + optimization notebook |
| `data/northeast_freight_network_raw.csv` | Dataset |
| `requirements.txt` | Environment dependencies |

---

## 📈 Business Impact
> The system demonstrates how predictive analytics and linear optimization can jointly drive data-driven decisions in logistics, reducing operational cost while maintaining service quality.

---

### Author
**Damodar Satyadeva Madhukar Naraparaju**  
Master’s in Business Analytics – Saint Peter’s University, NJ  
📧 dsd.madhukar@outlook.com
