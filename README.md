# 🚗 Small Car Price Prediction

This project builds a machine learning model to predict the **selling price of used cars** based on various features such as year, present price, kilometers driven, fuel type, seller type, transmission, and number of previous owners.

---

## 📌 Objective

The goal of this project is to:

* Analyze a dataset of used cars
* Perform data preprocessing and feature engineering
* Train regression models to predict car prices
* Compare model performance and select the best one

---

## 📊 Dataset

The dataset contains information about used cars, including:

* **Car_Name** – Name of the car
* **Year** – Year of manufacture
* **Selling_Price** – Price at which the car is sold (target variable)
* **Present_Price** – Current ex-showroom price
* **Kms_Driven** – Distance driven in kilometers
* **Fuel_Type** – Petrol / Diesel / CNG
* **Seller_Type** – Dealer / Individual
* **Transmission** – Manual / Automatic
* **Owner** – Number of previous owners

---

## ⚙️ Project Workflow

1. **Data Loading**
2. **Data Cleaning & Preprocessing**
3. **Categorical Encoding**
4. **Feature Engineering**

   * Created a new feature: **Car_Age**
5. **Exploratory Data Analysis (EDA)**
6. **Train-Test Split**
7. **Model Training**

   * Linear Regression
   * Lasso Regression
8. **Model Evaluation**
9. **Model Comparison**
10. **Final Prediction**
11. **Model Saving**

---

## 🧠 Models Used

* **Linear Regression**
* **Lasso Regression**

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## 🏆 Results

* **Lasso Regression performed better on test data**
* It showed better generalization compared to Linear Regression
* Therefore, **Lasso Regression was selected as the final model**

---

## 💡 Key Feature Engineering

A new feature was created:

```python
Car_Age = Current Year - Year of Manufacture
```

This improved model interpretability and performance.

---

## 🧪 Sample Prediction

The model can predict the selling price based on input features such as:

* Present Price
* Kms Driven
* Fuel Type
* Seller Type
* Transmission
* Owner
* Car Age





