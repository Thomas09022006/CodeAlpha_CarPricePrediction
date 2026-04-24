# 🚗 Car Price Prediction using Machine Learning

## 📌 CodeAlpha Data Science Internship Project

This project focuses on predicting the **selling price of used cars** using Machine Learning techniques.
It was developed as part of the **CodeAlpha Data Science Internship**, demonstrating practical skills in data preprocessing, model building, and evaluation.

---

## 🎯 Objective

* Predict car prices based on multiple features
* Perform data cleaning and feature engineering
* Train and evaluate machine learning models
* Generate meaningful insights using visualization

---

## 📊 Dataset Description

The dataset includes the following features:

* **Car_Name** – Name of the car
* **Year** – Year of purchase
* **Selling_Price** – Target variable
* **Present_Price** – Current ex-showroom price
* **Kms_Driven** – Distance driven
* **Fuel_Type** – Petrol/Diesel/CNG
* **Seller_Type** – Dealer/Individual
* **Transmission** – Manual/Automatic
* **Owner** – Number of previous owners

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔄 Project Workflow

1. **Data Collection**
2. **Data Cleaning**

   * Removed unnecessary columns
3. **Feature Engineering**

   * Created `Car_Age = Current Year - Year`
4. **Encoding**

   * Converted categorical variables using one-hot encoding
5. **Train-Test Split**
6. **Model Training**

   * Random Forest Regressor
7. **Model Evaluation**
8. **Visualization**

---

## 🤖 Machine Learning Model

* **Algorithm:** Random Forest Regressor
* Handles complex and non-linear relationships
* Provides feature importance for interpretability

---

## 📈 Model Performance

| Metric   | Value  |
| -------- | ------ |
| R² Score | ~0.90+ |
| MAE      | Low    |

✔ The model shows strong predictive performance on unseen data

---

## 📊 Visualizations

* 🔥 Correlation Heatmap
* 📉 Actual vs Predicted Price Plot
* 📊 Feature Importance Graph

---

## 💾 Model Saving & Loading

### Save Model

```python
import pickle
with open("car_price_model.pkl", "wb") as f:
    pickle.dump(model, f)
```

### Load Model

```python
with open("car_price_model.pkl", "rb") as f:
    model = pickle.load(f)
```

⚠️ Note: The `.pkl` file is a binary file and cannot be opened directly.

---

## 🚀 How to Run the Project

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Thomas09022006/CodeAlpha_CarPricePrediction.git
```

### 2️⃣ Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3️⃣ Run Notebook

```bash
jupyter notebook
```

---

## 📌 Key Highlights

✔ End-to-end Machine Learning workflow
✔ Feature engineering improves accuracy
✔ Clean and structured implementation
✔ Visualization for better understanding
✔ Model saved for future use

---

## 🔮 Future Enhancements

* Hyperparameter tuning for improved accuracy
* Integration with web apps (Streamlit/Flask)
* Real-time price prediction system
* Deployment on cloud platforms

---

## 🙌 Acknowledgement

This project was successfully completed under the **CodeAlpha Internship Program**, providing valuable hands-on experience in Data Science and Machine Learning.

---

## 👤 Author

**Sanjay Thomas**
Data Science Intern
GitHub: https://github.com/Thomas09022006
