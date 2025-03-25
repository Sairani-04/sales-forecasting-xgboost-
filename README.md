# **Sales Forecasting Using XGBoost (Predictive Analytics)**

## **Project Overview**

This project aims to **predict future sales** using **XGBoost**, a powerful machine learning algorithm. By analyzing historical sales data, businesses can improve **inventory management, pricing strategies, and marketing decisions** to maximize revenue.

## **Technologies Used**

- **Python** (Data processing & modeling)
- **XGBoost** (Predictive modeling)
- **Pandas & NumPy** (Data manipulation)
- **Scikit-Learn** (Preprocessing & evaluation)
- **Matplotlib & Seaborn** (Data visualization)

## **Project Structure**

```
sales-forecasting-xgboost
│-- sales_forecasting.ipynb   # Jupyter Notebook with model training & evaluation
│-- supermarket_sales.csv     # Dataset
│-- README.md                 # Project documentation
│-- requirements.txt          # Python dependencies
```

## **How to Run**

### **Clone the Repository**

```bash
git clone https://github.com/<your-username>/sales-forecasting-xgboost.git
cd sales-forecasting-xgboost
```

### **Install Dependencies**

```bash
pip install -r requirements.txt
```

### **Open the Jupyter Notebook**

```bash
jupyter notebook sales_forecasting.ipynb
```

## **Model Performance**

- **Best Model:** XGBoost Regressor
- **Hyperparameter Tuning:** GridSearchCV used for optimization
- **Evaluation Metrics:**
  - **Mean Absolute Error (MAE):** 9.83
  - **Root Mean Squared Error (RMSE):** 253.9
  - **R² Score:** 0.9964

## **Next Steps**

- **Enhance feature engineering** to improve accuracy.
- **Optimize hyperparameters** further using Bayesian Optimization.
- **Experiment with deep learning models (LSTM, GRU)** for time-series forecasting.
- **Deploy a real-time prediction system** using a Flask or FastAPI backend.

## **License**

This project is open-source and available under the **MIT License**.

Feel free to **fork, contribute, or provide suggestions**!

