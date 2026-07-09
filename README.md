# Market_Analysis_Project-2

📈 Stock Market Analysis Project 2
A complete data cleaning, transformation, and preparation pipeline for historical stock market data.

🔍 Overview
This project is the second stage of a multi‑part stock market analysis workflow.
The goal of Project 2 is to take the raw datasets from Project 1 and perform:

Advanced data cleaning

Outlier detection and correction

Feature engineering

Data normalization

Categorical encoding

Dataset consolidation

Train/validation/test splitting

The final output is a fully cleaned, encoded, and standardized dataset ready for predictive modeling.
🧠 Objectives
✔ Advanced Data Cleaning
Forward-fill and backward-fill imputation

Linear interpolation for numeric gaps

Correction of date parsing errors

Removal of invalid or corrupted rows

✔ Outlier Handling
IQR-based detection

Capping extreme values for close and volume

✔ Feature Engineering
Includes multiple technical indicators:

Rolling averages (7-day, 30-day)

Volatility measures

Daily returns

Price range

SMA‑14

EMA‑14

RSI‑14

✔ Data Transformation
One-hot encoding for categorical fields

Standardization of numerical features

✔ Modeling Preparation
Consolidated final dataset

Train/validation/test split

Export of all cleaned datasets

📊 Before & After Visualizations
The notebook includes a full visualization section showing:

Missing values before vs. after imputation

Outlier distributions before vs. after capping

Histograms comparing raw vs. cleaned data

Boxplots for close and volume

These visualizations demonstrate the effectiveness of the cleaning pipeline and justify the chosen methods.

🛠 Technologies Used
Python 3

Pandas

NumPy

Matplotlib / Seaborn

Scikit‑Learn

Google Colab

📦 Output Files
The notebook generates the following cleaned datasets:

clean_stock_data.csv

X_train.csv

X_val.csv

X_test.csv

y_train.csv

y_val.csv

y_test.csv

These files are saved in the Colab environment for use in Project 3 (Modeling).

📝 How to Use
Open the notebook in Google Colab

Upload the raw CSV files from Project 1

Run each cell in order

Download the cleaned datasets for modeling

🎓 Author
Crystal MacNeil  
Market Analysis Project – Part 2
Created using Google Colab 

