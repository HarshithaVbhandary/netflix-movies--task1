# 📊 Netflix Movies - Data Cleaning Project

## 📝 Project Overview

This project involves cleaning and preprocessing a raw dataset containing information about Netflix Movies . The dataset includes missing values, duplicate records, and inconsistent formatting — all of which are addressed in this task.

The cleaned dataset can be used for further analysis, visualization, or building machine learning models.

---

## 📁 Files Included

- `netflix_uncleaned_large.csv` – Original raw dataset with 1000+ rows
- `netflix_cleaned.csv` – Final cleaned dataset
- `notebook.ipynb` – Jupyter Notebook with all cleaning steps
- `README.md` – This file

---

## 🧼 Data Cleaning Steps

The following steps were performed to clean the dataset:

1. **Loaded the dataset** using Pandas from the `.csv` file.
2. **Checked for missing values**  using `.isnull()`.
3. **Removed duplicate rows** using `.drop_duplicates()`.
4. **Converted `date_added`** to `datetime` format.
5. **Standardized text values** in `country` column to lowercase.
6. **Renamed column headers** to be lowercase and replaced spaces with underscores.
7. **Exported cleaned data** to a new `.csv` file.

---

## ⚙️ How to Run

To run this project:

1. Make sure you have Python installed with `pandas` and `jupyter`.
2. Open the Jupyter Notebook and run the code

