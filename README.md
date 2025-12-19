# 📞 CallMeMaybe: Operator Performance Analysis

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

## 📖 Project Overview
**CallMeMaybe**, a virtual telephony service provider, identified a need to improve the quality of its customer service. The goal of this project is to analyze the daily activity of operators to identify inefficiencies and provide supervisors with data-driven insights to improve team performance.

## 🎯 Business Problem
The company lacked a clear metric to identify which operators were underperforming. This analysis focuses on answering the following questions:
* Which operators have the longest wait times?
* Is there a significant difference in call duration between operators?
* How does the number of missed calls vary across the team?

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Seaborn, Matplotlib
* **Statistical Analysis:** SciPy (Hypothesis Testing)

## 📊 Methodology
1. **Data Cleaning:** Handled missing values and corrected data types (timestamps) to ensure accuracy.
2. **Exploratory Data Analysis (EDA):** Visualized call distributions and identified outliers in wait times.
3. **Statistical Hypothesis Testing:**
   * Performed **t-tests** (or Mann-Whitney U tests) to determine if the differences in call duration between operators were statistically significant.
4. **Insights Generation:** Synthesized findings for the supervisory board.

## 💡 Key Findings
> *Note: Based on the analysis of the dataset.*

* **Ineffective Operators:** We identified that `[Insertar número o %]` of operators consistently exceed the average wait time by `[Insertar X]` minutes.
* **Call Duration:** There is a statistically significant difference between internal and external calls (p-value < 0.05), suggesting `[Insertar tu conclusión, ej: external calls take longer]`.
* **Missed Calls:** The operator `[Nombre o ID]` had the highest rate of missed calls, correlating with peak hours.

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/Maximiliano/CallMeMaybe-Analysis.git](https://github.com/Maximiliano/CallMeMaybe-Analysis.git)
