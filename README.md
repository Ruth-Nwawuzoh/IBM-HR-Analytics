# IBM-HR-Analytics
Employee Attrition Analysis


# IBM HR Analytics – Employee Attrition Project

## **Project Overview**
This repository contains data, code, and outputs for my **Business Analytics Milestone 1** assignment, focused on **employee attrition analysis** using IBM HR Analytics data.

---

## **Instructions to Clone and Unzip Repository**
1. Clone the repository or unzip file ('HR Data Analysis.zip'), If downloaded
2. Launch the notebook

---

## **Contents**
- `Analysis_code.ipynb` – Data cleaning, preprocessing, and exploratory data analysis notebook.
- `output/` – Directory containing saved plots and cleaned dataset.
- `WA_Fn-UseC_-HR-Employee-Attrition.csv` – Original dataset.
- `HR_Attrition_Cleaned.csv` – Final cleaned and transformed dataset ready for modeling.

---

## **Dataset**
- **Source:** Kaggle  
- **Link:** [IBM HR Analytics Employee Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data)

---

## **Methods and Tools**
- **Language:** Python  
- **Libraries:** pandas, numpy, seaborn, matplotlib, sklearn
- **Tools:** Jupyter Notebook

---

## **Data Preparation**
1. **Imported data** and checked shape, columns, and info.
2. **Cleaned data:**
   - Checked for missing values (none found).
   - Label encoded categorical columns.
3. **Feature engineering:**
   - Created `TenureBucket` from `YearsAtCompany`.
   - Created `IncomePerJobLevel` as MonthlyIncome divided by JobLevel.
4. **Data quality assessment:**
   - Checked for outliers and correlations.

---

## **Exploratory Data Analysis**
- Attrition count plot (majority stayed).
- Correlation heatmap (tenure & income variables highly correlated).
- Boxplot of Monthly Income vs Attrition.

---

## **Ethics and Bias Consideration**
- Data is anonymized and used only for educational purposes.  
- Attrition is imbalanced; class balancing will be considered in modeling.

