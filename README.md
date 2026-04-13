# Yulu-Bike-Sharing---Demand-Analysis-report
Yulu is experiencing a decline in revenue and seeks to identify the key factors influencing the demand for shared electric cycles in the Indian market.
# 🚲 Yulu Bike Demand Analysis — Data Science Case Study

## 📌 Business Problem

Yulu, India's leading micro-mobility service provider, has experienced a decline in revenue. The company wants to understand the factors influencing demand for shared electric cycles to improve utilization and increase revenue.

This project analyzes demand patterns using Exploratory Data Analysis (EDA) and Hypothesis Testing.

---

## 🎯 Objective

Identify:

* Which variables significantly affect demand
* How well these variables explain bike rentals
* Business recommendations to improve demand

---

## 📂 Dataset Information

The dataset contains the following variables:

| Feature    | Description                                   |
| ---------- | --------------------------------------------- |
| datetime   | Date & time                                   |
| season     | Season (1-Spring, 2-Summer, 3-Fall, 4-Winter) |
| holiday    | Whether day is holiday                        |
| workingday | Working day or not                            |
| weather    | Weather condition                             |
| temp       | Temperature                                   |
| atemp      | Feels like temperature                        |
| humidity   | Humidity                                      |
| windspeed  | Wind speed                                    |
| casual     | Casual users                                  |
| registered | Registered users                              |
| count      | Total bikes rented (Target Variable)          |

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Statistical Analysis

---

## 📊 Analysis Performed

### 1. Exploratory Data Analysis (EDA)

* Data Structure Analysis
* Missing Value Check
* Data Type Conversion
* Statistical Summary

---

### 2. Univariate Analysis

Continuous Variables

* Temperature
* Humidity
* Windspeed
* Count

Categorical Variables

* Season
* Weather
* Holiday
* Workingday

---

### 3. Bivariate Analysis

Relationship between:

* Workingday vs Count
* Season vs Count
* Weather vs Count
* Temperature vs Count
* Humidity vs Count
* Windspeed vs Count

---

## 🧪 Hypothesis Testing

### 1. 2-Sample T-Test

Workingday vs Bike Count

Result:

* No significant difference
* Workingday does not impact demand

---

### 2. ANOVA Test

Season vs Bike Count

Result:

* Significant difference
* Season affects demand

---

### 3. ANOVA Test

Weather vs Bike Count

Result:

* Significant difference
* Weather affects demand

---

### 4. Chi-Square Test

Season vs Weather

Result:

* Weather dependent on season

---

## 📈 Key Insights

* Fall and Summer seasons show highest demand
* Clear weather results in more bike rentals
* Rainy weather reduces demand
* Temperature positively affects bike rentals
* Humidity negatively affects demand
* Workingday has minimal impact

---

## 💡 Business Recommendations

### 1. Seasonal Fleet Planning

Increase bikes during:

* Summer
* Fall

Reduce bikes during:

* Winter
* Rainy season

---

### 2. Weather Based Planning

* Use weather forecast
* Increase bikes during clear weather
* Reduce bikes during rain

---

### 3. Dynamic Pricing

* High demand → Premium pricing
* Low demand → Discount offers

---

### 4. Smart Bike Allocation

Deploy more bikes:

* Office areas
* Metro stations
* College locations

---

## 📊 Project Workflow

1. Problem Understanding
2. Data Cleaning
3. Exploratory Data Analysis
4. Bivariate Analysis
5. Hypothesis Testing
6. Business Insights
7. Recommendations

---

## 📁 Project Structure

```
Yulu-Demand-Analysis
│
├── yulu_data.csv
├── Yulu_EDA.ipynb
├── README.md
└── images/
```

---

## 🚀 Future Improvements

* Build prediction model
* Demand forecasting
* Time series analysis
* Machine learning model

---

## 📌 Conclusion

Season and weather are the most significant factors affecting bike demand. Yulu can improve revenue by implementing seasonal planning, weather-based deployment, and dynamic pricing strategies.

---

## 👤 Author

Praneetha
Data Science Enthusiast
Python | Statistics | Machine Learning

---

## ⭐ If you found this project helpful

Please consider giving a ⭐ to this repository
