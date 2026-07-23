# ANN
# Concrete Strength Prediction using Machine Learning

A machine learning project for predicting the **Compressive (C-Strength)**, **Tensile (T-Strength)**, and **Flexural (F-Strength)** of Normal and Bacterial Concrete using experimental data. Multiple regression models are evaluated and compared to identify the most accurate predictor.

---

## Features

- Predicts:
  - Compressive Strength
  - Tensile Strength
  - Flexural Strength
- Data preprocessing using Scikit-learn Pipelines
- Feature scaling and categorical encoding
- 5-Fold Cross Validation
- Model comparison using **R², RMSE, and MAE**
- Hyperparameter tuning with **GridSearchCV**
- Ensemble learning for improved prediction accuracy
- Experimental vs. predicted strength validation

---

## Models Used

- Random Forest Regressor
- Support Vector Regressor (SVR)
- Artificial Neural Network (ANN)
- Decision Tree Regressor
- Gradient Boosting Regressor
- Bayesian Ridge Regressor
- Kernel Ridge Regressor
- Weighted Ensemble Model

---

## Tech Stack

- Python
- Scikit-learn
- TensorFlow / Scikeras
- Pandas
- NumPy
- Matplotlib
- SciPy

---

## Project Structure

```
.
├── c_strength.py
├── f_all_regression.py
├── f_ann.py
├── t_strength_ann_final.ipynb
├── datasets/
├── results/
└── README.md
```

---

## Installation

```bash
git clone https://github.com/ajju170207/ANN.git

cd project
```

---

## Run

```bash
python c_strength.py
```

or

```bash
python f_all_regression.py
```

---

## Evaluation Metrics

- R² Score
- RMSE
- MAE

---

## Author

**Ajay Vinod Sharma**  
B.Tech – Artificial Intelligence & Data Science  
Vidya Pratishthan's Kamalnayan Bajaj Institute of Engineering & Technology (VPKBIET)

---

## License

This project is intended for academic and research purposes.