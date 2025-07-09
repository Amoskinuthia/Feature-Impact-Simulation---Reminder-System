# SMS Reminder System: A/B Test Simulation

## 📌 Objective
To simulate and analyze the impact of sending SMS reminders on member contribution behavior in a Chama setup.

## 🧪 Dataset
- **Simulated data** of 300 members over 3 months
- **Group A**: Received SMS reminders
- **Group B**: No reminders (control group)

Dataset fields:
- `member_id`, `group`, `due_date`, `payment_date`, `days_late`, `is_late`, `amount`

## 📊 Analysis Summary
| Metric               | Group A (SMS) | Group B (No SMS) |
|----------------------|---------------|------------------|
| Avg Days Late        | 0.02 days     | 1.72 days        |
| Default Rate         | 35%           | 65%              |
| Avg Contribution     | KES 3,512     | KES 3,305        |

## ✅ Conclusion
The analysis supports investing in an SMS reminder system:
- Reduced payment lateness
- Lower default rates
- Higher average contributions

## 📂 Files Included
- `ab_test_analysis.ipynb`: Python notebook with simulation + analysis
- `ab_contribution_simulation.csv`: Cleaned dataset

## 🛠 Tools Used
- Python (Pandas, NumPy)
- Jupyter Notebook
- Statistical summary and descriptive comparison

---

### ✅ Recommendation
Deploy SMS reminders in future contribution cycles to drive on-time behavior and improved cash flow.

