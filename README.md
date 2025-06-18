Based on the analysis of your two uploaded Jupyter Notebooks (`A1.ipynb` and `A2.ipynb`), here is a README description that explains both files clearly:

---

## 📊 DeepFlow Data Analysis Notebooks

This repository contains two Python Jupyter notebooks for **data preprocessing, visualization, and feature engineering** on distinct datasets. The goal is to prepare the datasets for machine learning or data insights using structured, well-documented steps.

---

### 📁 Files Overview

#### `A1.ipynb` – **Auction Sales Data Preprocessing & Encoding**

* **Purpose:** Preprocess machinery auction sales data (Train/Test CSVs).
* **Key Steps:**

  * Load datasets using `pandas`.
  * Parse and sort by `saledate`.
  * Drop columns with over 30% missing values.
  * Remove identifiers and date fields (`SalesID`, `MachineID`, `ModelID`, `saledate`).
  * Fill missing numeric values using **median imputation**.
  * Use **Label Encoding** for categorical variables using `sklearn.preprocessing.LabelEncoder`.
* **Target Outcome:** Cleaned, encoded training and testing datasets ready for modeling.

#### `A2.ipynb` – **Zomato Dataset Overview & Statistics**

* **Purpose:** Perform exploratory data analysis on a restaurant dataset (`zomato.csv`).
* **Key Steps:**

  * Read the CSV (likely exported from Excel).
  * Display initial records with `.head()`.
  * Show dataset structure using `.info()` and `.describe()`.
  * Print all column names for reference.

---

### 📦 Requirements

Install the dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---


