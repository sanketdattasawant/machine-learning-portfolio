
# 📈 Linear Regression – Concept, Example & Implementation

**Linear Regression** is one of the simplest and most widely used Machine Learning algorithms. It is used to model the relationship between a dependent variable (target) and one or more independent variables (features) by fitting a linear equation.

---

## 🔢 Formula (Simple Linear Regression)

y = θ₀ + θ₁x

Where:
- y is the predicted value
- x is the input feature
- θ₀ is the intercept (bias)
- θ₁ is the slope (coefficient)

---

## 📘 Real-World Example – Predicting Bike Rental Demand

Let’s say a bike rental company wants to predict how many bikes will be rented based on the temperature of the day.

| Temperature (°C) | Bikes Rented |
|------------------|--------------|
| 10               | 100          |
| 15               | 200          |
| 20               | 300          |
| 25               | 400          |

We can train a linear regression model to learn the pattern: as temperature increases, so does demand.

---

## 🧠 How It Works

- **Loss Function:** Mean Squared Error (MSE) is used to measure the difference between predicted and actual values.
- **Optimization:** Gradient Descent is often used to minimize the loss and update θ₀ and θ₁ iteratively.

---

## 📊 Visual Representation

A straight line that best fits the data points in a 2D plot (x = feature, y = prediction).

---

## 🛠️ Use Cases
- Predicting house prices based on square footage
- Estimating insurance costs based on age/income
- Forecasting product sales using ad spend

---

> 🚀 Linear regression is often the starting point for learning more advanced ML algorithms. Though simple, it’s powerful and forms the foundation for deeper statistical modeling.

