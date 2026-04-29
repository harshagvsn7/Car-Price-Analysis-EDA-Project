# 🚗 Car Price Analysis (EDA Project)

> Exploratory Data Analysis on a used car dataset to understand price patterns, feature relationships, and key influencing factors.

---

## 📌 Overview

This project performs detailed Exploratory Data Analysis on a used car dataset.
The goal is to uncover insights about how different factors like vehicle age, kilometers driven, and brand affect selling price.

---

## 🎯 Objectives

* Clean and preprocess raw data
* Handle missing values and duplicates
* Analyze distributions of key variables
* Identify relationships between features
* Generate insights that impact car pricing

---

## 📊 Dataset

The dataset contains information about used cars, including:

* Selling price
* Kilometers driven
* Vehicle age
* Brand and other attributes

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries:**

  * pandas
  * numpy
  * matplotlib
  * seaborn

---

## 🔍 Data Cleaning Steps

* Removed duplicate records
* Handled missing values by dropping incomplete rows
* Converted data types for numerical analysis
* Created new feature: `year` from vehicle age
* Filtered unrealistic values

---

## 📈 Exploratory Analysis

### Univariate Analysis

* Distribution of selling price
* Distribution of kilometers driven
* Outlier handling using percentile capping

### Feature Engineering

* Converted vehicle age into manufacturing year
* Standardized numerical columns

### Visualization

* Histograms for numeric features
* KDE plots for distribution insights
* Trend analysis across variables

---

## 💡 Key Insights

* Newer cars generally have higher selling prices
* Higher kilometers driven tends to reduce price
* Price distribution is skewed and requires outlier handling
* Data cleaning significantly improves analysis quality

---

## ⚙️ How to Run

```bash
# Clone repository
git clone https://github.com/your-username/car-price-eda.git

# Navigate into folder
cd car-price-eda

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Run notebook
jupyter notebook eda.ipynb
```

---

## 📂 Project Structure

```plaintext
car-price-eda/
│── eda.ipynb
│── dataset.csv
│── README.md
```

---

## 👤 Author

Your Name
GitHub:harshagvsn7 

---

## ⭐ Support

If you found this useful, give it a star.
