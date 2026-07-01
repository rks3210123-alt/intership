# 🎬 Netflix Movies & TV Shows - Data Cleaning and Preprocessing

## 📌 Internship Task

This project was completed as **Task 1: Data Cleaning and Preprocessing** for the **Elevate Labs Data Analyst Internship**.

### 🎯 Objective

The objective of this task is to clean and preprocess a raw dataset by handling missing values, removing duplicates, standardizing data formats, and preparing the dataset for further analysis.

---

## 📂 Dataset

**Dataset:** Netflix Movies and TV Shows

**Source:** Kaggle

https://www.kaggle.com/datasets/shivamb/netflix-shows

---

## 🛠 Tools Used

- Python
- Pandas
- NumPy
- Google Colab
- KaggleHub

---

## 📋 Data Cleaning Steps Performed

### ✅ Imported the dataset
- Downloaded the dataset using KaggleHub.
- Loaded the CSV file into a Pandas DataFrame.

### ✅ Inspected the dataset
- Viewed the first few records using `head()`
- Checked dataset dimensions using `shape`
- Examined column names
- Verified data types using `info()`

### ✅ Handled Missing Values
Filled missing values as follows:

| Column | Action |
|---------|--------|
| director | Filled with "Unknown" |
| cast | Filled with "Unknown" |
| country | Filled with "Unknown" |
| rating | Filled with "Unknown" |
| date_added | Filled using Mode |
| duration | Filled using Mode |

---

### ✅ Duplicate Check

- Checked duplicate records using `duplicated().sum()`
- No duplicate rows were found.

---

### ✅ Standardized Data

- Removed leading and trailing spaces from text columns.
- Converted the `date_added` column into datetime format.
- Verified all column names and data types.

---

### ✅ Exported Clean Dataset

The cleaned dataset was saved as:

```
cleaned_netflix_dataset.csv
```

---

## 📁 Repository Structure

```
📦 internship
│
├── README.md
├── netflix_titles.ipynb
└── cleaned_netflix_dataset.csv
```

---

## 📊 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Handling Missing Values
- Duplicate Detection
- Data Type Conversion
- Pandas DataFrame Operations
- Google Colab
- GitHub

---

## 📌 Outcome

The dataset was successfully cleaned and prepared for exploratory data analysis and machine learning applications.

---

## 👨‍💻 Author

**Rohan Singh**

MBA Student | Aspiring Data Analyst | Digital Marketing Enthusiast

GitHub: https://github.com/rks3210123-alt
