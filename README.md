# 🏠 Bengaluru House Price Prediction

A Machine Learning project that predicts house prices in Bengaluru using various regression algorithms. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, hyperparameter tuning, and model serialization.

---

## 📌 Project Overview

The goal of this project is to build a machine learning model capable of accurately predicting house prices in Bengaluru based on property features. Multiple regression algorithms are trained and compared to determine the best-performing model.

---

## 📂 Project Structure

```
├── Bangaluru_House_Price_Dataset.ipynb   # Jupyter Notebook
├── Bengaluru_House_Data.csv              # Dataset
├── README.md                             # Project documentation
└── model.pkl                             # Saved trained model (generated)
```

---

## 🚀 Features

- Data loading and preprocessing
- Handling missing values
- Exploratory Data Analysis (EDA)
- Feature engineering
- Encoding categorical variables
- Training multiple regression models
- Hyperparameter tuning using GridSearchCV and RandomizedSearchCV
- Model performance evaluation
- Saving the best model using Pickle

---

## 📊 Dataset

The project uses the **Bengaluru House Price Dataset**, which contains information such as:

- Area Type
- Availability
- Location
- Size (BHK)
- Total Square Feet
- Number of Bathrooms
- Balcony
- Price

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Pickle

---

## 🤖 Machine Learning Models

The following regression algorithms are implemented and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- K-Nearest Neighbors (KNN) Regressor
- Support Vector Regressor (SVR)

---

## 📈 Model Evaluation

The models are evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

Hyperparameter tuning is performed using:

- GridSearchCV
- RandomizedSearchCV

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/bengaluru-house-price-prediction.git
```

Navigate to the project folder:

```bash
cd bengaluru-house-price-prediction
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Bangaluru_House_Price_Dataset.ipynb
```

---

## ▶️ Usage

1. Load the dataset.
2. Perform preprocessing and cleaning.
3. Train the regression models.
4. Compare model performance.
5. Tune hyperparameters.
6. Save the best-performing model.
7. Use the saved model for house price prediction.

---

## 📌 Results

The notebook compares the performance of multiple regression algorithms and identifies the model that provides the best prediction accuracy for Bengaluru house prices.

---

## 🔮 Future Improvements

- Build a Flask or Streamlit web application
- Deploy the model on the cloud
- Add location-based visualization
- Use advanced boosting algorithms such as XGBoost, LightGBM, or CatBoost
- Perform automated feature selection

---

## 👨‍💻 Author

**Abdulla Ishaq**

---

## 📄 License

This project is intended for educational and learning purposes.
