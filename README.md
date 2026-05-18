# 🚗 Vehicle Price Prediction using Random Forest

## 📌 Project Overview
This project applies a **Random Forest Regressor** to estimate the market value of used vehicles based on historical sales data. By analyzing mechanical, temporal, and market features, the model provides a data-driven approach to car valuation, assisting buyers and sellers in determining fair market prices through automated ensemble regression analysis.

## 🛠️ Key Features
* **Regression Engine:** Implements a Scikit-Learn `RandomForestRegressor` configured with 90 estimators to capture non-linear relationships across continuous price variables, moving beyond simple classification to precise value estimation.
* **Categorical Encoding:** Utilizes `LabelEncoder` to seamlessly transform nominal structural columns like fuel types, transmission modes, and seller categories into machine-readable numerical formats for the training pipeline.
* **Optimized Preprocessing:** Evaluates multi-dimensional characteristics including vehicle age, usage (KM driven), and ownership history to significantly minimize prediction variance and optimize the final $R^2$ score.
* **Predictive Inference:** Includes a custom testing utility designed to accept real-world vehicle specifications and return instantaneous, calibrated market value predictions.

## 📋 Data Features
The model analyzes the following 6 core features to determine vehicle value:
* **Temporal:** Manufacturing Year (Tracks asset depreciation curves over time).
* **Usage:** Kilometers (KM) Driven (Quantifies structural and mechanical wear and tear).
* **Technical:** Fuel Type (Petrol, Diesel, CNG, LPG) and Transmission Mode (Manual vs. Automatic).
* **Market Variables:** Seller Type (Individual vs. Dealer) and Owner History (Number of previous owners).

## 💻 Tech Stack
* **Language:** Python 3.x
* **Data Processing:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (`RandomForestRegressor`, `LabelEncoder`, `train_test_split`)
* **Data Visualization:** Matplotlib, Seaborn

---

## 🚀 How to Run the Code

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ShehrozGhouri/Car-Price-Prediction-Model-Random-Forest.git](https://github.com/ShehrozGhouri/Car-Price-Prediction-Model-Random-Forest.git)
    cd Car-Price-Prediction-Model-Random-Forest
    ```

2.  **Install Required Dependencies:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```

3.  **Run the project:**
    Execute your primary python training script or Jupyter Notebook to process the raw parameters, assemble the decision tree estimators, and check the performance validation metrics.
