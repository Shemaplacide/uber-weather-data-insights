Here is your **final markdown report** with all requested details added, including your **name, ID, university, course, and lecturer**:

---

# 🚖 Uber Rides and Weather Impact Analysis

### 📚 Introduction to Big Data

**Name:** Shema Placide

**ID:** 26497

**University:** Adventist University of Central Africa (AUCA)

**Lecturer:** Maniraguha Eric

---

## 📌 1. Introduction

This project analyzes Uber ride data along with weather conditions to understand how time, location, and environmental factors affect ride demand and fare pricing. The objective is to generate valuable business insights using Power BI visualizations.

---

## 🛠️ 2. Exploratory Data Analysis (EDA)

In this phase, we inspected the data for:

* Missing values
* Outliers in fare amounts
* Distributions of key variables like `fare_amount` and `pickup_datetime`
* Basic statistics and time patterns

### 📸 Screenshot:

![EDA Screenshot](insert/path/to/eda_screenshot.png)

---

## ⚙️ 3. Feature Engineering

We enriched the dataset with new variables to aid deeper analysis:

* **Time Features**: Extracted `hour`, `day`, and `month` from `pickup_datetime`
* **Weather Merge**: Joined with weather data by date
* **Location Buckets**: Grouped pickups by geographical zones

### 📸 Screenshot:

![Feature Engineering Screenshot](insert/path/to/feature_engineering_screenshot.png)

---

## 📊 4. Data Analysis in Power BI

Using Power BI, we created visuals to analyze:

* Fare distributions
* Trip frequency by hour/day
* Weather influence on trip count
* Location-based pickup density

### 📸 Screenshot:

![Power BI Analysis Screenshot](insert/path/to/powerbi_analysis_screenshot.png)

---

## 📈 5. Dashboard Creation in Power BI

A professional and interactive dashboard was designed with:

* 📊 Fare Distribution: Histogram (Clustered Column Chart)
* 🕒 Ride Time Trends: Line chart by hour
* 🗺️ Geographic Map: Bubble size = fare, Tooltip = details
* 🔍 Filters: Date, Weather conditions, Fare range

### 📸 Screenshot:

![Dashboard Screenshot](insert/path/to/dashboard_screenshot.png)

---

## 🔍 6. Results

Key findings:

* Highest rides occur during morning (7–9 AM) and evening (4–6 PM) rush hours.
* Rainy weather reduces ride frequency but increases average fare.
* Central business areas have denser pickups and higher fares.
* Night rides show higher variability in fare amounts.

---

## 📌 7. Conclusion

By analyzing Uber rides against time and weather data, we discovered meaningful insights about user behavior and pricing trends. These patterns can help Uber enhance its dynamic pricing and improve rider satisfaction.

---

## 💡 8. Recommendations

* Increase driver availability during peak hours and bad weather.
* Offer ride discounts during low-demand hours.
* Use weather predictions to optimize fleet distribution.
* Implement fare surge only when weather impact is statistically significant.

---

### 📁 GitHub Repository

**Repository Name**: `uber-weather-analysis-powerbi`

**Description**:

> A data visualization project combining Uber ride data and weather insights to analyze temporal and spatial trends affecting pricing and ride demand. Built using Power BI with detailed EDA, feature engineering, and dashboard creation.

---

Let me know if you'd like this turned into a `.md` or `.pdf` file or need help uploading your screenshots to GitHub.
