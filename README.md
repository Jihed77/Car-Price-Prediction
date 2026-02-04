# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict the selling price of used cars using Machine Learning models.  
We implemented and compared:

- **Linear Regression**
- **Lasso Regression (L1 Regularization)**

The goal is to analyze how different car features influence price and evaluate model performance using the **R² score**.

---

## 📊 Dataset

The dataset contains information about used cars, including:

- Car Name
- Year
- Present Price
- Kms Driven
- Fuel Type
- Seller Type
- Transmission
- Owner
- Selling Price (Target)

---

## ⚙️ Project Workflow

1. Data Loading  
2. Data Preprocessing  
   - Encoding categorical variables  
   - Feature engineering (Car Age creation)  
3. Train/Test Split  
4. Model Training  
   - Linear Regression  
   - Lasso Regression  
5. Model Evaluation (R² Score)  
6. Visualization of predictions  

---

## 🧠 Feature Engineering

We transformed:

Car_Age = Current Year - Manufacturing Year


This improves model interpretability and predictive power.

---

## 📈 Models Used

### 1️⃣ Linear Regression
- Baseline regression model
- No regularization

### 2️⃣ Lasso Regression
- Uses L1 regularization
- Helps reduce overfitting
- Performs feature selection

---

## 📊 Model Evaluation

Performance was evaluated using:

- **R² Score (Coefficient of Determination)**

Example output:

Linear Regression R² Train: 0.88
Linear Regression R² Test : 0.84

Lasso R² Train: 0.86
Lasso R² Test : 0.83


---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn



---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/Jihed77/Car-Price-Prediction.git

2. Navigate into the project folder:
cd Car-Price-Prediction

3. Make sure you have Python installed

4. Install the required libraries manually:
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

5. Launch Jupyter Notebook:
jupyter notebook

6. Open:
Car_Price_Prediction_Notebook_.ipynb

7. Run all cells.
