### Support Vector Machines (SVM)

## 📌 Objective

Use **Support Vector Machines (SVM)** for both **linear** and **non-linear classification**, understand margin maximization, apply kernel tricks, tune hyperparameters, and visualize the decision boundary.

---

## 📁 Dataset
- **Name**: Breast Cancer Wisconsin Diagnostic Dataset  
- **Source**: `sklearn.datasets.load_breast_cancer()`  
- **Classes**: Binary classification – `0` = Malignant, `1` = Benign  
- **Features**: 30 numerical features extracted from cell nuclei images

---

## 🔧 Tools & Libraries

- Python  
- Scikit-learn  
- NumPy  
- Matplotlib / Seaborn  
- Pandas

---
## ✅ What I Implemented

| Feature                | Description                                                       |
|------------------------|-------------------------------------------------------------------|
| Data Preprocessing     | Scaled data using `StandardScaler` and split into train-test      |
| SVM with Linear Kernel | Trained a basic linear classifier                                 |
| SVM with RBF Kernel    | Captured non-linear relationships                                 |
| PCA Visualization      | Reduced features to 2D for plotting decision boundaries           |
| Hyperparameter Tuning  | Used `GridSearchCV` to find best `C` and `gamma`                  |
| Evaluation Metrics     | Printed accuracy, classification report, and confusion matrix     |
| Cross-Validation       | Applied 5-fold cross-validation for model reliability             |

---

## 📊 Results

| Model                    | Accuracy |
|--------------------------|----------|
| SVM (Linear Kernel)      | ~96%     |
| SVM (RBF Kernel)         | ~97%     |
| Tuned RBF SVM (Best)     | ~98%     |
| 5-Fold CV Accuracy       | ~91% ± 1.2% |

✅ **Best Parameters Found**:
```python
{'C': 1, 'gamma': 'scale', 'kernel': 'rbf'}
```
---
## 📈 Visualizations

- Decision boundary using PCA + Linear SVM  
- Confusion matrix for RBF SVM

---

## 🧠 Key Learnings

- Difference between linear and RBF kernel  
- Importance of feature scaling in SVMs  
- Margin maximization and how support vectors impact decision boundaries  
- GridSearchCV for tuning `C` and `gamma`  
- Visualizing high-dimensional data using PCA

---

## 👩 Author
Shweta Yenaji
