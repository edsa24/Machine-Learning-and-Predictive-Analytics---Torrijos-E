# Draft Milestone 1: Project Predictive Model

## Course
MO-IT134

## Program and Section
BSIT-A1101

## Student
Torrijos, Edsa Mae

---

## Project Overview
This folder contains the **draft version** of our Milestone 1 project. The goal is to create an initial predictive model to estimate if a customer is likely to make a purchase.

We used the **merged and cleaned dataset (`Week 3 - Homework.csv`)** as the base for this draft model.

---

## What We Did

1. **Loaded the dataset**
   - Checked data types and missing values  
   - Converted numeric columns stored as text into numbers  
   - Filled missing categorical values with `"Unknown"` and numeric missing values with `0`  

2. **Selected Features**
   - Numeric features related to purchasing behavior:  
     - Quantity  
     - Product price  
     - Total cost  
     - Company profit  
     - Total transactions  
     - Total spent  
     - Average transaction value  
     - Recency (days since last purchase)  
   - Target column: `frequent_buyer` (1 = likely to buy, 0 = not likely)  

3. **Built the Model**
   - Scaled features using StandardScaler  
   - Trained a **Logistic Regression** model  

4. **Evaluated the Model**
   - Accuracy score  
   - Confusion matrix  
   - Precision, recall, F1-score  

---

## Files in This Folder
- `Milestone1_Predictive_Model.ipynb` – Jupyter notebook with the draft model  
- `Week 3 - Homework.csv` – the dataset used  
- `README.md` – this file  

---

## Notes
- This is just the **draft version**; results and evaluation are preliminary.  
- The notebook is ready to be improved for the **final Milestone 1** submission.
