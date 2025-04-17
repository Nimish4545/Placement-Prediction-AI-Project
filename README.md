
# 🎓 Placement Prediction using Machine Learning

This project focuses on predicting student placement outcomes based on historical and categorical data using multiple machine learning models.

---

## 📌 Features

- Preprocessing with Label Encoding
- Comparison of 5 machine learning models:
  - Naive Bayes
  - Decision Tree
  - Random Forest
  - XGBoost
  - MLP Classifier (Neural Network)
- Evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion Matrix
- Visualizations for:
  - Accuracy comparison
  - Precision, Recall, and F1 comparison
  - Confusion matrices
  - Neural Network loss curve
- Label encoding mappings are saved to JSON for reuse

---

## 🧠 Models Used

| Model           | Type             | Purpose                            |
|----------------|------------------|-------------------------------------|
| Naive Bayes     | Probabilistic    | Baseline for classification         |
| Decision Tree   | Tree-based       | Easy to interpret                   |
| Random Forest   | Ensemble         | Robust to overfitting               |
| XGBoost         | Boosting         | High performance & accuracy         |
| MLP Classifier  | Neural Network   | Deep learning approach              |

---

## 🗂️ File Structure

```
Placement_Prediction/
├── Placement_Prediction.ipynb     # Main notebook
├── label_encodings.json           # Encoded label mappings
├── README.md                      # Project documentation
└── requirements.txt               # Python dependencies (optional)
```

---

## 📈 Sample Outputs

### ✅ Model Performance Comparison

| Model         | Train Acc | Test Acc | Precision | Recall | F1 Score |
|---------------|-----------|----------|-----------|--------|----------|
| Naive Bayes   | 0.84      | 0.81     | 0.82      | 0.81   | 0.81     |
| Decision Tree | 1.00      | 0.87     | 0.88      | 0.87   | 0.87     |
| Random Forest | 0.99      | 0.90     | 0.91      | 0.90   | 0.90     |
| XGBoost       | 0.98      | 0.91     | 0.92      | 0.91   | 0.91     |
| MLPClassifier | 0.93      | 0.89     | 0.89      | 0.89   | 0.89     |

> 📌 *Values shown are just for representation. Please replace with actual results.*

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/placement-prediction.git
   cd placement-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   Open `Placement_Prediction.ipynb` in Jupyter or VS Code and execute the cells.

---

## 📦 Requirements (Add to `requirements.txt`)

```
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
```

---

## 🙌 Contributors

- **Nimish** – Model development & visualization  

