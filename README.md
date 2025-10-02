# Support Vector Machine (SVM) Classifier with Visualization

This project implements a **Support Vector Machine (SVM)** classifier using Python and scikit-learn.  
It is designed to be **dataset-agnostic** — meaning the code will automatically use your dataset if you have already defined `X` and `y`, or fallback to the Iris dataset if no dataset is provided.  

The pipeline includes **training, hyperparameter tuning, evaluation, cross-validation, and visualization** (using PCA for 2D reduction).

---

## 📌 Features
- Automatic dataset handling (uses your dataset if available, otherwise defaults to Iris dataset).
- Train/test split with stratification.
- Hyperparameter tuning using **GridSearchCV**.
- Evaluation with:
  - Accuracy score
  - Classification report
  - Confusion matrix heatmap
- **Cross-validation (CV)** for reliable performance metrics.
- **Memory-safe visualization** of decision boundaries using PCA (2D reduction).
- Works seamlessly in **Google Colab / Jupyter Notebook**.

---

## 🛠️ Tech Stack
- **Python 3**
- **scikit-learn** (SVM, PCA, GridSearchCV, metrics)
- **Matplotlib** & **Seaborn** (visualizations)
- **NumPy**

---

## 🚀 How to Run

1. Clone the repository or open the notebook in Google Colab.
2. Ensure the following libraries are installed:
   ```bash
   pip install numpy scikit-learn matplotlib seaborn
