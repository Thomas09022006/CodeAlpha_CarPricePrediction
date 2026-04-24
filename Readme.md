# 🚗 Car Price Prediction - CodeAlpha Internship

## 📌 Project Overview

This project predicts the **selling price of cars** using Machine Learning techniques.
It was developed as part of the **CodeAlpha Data Science Internship**.

The model analyzes various car features such as fuel type, transmission, kilometers driven, and car age to estimate the price.

---

## 🎯 Objective

* Build a regression model to predict car prices
* Perform data preprocessing and feature engineering
* Evaluate model performance
* Visualize insights from data

---

## 📊 Dataset

The dataset contains information about used cars, including:

* Year of purchase
* Present price
* Kilometers driven
* Fuel type
* Seller type
* Transmission
* Number of previous owners

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔄 Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering (Car Age calculation)
4. Encoding categorical variables
5. Train-Test Split
6. Model Training (Random Forest Regressor)
7. Model Evaluation
8. Visualization

---

## 🤖 Machine Learning Model

* **Algorithm Used:** Random Forest Regressor
* Handles non-linear relationships effectively
* Provides feature importance

---

## 📈 Results

* Achieved high accuracy with strong R² score
* Low Mean Absolute Error (MAE)
* Model performs well on unseen data

---

## 📊 Visualizations

* Correlation Heatmap
* Actual vs Predicted Price Graph
* Feature Importance Plot

---

## 💾 Model Saving

The trained model is saved using **Pickle**:

```python
import pickle
with open("car_price_model.pkl", "wb") as f:
    pickle.dump(model, f)
```

---

## 🔮 Future Improvements

* Add more features (brand value, engine capacity, etc.)
* Deploy as a web application (Streamlit/Flask)
* Hyperparameter tuning for better accuracy

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/Thomas09022006/CodeAlpha_CarPricePrediction.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook or script:

```bash
jupyter notebook
```

---

## 🙌 Acknowledgement

This project was completed as part of the **CodeAlpha Internship Program**, providing hands-on experience in data science and machine learning.

---

## 📌 Author

**Sanjay Thomas**
Data Science Intern
