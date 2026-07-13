# 📊 UAE Live Births Analysis (1997-2015)

This repository contains a data analysis project exploring the trends of live births across the seven Emirates of the UAE from 1997 to 2015. The project was completed as part of the "Computational Thinking and Coding (ICT2013)" course.

---

## 🎯 Project Goal

The primary objective was to analyze the provided dataset to answer key questions about birth rates, identify trends over time, and compare demographic patterns across the different Emirates. The project showcases the complete data analysis lifecycle, from data acquisition and cleaning to exploratory analysis and visualization.

---

## ❓ Analysis Questions

We aimed to answer several key questions, including:
1.  What was the total number of births in the UAE during this period?
2.  How did the number of births in each Emirate compare to others?
3.  What were the top 5 years with the highest birth rates?
4.  Was the overall trend of births increasing or decreasing over time?
5.  What was the average number of births per year, and how did it change?

---

## 📄 Data Source

The dataset used for this analysis was obtained from **[Bayanat.ae](https://bayanat.ae/en/Data)**, the official open data portal of the UAE.

- **Dataset Name:** Live Births by Emirate, Gender and Nationality 1997 - 2015
- **Direct Link:** https://admin.bayanat.ae/Home/DatasetInfo?dID=vMeX8LEWLHbeQ2cBmwzQuQw22lDMVNo9d45dlCDcCVY

---

## 🛠️ Technologies & Libraries Used

- **Language:** Python
- **Libraries:**
  - **Pandas:** For data manipulation, cleaning, and analysis.
  - **Matplotlib / Seaborn:** For data visualization.
  - **Jupyter Notebook / Google Colab:** As the development environment.

---

## 🔄 My Role & Project Workflow

As a key member of the team, my responsibilities were central to the project's success:

1.  **Data Acquisition and Cleaning:**
    *   Loaded the dataset from an Excel file into a Pandas DataFrame.
    *   Handled missing values (`dropna`, `fillna`) and removed unnecessary columns.
    *   Renamed columns for better readability and consistency (e.g., `Value` to `Births`).

2.  **Exploratory Data Analysis (EDA):**
    *   Performed statistical analysis to find the total number of births.
    *   Utilized grouping (`groupby`) to calculate the total births per Emirate.
    *   Conducted complex analysis by combining filtering, sorting, and grouping to answer specific questions, such as finding the average births in 2004.

This project was my first deep dive into the world of data analytics, solidifying my skills in Python, Pandas, and the logical process of turning raw data into meaningful insights.

---

## 📄 Project Documentation
For a detailed explanation of the methodology, data analysis process, and full findings, please refer to the project report:
* [View UAE Birth Rate Analysis Report (PDF)](UAE-Birth-Rate-Analysis-ICT2013.docs/UAE-Birth-Rate-Analysis-ICT2013.pdf)

---

## 📈 Key Findings & Visualizations


**Overall Birth Trend (1997-2015)**


<img width="590" height="455" alt="image" src="https://github.com/user-attachments/assets/0e645e14-95cc-440f-ac6d-2809ceffe79c" />



**Births by Emirate**


<img width="597" height="553" alt="image" src="https://github.com/user-attachments/assets/dd229c0d-1453-44e0-b23b-d945b6b941a5" />

---

## 📂 Repository Contents

- `UAE-Birth-Rate-Analysis.ipynb`: The main Jupyter Notebook containing all the Python code, analysis, and commentary.
- `live-births-emirate1997-2015.xlsx`: The original dataset used for this analysis.
- `README.md`: This summary file.
