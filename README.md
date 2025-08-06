# INX-Future-Inc.-Employee-Performance-Prediction-and-Analysis

---

## 🔍 Project Objectives

- Identify and fix issues in employee performance dataset.
- Understand key drivers of performance.
- Visualize department-wise, gender-wise, and salary-based trends.
- Train ML model to predict future employee performance.
- Build a reusable prediction pipeline.

---

## 🧪 Notebooks Explained

| Notebook                         | Purpose |
|----------------------------------|---------|
| `data_processing.ipynb`          | Loads raw data, handles missing values, encodes categorical features, and scales data. |
| `data_exploratory_analysis.ipynb`| Performs detailed EDA using plots (distribution, correlation, department trends). |
| `train_model.ipynb`              | Trains models (e.g., Random Forest), evaluates accuracy, and saves the best model (`employee_perf_rf_model.pkl`). |
| `predict_model.ipynb`            | Loads saved model and predicts performance on new/real-time employee data. |
| `visualize.ipynb`                | Shows dashboards using Seaborn/Matplotlib for department-wise, experience-wise insights. |

---

## 📦 Model Artifacts

Saved inside: `models/saved/`

- `employee_perf_rf_model.pkl` – Trained Random Forest model
- `required_features.pkl` – List of input features expected by model

---

## ▶️ How to Run

1. Clone this repo or download the files.
2. Open each `.ipynb` notebook in Jupyter or VS Code.
3. Run `data_processing.ipynb` → `EDA` → `train_model.ipynb`
4. Make sure `models/saved/` folder contains the saved model.
5. Use `predict_model.ipynb` to load the model and test on new data.

---

## 📊 Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📌 Example Use Case

> Predict whether a newly hired employee is likely to underperform, based on department, education, KPIs, and experience.

---


This project is for academic and learning purposes.

