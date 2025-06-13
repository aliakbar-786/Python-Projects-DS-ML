# ETL and Predictive Modeling Project

This project demonstrates a simple but complete ETL (Extract, Transform, Load) pipeline, followed by data visualization and predictive modeling using Linear Regression.

The project extracts data from multiple sources (`CSV`, `JSON`, and `XML`), cleans and transforms the data, visualizes trends, and finally builds a regression model to predict sales over time.

## 📁 Folder Structure

etl_project/
│
├── j1.json
├── j2.json
├── c1.csv
├── c2.csv
├── x1.xml
├── x2.xml
├── etl_pipeline.py # Main Python script
└── README.md

## 🚀 Technologies Used

- **Python 3**
- **Pandas** for data manipulation
- **Matplotlib** for visualization
- **scikit-learn** for machine learning
- **JSON / XML / CSV** file handling
- **Requests** (for future API data integration)

## 🔍 Key Steps

### 1. Data Extraction
- Load multiple JSON, CSV, and XML files into pandas DataFrames.

### 2. Data Transformation
- Convert dates, sales data, and handle missing values.
- Merge all sources into a single, clean dataset.

### 3. Data Visualization
- Bar chart of total sales by region.
- Line chart showing sales trends over time.

### 4. Predictive Modeling
- Apply Linear Regression to predict sales using time-series features.
- Evaluate with **Mean Absolute Error**.
- Visualize predicted vs actual sales.

## 📊 Sample Output

> Bar Chart: Total Sales by Region  
> Line Plot: Sales Trend Over Time  
> Scatter Plot: Actual vs Predicted Sales

## 🛠️ How to Run

Make sure to have the required files (`j1.json`, `j2.json`, `c1.csv`, etc.) in the project directory.

1. Install dependencies:

```bash
pip install pandas matplotlib scikit-learn
Run the Python script:

python etl_pipeline.py