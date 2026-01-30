# 🚦 Road Traffic Accident Analysis (Exploratory Data Analysis)

## 📌 Project Overview
Road traffic accidents are a major public safety issue, often leading to injuries, loss of life, and economic strain. Understanding *when*, *how*, and *why* these accidents occur is essential for designing effective prevention strategies.

This project explores road traffic accident data from **Addis Ababa City** to identify patterns related to accident severity, time of occurrence, driver characteristics, and causes of accidents. The goal is to generate actionable insights that can support safer road use and data-driven decision making.

---

## 🎯 Objectives
- Understand the severity of road traffic accidents
- Identify high-risk days and time periods
- Analyze accident involvement by driver demographics
- Examine the most common causes of accidents
- Assess the human impact through casualty distribution

---

## 🧰 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 🗂 Dataset Overview
- **Location:** Addis Ababa City  
- **Rows:** 13,063  
- **Columns:** 31  

---

##  Data Preparation & Cleaning
To ensure accurate analysis, the following steps were carried out:
- Imported required libraries and loaded the dataset
- Reviewed the first few rows to understand structure and content
- Checked dataset size and column information
- Identified missing values
- Converted *Day of the Week* to an ordered categorical variable
- Converted *Time* column to datetime format
- Extracted hour values for time-based analysis

---

## 📊 Exploratory Data Analysis & Insights

### 1️⃣ Accident Severity: Understanding the Impact of Crashes
Most recorded accidents resulted in slight injuries, while serious and fatal injuries occurred less frequently. Although severe cases are fewer, their presence highlights the continued risk to human life and the importance of preventive road safety measures.

---

### 2️⃣ Accidents by Day of the Week: Identifying High-Risk Days
Accidents were not evenly distributed across the week. Fridays recorded the highest number of accidents, while Sundays had the lowest. This trend reflects increased traffic volume and driver fatigue toward the end of the workweek.

---

### 3️⃣ Time-Based Patterns: When Accidents Are Most Likely
Accidents were most frequent during evening hours, especially around 5 PM. Friday evenings showed the highest accident concentration, pointing to rush-hour traffic and end-of-day commuting as key risk periods.

---

### 4️⃣ Driver Gender: Who Is More Involved in Accidents
Male drivers were involved in a significantly higher number of accidents compared to female drivers. This imbalance suggests differences in driving exposure or behavior and highlights an opportunity for targeted safety awareness.

---

### 5️⃣ Driver Age Groups: Understanding Age-Related Risk
Younger and middle-aged drivers recorded the highest accident involvement, likely due to higher driving frequency and road exposure. A large amount of missing age data also revealed limitations in data collection quality.

---

### 6️⃣ Causes of Accidents: Why Accidents Happen
Most accidents were linked to avoidable driving behaviors. Lack of proper distancing emerged as the leading cause, followed by unsafe lane changes. This indicates that better driving discipline and enforcement could significantly reduce accident rates.

---

### 7️⃣ Casualties per Accident: Measuring Human Impact
Most accidents involved one casualty, while fewer cases involved multiple people. However, some accidents affected up to eight individuals, highlighting the potential severity and broader human impact of road traffic incidents.

---

## 📌 Key Insights
- Accident risk increases during weekday rush hours
- Friday evenings represent the highest-risk period
- Male and younger drivers are more frequently involved
- Many accidents result from preventable behaviors

---

## ✅ Recommendations
- Increase traffic monitoring and enforcement during peak hours
- Promote awareness on safe following distances
- Target road safety campaigns toward high-risk driver groups
- Improve data collection to reduce missing demographic information
- Strengthen traffic control during high-congestion periods

---

## ✍🏽 Author
**Temitope Adeyemi**  
Data Analyst | Python | Exploratory Data Analysis | Data Visualization
