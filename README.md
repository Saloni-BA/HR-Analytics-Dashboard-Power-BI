HR Analytics Dashboard using Power BI
Objective
The objective of this project is to identify the key factors driving employee attrition and provide actionable insights for improving workforce retention in an organization. This dashboard provides insights of the attrition of an organization which helps the HR team for their further analysis.

Throughout this project, I've had the chance to:

Dive deep into HR data to uncover valuable insights.
Develop interactive dashboards to visualize key HR metrics.
Provide data-driven recommendations for strategic decision-making.
Steps followed:
1. Data Gathering:

Importing raw data .csv file into Power BI & transform to Power Query editor for cleaning and data processing.
2. Data cleaning:

Cleaning is done by removing empty column, removing duplicates, errors etc.
Replacing values in column with proper values and naming.
Detecting data type of every column, using the auto detect data type function in Power query editor.
3. Data processing:

In the Power Query editor, creating new column called "AttritionCount" by using conditional column feature in add column which is created on the basis of certain condition like (IF attrition = 'Yes' then 1, Else 0).
This new column is further used for creating different KPI's and charts.Then creating the Attrition Rate by applying DAX queries, adding new measure (Attrition Rate = SUM([AttritionCount]))/SUM([Employeecount])) in %.
4. Data analysis:

Analysis involves the creation of a range of visual representations, including bar charts, key performance indicators (KPIs), table charts, pie charts, and other relevant visualizations.
These tools are utilized to gain insights and present data in a comprehensive and easily understandable manner.
Key Questions of the Dashboard :
What is the Total Employee Count ?
What is the Attrition Count of men and women ?
What is the employee's Average Age & Average Salary ?
What is employees Working years at the Company ?
Which Education Field has maximum employees ?
Which Department has maximum employee ?
Which Age Group has maximum employees ?
What are the Job Roles and Salary Slabs of the employees?
Learned about:
Calculated Field: To Calculate Attrition Rate & Active Employees
Matrix table: To show Job Satisfaction rating
Donut chart and Pie Chart
Bar Chart and Cluster chart 📊
KPI(Key Performing Indicators) and Slicer.
Filters: Used to filter data according to different education fields.
Key Insights Summary:
Total Employees: The organization has grown significantly, currently employing 1470 individuals, indicating substantial growth and scale.
Attrition Analysis: A total of 237 employees left the organization. Among them, 140 were male, and 79 were female, indicating a higher attrition rate among males.
Education Field Impact: Employees in the life sciences field had the highest attrition rate, emphasizing the need to address retention challenges in this specific area.
Job Role Affected: The Laboratory Technician had the highest attrition rate, indicating a need for focused retention efforts in this department to reduce turnover.
Salary Slab wise Attrition: The salary upto 5k has the maximum attrition.
Attrition Rate by Gender for Different Age Group: The attrition count among the age group of 26-35 years 116 which is maximum among the other age groups.
[Dashboard] : https://drive.google.com/file/d/17I_OcgqQKdyZmViYDaDFtN_QlFCfREDf/view?usp=drive_link

[HR Analytics dashboard] : https://github.com/Saloni-BA/HR-Analytics-Dashboard-Power-BI/blob/main/HR_Analytics.pbix

