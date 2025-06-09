# 🤖 Supervised Learning — Binary Classification: Breast Cancer Prediction

## 📌 Project Title
**Breast Cancer Wisconsin (Diagnostic) Classification**

## 🎯 Objective
Predict whether a breast tumor is **malignant (M)** or **benign (B)** using clinical features extracted from digitized images of fine needle aspirates (FNA) of breast masses.

---

## 📂 Dataset Information

- **Source**: [Breast Cancer Wisconsin (Diagnostic)](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Rows**: 569 instances
- **Target Column**: `diagnosis`
  - `M` = Malignant
  - `B` = Benign
- **Features**: 30 numeric features (mean, standard error, worst values for radius, texture, perimeter, area, etc.)

---

## 📊 Machine Learning Workflow

### 1. Data Preprocessing
- Removed low-variance and highly correlated features
- Scaled features using `StandardScaler`
- Converted categorical target to binary (0/1)

### 2. Train/Test Split
- 80% Training
- 20% Testing
- `random_state=42` for reproducibility

### 3. Model Benchmarking
Trained and evaluated multiple classifiers:

- Logistic Regression
- Ridge Classifier
- SGD Classifier
- Decision Tree
- Random Forest
- Gradient Boosting
- HistGradient Boosting
- K-Nearest Neighbors
- Support Vector Machine (SVM)
- Multi-Layer Perceptron (MLP)

### 4. Evaluation Metrics
Each model was evaluated using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- Confusion Matrix
- Feature Importance (for tree- and linear-based models)

---

## 🥇 Best Performing Models

| Model              | Accuracy | Precision | Recall | F1 Score |
|--------------------|----------|-----------|--------|----------|
| MLP Classifier     | 0.982    | 1.000     | 0.953  | 0.976    |
| Random Forest      | 0.974    | 0.976     | 0.953  | 0.965    |
| Gradient Boosting  | 0.965    | 0.953     | 0.953  | 0.953    |

---

## 🔍 Insights

- MLP outperformed all others with perfect precision and high recall.
- Ensemble models (Random Forest, Gradient Boosting) were very stable and interpretable.
- Important features across models included:
  - `perimeter_worst`
  - `concave points_mean`
  - `radius_mean`

---

## ✅ Next Steps

- Hyperparameter tuning (e.g., grid search on top 3 models)
- Model ensembling (soft voting)
- Cross-validation for performance robustness
- Addressing potential class imbalance

---

---

## 📚 References

- [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Scikit-learn Documentation


