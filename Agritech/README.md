
# Crop Data Analysis – Agritech

## Assignment Overview
The objective of this project is to generate actionable insights for optimal crop selection by analyzing soil and environmental factors. The analysis focuses on how different crops respond to variations in soil nutrients, climatic conditions, and rainfall patterns.

This project aims to support data driven agricultural decision making.

---

## Project Objectives
- Analyze the impact of soil nutrients and environmental factors on crop types
- Identify patterns and relationships between climate conditions and crop growth
- Build statistical and predictive models to assist in crop selection

---

## Tasks Performed

### Data Visualization
- Plotted distributions of soil nutrients (N, P, K) across different crop types to identify patterns
- Created scatter plots to examine relationships between:
  - Temperature and crop type  
  - Humidity and crop type  
  - Soil pH and crop type  
  - Rainfall and crop type
- Developed correlation heatmaps to analyze relationships among all numerical variables

### Statistical Analysis
- Performed ANOVA tests to evaluate whether environmental factors such as temperature, humidity, and rainfall vary significantly across crop types
- Applied regression models to assess the influence of soil nutrients and climate variables on crop type
- Interpreted p values to identify statistically significant predictors

---

## Key Outcomes

### Correlation Analysis
Identified soil and environmental factors that show strong relationships with specific crop types.

### Predictive Modeling
Built models that help recommend suitable crops based on given environmental and soil conditions.

### Decision Support Insights
Provided insights that can guide farmers in improving crop selection, yield optimization, and resource utilization.

---

## Tools and Techniques Used

### Visualization
- Matplotlib
- Seaborn

### Statistical and Predictive Modeling
- SciPy for ANOVA testing
- Scikit learn and statsmodels for regression and predictive analysis

---

## Dataset Description
The dataset represents agricultural conditions relevant to Indian farming and includes the following variables:

- **N (Nitrogen)** – Nitrogen content in the soil  
- **P (Phosphorus)** – Phosphorus level in the soil  
- **K (Potassium)** – Potassium level in the soil  
- **Temperature** – Measured in degrees Celsius  
- **Humidity** – Relative humidity percentage  
- **pH** – Soil acidity or alkalinity  
- **Rainfall** – Rainfall amount in millimeters  

---

## Practical Considerations
The analysis considers a wide range of agricultural conditions present in the dataset. The insights derived from this study are intended to help farmers select crops best suited to their local environmental conditions, supporting better productivity and efficient resource usage.
