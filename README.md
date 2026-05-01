Project: Data Integrity & Structural Analysis (Kaggle Dataset)
📌 Project Overview
This project was initiated as part of my journey to transition from Data Entry to Data Analytics. The primary objective was to perform exploratory data analysis (EDA) and build an automated dashboard using Microsoft Excel to visualize trends within a Kaggle-sourced dataset.
📖 The Project Story
As an aspiring Data Analyst, I believe that real-world data is rarely clean. To sharpen my skills, I selected a dataset from Kaggle to practice data cleaning, Power Query transformations, and advanced Pivot Table reporting. The goal was to transform raw time-series data into a functional dashboard.
🛠 Tools & Technologies
Microsoft Excel: Data Processing & Formula application.
Power Query: ETL (Extract, Transform, Load) operations.
Kaggle: Source of raw data.
⚠️ Technical Blocker: The "Date Logic" Fault
During the development phase of the dashboard, I encountered a critical data integrity issue that serves as a significant case study for data quality.
The Issue:
The dataset contains structural anomalies in the date column. Specifically, it includes non-existent dates such as September 31st (Row 109 and others).
The Impact:
Pivot Table Failure: Excel cannot recognize these rows as valid dates. As a result, the "Date Grouping" feature (Years, Quarters, Months) in Pivot Tables is disabled.
Dashboard Accuracy: Any dashboard built on this data would provide skewed or incorrect insights due to these "ghost" entries.
🛑 Project Conclusion
After identifying these widespread anomalies across 500+ rows, I have decided to conclude the project at this stage.
While the original goal was to build a final dashboard, the most important lesson learned here was Data Auditing. Instead of forcing a visualization on broken data, I am documenting this as a "Data Quality Report."
This project highlights my ability to:
Identify structural inconsistencies in large datasets.
Understand the technical limitations of Excel when dealing with invalid logic.
Prioritize data accuracy over aesthetic visualization.
🎓 Key Takeaways
Data cleaning is 80% of the work in Analytics.
Always verify date logic before attempting to build Pivot Tables.
Knowing when to stop and fix the source is a vital skill for any Data Analyst.
Developed as part of my Data Analytics Mastery Journey.
