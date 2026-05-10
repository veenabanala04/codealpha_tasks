Task 2 – Unemployment Rate Analysis & Covid-19 Impact Study
📌 Overview

This task focuses on performing an in-depth data analysis of unemployment trends using real-world data. The objective is to analyze unemployment patterns across regions, identify seasonal trends, and evaluate the impact of Covid-19 on employment rates.

The project follows a structured data science workflow including data cleaning, exploratory data analysis (EDA), visualization, statistical analysis, and insight generation.

🎯 Objective
Analyze unemployment rate trends over time
Compare regional unemployment patterns
Identify seasonal variations
Evaluate the impact of Covid-19 on unemployment
Generate meaningful visual insights
📂 Dataset Used

File: Unemployment_Rate_upto_11_2020.csv

The dataset includes:

Region
Date
Estimated Unemployment Rate
Estimated Employed
Estimated Labour Participation Rate
Longitude & Latitude

The dataset spans pre-Covid and post-Covid periods, allowing comparative analysis.

🛠 Implementation Workflow
1️⃣ Data Loading & Cleaning
Imported dataset using Pandas
Renamed columns for clarity
Converted Date column to datetime format
Checked and handled missing values
2️⃣ Exploratory Data Analysis (EDA)
Generated statistical summaries
Calculated average unemployment rate
Created monthly feature extraction
3️⃣ Data Visualization

The following visual analyses were performed:

📈 Unemployment Trend Over Time
📊 Region-wise Unemployment Comparison
📦 Monthly Distribution (Boxplots)
🦠 Covid-19 Impact Analysis (Pre vs Post March 2020)
🔥 Correlation Heatmap
📉 Rolling Average Trend Analysis
🗺 Region vs Month Heatmap
📊 Distribution & Outlier Detection
🦠 Covid-19 Impact Analysis

The dataset was divided into:

Pre-Covid Period: Before March 2020
Covid Period: After March 2020

A comparative analysis showed a noticeable increase in unemployment rates during the Covid period, highlighting the economic disruption caused by the pandemic.

📈 Key Insights
Unemployment rates increased significantly during the Covid-19 period.
Certain regions consistently reported higher unemployment levels.
Seasonal and monthly patterns are observable in the data.
Rolling averages reveal smoother long-term employment trends.
Correlation analysis provides insights into relationships between employment metrics.
▶️ How to Run
✅ On Google Colab
Open Google Colab
Upload:
Your Task 2 Python file
Unemployment_Rate_upto_11_2020.csv
Install required libraries (if needed):
!pip install pandas numpy matplotlib seaborn
Run the script:
!python "your_task2_filename.py"
✅ Run Locally
pip install pandas numpy matplotlib seaborn
python "your_task2_filename.py"

Make sure the dataset file is in the same directory as the script.

💡 Skills Demonstrated
Data Cleaning & Preprocessing
Time-Series Analysis
Exploratory Data Analysis (EDA)
Statistical Interpretation
Data Visualization
Covid-19 Impact Assessment
Insight Generation from Real-World Data
