# Online-course-dashboard
📊 Online Course Platform: Student Performance & Engagement Analysis
This project involves end-to-end data cleaning and visualization for an online course platform. The goal is to analyze student performance, engagement, and behavior using Excel and Power BI.

📁 Dataset Overview
Total Rows: 1,200
Key Columns:
Student_ID
Name (inconsistent casing and spacing)
Email (missing/malformed entries)
Gender (variations like "Male", "M", "FEMALE", etc.)
Country (inconsistent formatting: "India", "india", "IN")
Age (some missing/invalid)
Enrollment_Date (multiple formats)
Course_Name, Course_Category
Progress (%) (mixed strings with/without "%")
Time_Spent (hrs) (some in minutes/text)
Completed (values like "Y", "Yes", "1", "No", etc.)
Feedback_Rating (1 to 5, some blank/out of range)
Session_Attendance (comma-separated session dates)
🧹 Part 1: Excel – Advanced Data Cleaning
✅ Key Cleaning Tasks:
Normalize Time_Spent: Convert to hours (e.g., "30 mins" → 0.5).
Fix Age: Impute missing/invalid entries using mean or median.
Sessions Count: Extract number of sessions from Session_Attendance.
Email Cleanup: Remove invalid/malformed entries, identify duplicates.
High Performer Flag: Define as Completed = Yes AND Rating ≥ 4.
New Features:
Experience_Level: Based on Age (e.g., Student, Early Career).
Engagement_Level: Derived from Time_Spent + Progress.
📈 Part 2: Power BI – Interactive Dashboard
📄 Multi-Page Layout:
Overview Page: KPIs, summary metrics.
Category Analysis: Deep-dive by course category.
Engagement Heatmap: Visualize student interaction levels.
🧮 KPIs:
Total Students
Average Progress
Average Feedback Rating
Course Completion Rate
📊 Visualizations:
Bar/Column Charts: Students by Category, Completion by Country
Matrix Table: Cross-tab → Course vs Feedback Rating
Line/Area Chart: Monthly Enrollment Trend
Scatter Plot: Correlation between Progress and Rating
🔍 Interactivity:
Drill-through: From summary to individual student details
Slicers: Filter by Course Category, Country, and Experience Level
💡 Tools Used
Microsoft Excel: Data wrangling, transformation
Power BI: Dashboard creation, DAX measures
DAX (Data Analysis Expressions): Custom KPIs and visuals
📌 Project Goals
Identify trends in student performance and behavior.
Build robust data pipelines for cleaning and feature creation.
Design dynamic dashboards for stakeholders and educators.
