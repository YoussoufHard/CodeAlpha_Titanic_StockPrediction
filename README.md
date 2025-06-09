# CodeAlpha Tasks - Titanic Classification & Stock Price Prediction

Welcome to this repository containing the solutions for **TASK 1** and **TASK 2** of the CodeAlpha challenge.

---

## Project Structure

```

├── Task1_Titanic_Classification
│   ├── .ipynb\_checkpoints
│   ├── Titanic Survival.ipynb
│   └── train.csv
│
└── Task2\_Stock\_Prediction
├── .ipynb\_checkpoints
├── AAPL_stock_data.csv
├── lstm_stock_model.keras
├── stock_prediction.ipynb
├── README.md
└── requirements.txt

````

---

## Task Descriptions

### TASK 1 - Titanic Classification
This notebook implements a classification model to predict whether a Titanic passenger survived or not.  
**Objectives:**  
- Analyze the factors affecting survival such as age, gender, socio-economic status, and more.  
- Perform data preprocessing and handle missing values.  
- Build and evaluate classification models (e.g., Random Forest, Logistic Regression).

The `train.csv` file contains the raw data used for training.

---

### TASK 2 - Stock Price Prediction
This notebook uses an LSTM model to predict the future stock price of a company (example: Apple - AAPL).  
**Objectives:**  
- Download and preprocess historical stock price data.  
- Build an LSTM model for time series prediction.  
- Predict stock prices for the next 30 days.  
- Add technical indicators (RSI, MACD) for deeper analysis.

The files `AAPL_stock_data.csv` and `lstm_stock_model.keras` contain the historical stock data and the trained model respectively.

---

## Prerequisites and Installation

This project requires Python 3.x and the packages listed in `requirements.txt`.

To install the dependencies, run:

```bash
pip install -r requirements.txt
````

---

## Usage

1. **Task 1**
   Open and run `Task1_Titanic_Classification/Titanic Survival.ipynb` in Jupyter Notebook or JupyterLab.

2. **Task 2**
   Open and run `Task2_Stock_Prediction/stock_prediction.ipynb` in Jupyter Notebook or JupyterLab.

---

## Notes

* This project is for educational purposes as part of the CodeAlpha challenge.
* Stock price predictions are inherently uncertain and should **not** be used for real investment decisions.

---

## Author

\YOUSSOUF TANGARA
Email: \[[ytangara2003@gmail.com](mailto:ytangara2003@gmail.com)]

---

## License

This project is licensed under the MIT License.

---

Thank you for checking out this project!
Happy learning and coding 🚀
