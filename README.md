# Telecom Churn Survival Analysis

Predicts **when** customers churn using Cox Proportional Hazards (C-index **0.846**). Business insights: Fiber Optic + e-check = high risk.

## Results Table
| Metric          | Score    | Insight                     |
|-----------------|----------|-----------------------------|
| **Test C-Index**| **0.846** | Model reliability           |
| **CV C-Index**  | **0.858** | Cross-validated stability   |
| Dataset         | 7043 customers | Kaggle Telco (tenure/Churn) |

![Survival Curves](<img width="846" height="547" alt="survival_curve" src="https://github.com/user-attachments/assets/6352d22e-aedd-4a23-bcc8-ae7234446ef0" />
)
![Cox Hazards](<img width="885" height="881" alt="image" src="https://github.com/user-attachments/assets/d6448a1b-f1d3-412c-b7e6-0d44ad8bb052" />
)

## Key Insights
- **Churn Bombs:** Month-to-month + Fiber Optic (HR ~1.4)
- **Retention Wins:** TechSupport + 2yr contracts (HR <0.7)
- **Action:** Target month 6 interventions → Save $XM LTV

## Run Locally
```bash
git clone https://github.com/Tanishka-001/telecom-churn-survival-analysis
cd telecom-churn-survival-analysis
pip install -r requirements.txt
jupyter notebook churn_survival_analysis.ipynb

