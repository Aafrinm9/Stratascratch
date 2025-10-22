# Demand for Electric Bicycles

This project is a StrataScratch take-home style analysis based on Yulu’s bike sharing data. The goal is to find which factors drive hourly demand for shared electric bicycles in the Indian market.

---

## About Yulu
Yulu is a micro-mobility service in India that offers shared vehicles for daily commutes through a mobile app. Yulu zones are placed near metro stations, bus stands, offices, residential areas, and other busy spots to make first and last mile travel affordable and convenient.

---

## Assignment
Yulu has seen a dip in revenue and wants to understand the drivers of demand. Your analysis should answer:

1. Which variables are significant in predicting demand for shared electric bicycles in the Indian market?
2. How well do those variables explain the demand?

---

## Data
Source file: `bike_sharing.csv`  
Each row is one hour of usage data.

| Column        | Description |
|---------------|-------------|
| `datetime`    | Start of the hour for which data is aggregated |
| `season`      | 1 = spring, 2 = summer, 3 = fall, 4 = winter |
| `holiday`     | 1 if the day is a holiday, else 0 |
| `workingday`  | 1 if not weekend and not holiday, else 0 |
| `weather`     | 1 = clear to scattered clouds, 2 = mist variants, 3 = light snow or light rain variants, 4 = heavy rain or snow with fog |
| `temp`        | Air temperature in °C |
| `atemp`       | Feels-like temperature in °C |
| `humidity`    | Humidity in percent |
| `windspeed`   | Wind speed in km/h |
| `casual`      | Bikes rented by casual users |
| `registered`  | Bikes rented by registered users |
| `count`       | Total rentals = casual + registered |

---

