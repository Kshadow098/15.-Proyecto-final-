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
A. **Detected Inefficiency Volume**
Out of the 1,092 operators evaluated, 308 were classified as inefficient (28.2%). However, understanding the breakdown of this metric is crucial:

Low Outbound Activity: The vast majority (271 operators) were flagged for low outbound call volume. This suggests that many might be dedicated exclusively to inbound support. Therefore, this indicator warrants a case-by-case review to rule out false positives.

Excessive Wait Times: A critical group of 44 operators exhibited prolonged wait times. This represents the most urgent issue to address, as it directly impacts the overall customer experience.

Missed Calls: The issue of missed calls is marginal. Only 13 operators showed severe deficiencies in this area, indicating that the inbound call infrastructure remains highly robust.

B. **Correlation with Pricing Plans**
Statistical testing confirmed a direct relationship between the client's contracted plan and operator efficiency:

Plan A: Clients subscribed to this tier feature the most efficient operators, with an inefficiency rate of only 18%.

Plan C: This is the most problematic segment, where the inefficient operator rate spikes to 35.7%. This disparity suggests that companies utilizing Plan C may be experiencing staff saturation, high workloads, or a lack of supervision.

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/Maximiliano/CallMeMaybe-Analysis.git](https://github.com/Maximiliano/CallMeMaybe-Analysis.git)
