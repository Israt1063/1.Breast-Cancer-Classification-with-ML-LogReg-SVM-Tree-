


# Breast Cancer Classifier using Machine Learning

This project implements a supervised machine learning pipeline to classify breast cancer tumors as **malignant** or **benign** using multiple algorithms including Logistic Regression, Decision Tree, and Support Vector Machine (SVM). The models are trained and evaluated on the popular Breast Cancer Wisconsin dataset.

---

## 📂 Project Structure

- `breast_cancer_classifier.ipynb` — Jupyter notebook with full data exploration, model training, and evaluation.
- `breast_cancer_logreg_model.pkl` — Saved Logistic Regression model.
- `breast_cancer_decision_tree.pkl` — Saved Decision Tree model.
- `breast_cancer_svm_model.pkl` — Saved SVM model.
- `README.md` — Project documentation.
- `.gitignore` — Git ignore file to exclude unnecessary files.

---



### Prerequisites

- Python 3.x
- Jupyter Notebook or Google Colab
- Required libraries:
  ```bash
  pip install numpy pandas scikit-learn matplotlib seaborn joblib
````

---




## 📊 Models Used

* Logistic Regression
* Decision Tree Classifier
* Support Vector Machine (SVM)

---

## 🔍 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC

---

## 📈 Results Summary

| Model               | ROC-AUC Score |
| ------------------- | ------------- |
| Logistic Regression | 1.00          |
| Decision Tree       | 0.94          |
| SVM                 | 1.00          |

---

## ⚠️ Notes

* This project uses supervised learning with labeled data.
* Models are trained on the Breast Cancer Wisconsin dataset.
* Perfect ROC-AUC may indicate overfitting; cross-validation recommended.

---

## 📚 References

* [Breast Cancer Wisconsin Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
* [Scikit-learn Documentation](https://scikit-learn.org/stable/)

---

## 👤 Author

Your Name — [GitHub Profile](https://github.com/Israt1063)

---

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

