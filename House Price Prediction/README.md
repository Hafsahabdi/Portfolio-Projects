# 🏠 House Price Prediction Using Regression

This project builds a regression-based machine learning model to predict house prices using data from the `kc_house_data.csv` dataset. The dataset includes features like house size, number of bedrooms, location, and condition ratings.

---

## 📊 Summary

This project walks through the process of data preprocessing, model training, evaluation, and improvement using regularization techniques.

### 1. 🧹 Data Exploration & Preprocessing
- Loaded and examined key features from `kc_house_data.csv`.
- Used a correlation heatmap to identify important predictors.
- One-hot encoded the `zipcode` column, resulting in **76 total features**.
- Split data into 80% training and 20% testing sets using `train_test_split()`.

### 2. 🤖 Model Development
- Trained a **Linear Regression** model on the selected features.
- Evaluated the model using unseen test data.

### 3. 📈 Model Evaluation
- **R² Score**: 0.6522 (model explains ~65.2% of price variance)
- **RMSE**: \$194,340
- **MAE**: \$109,983

### 4. 🛠 Regularization Techniques
- Applied **Ridge**, **Lasso**, and **ElasticNet** to reduce overfitting.
- Regularization added penalties to large coefficients, improving model generalization.

### 5. 💡 Key Insights & Future Improvements
- The baseline linear regression model performed moderately but showed high error.
- Future improvements could include:
  - Advanced feature engineering and outlier detection.
  - Testing non-linear models (e.g., **Random Forest**, **XGBoost**).
  - Hyperparameter tuning for regularization models.

---

## 🔧 Tools & Libraries
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook

---

## ▶️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Hafsahabdi/Portfolio-Projects.git
   cd Portfolio-Projects/House Price Prediction

 ## How to Contribute
Contributions are welcome! To suggest improvements or add features:

Fork the repository.

Create a new branch:

bash
Copy
Edit
git checkout -b feature-name
Commit your changes:

bash
Copy
Edit
git commit -m "Describe your changes"
Push to your branch:

bash
Copy
Edit
git push origin feature-name
Open a pull request and explain your changes.
