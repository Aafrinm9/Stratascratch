# 🚖 Insights from City Supply and Demand Data

This project analyzes city supply and demand data, originally used as a take-home assignment for data science recruitment at Uber. The goal is to derive key insights and patterns related to trip requests, driver supply, and demand fluctuations over a two-week period.

---

## 📌 Assignment Objectives

Using the provided dataset, this analysis answers the following questions:

1. **🚗 Peak Trip Volume**
   - Which date had the most completed trips during the two-week period?
   - What was the highest number of completed trips within a 24-hour period?

2. **⏰ Hourly Demand Analysis**
   - Which hour of the day had the most trip requests?
   - What percentage of all zero requests occurred on weekends?  
     *(Weekend is defined as Friday at 5 PM to Sunday at 3 AM.)*

3. **📊 Driver Performance & Efficiency**
   - What is the weighted average ratio of completed trips per driver?  
     *(Weighted by total trip volume in each hour.)*

4. **🕗 Optimal Driver Shifts**
   - What are the busiest **8-hour consecutive shifts** for drivers?  
     *(Assume shifts start every 8 hours, and a driver works the same shift daily.)*

5. **📈 Supply vs. Demand Trends**
   - **True or False:** Does driver supply always increase when demand increases?  
     *(Visualizations may help confirm this.)*

6. **📉 Highest Ratio of Zeroes to Eyeballs**
   - In which **72-hour period** is the ratio of Zeroes to Eyeballs the highest?

7. **👥 Optimizing Driver Allocation**
   - If you could **add 5 drivers** to any single hour of every day, which hour should you choose?  
     *(Consider both rider demand and driver supply when making this decision.)*

8. **📅 Data Timeframe & End-of-Day Definition**
   - **True or False:** Does the dataset cover exactly **two weeks**?
   - What time should be considered the "true end of the day" instead of midnight?  
     *(Determine when both supply and demand are at their natural minimums.)*

---

## 📁 Dataset Information
- The dataset contains **two weeks of trip request data** with timestamps, completed trip counts, driver supply, and other key metrics.
- **Time Zone:** Local time values represent the **start of each hour** (e.g., `15` represents 3:00 PM - 4:00 PM).

---

## 🔧 Tools & Libraries Used
- **Python (Pandas, NumPy, Matplotlib, Seaborn)**
- **Jupyter Notebook**
- **Data Visualization & Analysis**

---

## 📊 Visual Insights
To confirm insights, **data visualizations** were used to:
- Identify trends in driver supply vs. demand
- Determine peak hours and optimal driver scheduling
- Evaluate fluctuations in trip requests and completed trips

---

## 🚀 Results & Key Findings
*Results of the analysis are posted as Uberanalysis.ipynb*

---

## 🏗 Future Improvements
- Advanced machine learning models to predict demand trends
- Optimizing driver supply allocation using AI-based forecasting
- Automating data processing for real-time insights

---

## 📜 License
This project is for educational purposes only.

---

### 📩 Contact
For any questions, feel free to reach out via GitHub Issues.

