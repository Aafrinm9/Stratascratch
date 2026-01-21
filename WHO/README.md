# Air Quality Analysis: New York vs Bogota (PM2.5)

This project analyzes air pollution data from two monitoring stations:

- Queens College, New York City (USA)
- San Cristobal, Bogota (Colombia)

The goal is to study PM2.5 pollution patterns using time series analysis, rolling mean calculations, and anomaly detection based on World Health Organization (WHO) guidelines.

---

## Project Goals

- Perform time series analysis of PM2.5 levels for each city
- Identify periods of highest and lowest pollution
- Detect trends and seasonal behavior
- Compare pollution levels between New York and Bogota
- Measure correlation between both time series
- Apply WHO pollution limits to detect violations
- Mark periods where 24 hour rolling mean exceeds safe limits
- Support findings using clear visualizations

---

## Tools and Technologies

- Python  
- Pandas  
- Matplotlib  
- SciPy  

---

## Dataset Overview

The datasets are provided as `.txt` files with `|` as the column separator.

### 1. New York Station

**File:** `StationData-NY_QueensCollege.txt`

- Data source: New York State Department of Environmental Conservation  
- Parameter: PM2.5  
- Station: Queens College  
- Date range: 2016-09-01 to 2017-04-01  
- Time resolution: 1 hour  

### 2. Bogota Station

**File:** `StationData-Bogota_SanCristobal.txt`

- Data source: Red de Monitoreo de Calidad del Aire de Bogotá (RMCAB)  
- Parameters: PM2.5, PM10  
- Station: San Cristobal  
- Date range: 2016-09-01 to 2017-04-01  
- Time resolution: 1 hour  

---

## Assignment Objectives

The analysis is structured around the following three questions.

---

## Question 1: Time Series Analysis of Pollution Levels

Perform a time series analysis on the PM2.5 pollution levels for each city individually.

### Tasks

- Load and clean hourly pollution data  
- Handle missing values and incorrect timestamps  
- Plot PM2.5 levels over time  
- Identify:
  - Periods with highest pollution  
  - Periods with lowest pollution  
  - Daily, weekly, and monthly patterns  
  - Seasonal trends if present  

### Outputs

- Time series plots for both cities  
- Summary statistics  
- Observations on trends and seasonality  

---

## Question 2: Comparison Between New York and Bogota

Compare PM2.5 pollution levels between both cities.

### Tasks

- Align both datasets by timestamp  
- Create visualizations showing:
  - Periods when New York pollution is higher than Bogota  
  - Periods when Bogota pollution is higher than New York  
- Analyze:
  - Seasonal similarities or differences  
  - Long-term trends  
  - Statistical correlation between the two time series  

### Outputs

- Overlay or difference plots  
- Correlation coefficient and interpretation  
- Trend comparison summary  

---

## Question 3: WHO Pollution Limit Analysis and Anomaly Detection

Explore pollution limits defined by the World Health Organization (WHO).

### Tasks

- Identify WHO acceptable PM2.5 limits:
  - Annual mean threshold  
  - 24-hour mean threshold  
- Compute:
  - Annual mean PM2.5 for both cities  
  - 24-hour rolling mean values  
- Implement an algorithm to:
  - Detect timestamps where the 24-hour mean exceeds WHO limits  
  - Flag these as pollution violations  

### Visualization

- Time series plots with:
  - WHO threshold lines  
  - Highlighted violation periods  

### Outputs

- Compliance summary for both cities  
- Violation frequency and duration  
- Annotated plots showing exceedance windows  


---

### City Comparison

- Compare PM2.5 values between New York and Bogota
- Visualize:
  - When New York pollution exceeds Bogota
  - When Bogota pollution exceeds New York
- Check statistical correlation between both time series
- Analyze similarities and differences in seasonal trends

---

### WHO Pollution Threshold Analysis

Using WHO air quality standards:

- Compute annual mean PM2.5 for both cities
- Check compliance with WHO acceptable limits
- Compute 24 hour rolling mean
- Detect and flag periods where pollution exceeds WHO limits
- Visualize violation windows clearly on time series plots

---

## License

This project is intended for educational use.

---



