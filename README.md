# EV-Charging-Demand-Forecasting-and-Infrastructure-Planning
Machine learning–based analysis of EV charging electricity consumption (2023–2025) to forecast future demand and support profit-aware charging infrastructure expansion planning.


# ⚡ EV Charging Infrastructure Planning and Demand Forecasting in Telangana

## Overview

This project presents a **data-driven framework for forecasting Electric Vehicle (EV) charging demand and planning charging infrastructure across Telangana**. The framework integrates **time-series forecasting, machine learning, and interactive data visualization** to support intelligent and sustainable EV infrastructure planning.

Using real-world electricity consumption data collected between **2023 and 2025**, the system predicts future charging demand, estimates the number of additional charging stations required, evaluates infrastructure profitability, and generates interactive dashboards for decision-making.

---

## Problem Statement

The rapid adoption of Electric Vehicles has significantly increased the demand for charging infrastructure. Traditional planning approaches primarily rely on historical averages and static assumptions, often leading to infrastructure shortages or inefficient utilization of charging stations. This project addresses these challenges by providing an intelligent, data-driven framework that accurately forecasts future demand and supports evidence-based infrastructure expansion planning.

---

## Objectives

* Forecast future EV charging electricity demand.
* Analyze charging infrastructure requirements across Telangana.
* Estimate additional charging stations required in each division.
* Evaluate infrastructure profitability using Machine Learning.
* Generate interactive dashboards for visualization and decision support.

---

## Dataset

* **Source:** Telangana State Power Distribution Corporation (TSPDCL/TGSPDCL)
* **Duration:** 2023–2025
* **Data Type:** Monthly EV charging electricity consumption
* **Coverage:** Multiple divisions across Telangana

### Dataset Features

* Division Name
* Year
* Month
* Electricity Consumption (Units)
* Load Utilization
* Billing Services
* Revenue Indicators
* Infrastructure Statistics

---

## Methodology

### 1. Data Collection

Collected EV charging electricity consumption data from multiple Telangana divisions covering the years 2023–2025.

### 2. Data Preprocessing

* Missing value handling
* Duplicate record removal
* IQR-based outlier detection
* Feature engineering
* Data cleaning

### 3. Exploratory Data Analysis (EDA)

* Monthly demand analysis
* Year-wise demand growth
* Division-wise comparison
* Consumption trend visualization

### 4. Demand Forecasting

Implemented the **Holt–Winters Exponential Smoothing** model to forecast future EV charging electricity demand while capturing both trend and seasonality.

### 5. Infrastructure Planning

Forecasted demand is proportionally allocated among divisions based on historical consumption. Infrastructure requirements are estimated considering:

* Peak demand
* Charging station capacity
* Target utilization
* EV growth assumptions

### 6. Profitability Analysis

A **Random Forest** model predicts the probability of profitable infrastructure expansion using demand and utilization indicators.

### 7. Dashboard Generation

Interactive dashboards provide comprehensive visualizations for forecasting, infrastructure planning, profitability analysis, and geographic insights.

---

## Machine Learning Models

### Holt–Winters Exponential Smoothing

**Purpose:** Forecast future EV charging electricity demand.

### Random Forest

**Purpose:** Predict profitability of proposed charging infrastructure expansion.

---

## Key Features

* EV Charging Demand Forecasting
* Infrastructure Requirement Estimation
* Profitability Prediction
* Geographic Planning Support
* Interactive HTML Dashboards
* Time-Series Analysis
* Machine Learning-Based Decision Support
* Data Visualization

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-learn
* Statsmodels
* Plotly
* Matplotlib
* YData Profiling

### Tools

* Google Colab
* Jupyter Notebook
* Git
* GitHub

---

## Project Structure

```text
EV-Charging-Infrastructure-Planning/
│
├── EV_Charging_Analysis.ipynb
├── Dataset.csv
├── Dashboard_Page1.html
├── Dashboard_Page2.html
├── Dashboard_Page3.html
├── Dashboard_Page4.html
├── Dashboard_Page5.html
├── README.md
├── requirements.txt
└── screenshots/
```

---

## Results

The proposed framework successfully:

* Forecasted future EV charging electricity demand.
* Identified divisions requiring additional charging infrastructure.
* Estimated charging station requirements based on projected demand.
* Evaluated profitability for infrastructure expansion.
* Generated interactive dashboards for data-driven decision-making.
* Supported sustainable and scalable EV infrastructure planning.

---

## Future Scope

* Integration with real-time EV charging data.
* GIS-based charging station location optimization.
* Deep Learning models for enhanced forecasting accuracy.
* Web application deployment using Flask or Streamlit.
* Integration with live traffic and EV registration datasets.
* Smart city infrastructure planning support.

---

## Repository Contents

* Google Colab Notebook
* EV Charging Dataset
* Interactive HTML Dashboard Reports
* Data Analysis and Forecasting Models
* Documentation

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Benarji-chowdary/EV-Charging-Infrastructure-Planning.git
```

### 2. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 3. Open the Notebook

Open the provided Google Colab Notebook or Jupyter Notebook and execute all cells sequentially.

---

## Applications

* EV Infrastructure Planning
* Smart City Development
* Government Policy Support
* Power Distribution Planning
* Sustainable Transportation
* Data-Driven Decision Support

---

## Author

**K.Benarji Chowdary**

B.Tech Minor Project

Department of Computer Science and Engineering(AI & ML)

---

## License

This project is developed for **academic and educational purposes**.

---

## Acknowledgements

The author gratefully acknowledges the support of the project guide, the Department of Computer Science and Engineering(AI & ML), and Telangana State Power Distribution Corporation (TSPDCL/TGSPDCL) for providing the data and guidance necessary to complete this work.
