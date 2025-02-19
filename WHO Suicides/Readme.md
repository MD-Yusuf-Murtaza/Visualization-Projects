# WHO Suicides Analysis (1979-2016)

## 📌 Project Title
**Analysis and Visualization on WHO suicides dataset**

## 📖 Description
This project analyzes global suicide trends from **1979 to 2016** using WHO mortality data. The dataset provides insights into suicide rates across **different countries, age groups, and genders**, allowing us to explore long-term trends, demographic disparities, and potential influencing factors.

## 📊 Dataset Overview
- **Source:** WHO Mortality Database
- **Total Records:** 43,776
- **Columns:**
  - `country`: Name of the country
  - `year`: Year of record
  - `sex`: Gender of individuals (Male/Female)
  - `age`: Age group of individuals
  - `suicides_no`: Number of suicides recorded
  - `population`: Population count for the respective demographic
- **Missing Values:** Some records have missing population or suicide numbers, requiring preprocessing.

## Objectives
- Identify **long-term trends** in suicide rates.
- Analyze **age and gender distributions**.
- Examine **regional variations** in suicide cases.
- Compare suicide rates against **population demographics**.
- Visualize findings using statistical plots.

## 🚀 How to Install and Run the Project
### 1. Install Dependencies
Run the following command to install necessary libraries:
```bash
pip install pandas matplotlib seaborn numpy plotly
```

### 2. Run the Jupyter Notebook
Launch Jupyter Notebook and open `WHO_Suicides.ipynb` to explore the analysis.
```bash
jupyter notebook
```

## 📌 Methodology
### 1. Data Cleaning & Preprocessing
- Handled missing values by imputing or removing incomplete records.
- Standardized column names and formatted the dataset.
- Filtered out irrelevant or erroneous data points.

### 2. Exploratory Data Analysis (EDA)
- **Yearly Trends:** Examined suicide trends over time.
- **Age & Gender Analysis:** Compared suicide rates across different age groups and sexes.
- **Country-wise Breakdown:** Identified nations with the highest and lowest suicide rates.
- **Correlation Analysis:** Explored relationships between population size and suicide rates.

### 3. Data Visualization
- **Line Plots:** Show overall trends in suicide rates across decades.
- **Bar Charts:** Compare suicide cases by age group and gender.
- **Heatmaps:** Display country-wise suicide patterns.
- **Pie Charts:** Illustrate demographic distributions.

## 🛠️ Tools & Libraries Used
- **Programming Language:** Python
- **Libraries:**
  - `pandas` - Data manipulation and preprocessing
  - `matplotlib` & `seaborn` - Data visualization
  - `numpy` - Numerical computations
  - `plotly` - Interactive visualizations



## 📌  Key Findings
- Suicide rates have fluctuated significantly across different time periods.
- **Males have consistently higher suicide rates** compared to females across all age groups.
- Elderly populations and young adults are particularly vulnerable.
- Countries exhibit significant variations, indicating cultural and socioeconomic factors play a role.

## 🙌 Acknowledgments
- **WHO** for providing the raw dataset.
- Open-source libraries like `pandas`, `matplotlib`, and `seaborn` for enabling analysis and visualization.

**A pdf file is also attached that has the poster of the above dataset analysis**
