# 🦠 COVID-19 Data Analysis Using Python & Pandas

## 📌 Project Overview

This project focuses on analyzing COVID-19 datasets using Python and Pandas in Jupyter Notebook. The project includes data cleaning, preprocessing, filtering, grouping, and visualization to gain meaningful insights from pandemic-related data.

The analysis helps in understanding confirmed cases, recovered cases, deaths, active cases, and trends across different regions and countries using Exploratory Data Analysis (EDA) techniques.

---

# 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

# 📚 Libraries Used

## 🔹 Pandas

```python id="9lfv9j"
import pandas as pd
```

Used for data manipulation, cleaning, filtering, and analysis.

---

## 🔹 NumPy

```python id="x0mxzm"
import numpy as np
```

Used for numerical operations and array handling.

---

## 🔹 Matplotlib

```python id="s3w9go"
import matplotlib.pyplot as plt
```

Used for creating charts and visualizations.

---

## 🔹 Seaborn

```python id="mjlwmz"
import seaborn as sns
```

Used for advanced data visualization and plotting.

---

# 📂 Dataset Information

The dataset contains COVID-19 related information such as:

- Confirmed Cases  
- Recovered Cases  
- Death Cases  
- Active Cases  
- Country/Region Details  
- Date-wise Pandemic Records  

The dataset helps in analyzing the spread and impact of COVID-19 across different locations.

---

# 📊 Key Operations Performed

- Data Cleaning and Preprocessing  
- Handling Missing Values  
- Filtering and Sorting Data  
- Grouping Data using `groupby()`  
- Statistical Analysis  
- Country-wise Analysis  
- Date-wise Trend Analysis  
- Data Visualization using Graphs and Charts  

---

# 🔍 Analysis Performed

## ✅ Checking Missing Values

```python id="8r8k9k"
df.isnull().sum()
```

Used to identify null or missing values in the dataset.

---

## ✅ Filtering Records

```python id="6o9lye"
df[df['Confirmed'] > 1000]
```

Used to filter records based on conditions.

---

## ✅ Grouping Data

```python id="av3m94"
df.groupby('Region').sum()
```

Used to summarize data region-wise.

---

## ✅ Sorting Values

```python id="cw4ay2"
df.sort_values(by='Confirmed', ascending=False)
```

Used to sort records based on confirmed cases.

---

## ✅ Data Visualization

```python id="rxr6fi"
plt.plot()
```

Used to visualize trends and patterns in COVID-19 data.

---

# 📈 Project Objectives

- Analyze real-world COVID-19 datasets  
- Understand pandemic trends and patterns  
- Perform exploratory data analysis using Python  
- Visualize confirmed, recovered, and death cases  
- Improve practical knowledge of Pandas and data analytics  

---

# 📊 Sample Analysis Tasks

- Finding countries with highest confirmed cases  
- Comparing recovery and death rates  
- Analyzing active cases region-wise  
- Visualizing COVID-19 trends over time  
- Filtering records based on conditions  
- Grouping data for statistical insights  

---

# 🎯 Learning Outcomes

Through this project, I improved my understanding of:

- Data Cleaning  
- Exploratory Data Analysis (EDA)  
- Pandas Operations  
- Data Filtering and Grouping  
- Data Visualization  
- Working with Real-World Datasets  
- Statistical Analysis using Python  

---

# 📁 Project Structure

```bash id="vw9j0w"
Covid_19-Data_Analysis-Using-Python-Pandas/
│
├── Covid_19_Analysis.ipynb
├── covid19_dataset.csv
├── README.md
```

---
# 📚 Conclusion

This project demonstrates how Python and Pandas can be used to analyze real-world COVID-19 datasets effectively. It showcases practical data analysis techniques including data cleaning, filtering, grouping, visualization, and trend analysis.

The project also helped in understanding pandemic-related patterns and improved practical skills in exploratory data analysis using Python.



