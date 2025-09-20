# 🛒 Sales Analysis Project

This project focuses on analyzing retail transaction data to uncover customer insights using both **Python (Jupyter Notebook)** and **Power BI**.  
The workflow covers data cleaning, transformation, and customer segmentation using **RFM (Recency, Frequency, Monetary) analysis**.

---

## 📂 Project Structure

- **Jupyter Notebook (`notebook.ipynb`)**  
  Contains step-by-step data cleaning, transformation, and RFM calculation.

- **Datasets** (hosted externally on Google Drive)  
  - `online_retail.xlsx` → Raw dataset with original transaction records  
  - `cleaned_data.csv` → Cleaned dataset (duplicates removed, invalids filtered, formatted)  
  - `final_df.csv` → Aggregated dataset with RFM metrics per customer  

- **Power BI Dashboard (`dashboard.pbix`)**  
  Interactive dashboard for visualizing key insights.  

---

## 📊 Data Access

All datasets and the Power BI file are hosted on Google Drive:  
🔗 [Access Files on Google Drive](https://drive.google.com/drive/folders/1K9Ds_7M7H3kVjTv8oh-Vr3O2CXT8E0rE?usp=drive_link)

---

## ⚙️ Methodology

1. **Data Cleaning**
   - Removed null values and duplicates  
   - Filtered invalid transactions (negative quantities, cancelled invoices)  
   - Standardized date and numeric formats  

2. **Data Preparation**
   - Exported a clean CSV (`cleaned_data.csv`)  
   - Aggregated customer-level metrics for RFM analysis (`final_df.csv`)  

3. **RFM Analysis**
   - **Recency** → Days since last purchase  
   - **Frequency** → Number of transactions per customer  
   - **Monetary** → Total spend per customer  

4. **Visualization**
   - Insights visualized in **Power BI** dashboard  

---

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/Nafay-Aftab/customer-segmentation-analysis.git
   cd customer-segmentation-analysis
