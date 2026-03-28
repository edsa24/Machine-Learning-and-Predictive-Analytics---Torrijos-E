## Course
MO-IT134

## Program and Section
BSIT- S3101

## Student
Torrijos, Edsa Mae

---

## Project Overview
This project is about building a predictive model to guess if a customer is likely to make a purchase.  

I started with **3 raw CSV files** (customers, products, transactions). These were merged and checked in **Week 2 and Week 3** to clean the data and make sure everything looks right.  

The final dataset I used for building the model is **Week2-3_Data_Processing.csv**.  

The project workflow:
1. Merge and check raw data (Week 2 & 3)  
2. Build draft model (Draft Milestone 1)  
3. Next is for finishing Milestone 1

---

## Dataset
- **Week2-3_Data_Processing.csv** – the cleaned dataset ready for modeling.  
- The original 3 CSVs were used to check and merge the data but are not used directly in the model.

---

## Tools and Libraries
- Python  
- Jupyter Notebook  
- pandas  
- scikit-learn  
- matplotlib / seaborn (for charts)

---

## How I Did It

### 1. Data Checking and Cleaning
- Loaded the merged dataset for checking  
- Checked missing values and data types  
- Converted numeric columns stored as text to numbers  
- Filled missing categorical values with `"Unknown"` and missing numbers with `0`  
- Final dataset has no missing values

### 2. Picking Features
Numeric features used for model training:
- Quantity  
- Product price  
- Total cost  
- Company profit  
- Total transactions  
- Total spent  
- Average transaction value  
- Recency (days since last purchase)  

Target: `frequent_buyer` (1 = likely to buy, 0 = not likely)

### 3. Building the Model
- Scaled the features using StandardScaler  
- Trained a **Logistic Regression** model  

### 4. Checking the Model
- Accuracy  
- Confusion matrix  
- Precision, recall, F1-score  
- Optional charts (like distribution of buyers or feature importance)

### 5. Results
- The model can predict which customers are likely to buy  
- Spending, frequency, and recency are important features  

---

## Folder Structure

📁 Machine Learning and Predictive Analytics
│
├── 📁 WEEK 2&3 - Data Processing
│ ├── customers_data.csv
│ ├── products_data.csv
│ ├── transactions_data.csv
│ ├── Week2-3_Data_Processing.csv
│ ├── WEEK 2-3_DataProcessing.ipynb
│ └── README.md
│
├── 📁 MO-IT134 Draft of Milestone 1 Project Predictive Model BSIT-A1101 Torrijos, E
│ ├── Draft Milestone 1 Predictive Model.ipynb
│ ├── Week2-3_Data_Processing.csv
│ └── README.md
│
├── 📁 MO-IT134 Milestone 1 Project Predictive Model BSIT-A1101 Torrijos, E
│ ├── 
│ ├── 
│ └── README.md
│
└── README.md (this file)


---

## Notes
- The raw 3 CSVs were merged for checking in Week 2 and Week 3  
- The final dataset (`Week2-3_Data_Processing.csv`) is what we actually used for modeling  
- Draft Milestone 1 is the first version of the model  
- Final Milestone 1 includes the polished model, evaluation, and results  

---

## Additional Notes

The presentation slides are submitted separately as required in the course guidelines.
The core model implementation remained unchanged, as it was already functioning correctly.
Improvements were focused on:
Adding detailed documentation
Presenting forecasted results clearly
Enhancing visualizations

=== 

## Author

edsa torrijos
BSIT Student – Machine Learning & Predictive Analytics

---

## Acknowledgment

This project was developed as part of the Terminal Assessment for the Machine Learning and Predictive Analytics course.
