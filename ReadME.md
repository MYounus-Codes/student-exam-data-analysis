# Analyzing Student Academic Trends

## GOOGLE COLAB LINK:

# [Here Project Code](https://colab.research.google.com/drive/1s3dyp-2rfx7mkJ00FJte7Gt5WQ2qo-_F?usp=sharing)
---
**Project Repository**
---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Dataset Description](#dataset-description)  
3. [Objectives](#objectives)  
4. [Data Cleaning & Preprocessing](#data-cleaning--preprocessing)  
5. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)  
6. [Modeling & Analysis](#modeling--analysis)  
7. [Results & Findings](#results--findings)  
8. [Usage](#usage)  
9. [Dependencies & Installation](#dependencies--installation)  
10. [Project Structure](#project-structure)  
11. [Future Work](#future-work)  
12. [Acknowledgments](#acknowledgments)  
13. [License](#license)  

---

## Project Overview

This project aims to analyze academic trends among students using the *Analyzing Student Academic Trends* dataset from Kaggle.  
By cleaning, exploring, and modeling this data, the project uncovers relationships among demographic, behavioral, and performance features.  

The main goal is to provide insights that might help educators, schools, or policy makers understand:

- Which factors most influence student performance  
- Where interventions might be most effective  
- Trends across gender, socioeconomic background, school types, etc.  

---

## Dataset Description

- **Name:** Analyzing Student Academic Trends  
- **Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/saadaliyaseen/analyzing-student-academic-trends)  
- **Key Features:**  
  - Student demographics (Age, Gender, Socioeconomic factors)  
  - Parental education and support  
  - Study time, activities, and attendance  
  - Academic performance scores and trends  
- **Number of Records & Size:** *[to be filled]*  
- **Missingness / Data Issues:** *[to be filled]*  

---

## Objectives

The project focuses on solving the following:

- Identify which factors (demographic, study habits, parental education, etc.) are most predictive of student performance.  
- Explore how performance differs across genders and other groups.  
- Detect patterns in academic performance trends over time or across categories.  
- Build predictive models to estimate student scores or categories of performance.  
- Provide recommendations and actionable insights for improving outcomes.  

---

## Data Cleaning & Preprocessing

Steps performed before analysis:

1. **Missing Data Handling** – Identified and treated missing values using imputation or removal techniques.  
2. **Data Type Conversion** – Converted strings to categorical or datetime fields as needed.  
3. **Outlier Detection** – Detected and handled extreme values using IQR and statistical rules.  
4. **Feature Engineering** – Created new variables to capture additional relationships.  
5. **Encoding** – Applied one-hot encoding or label encoding to categorical variables.  
6. **Scaling/Normalization** – Scaled numerical variables for models requiring normalized data.  

---

## Exploratory Data Analysis (EDA)

EDA was performed to identify key patterns and correlations in the dataset using visualizations and summary statistics.

- Visualized the distribution of academic scores using **histograms** and **boxplots**  
- Compared performance by gender, school type, and parental education using **bar charts** and **violin plots**  
- Built a **correlation heatmap** to identify relationships among variables  
- Detected skewness and imbalances in the dataset  
- Identified potential areas for intervention through data storytelling  

---

## Modeling & Analysis

Several machine learning models were applied to understand and predict student performance:

- **Regression Models** – Linear Regression, Ridge, and Lasso for score prediction  
- **Classification Models** – Decision Trees, Random Forests, Gradient Boosting for categorizing performance  
- **Model Evaluation** – Used metrics like MAE, RMSE, Accuracy, and F1 Score  
- **Cross-validation** – Ensured models generalized well to unseen data  
- **Feature Importance Analysis** – Identified the most impactful variables influencing academic trends  

---

## Results & Findings

- **Key Insights:**
  - Parental education and support strongly correlate with student performance.  
  - Students with consistent study habits and higher attendance perform significantly better.  
  - Gender disparities were observed in specific subjects, highlighting targeted improvement areas.  

- **Model Performance:**
  - Regression models achieved an RMSE of *[value]* on the test dataset.  
  - Classification models reached an accuracy of *[value]* with Random Forest performing best.  

- Visualizations support these findings and are provided in the `reports/figures` directory.

---

## Usage

Follow the steps to run this project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/MYounus-Codes/student-exam-data-analysis.git
   cd student-exam-data-analysis


   
