# 🚀 Support Vector Machines with Hyperparameter Tuning

## 📌 Overview

This project demonstrates the implementation of **Support Vector Machines (SVM)** for classification using a synthetic dataset. It explores different **kernel functions**, performs **hyperparameter tuning**, and evaluates model performance using both **quantitative metrics and visualizations**.

The project is designed to provide a clear understanding of how SVM works, including decision boundaries, kernel behavior, and optimization techniques. This project is colorblind friendly.

---

## 🎯 Objectives

* Understand **machine learning classification**
* Implement **SVM with different kernels**
* Perform **hyperparameter tuning using GridSearchCV**
* Visualize **decision boundaries and accuracy**
* Ensure **accessible (colorblind-friendly) visualizations**

---

## 📊 Dataset

The dataset is generated using `make_classification`:

* 300 samples
* 2 features (for visualization)
* Controlled complexity (`class_sep=1.5`)
* Reproducible (`random_state=42`)

This allows clear visualization of decision boundaries and model performance.

---

## ⚙️ Technologies Used

* Python 🐍
* Scikit-learn
* NumPy
* Matplotlib

---

## 🧠 SVM Concepts Covered

* Linear vs Non-linear classification
* Support vectors & margin maximization
* Kernel trick
* Common kernels:

  * Linear
  * Polynomial
  * RBF (Gaussian)

---

## 🔧 Hyperparameter Tuning

GridSearchCV is used to find optimal parameters:

* **C** → Regularization
* **Gamma** → Boundary complexity

✔ 5-fold cross-validation ensures robust evaluation.

---

## 📈 Results

### 🔹 Classification Performance

* Accuracy: **~99%**
* Precision, Recall, F1-score: **~0.99**
* Balanced performance across both classes

### 🔹 Kernel Comparison

| Kernel     | Accuracy |
| ---------- | -------- |
| Linear     | 0.989    |
| Polynomial | 0.978    |
| RBF        | 0.989    |

👉 Linear and RBF perform best, showing dataset is well-structured.

---

## 📊 Visualizations

The project includes:

* Dataset scatter plot
* Decision boundary plots
* Kernel comparison chart
* Accuracy heatmap

✔ All visualizations are **colorblind-friendly** using:

* Distinct markers (o, s)
* Accessible color palettes
* Grid-enhanced heatmaps

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/pradeep271/Support-Vector-Machine.git
cd Support-Vector-Machine
```

### 2. Install dependencies

```bash
pip install numpy matplotlib scikit-learn
```

### 3. Run the notebook

Open:

```bash
svm_code.ipynb
```

---

## 📁 Project Structure

```
├── svm_code.ipynb
├── licence
├── README.md
└── svm.pdf
```

---

## ♿ Accessibility Features

* Colorblind-friendly plots
* Marker-based class distinction
* Clear labels and legends
* Grid-enhanced visualizations

---

## 📚 References

* Cortes, C., & Vapnik, V. (1995). *Support-vector networks*
* Pedregosa, F. et al. (2011). *Scikit-learn: Machine Learning in Python*
* Bishop, C. M. (2006). *Pattern Recognition and Machine Learning*
* Hastie, T. et al. (2009). *The Elements of Statistical Learning*

---

## 👨‍💻 Author

**Pradeep Raj Katipagala**
Student ID: 24145399

GitHub: [https://github.com/pradeep271/Support-Vector-Machine](https://github.com/pradeep271/Support-Vector-Machine)

---

## ⭐ Final Notes

This project highlights that:

* Proper **kernel selection** is crucial
* **Hyperparameter tuning** significantly improves performance
* **Simple models can perform as well as complex ones**
* **Visualization enhances understanding and communication**

---
