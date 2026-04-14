# 🧬 Liver Disease Patient Analysis (Excel-Based)

## 📌 Project Overview
Analysis of liver disease patients using Microsoft Excel enables efficient data organization, statistical analysis, and visualization. Biomarkers like bilirubin and SGPT are evaluated to identify patterns, correlations, and predictors, supporting clinical interpretation and informed healthcare decisions.
This project presents a comprehensive analysis of **30,000 liver disease patient records** using Microsoft Excel as the primary analytical tool. The goal is to explore biomarker distributions, identify correlations, and determine key predictors of liver disease for clinical interpretation and decision-making.

## 🎯 Objectives

* Analyze the **distribution and averages** of key liver biomarkers
* Examine **correlations** between biochemical parameters
* Identify **significant predictors** of liver disease
* Compare **liver patients vs non-patients**
* Provide **clinical insights** from data patterns

## 📂 Dataset Description

The dataset consists of **30,000 patient records** with demographic and biochemical features.

### 📊 Variables in the Dataset

| Variable        | Description                                         |
| --------------- | --------------------------------------------------- |
| Patient ID      | Unique identifier for each patient                  |
| Location        | Patient location (e.g., Abuja, Lagos, Enugu)        |
| Age             | Age of patient                                      |
| Gender          | Male/Female                                         |
| Total_Bilirubin | Total bilirubin level                               |
| Bilirubin       | Direct bilirubin                                    |
| Alkphos         | Alkaline phosphatase enzyme                         |
| SGPT (ALT)      | Liver enzyme indicator                              |
| SGOT (AST)      | Liver enzyme indicator                              |
| Total_Proteins  | Total protein level                                 |
| Albumin         | Protein produced by liver                           |
| A_G_Ratio       | Albumin/Globulin ratio                              |
| Selector        | Target variable (1 = Liver Disease, 0 = No Disease) |


## 🛠️ Tools & Techniques

* **Microsoft Excel**

  * Data Cleaning & Preprocessing
  * Pivot Tables
  * Data Analysis ToolPak
* Statistical Methods:

  * Descriptive Statistics
  * Correlation Analysis
  * Regression Analysis
* Visualization:

  * Histograms
  * Scatter Plots
  * Bar Charts

## 📈 Key Findings

### 🔹 Descriptive Statistics (Selected Biomarkers)

| Metric  | Total Bilirubin | SGPT (ALT) | Albumin |
| ------- | --------------- | ---------- | ------- |
| Mean    | 2.60            | 104.29     | 3.75    |
| Median  | 2.61            | 104.00     | 3.76    |
| Min     | 0.20            | 10.00      | 2.00    |
| Max     | 5.00            | 199.00     | 5.50    |
| Std Dev | 1.39            | 54.87      | 1.01    |

### 🔹 Insights

* Elevated **SGPT and SGOT levels** are strongly associated with liver dysfunction
* **Total Bilirubin** shows significant variation among patients
* Lower **Albumin levels** are linked with liver disease cases
* Biomarkers collectively improve prediction compared to single variables

## 🔍 Analysis Performed

### 1. Distribution Analysis

* Histograms used to assess spread of biomarkers
* Identified skewness in enzyme levels

### 2. Correlation Analysis

* Scatter plots used to examine relationships:

  * SGPT vs SGOT
  * Bilirubin vs SGPT
* Moderate to strong correlations observed

### 3. Predictive Modeling

* Regression analysis applied using Excel ToolPak
* Identified key predictors:

  * SGPT
  * SGOT
  * Total Bilirubin

### 4. Comparative Analysis

* Compared:

  * Liver disease patients (Selector = 1)
  * Non-liver patients (Selector = 0)
* Significant biochemical differences observed

## 🔍 Key Insights
•	Certain biomarkers (e.g., SGPT, SGOT, Bilirubin) show strong association with liver disease
•	Albumin and A/G ratio provide additional clinical relevance
•	Some variables may have weak predictive power, indicating the need for multivariate analysis

## 🧠 Clinical Interpretation

* High enzyme levels (SGPT, SGOT) indicate **hepatocellular injury**
* Elevated bilirubin suggests **impaired liver function or bile flow obstruction**
* Reduced albumin reflects **poor liver synthetic function**

## 📊 Dashboard Features (Excel)

* Interactive charts
* Slicers for:
  * Gender
  * Location
  * Disease status
* KPI summaries for quick insights

## 🚀 How to Use

1. Download the Excel dataset
2. Open in Microsoft Excel
3. Enable **Data Analysis ToolPak**
4. Explore:

   * Pivot Tables
   * Charts
   * Regression outputs

## 📌 Conclusion

This project demonstrates how Excel can be effectively used for **clinical data analysis**, enabling meaningful insights into liver disease patterns. The findings highlight the importance of biochemical markers in diagnosis and provide a foundation for more advanced analytics using tools like Python or Power BI.


## 👤 Author

**Ibrahim Salihu Usman**
Biomedical Engineering | Bioinformatics | Data Analytics

