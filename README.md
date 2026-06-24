HR Attrition Analysis
An exploratory data analysis of employee turnover using internal HR data from a retail organization (~1,470 employees, 35 attributes).

What It Does
Calculates overall attrition rate (16.1%)
Compares attrition across departments, overtime status, job satisfaction levels, and work-life balance scores
Creates a risk segmentation based on overtime + low satisfaction + promotion gaps
Exports summary tables to Excel for HR review
Generates bar charts, boxplots, and a correlation heatmap
Files
File	Description
HRattriton.ipynb	Analysis notebook
hr_data.csv	Employee dataset (1,470 records)
attrition_summary.xlsx	Excel export with department/job role/risk summaries
hr_attrition_brief.docx	Project brief
What I Learned
Data profiling with pandas (dtypes, nulls, value counts)
Grouped aggregations for segmentation analysis
Data visualization with matplotlib + seaborn
Custom risk scoring logic based on multiple conditions
Exporting analysis results to Excel
To Improve
Analyze attrition by tenure milestones (1yr, 3yr peaks)
Test whether below-median pay predicts attrition
Add statistical tests to support findings
Validate risk segments against actual attrition rates
