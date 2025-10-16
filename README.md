# 🧪 A/B Test Project

**A production-style A/B testing analysis pipeline — from data validation to business translation.**

This project simulates a real-world experimentation workflow used by data science teams to ensure statistical rigor, anti-leakage protection, and reproducibility.

---

## 🚀 Overview

The notebook performs:
- ✅ **Schema & Health Validation**
- ✅ **SRM (Sample Ratio Mismatch) Check**
- ✅ **Two-Proportion Z-Test**
- ✅ **95% Confidence Interval & Lift**
- ✅ **Actionable Business Translation**

---

## 📈 Results Summary

SRM check → group balance ratio: 0.9992  

✅ SRM within acceptable range (no major imbalance).

A: 12.0297%  (n=145,232)

B: 11.8843%  (n=145,352)

Δ = -0.1455%   |   Lift = -1.21%

Z = 1.21,  p = 0.2269,  95% CI for B = [11.7179%, 12.0506%]

⚠️ *No statistically significant lift observed — recommend extending test duration or increasing sample size for sufficient power.*

---

## 💡 Tech Stack
`Python`, `Pandas`, `NumPy`, `Matplotlib`, `Statsmodels`, `Scikit-learn`

---

📍 **Author:** Siyu Chen  
📅 *October 2025 — personal project*  
🏷️ *#DataScience #ABTesting #Experimentation #Statistics #PortfolioProject*
