# 📊 Exploratory Data Analysis (EDA) on App Dataset

## 🚀 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on an application dataset to extract meaningful insights about app categories, installs, ratings, pricing, and user engagement.

The goal is to understand data patterns, handle missing values, detect outliers, and visualize relationships between different features.

---

## 📁 Dataset Description

The dataset contains information about various applications, including:

* 📌 App Name
* 📂 Category
* ⭐ Rating
* 📈 Rating Count
* 📥 Maximum Installs
* 💰 Price
* 🆓 Free/Paid
* 📦 Size

---

## 🛠️ Technologies Used

* 🐍 Python
* 📊 Pandas
* 🔢 NumPy
* 📉 Matplotlib
* 🎨 Seaborn
* 📓 Jupyter Notebook

---

## 🔍 Steps Performed

### 1. Data Cleaning

* Handled missing values (mean/median strategies)
* Removed duplicates
* Converted data types
* Standardized columns

### 2. Null Value Treatment

* Filled missing values in **Rating Count**
* Decided between **mean vs median** based on distribution

### 3. Feature Engineering

* Converted size values (K, M, G) into numeric format
* Created categorical ranges (e.g., installs range)

### 4. Outlier Detection

* Used **IQR (Interquartile Range)**
* Applied **log transformation** for skewed data

### 5. Data Visualization

* Count plots (Category vs Free/Paid)
* Scatter plots (Installs vs Rating Count)
* Distribution plots
* Correlation heatmap

---

## 📊 Key Insights

* 📌 Most apps are **free**, with very few paid apps
* 📌 Certain categories dominate in installs (e.g., Gaming, Tools)
* 📌 High installs do not always guarantee high ratings
* 📌 Data is highly **skewed**, requiring transformation
* 📌 Strong correlation observed between installs and rating count

---

## 📈 Visualizations Included

* Category distribution
* Free vs Paid app comparison
* Installs vs Rating relationship
* Correlation heatmap

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone <your-repo-link>
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

3. Run the notebook

```bash
jupyter notebook
```

---

## 🎯 Objective

To gain insights into app performance and user behavior using data analysis techniques and visualization tools.

---

## 👨‍💻 Author

**Ankit Virat**
