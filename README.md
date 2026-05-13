# 🚗 Vehicle Price Prediction using Random Forest

## 📌 Project Overview
This project applies a **Random Forest Regressor** to estimate the market value of used vehicles based on historical sales data. By analyzing mechanical, temporal, and market features, the model provides a data-driven approach to car valuation, assisting buyers and sellers in determining fair market prices through automated regression analysis.

## 🛠️ Key Features
- **Regression Engine:** Implements a Scikit-Learn `RandomForestRegressor` with 90 estimators to handle continuous price variables, moving beyond simple classification to precise value estimation.
- **Categorical Encoding:** Utilizes `LabelEncoder` to transform fuel types, transmission modes, and seller categories into machine-readable numerical formats for the model pipeline.
- **Optimized Preprocessing:** Handles multi-dimensional features including vehicle age, usage (KM driven), and ownership history to minimize prediction variance and maximize R² scores.
- **Predictive Inference:** Includes a custom testing module to input real-world vehicle specifications and receive instantaneous price predictions.

## 📋 Data Features
The model analyzes the following 6 core features to determine vehicle value:
- **Temporal:** Manufacturing Year (Tracks vehicle depreciation over time).
- **Usage:** Kilometers (KM) Driven (Quantifies mechanical wear and tear).
- **Technical:** Fuel Type (Petrol, Diesel, CNG, LPG) and Transmission (Manual vs. Automatic).
- **Market:** Seller Type (Individual vs. Dealer) and Owner History (Number of previous owners).

## 🚀 Installation & Usage
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/vehicle-price-prediction.git](https://github.com/your-username/vehicle-price-prediction.git)
