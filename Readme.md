# 🚗 Car Price Prediction using Machine Learning

## 📌 Internship Project - CodeAlpha

This project is developed as part of the **CodeAlpha Data Science Internship**.
It predicts the **selling price of used cars** using Machine Learning techniques.

---

## 🎯 Objective

* Predict car prices based on features like:

  * Year
  * Present Price
  * Kilometers Driven
  * Fuel Type
  * Transmission
* Apply regression algorithms for prediction
* Evaluate model performance

---

## 📊 Dataset

The dataset contains details of used cars including:

* Car_Name
* Year
* Selling_Price
* Present_Price
* Kms_Driven
* Fuel_Type
* Seller_Type
* Transmission
* Owner

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

1. Data Collection
2. Data Cleaning
3. Feature Engineering

   * Created **Car Age** feature
4. Encoding categorical variables
5. Train-Test Split
6. Model Training (Random Forest Regressor)
7. Model Evaluation
8. Visualization

---

## 🤖 Machine Learning Model

* **Random Forest Regressor**
* Handles non-linear relationships effectively
* Provides feature importance

---

## 📈 Model Performance

* R² Score: ~0.90+
* MAE: Low error
* Good prediction accuracy on unseen data

---

## 📊 Visualizations

* Correlation Heatmap
* Actual vs Predicted Graph
* Feature Importance Graph

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

---

## 🚀 How to Run

1. Clone repository:

```bash
git clone https://github.com/Thomas09022006/CodeAlpha_CarPricePrediction.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📌 Key Features

✔ Data preprocessing
✔ Feature engineering
✔ Model training & evaluation
✔ Visualization
✔ Model saving

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Add more features (engine, brand value)
* Deploy using Streamlit/Flask
* Build real-time prediction system

---

## 🙌 Acknowledgement

This project was completed under the **CodeAlpha Internship Program**, providing hands-on experience in Machine Learning and Data Science.

---

## 👤 Author

**Sanjay Thomas**
Data Science Intern
