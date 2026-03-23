# 📊 E‑commerce Sales Analysis – UCI Online Retail Dataset

Data analysis project using Python, pandas and seaborn to explore transactional sales data from an online retailer in the UK.

Dataset source: [UCI Machine Learning Repository – Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail).

## 🎯 Project goal

The goal of this project is to:
- understand the sales trend over time,
- identify the most important countries and products,
- analyze customer behavior (number of orders, total spending).


## 🔎 Dataset overview

The dataset contains transactional data from an online retailer based in the UK.  
Main columns:
- `InvoiceNo` – invoice (transaction) number,
- `StockCode` – product code,
- `Description` – product description,
- `Quantity` – number of items,
- `InvoiceDate` – transaction date and time,
- `UnitPrice` – price per unit,
- `CustomerID` – customer identifier,
- `Country` – customer country.


## 🧩 Features

data  
  - `Online Retail.xlsx` – original dataset file.

notebook  
  - `online_retail.ipynb` – main Jupyter Notebook with:
    - data loading and cleaning,
    - exploratory data analysis (EDA),
    - monthly sales trend,
    - sales by country,
    - top‑performing products,
    - simple RFM‑style customer analysis (Recency, Frequency, Monetary),
    - basic customer segmentation (top 10% of spenders).

business insights
   - `business_insights.md` with visualisations and clue business insights.


# ⚙️ Getting Started

Clone the repository: git clone https://github.com/oolender/online_retail_analysis

Install dependencies: pip install -r requirements.txt

Run the notebook: jupyter notebook `online_retail.ipynb`


# 🛠️ Technologies
Python 3.9.6

pandas – data manipulation and cleaning

seaborn & matplotlib – visualization

Jupyter Notebook – interactive analysis


# 🤝🏻 Contribution
Feel free to open issues or pull requests if you have suggestions for improvements, new analyses, or additional visualizations.📊
