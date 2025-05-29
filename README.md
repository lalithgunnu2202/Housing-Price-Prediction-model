# 🏠 House Price Prediction - ML Regression Project

This project predicts house prices based on various features like area, number of bedrooms, bathrooms, furnishing status, and more. It uses **Linear Regression** as a baseline model, with potential upgrades to **tree-based models** for better performance.

## 📊 Dataset

The dataset contains 545 entries and 14 columns:

- `price` (Target variable)
- `area`, `bedrooms`, `bathrooms`, `stories`, `parking` (Numerical)
- `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea` (Binary)
- `furnishingstatus` (Categorical, one-hot encoded into `furnish_semi-furnished`, `furnish_unfurnished`)

---

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`

---

## 📈 Model Pipeline

1. **Preprocessing**
   - One-hot encoding for categorical features
   - Feature scaling (optional)
   - Train-test split (62-38)

2. **Model**
   - Linear Regression using `sklearn.linear_model.LinearRegression`

3. **Evaluation**
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score

4. **Visualization**
   - Actual vs Predicted Price Plot
   - Residual plot
   - Reference line (`y = x`) for visual comparison

---

## 📌 How to Run

```bash
# Step 1: Clone the repo
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Run the notebook or script
