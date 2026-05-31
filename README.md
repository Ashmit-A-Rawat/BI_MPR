# Global Job Market Analysis Using Data Mining

## Overview

This project focuses on analyzing a large-scale global job market dataset and applying data mining techniques to uncover salary patterns, employment trends, and workforce insights. The project includes exploratory data analysis (EDA), data preprocessing, machine learning-based salary prediction, clustering, and business intelligence (BI) interpretation.

## Objectives

* Analyze global job market trends across countries and occupations.
* Identify factors influencing employee salaries.
* Perform data cleaning and preprocessing.
* Visualize employment and compensation patterns.
* Predict salaries using machine learning techniques.
* Discover hidden job market segments using clustering.
* Generate actionable business intelligence insights.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

## Project Workflow

### 1. Data Exploration

* Dataset overview and statistical analysis
* Missing value analysis
* Occupation distribution analysis
* Salary distribution analysis
* Experience and salary relationship analysis

### 2. Data Preprocessing

* Verification of missing values
* Label Encoding of categorical variables
* Feature Scaling using StandardScaler
* Train-Test Split preparation

### 3. Data Mining Algorithms

#### Decision Tree Regressor

Used to predict salary based on:

* Experience
* Education Level
* Occupation
* Location
* Employment Type
* Company Size

#### K-Means Clustering

Used to:

* Group similar job profiles
* Identify salary-based workforce segments
* Discover hidden patterns in employment data

### 4. Model Evaluation

Regression metrics used:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score
* Adjusted R² Score

Clustering evaluation:

* Silhouette Score

### 5. Business Intelligence Insights

Key findings from the analysis:

* Salary generally increases with experience.
* Higher education levels are associated with higher compensation.
* Certain occupations show consistently higher salary ranges.
* Job market segments can be identified through clustering.
* Data-driven salary prediction can support HR and recruitment decisions.

## Dataset

Dataset used:

**Job Market Dataset (Global)**

Dataset Source:

https://www.kaggle.com/datasets/kundanbedmutha/job-market-dataset-global/data

Dataset Characteristics:

* 500,000 synthetic job records
* Global coverage across countries and cities
* Includes salary, education, experience, occupation, and demographic attributes
* No missing values

## Repository Structure

```text
BI_MPR/
│
├── BI_LAB_MPR.ipynb
├── README.md
└── .gitignore
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/Ashmit-A-Rawat/BI_MPR.git
```

2. Download the dataset from Kaggle.

3. Place the dataset file:

```text
job_market_dataset.csv
```

inside the project directory.

4. Open the notebook using Google Colab or Jupyter Notebook.

5. Run all cells sequentially.

## Results

* Successfully analyzed 500,000 job market records.
* Identified major factors affecting salary.
* Built a Decision Tree Regression model for salary prediction.
* Performed K-Means clustering to identify workforce segments.
* Generated business intelligence insights from workforce data.

## Learning Outcomes

* Exploratory Data Analysis (EDA)
* Data Preprocessing Techniques
* Feature Engineering
* Regression Modeling
* Clustering Analysis
* Business Intelligence Interpretation
* Real-world Data Mining Workflow

## Team Members

* Jaahnvi
* Alisha
* Ashmit Rawat
* Jiya

## Academic Information

**Subject:** DMBI (Data Mining and Business Intelligence)

**Mini Project – Business Intelligence Laboratory**

---

Data mining transforms raw job market data into actionable insights, enabling smarter workforce planning, salary benchmarking, and strategic decision-making.
