# 🚗 Car Price Prediction using Machine Learning

A Machine Learning project that predicts the selling price of used cars based on various features such as present price, kilometers driven, fuel type, transmission type, ownership history, and vehicle age.

---

## 📌 Project Overview

The objective of this project is to build a regression model capable of estimating the resale value of a car. By analyzing historical car data and applying machine learning techniques, the model learns the relationship between vehicle characteristics and selling price.

This project demonstrates the complete machine learning workflow, including:

- Data Collection
- Data Preprocessing
- Feature Engineering
- Data Visualization
- Model Training
- Model Evaluation
- Price Prediction

---

## 📊 Dataset

The dataset contains information about used cars, including:

- Car Name
- Manufacturing Year
- Present Price
- Selling Price
- Kilometers Driven
- Fuel Type
- Seller Type
- Transmission Type
- Number of Previous Owners

### Target Variable

**Selling_Price** – The price at which the car is sold.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔧 Data Preprocessing

The following preprocessing steps were performed:

- Created a new feature: **Car_Age**
- Removed unnecessary columns (`Car_Name`, `Year`)
- Encoded categorical variables:
  - Fuel_Type
  - Selling_type
  - Transmission
- Split data into training and testing sets

---

## 📈 Data Visualization

Matplotlib and Seaborn were used to visualize:

- Selling Price Distribution
- Correlation Heatmap
- Actual vs Predicted Prices
- Residual Plot
- Feature Importance Graph

---

## 🤖 Machine Learning Model

### Random Forest Regressor

Random Forest Regression was used because:

- Handles non-linear relationships effectively
- Reduces overfitting through ensemble learning
- Provides feature importance scores
- Produces high prediction accuracy

---

## 📂 Project Structure

```text
Car-Price-Prediction/
│
├── car data.csv
├── Car_Price_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Car-Price-Prediction.git
```

Move into the project folder:

```bash
cd Car-Price-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Car_Price_Prediction.ipynb
```

Run all cells sequentially.

---

## 📋 Features Used for Prediction

The model uses the following features:

- Present_Price
- Driven_kms
- Fuel_Type
- Selling_type
- Transmission
- Owner
- Car_Age

---

## 📊 Model Evaluation Metrics

The model performance was evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

A higher R² score and lower MAE/RMSE indicate better model performance.

---

## 🔮 Sample Prediction

Example Input:

```text
Present Price = 5.59
Driven Kms = 27000
Fuel Type = Petrol
Selling Type = Dealer
Transmission = Manual
Owner = 0
Car Age = 11
```

Example Output:

```text
Predicted Selling Price = 3.25 Lakhs
```

---

---

## 📚 Learning Outcomes

Through this project, the following concepts were applied:

- Data Cleaning
- Feature Engineering
- Label Encoding
- Regression Analysis
- Model Evaluation
- Data Visualization
- Predictive Modeling

---

## 👩‍💻 Author

**MANAN SUTARIYA**
---

## ⭐ If you found this project useful, consider giving it a star!
