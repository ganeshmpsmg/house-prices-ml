# House Prices Prediction – ML Project

This project predicts **house sale prices** using machine learning techniques with Python and scikit-learn.  
The Jupyter notebook `1st_task-loaded.ipynb` contains the full workflow from **data loading** to **Kaggle submission**.

---

## 🗂 Project Structure

---

## 🔹 Dataset

- **train.csv** – Training data with features + target `SalePrice`  
- **test.csv** – Test data (features only)  
- **sample_submission.csv** – Sample CSV for Kaggle submission  

> Datasets are **not included** in this repository due to size.  
> Download them from Kaggle: [House Prices – Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

---

## 🔹 Workflow / Steps

1. **Load Data** – Using Pandas for train/test CSVs  
2. **EDA (Exploratory Data Analysis)** – Explore distributions, correlations, missing values  
3. **Data Preprocessing** – Handle missing values, encode categorical variables  
4. **Feature Engineering** – Scaling and transformations  
5. **Train/Test Split** – Split data for validation  
6. **Model Training** – Linear Regression & Random Forest Regressor  
7. **Model Evaluation** – Using RMSE metric  
8. **Final Predictions** – Train on full training data and predict on test set  
9. **Submission** – Save predictions in CSV format for Kaggle

---

## 🔹 Technologies Used

- Python 3.13  
- Jupyter Notebook  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- scikit-learn  

---

## 🔹 Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/house-prices-ml.git