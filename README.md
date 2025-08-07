# 📈 Linear & Multiple Regression – Sales Prediction

This project demonstrates both **Simple Linear Regression** and **Multiple Linear Regression** using the [Advertising dataset](https://www.kaggle.com/datasets/ashydv/advertising-dataset) to predict product sales based on ad spending.

## 🗂 Dataset

- The dataset used is `Advertising.csv` (included in this repo).
- It contains advertising budgets in different media channels and their corresponding sales:
  
| TV | Radio | Newspaper | Sales |
|----|-------|-----------|-------|
| 230.1 | 37.8 | 69.2 | 22.1 |
| ... | ... | ... | ... |

## 💡 Objectives

- Build a **Simple Linear Regression** model using `TV` ad spend.
- Build a **Multiple Linear Regression** model using `TV`, `Radio`, and `Newspaper`.
- Evaluate both models using MAE, MSE, and R².
- Visualize the regression line for simple regression.

---

## 🚀 How to Run

### 🧩 Requirements

- Python 3.7+
- `pandas`
- `matplotlib`
- `scikit-learn`
- For Google Colab: `google.colab` module is pre-installed.

### 📦 Steps

1. Clone the repo or download the ZIP.
2. Open the Jupyter Notebook or Python file:
   - `linear_regression_simple.ipynb` for simple regression (TV vs Sales)
   - `multiple_regression.ipynb` for multiple regression (TV + Radio + Newspaper)
3. Upload the `Advertising.csv` file when prompted (if using Colab), or keep it in the same directory.
4. Run all cells.

---

## 🧪 Evaluation Metrics

| Metric | Description |
|--------|-------------|
| MAE (Mean Absolute Error) | Average of absolute errors |
| MSE (Mean Squared Error)  | Average of squared errors |
| R² Score                  | Proportion of variance explained by the model |

---

## 📊 Output Example (Simple Linear Regression)

- Regression Line: Red line showing predicted Sales based on TV budget.
- Scatter Plot: Actual Sales vs TV ad spend.
- Metrics printed: MAE, MSE, R²

---

## 📁 Files in This Repo

| File | Description |
|------|-------------|
| `Advertising.csv` | Dataset used for modeling |
| `linear_regression_simple.ipynb` | Notebook for simple regression |
| `multiple_regression.ipynb` | Notebook for multiple regression |
| `README.md` | This file |

---

## 👨‍💻 Author

- Your Name (Optional)
- Internship Task 3 – Linear Regression Project

---

## 📚 References

- [Scikit-learn documentation](https://scikit-learn.org/stable/)
- [Advertising Dataset – Kaggle](https://www.kaggle.com/datasets/ashydv/advertising-dataset)
