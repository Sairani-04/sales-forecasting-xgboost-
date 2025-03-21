# Sales Forecasting Using Time Series Analysis (Predictive Analytics)

## Project Overview
This project predicts future sales based on past trends using XGBoost. By analyzing historical sales data, businesses can optimize inventory, pricing, and marketing strategies for better decision-making.

## Technologies Used
- Python
- XGBoost (for predictive modeling)
- Pandas & NumPy (for data manipulation)
- Scikit-Learn (for preprocessing & evaluation)
- Matplotlib & Seaborn (for data visualization)

## Project Structure
```
sales-forecasting-xgboost
│-- sales_forecasting.ipynb   # Jupyter Notebook with model training & evaluation
│-- supermarket_sales.csv    # Dataset
│-- README.md                # Project documentation
│-- requirements.txt         # Python dependencies
```

## How to Run

1. Clone the Repository
   ```
   git clone https://github.com/<your-username>/sales-forecasting-xgboost.git
   cd sales-forecasting-xgboost
   ```
2. Install Dependencies
   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook
   ```
   jupyter notebook sales_forecasting.ipynb
   ```

## Model Performance
- **Best Model:** XGBoost Regressor
- **Hyperparameter Tuning:** GridSearchCV used for optimization
- **Evaluation Metrics:**
  - Mean Absolute Error (MAE): 2.41
  - Mean Squared Error (MSE): 13.98
  - R² Score: 0.9998

## Next Steps
- Further optimize the XGBoost model with advanced hyperparameter tuning
- Experiment with LSTM (Long Short-Term Memory) for time-series forecasting
- Implement real-time sales prediction using a Flask API

## License
This project is open-source and available under the MIT License.

Feel free to fork, contribute, or provide suggestions!

