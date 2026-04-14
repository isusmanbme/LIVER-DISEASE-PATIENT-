# 🧬 Liver Disease Patient Analysis 

![Image](https://github.com/user-attachments/assets/5b31a32c-bbf3-4cf9-a7cc-053245093938)

## 📌 Project Overview
Analysis of liver disease patients using Microsoft Excel enables efficient data organization, statistical analysis, and visualization. Biomarkers like bilirubin and SGPT are evaluated to identify patterns, correlations, and predictors, supporting clinical interpretation and informed healthcare decisions.
This project presents a comprehensive analysis of **30,000 liver disease patient records** using Microsoft Excel as the primary analytical tool. The goal is to explore biomarker distributions, identify correlations, and determine key predictors of liver disease for clinical interpretation and decision-making.

## 🎯 Objectives

* Analyze the **distribution and averages** of key liver biomarkers
* Examine **correlations** between biochemical parameters
* Identify **significant predictors** of liver disease
* Compare **liver patients vs non-patients**
* Provide **clinical insights** from data patterns

## 📊 🧪 Clinical Questions 

### 1. Distribution and Average of Key Biomarkers

* **Total Bilirubin**: Moderately right-skewed distribution with elevated values in liver patients; mean typically higher than median.
* **SGPT (ALT)**: Widely spread with strong right skew, indicating presence of high enzyme levels in diseased patients.
* **Albumin**: Relatively normal distribution but slightly lower in liver patients; mean slightly reduced.
  
| Biomarker       | Distribution Shape               | Mean (Approx) | Clinical Insight                   |
| --------------- | -------------------------------- | ------------- | ---------------------------------- |
| Total Bilirubin | Right-skewed                     | High          | Elevated in liver disease patients |
| SGPT (ALT)      | Highly right-skewed              | Very High     | Indicates liver cell injury        |
| Albumin         | Near-normal/slightly left-skewed | Moderate-Low  | Reduced in liver dysfunction       |

📊 Interpretation
Enzyme markers (SGPT) show high variability and skewness.
Albumin remains more stable but decreases in diseased patients

### 2. Correlation Between SGPT, SGOT, and Total Bilirubin

* **SGPT and SGOT**: Strong positive correlation (both liver enzymes rise together).
* **SGPT and Total Bilirubin**: Moderate positive correlation.
* **SGOT and Total Bilirubin**: Moderate positive relationship.
  👉 This indicates coordinated liver dysfunction.

  | Variables               | Relationship Strength | Direction |
| ----------------------- | --------------------- | --------- |
| SGPT vs SGOT            | Strong                | Positive  |
| SGPT vs Total Bilirubin | Moderate              | Positive  |
| SGOT vs Total Bilirubin | Moderate              | Positive  |

📈 Key Insight
Liver enzymes (SGPT, SGOT) rise together
Bilirubin increases alongside enzyme elevation → coordinated liver dysfunction

### 3. Significant Predictors of Liver Disease (Selector)

* Key predictors identified through regression:

  * **SGPT (ALT)**
  * **SGOT (AST)**
  * **Total Bilirubin**
  * **Albumin (negative influence)**
    👉 These variables significantly contribute to predicting liver disease status.

  | Variable        | Influence on Disease | Significance |
| --------------- | -------------------- | ------------ |
| SGPT (ALT)      | Strong Positive      | High         |
| SGOT (AST)      | Strong Positive      | High         |
| Total Bilirubin | Moderate Positive    | Significant  |
| Albumin         | Negative             | Significant  |

📌 Interpretation
Higher enzyme and bilirubin levels → higher probability of liver disease
Higher albumin → protective indicator

### 4. Difference Between Liver and Non-Liver Patients

* **Total Bilirubin**: Significantly higher in liver patients
* **SGPT**: Markedly elevated in liver patients
* **Albumin**: Significantly lower in liver patients
  👉 Clear biochemical distinction exists between both groups.

| Biomarker       | Liver Patients (Selector = 1) | Non-Liver Patients (Selector = 0) | Difference    |
| --------------- | ----------------------------- | --------------------------------- | ------------- |
| Total Bilirubin | High                          | Normal/Low                        | Significant ↑ |
| SGPT (ALT)      | Very High                     | Normal                            | Significant ↑ |
| Albumin         | Low                           | Normal/High                       | Significant ↓ |

📈 Key Insight
Liver patients show:
Elevated enzymes and bilirubin
Reduced protein levels (Albumin)
Confirms clear biochemical separation between groups

### 5. Strongest Biomarker & Clinical Interpretation

* **SGPT (ALT)** is typically the strongest predictor
  👉 Clinical meaning:
* Elevated SGPT indicates **hepatocellular injury**
* It is a **sensitive marker for liver damage**, especially in early-stage disease
Liver disease is strongly associated with elevated enzyme levels (SGPT, SGOT) and bilirubin, alongside reduced albumin. Among these, SGPT shows the highest predictive power, making it a key clinical biomarker for liver dysfunction assessment.

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
For collaboration, further study, or inquiries related to this project, please feel free to reach out via email:
# Ibrahim Salihu Usman
Biomedical Engineering | Data Analytics | AI in Healthcare
📧 isusmanbme@gmail.com
📱 WhatsApp: +234 813 811 8881

