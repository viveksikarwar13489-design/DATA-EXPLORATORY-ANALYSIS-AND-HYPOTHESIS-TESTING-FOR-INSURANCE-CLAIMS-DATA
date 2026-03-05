# DATA-EXPLORATORY-ANALYSIS-AND-HYPOTHESIS-TESTING-FOR-INSURANCE-CLAIMS-DATA
This project focuses on Exploratory Data Analysis (EDA) and Statistical Hypothesis Testing on insurance claims data to uncover patterns, detect fraudulent activities, and understand customer claim behavior.
Project Objectives

The main objectives of this project are:

Create a 360° view of customer insurance claims data

Perform data cleaning and preprocessing

Conduct exploratory data analysis (EDA)

Identify fraudulent claims patterns

Analyze claim trends across gender, age groups, and segments

Apply statistical hypothesis testing to validate business questions

📁 Dataset Description

The project uses two datasets:

1️⃣ Customer Data (cust_data.csv)

Contains customer demographic information.

Example columns:

customer_id

gender

state

segment

date_of_birth

2️⃣ Claims Data (claims_data.csv)

Contains insurance claim information.

Example columns:

claim_id

customer_id

incident_cause

claim_type

claim_amount

police_report

fraud_flag

claim_date

Both datasets are merged to create a single analytical dataset for deeper analysis.

🔍 Data Preparation Steps

The following preprocessing steps were performed:

Merged customer and claims datasets

Performed data type audit

Converted claim_amount to numeric and removed $ symbol

Created an alert flag for injury claims not reported to police

Removed duplicate records by keeping the most recent claim per customer

Handled missing values using:

Mean for numerical variables

Mode for categorical variables

Calculated customer age

Categorized customers into age groups:

Children (<18)

Youth (18–30)

Adult (30–60)

Senior (>60)

📊 Exploratory Data Analysis

The analysis includes:

Average claim amount by customer segment

Total claim amount by incident cause

Insurance claims across different states

Gender-wise claim analysis

Fraudulent claims analysis by age group

Monthly claim trend analysis

Claim amount distribution by gender and segment

📈 Data Visualizations

Several visualizations were created to better understand the data:

Histograms

Bar charts

Pie charts

Monthly trend charts

Faceted bar charts

Fraud analysis charts

These visualizations help identify patterns in claim behavior and fraud detection.

🧪 Hypothesis Testing

Statistical tests were performed to answer key business questions:

1️⃣ Is there any similarity in claim amounts between male and female customers?

2️⃣ Is there a relationship between customer segment and age category?

3️⃣ Has the average claim amount increased significantly compared to the 2016–17 average ($10,000)?

4️⃣ Is there a difference in insurance claims across age groups?

5️⃣ Is there a relationship between number of policy claims and claim amount?

Each hypothesis test includes:

Null Hypothesis (H₀)

Alternate Hypothesis (H₁)

Statistical Test Used

P-value Interpretation

Business Conclusion
