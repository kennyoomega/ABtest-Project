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

| Metric | Variant A | Variant B |
|:--|--:|--:|
| Conversion Rate | 12.03% | 11.88% |
| Lift | –1.21% |  |
| p-value | 0.2269 |  |
| Z-Score | 1.21 |  |
| 95% CI (B) | [11.72%, 12.05%] |  |
| SRM Ratio | 0.9992 | ✅ Balanced |

⚠️ *No statistically significant lift observed — recommend extending test duration or increasing sample size for sufficient power.*

---

## 💡 Tech Stack
`Python`, `Pandas`, `NumPy`, `Matplotlib`, `Statsmodels`, `Scikit-learn`

---

📍 **Author:** Siyu Chen  
📅 *October 2025 — personal project*  
🏷️ *#DataScience #ABTesting #Experimentation #Statistics #PortfolioProject*
