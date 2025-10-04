# Diabetes Prediction

**Objective:**  
Predict whether a patient has diabetes based on medical attributes.


## Techniques Used

- Data Cleaning & Exploration  
- Exploratory Data Analysis (EDA) using Matplotlib & Seaborn  
- Feature Scaling using `StandardScaler`  
- Train-Test Split (80/20)  

---

## Models Implemented

- Logistic Regression  

---

## Model Evaluation

- Accuracy Score  
- Confusion Matrix  
- Classification Report  
- Confusion Matrix Visualization  

---

## Predictive System

Sample predictions on new patient data using the trained Logistic Regression model:

```python
sample1 = np.array([[6,148,72,35,0,33.6,0.627,50]])
sample_scaled = scaler.transform(sample1)
prediction = model.predict(sample_scaled)
