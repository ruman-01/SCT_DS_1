# 🌍 Population Distribution Visualization - Task 01

This repository contains the code and resources for **Task 01** of my Data Science Internship at **SkillCraft Technology**.

## 🎯 Objective
The goal of this task is to create a bar chart or histogram to visualize the distribution of a categorical or continuous variable. 

For this project, I used the **World Bank Total Population Dataset** to visualize the **Top 10 Most Populous Countries in 2022** using a horizontal bar chart. 

## 🛠️ Tools & Technologies
* **Language:** Python
* **Libraries:** `pandas`, `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook / Any Python IDE

## 📊 Dataset
* **Source:** World Bank (API_SP.POP.TOTL_DS2_en_csv_v2_40826.csv)
* **Description:** The dataset tracks the total population per country from 1960 to 2024. 
* *Note: The dataset focuses on total overall population figures across nations rather than demographic breakdowns like age or gender.*

## 🚀 Key Steps Performed
1. **Data Loading & Cleaning:** * Loaded the main population dataset, skipping the irrelevant header rows.
   * Merged the data with the country metadata file to filter out regional aggregates (like "World" or "Africa") so only actual countries remained.
2. **Data Extraction:** Isolated the population data specifically for the year **2022** and extracted the top 10 largest values.
3. **Data Visualization:** Generated a horizontal bar chart using Seaborn to clearly display the population differences among the top countries.

## 📈 Output Visualization
<img width="2970" height="1765" alt="task-1" src="https://github.com/user-attachments/assets/4bfe632c-b6e1-4ea5-8185-491a19f5e218" />

---
*This project is part of my Data Science internship at SkillCraft Technology. Feel free to explore the code and reach out if you have any questions!*
