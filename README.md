# House Prices Prediction – Machine Learning Project

This project focuses on predicting house sale prices using machine learning techniques.  
The solution is implemented in **Python** using **Jupyter Notebook** and trained on the **Kaggle House Prices dataset**.

The notebook demonstrates the **complete ML workflow** including data loading, preprocessing, model training, evaluation, and final prediction submission.

---

## 📌 Project Overview

- **Problem Type**: Regression
- **Goal**: Predict the final sale price of residential homes
- **Evaluation Metric**: RMSE (Root Mean Squared Error)
- **Platform**: Kaggle – House Prices Competition

---

## 📂 Project Structure
house-prices-ml/
│
├── 1st_task-loaded.ipynb # Main Jupyter notebook (full ML pipeline)
├── README.md # Project documentation
├── requirements.txt # Required Python packages
├── submission_v1.csv # Final prediction file (optional)
└── .gitignore # Ignored files and folders 

---

## 📊 Dataset Information

- **Dataset Name**: House Prices – Advanced Regression Techniques
- **Source**: Kaggle
- **Link**: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

### Files Used
- `train.csv` – Training data (features + target `SalePrice`)
- `test.csv` – Test data (features only)
- `sample_submission.csv` – Submission format reference

> ⚠️ Dataset files are **not included** in this repository due to size constraints.

---

## ⚙️ Technologies & Libraries

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

---

## 🧠 Machine Learning Models

- **Baseline Model**: Linear Regression  
- **Primary Model**: Random Forest Regressor  

---

## 📈 Model Evaluation

- **Metric Used**: RMSE (Root Mean Squared Error)
- Lower RMSE indicates better model performance

> Model evaluation is performed using a train-validation split.

---

## 🔄 Workflow Steps

1. Load training and test datasets
2. Exploratory Data Analysis (EDA)
3. Handle missing values
4. Encode categorical variables
5. Feature scaling
6. Train machine learning models
7. Evaluate model performance
8. Predict house prices for test data
9. Generate submission file

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/ganeshmpsmg/house-prices-ml.git