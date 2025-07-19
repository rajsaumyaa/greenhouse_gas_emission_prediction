# 🌍 Greenhouse Gas Emission Prediction

This project focuses on **predicting greenhouse gas (GHG) emissions** related to U.S. industry supply chains using **machine learning**. By leveraging publicly available datasets from authoritative government sources, this project provides data-driven insights to help stakeholders understand and potentially reduce emissions.

---

## 📌 Project Objectives

- Analyze historical greenhouse gas emission data
- Clean and preprocess raw datasets
- Perform exploratory data analysis (EDA)
- Visualize emission trends by year, type, and level
- Build and evaluate machine learning models to predict future emissions
- Interpret results and generate insights for sustainability

---

## 📁 Repository Structure

greenhouse_gas_emission_prediction/

├── GHG_Analysis_and_prediction.ipynb # Main notebook (data analysis and ML)
  
   ├── README.md # Project documentation
   
   ├── SupplyChainEmissionFactorsforUSIndustriesCommodities.xlsx # dataset


---

## 📊 Features

- ✅ Data Cleaning: Renaming columns, filling missing values, formatting
- ✅ EDA: Trends across years, sectors, emission types
- ✅ Visualization: Grouped bar charts, line graphs, pivot plots
- ✅ Modeling: Regression models like Linear Regression, Random Forest
- ✅ Evaluation: RMSE, MAE, R² score
- ✅ Interpretation: Emission predictions with insights

---

## 📦 Datasets

The data used in this project are collected from:


https://catalog.data.gov/dataset/supply-chain-greenhouse-gas-emission-factors-for-us-industries-and-commodities

---

## 🧪 Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost (optional)

---

## 🚀 Getting Started

## ⚙️ How to Run the Project

### 📁 Prerequisites

Make sure you have the following installed:

- Python ≥ 3.7
- Jupyter Notebook (via Anaconda or pip)
- Required Python libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `joblib`)

### 🚀 Steps to Execute

1. **Clone the Repository**

   ```bash
   git clone https://github.com/rajsaumyaa/greenhouse_gas_emission_prediction.git
   cd greenhouse_gas_emission_prediction
   
2. **Prepare the Dataset**

Ensure the Excel file named SupplyChainEmissionFactorsforUSIndustriesCommodities.xlsx is placed in the project root directory.

This file should contain all relevant yearly sheets (e.g., 2010_Detail_Commodity, 2010_Detail_Industry, etc.).

3. **Launch Jupyter Notebook**

Open the notebook in your browser:

jupyter notebook GHG_Analysis_and_prediction.ipynb

**Week-1 TASK**
● Studied and understood dataset structure

● Cleaned and combined data from multiple Excel sheets (Commodity & Industry)

● Prepared a single, structured DataFrame for analysis and modeling


🙋‍♀️ Author

Saumya Raj
https://github.com/rajsaumyaa


Let’s predict for a greener future 🌱




