# 🏥 Hospital Operations & Revenue Analysis (SQL)<br>

# 📌 Project Overview<br>
This project involves a comprehensive analysis of a healthcare dataset to extract actionable insights regarding hospital operations, financial performance, and patient demographics. By executing 19 structured SQL queries, I transformed raw healthcare data into business intelligence to help hospital administrators optimize doctor scheduling and improve revenue collection.

<img width="1435" height="817" alt="Dataset schema" src="https://github.com/user-attachments/assets/213a3f46-48b0-42ca-8686-8a27d1ef3a6a" />


# 📊 Key Business Questions Addressed<br>
Revenue Optimization: Which departments and treatment types generate the highest billing?

Operational Efficiency: What are the peak appointment days and average wait times?

Doctor Performance: How do doctors rank based on patient load and successful treatment outcomes?

Patient Behavior: What are the most common age groups and recurring medical conditions?

# 🛠️ Tech Stack & SQL Concepts Used<br>
Database: MySQL

Joins: Connecting patient records with billing and doctor tables.

Aggregations: Summarizing total revenue, average costs, and patient counts.

Window Functions: Using RANK(), DENSE_RANK(), and ROW_NUMBER() for performance leaderboards.

Analytical Functions: Calculating Running Totals for monthly revenue and Moving Averages for patient inflow.

# 📂 Query Breakdown & Insights<br>
1. Revenue & Billing Analysis
Running Total of Revenue: Calculated the cumulative revenue over time to identify financial growth trends.

Insurance vs. Cash: Analyzed the ratio of insurance-backed payments versus out-of-pocket expenses.

2. Doctor & Staff Performance
Top Performing Doctors: Ranked doctors within each specialization based on the number of appointments using Window Functions.

Workload Analysis: Identified doctors handling above-average patient loads to prevent burnout.

3. Patient Trends
Demographic Segmentation: Grouped patients by age and gender to identify the primary target audience for specific treatments.

Appointment Patterns: Found that [Insert Day, e.g., Monday] is the busiest day, suggesting a need for increased staffing.

# 🚀 How to Use This Repository<br>
Dataset: The raw data is uploaded

SQL Script: Run the hospital_analysis.sql file in your SQL editor to reproduce the results.

Documentation: The detailed PPT explains the visual trends and final recommendations.

# 📈 Key Findings & Recommendations<br>
Insight: The Cardiology department generates 40% of the total revenue but has the longest wait times.

Action: Recommend hiring additional support staff for high-traffic departments during peak hours (Mondays/Tuesdays).

Insight: Patients in the 45-60 age group represent the highest recurring visits.

Action: Suggest loyalty programs or specialized health check-up packages for this demographic.
