# Telecom Churn Survival Analysis 🚀

Predicts **when** customers churn (not just who) using Cox Proportional Hazards model.

## 📊 Results That Matter
| Metric | Score |
|--------|-------|
| **Test C-Index** | **0.846** 🎯 |
| **CV C-Index** | **0.858** |
| **12mo Calibration (ICI)** | **0.020** |

**💡 Business Gold**: 
- Month-to-month + Fiber optic = **1.38× churn risk** ⚠️
- TechSupport/OnlineBackup = **protective (HR 0.58-0.65)** 🛡️

## 🎯 What I Did
1. Cleaned Telco dataset (7k customers, tenure=0 fix)
2. Train/test split + 5-fold CV
3. CoxPH model with penalizer for stability
4. Kaplan-Meier curves + hazard ratio forest
5. Calibration plots proving reliability

## 🔗 Run It
[

## 🛠️ Tech Stack
Python | lifelines | pandas | scikit-learn | matplotlib/seaborn

