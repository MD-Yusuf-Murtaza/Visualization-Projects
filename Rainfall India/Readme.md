# Rainfall Trends in India Analysis with Python

## 📌 Project Title
**Rainfall Trends in India Analysis and Forecasting**

## 📖 Description
Rainfall is a crucial component of India's climate system, influencing agriculture, water resources, and the overall economy. This project focuses on analyzing historical rainfall trends, detecting anomalies, clustering years based on rainfall patterns, and forecasting future rainfall using machine learning techniques.

Using Python and various data visualization techniques, this project aims to:
- Analyze long-term rainfall patterns
- Detect extreme rainfall years using anomaly detection
- Categorize years into Dry, Normal, and Wet using clustering
- Predict future rainfall trends using time-series forecasting

This analysis will help in effective planning for agriculture, disaster management, and water resource allocation.

---
## 📊 Dataset Overview
The dataset contains **115 years of rainfall data** (1901-2015) and consists of **19 columns**, including:
- **YEAR**: Year of observation
- **Monthly Rainfall (JAN - DEC)**: Rainfall (in mm) for each month
- **ANNUAL**: Total annual rainfall (in mm)
- **Seasonal Rainfall**: Jan-Feb, Mar-May, Jun-Sep, Oct-Dec
- **REGION**: Name of the region

The dataset has **no missing values**, and no transformations were required before visualization.

---
## 🚀 How to Install and Run the Project
### Prerequisites
Ensure you have Python installed on your system. Install the required dependencies using:

```bash
pip install numpy pandas matplotlib plotly scikit-learn prophet
```

### Running the Project
1. Clone the repository or download the notebook (`RailfallVisualization.ipynb`).
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Run the notebook to explore visualizations and insights.

---
## 🔍 Visualization Approaches

### **1. Simple Visualizations (Using Matplotlib & Pandas)**
- **Line plots**: Show trends in annual rainfall over time.
- **Bar plots**: Compare seasonal rainfall distributions.
- **Histograms & Density plots**: Display rainfall distribution across years.

### **2. Advanced Visualizations (Using Plotly, Sklearn & Prophet)**
#### **Anomaly Detection (Isolation Forest)**
- Identifies years with extreme or deficient rainfall.
- Highlights anomalies on the annual rainfall trend plot.

#### **Clustering (K-Means Clustering)**
- Categorizes years into **Dry, Normal, and Wet** clusters.
- Uses `Jan-Feb, Mar-May, Jun-Sep, Oct-Dec, and ANNUAL` rainfall as features.
- Displays results using an interactive scatter plot.

#### **Rainfall Forecasting (Prophet Model)**
- Predicts **annual rainfall for the next 20 years**.
- Displays confidence intervals for uncertainty estimation.
- Highlights long-term trends and potential shifts in rainfall patterns.

---
## 📌 Results & Insights
- **Anomalies detected**: Extreme rainfall years were identified in **1917, 1965, 2002, and 2009**.
- **Clustering results**: Wet years were more common in the **early and mid-20th century**, while dry years increased in the **late 20th and early 21st century**.
- **Forecasting trend**: The Prophet model suggests a **gradual decline** in annual rainfall, with continued fluctuations.

---
## 🛠️ Tools & Libraries Used
### **Simple Visualizations**
- **NumPy**: Numerical computations and array manipulations.
- **Pandas**: Data manipulation and analysis.
- **Matplotlib.pyplot**: Static and interactive visualizations.

### **Advanced Visualizations**
- **Plotly (graph_objects, express)**: Interactive visualizations for better insights.
- **Scikit-learn (IsolationForest, KMeans, StandardScaler)**: Machine learning tools for anomaly detection, clustering, and feature scaling.
- **Prophet (Prophet, plot_plotly)**: Time-series forecasting for predicting future rainfall trends.

---
## 🙌 Acknowledgments
This project was built using open-source libraries and publicly available rainfall data. Special thanks to the developers of:
- **Matplotlib** for static visualizations
- **Plotly** for interactive visualizations
- **Scikit-learn** for machine learning techniques
- **Prophet** for time-series forecasting

Their contributions have been instrumental in analyzing and visualizing rainfall trends effectively.

---
## 🏆 Conclusion
This project provides a comprehensive analysis of rainfall trends in India, leveraging data visualization and machine learning techniques. The findings can help policymakers, researchers, and environmentalists make informed decisions regarding climate adaptation strategies.

📌 **Next Steps:** Future improvements can include regional analysis, climate factor correlations, and integration with real-time rainfall data.

---



