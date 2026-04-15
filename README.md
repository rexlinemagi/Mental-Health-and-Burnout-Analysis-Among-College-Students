# 🧠 Student Mental Well-Being Predictor

> A machine learning project that predicts whether a student's mental well-being is **Good** or **Not Good** based on daily habits and academic environment — and actually explains *why*.

---

## 📌 Project Overview

Mental health in academic settings is often overlooked until it's too late. This project uses supervised machine learning to classify student mental well-being from lifestyle and academic factors, with a strong emphasis on **model interpretability** — not just accuracy.

Three classification algorithms were trained, tuned, and compared. The best-performing and most interpretable model was selected for final deployment consideration.

---

## ⚙️ Models Used

### 🌳 Random Forest Classifier
- Used as the **baseline model**
- Configured with `random_state=42` for reproducibility
- **Accuracy: 71.43%**

### 📍 K-Nearest Neighbors (KNN)
- Tuned with optimal `k=3` neighbors
- Significant improvement over the baseline
- **Accuracy: 85.71%**

### 🌲 Decision Tree Classifier
- Selected for its **interpretability**
- Decision rules are human-readable and auditable
- **Accuracy: 85.71%**

---

## 📊 Model Comparison

| Model | Accuracy |
|---|---|
| Random Forest | 71.43% |
| KNN (k=3) | 85.71% |
| Decision Tree | 85.71% |

---

## 🔍 Evaluation Method

Each model was evaluated using a **confusion matrix**, which captures:

- ✅ True Positives / True Negatives (correct predictions)
- ❌ False Positives / False Negatives (types of errors)

This gives a fuller picture of model behavior than accuracy alone — particularly important in a well-being context where misclassifications carry real consequences.

---

## 🏆 Final Model: Decision Tree

Although KNN and Decision Tree achieved identical accuracy, the **Decision Tree** was selected as the final model for one key reason: **interpretability**.

A Decision Tree produces explicit, readable rules that reveal *which factors actually influence student well-being* — making it not just a predictor, but a diagnostic tool.

> Insight > raw accuracy. A model that explains itself is a model that can be trusted.

---

## 🎯 Conclusion

This project demonstrates that machine learning can effectively classify student mental well-being using lifestyle and academic data.

- **Best performing models:** KNN & Decision Tree — both at **85.71%**
- **Final model:** Decision Tree, chosen for interpretability and explainability
- **Key takeaway:** Predictive power is most valuable when paired with transparency

---

## 🚀 Future Improvements

- [ ] Expand dataset size and diversity for better generalization
- [ ] Experiment with advanced models (SVM, XGBoost, Neural Networks)
- [ ] Apply feature engineering to improve predictive accuracy
- [ ] Build and deploy a web or mobile app for real-world use
- [ ] Incorporate SHAP values for deeper model explainability

---

## 🧠 Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core language |
| Scikit-learn | ML models and evaluation |
| Pandas / NumPy | Data manipulation |
| Matplotlib / Seaborn | Visualization |

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open a pull request or raise an issue.

---

*Built with a focus on student well-being — because the goal isn't just to predict, it's to understand.*