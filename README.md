# 🧬 Cancer Patient Analysis & Prediction

## 📌 Project Overview

This project focuses on predicting whether a tumor is **malignant (M)** or **benign (B)** using machine learning techniques.
A **Logistic Regression model** is trained on medical features extracted from cell nuclei to classify cancer diagnosis.

---

## 📊 Dataset Information

The dataset contains features computed from digitized images of a fine needle aspirate (FNA) of a breast mass.

### 🎯 Target Variable:

* **Diagnosis**

  * M → Malignant
  * B → Benign

---

## 🧪 Features Used

Each cell nucleus is described using the following features:

1. Radius (mean distance from center to perimeter)
2. Texture (standard deviation of gray-scale values)
3. Perimeter
4. Area
5. Smoothness
6. Compactness
7. Concavity
8. Concave Points
9. Symmetry
10. Fractal Dimension

Each feature includes:

* Mean
* Standard Error
* Worst (largest value)

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* Scikit-learn

---

## 🚀 Workflow

### 1. Data Collection

* Dataset loaded using Pandas from an online source.

### 2. Data Preprocessing

* Removed unnecessary columns:

  * `id`
  * `Unnamed: 32`

### 3. Feature & Target Split

* Features → `X`
* Target → `y`

### 4. Train-Test Split

* 70% training data
* 30% testing data

### 5. Model Selection

* Logistic Regression model used

### 6. Model Training

* Model trained using training dataset

### 7. Prediction

* Predictions made on test data

### 8. Evaluation Metrics

* Confusion Matrix
* Accuracy Score
* Classification Report

---

## 📈 Model Performance

* The model provides high accuracy in classifying tumors.
* Performance evaluated using:

  * Precision
  * Recall
  * F1-score

---

## 📂 Project Structure

```
Cancer-patient-Analysis/
│
├── Cancer_Prediction.ipynb   # Main notebook
├── README.md                 # Project documentation
```

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/srisaichinka/Cancer-patient-Analysis.git
```

2. Open the notebook:

* Use Jupyter Notebook / VS Code

3. Run all cells step-by-step

---

## 💡 Future Improvements

* Try advanced models (Random Forest, SVM, XGBoost)
* Hyperparameter tuning
* Deploy as a web app (Flask/Streamlit)
* Add visualization dashboards

---

## 🤝 Contribution

Feel free to fork this repository and improve the model.

---

## ⭐ Support

If you like this project:

* ⭐ Star the repository
* 👁 Watch for updates

---
