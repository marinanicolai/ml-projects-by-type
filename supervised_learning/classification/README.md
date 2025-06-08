# 🧠 Supervised Learning: Classification

## 📌 What is Classification?

**Classification** is a type of **supervised learning** where the goal is to predict categorical labels. In this approach, the model is trained on a labeled dataset where the output variable is a category or class (e.g., "Yes" or "No", "Spam" or "Not Spam", "Positive" or "Negative").

The model learns patterns in the data and uses these to classify new, unseen data into one of the predefined classes.

---

## 🧪 How It Works

- The input features (`X`) are provided along with their corresponding labels (`y`).
- The algorithm learns the relationship between features and labels.
- After training, the model can predict the class for new input data.

**Common Algorithms:**
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes

---

## 💼 Applications of Classification

### 1. Healthcare
Classification models are used to:
- Diagnose diseases
- Assess patient risk
- Identify conditions from diagnostic or imaging data  
**Example:** Classifying patients as "high risk" or "low risk" based on test results.

---

### 2. Finance
Financial institutions use classification to:
- Perform credit scoring
- Detect fraudulent transactions  
**Example:** Labeling transactions as "fraudulent" or "non-fraudulent".

---

### 3. Marketing
Classification supports:
- Customer segmentation
- Personalized marketing strategies  
**Example:** Categorizing users by behavior or demographics to target ads.

---

### 4. Retail
Retailers use classification for:
- Inventory management
- Forecasting demand
- Recommending products  
**Example:** Suggesting items based on user purchase history.

---

### 5. Manufacturing
In manufacturing, classification helps with:
- Quality control
- Fault detection  
**Example:** Classifying products as "faulty" or "non-faulty" during inspections.

---

## 📊 Linear vs. Non-Linear Classification

### 🔹 Linear Classification

**Definition:**  
A classification method is **linear** if it separates the classes using a straight line (2D), plane (3D), or hyperplane (higher dimensions).

**Key Characteristics:**
- Decision boundary is linear.
- Assumes a straight-line relationship between inputs and outputs.

**Examples:**
- Logistic Regression  
- Linear Support Vector Machines (SVM)  
- Perceptron

**Use Case:**  
Best when data is linearly separable (e.g., classes can be divided by a straight line).

---

### 🔸 Non-Linear Classification

**Definition:**  
Non-linear classifiers can separate data using curves or complex shapes.

**Key Characteristics:**
- Decision boundary is non-linear.
- Can capture complex patterns and relationships.

**Examples:**
- Decision Trees  
- Random Forest  
- Kernel SVM (e.g., RBF kernel)  
- Neural Networks  
- K-Nearest Neighbors (KNN)

**Use Case:**  
Best when data is not linearly separable.

---

### ✅ Comparison Table

| Feature                     | Linear Classification        | Non-Linear Classification          |
|----------------------------|------------------------------|------------------------------------|
| Decision Boundary          | Straight line/hyperplane     | Curved or complex surface          |
| Algorithms                 | Logistic Regression, Linear SVM | Decision Trees, Kernel SVM, Neural Networks |
| Assumes Linear Separation  | Yes                          | No                                 |
| Complexity                 | Low                          | Medium to High                     |
| Interpretability           | High                         | Medium to Low                      |

---

## ✅ Summary

Classification is one of the most widely used techniques in supervised learning. Its ability to categorize data into predefined classes makes it essential for decision-making in healthcare, finance, marketing, and beyond.
