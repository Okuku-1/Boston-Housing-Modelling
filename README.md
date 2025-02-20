# 🏡 Boston Housing Dataset Analysis

## 📌 Project Overview
In this project, we used the **Boston Housing Dataset** to build and evaluate different regression models for predicting house prices based on various features such as crime rate, number of rooms, and accessibility to highways.

---

## 🔹 Steps We Followed  

### 1️⃣ **Explored the Dataset**  
- Loaded the data and checked for missing values.  
- Analyzed the statistical distribution of features.  

### 2️⃣ **Performed Linear Regression**  
- Built a **Linear Regression model** to predict house prices.  
- Evaluated performance using **Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score**.  

### 3️⃣ **Polynomial Regression**  
- Transformed the features to **higher-degree polynomials**.  
- Observed improvement in model performance but checked for **overfitting**.  

### 4️⃣ **Feature Scaling & Regularization (Ridge & Lasso Regression)**  
- Applied **Ridge Regression** (L2 Regularization) to reduce model complexity.  
- Applied **Lasso Regression** (L1 Regularization) to perform feature selection.  
- Compared performance of **Linear, Polynomial, Ridge, and Lasso Regression** models.  

### 5️⃣ **Model Evaluation & Comparison**  
- Used **training and test errors** to assess model generalization.  
- Plotted **Residuals** to check model assumptions.  
- Compared all models to identify the best approach.  

---

## 🔹 Key Findings
- **Polynomial Regression** (Degree 2) improved predictions but risked **overfitting**.  
- **Ridge Regression** performed best in balancing bias-variance tradeoff.  
- **Lasso Regression** helped with feature selection but slightly reduced accuracy.  

---

## 📂 Technologies Used
✔ Python (NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn)  
✔ Regression Models (Linear, Polynomial, Ridge, Lasso)  

---

## 📊 Results Summary  

| Model                | Training MSE | Test MSE | Training R² | Test R² |
|----------------------|-------------|---------|------------|---------|
| **Linear Regression** | 24.29       | 24.29   | 0.67       | 0.67    |
| **Polynomial (Deg=2)** | 14.26      | 14.26   | 0.81       | 0.81    |
| **Ridge Regression**  | 6.98        | 11.21   | 0.92       | 0.85    |
| **Lasso Regression**  | 13.84       | 15.56   | 0.84       | 0.79    |

---

## 🚀 Conclusion  
This project serves as a foundational study on **regression techniques** and demonstrates how different models handle real-world data.  

📌 **Next Steps:**  
- Improve feature selection techniques.  
- Experiment with different polynomial degrees.  
- Try other regularization techniques like **ElasticNet**.  

---

👨‍💻 **Author:** _Eddy Okuku_  
📅 **Date:** _20/02/2025_   

---

📝 *Feel free to contribute, raise issues, or share feedback!* 🚀  
