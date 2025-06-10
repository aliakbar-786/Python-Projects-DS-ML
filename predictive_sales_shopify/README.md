# Predictive Modeling of Monthly Sales Revenue Using Shopify Data

This project performs time series forecasting to predict monthly sales revenue using Shopify order data. It leverages the Prophet library by Meta for prediction and includes end-to-end steps: data extraction, transformation, visualization, model building, forecasting, and evaluation.

## 📦 Requirements

- Shopify API access (API key & password)
- Python 3.x
- ShopifyAPI
- Prophet
- Pandas
- Matplotlib
- Scikit-learn

## 🔧 Installation

Install required libraries:

```bash
pip install -r requirements.txt

📈 Project Structure
Extract Data from Shopify
Uses API credentials to pull order data.

Prepare Data
Cleans data and aggregates it monthly.

Visualize Data
Line plot of monthly sales revenue.

Model Training
Prophet is used for forecasting future revenue.

Forecasting
Generates 12-month future predictions.

Evaluation
Compares predicted vs actual using MAE (Mean Absolute Error).

🚀 How to Run
Replace your API key and password in the script.

Run the notebook or script step-by-step.

Review the output plots and forecast accuracy.

📊 Sample Output
Monthly Sales Revenue Trend

Forecasted vs Actual Sales Plot

MAE Score for Accuracy Evaluation


---

### 📦 `requirements.txt`

```text
ShopifyAPI
prophet
pandas
matplotlib
scikit-learn
