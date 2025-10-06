# 🚖 Taxi Demand Forecasting

Forecasting the number of taxi orders using time series data and machine learning methods.  
The goal of this project is to build a model that predicts taxi demand and helps optimize the number of available drivers during peak hours.

## 📊 Tech Stack
- Python 3.11+
- pandas, numpy, scipy
- scikit-learn, statsmodels
- LightGBM, XGBoost, CatBoost
- matplotlib, seaborn

## ⚙️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/USERNAME/taxi-demand-forecasting.git
cd taxi-demand-forecasting

# core environment
pip install -r requirements.txt

# Jupyter Notebook support
pip install -r dev-requirements.txt
```

🚀 Usage

Open the Jupyter notebook: "taxi_demand_forecasting.ipynb"

📈 Models and Metrics

- Linear Regression
- Ridge
- Decision Tree Regressor
- Random Forest Regressor
- LightGBM

Evaluation metric: RMSE
Additionally, training and inference times are recorded for fair model comparison.

📂 Project Structure
```
├── requirements.txt          # minimal dependencies
├── dev-requirements.txt      # extended dependencies (jupyter, viz)
├── Прогнозирование заказов такси (1).ipynb
└── README.md
```
## 📝 Author
Educational project on time series forecasting and machine learning.  
Developed by [artemxdata](https://github.com/artemxdata).
