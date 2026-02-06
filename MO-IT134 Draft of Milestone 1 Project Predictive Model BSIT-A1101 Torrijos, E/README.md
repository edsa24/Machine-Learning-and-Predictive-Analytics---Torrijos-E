# Draft Milestone 1: Predictive Model

## Course
MO-IT134

## Program and Section
BSIT-A1101

## Student
Torrijos, Edsa Mae

---

## About This Draft
This is the **draft version** of my Milestone 1 project. The main goal is to build a first version of a model that predicts if a customer will likely make a purchase.

I used the **merged dataset (`Week2-3_Data_Processing.csv`)** which already has the cleaned customer, product, and transaction info.

---

## What I Did
1. **Loaded the dataset**  
   - Checked columns, data types, and missing values  
   - Converted numbers stored as text into actual numbers  
   - Filled missing values in text columns with `"Unknown"` and in numbers with `0`  

2. **Picked the features**  
   - Features related to buying behavior:  
     - Quantity, Product price, Total cost, Company profit  
     - Total transactions, Total spent, Average transaction value, Recency (days since last purchase)  
   - Target column: `frequent_buyer` (1 = likely to buy, 0 = not likely)  

3. **Built the model**  
   - Scaled the numbers with StandardScaler  
   - Used Logistic Regression to train the model  

4. **Checked the model**  
   - Accuracy  
   - Confusion matrix  
   - Precision, recall, and F1-score  

---

## Files in This Folder
- `Draft Milestone 1 Predictive Model.ipynb` – notebook with the draft model  
- `Week2-3_Data_Processing.csv` – dataset we used  
- `README.md` – this file  

