**Data Science Salary Analysis (2023-2024)**

**Overview:**
This project analyzes salary trends in the data science industry using a dataset of 2,576 unique job records. The analysis covers key factors such as experience level, employment type, company size, remote work, and geographic location. Additionally, a Multiple Linear Regression model was used to predict 2024 salaries based on past trends.

**Dataset:**
Total Records: 2,576 (after removing duplicates)

Columns:
1. work_year: Year of data collection (2020-2023)
2. experience_level: Entry (EN), Mid (MI), Senior (SE), Expert (EX)
3. employment_type: Full-time (FT), Part-time (PT), Contract (CT), Freelance (FL)
4. job_title: Various data science roles
5. salary_in_usd: Salary in USD
6. remote_ratio: 0% (Onsite), 50% (Hybrid), 100% (Fully Remote)
7. company_location: Country where the company is based
8. company_size: Small (S), Medium (M), Large (L)

**Key Findings**

**Top 5 Highest Paying Jobs (2023)**
1. Data Science Tech Lead - $375,000
2. Cloud Data Architect - $250,000
3. Principal Data Scientist - $198,171
4. Director of Data Science - $195,140
5. Machine Learning Software Engineer - $192,420

**Salary Trends (2020-2024)**
1. Average salary increased from $93,353 (2020) to $146,724 (2023)
2. Remote jobs showed mixed salary trends depending on country
3. Large companies pay more than small companies (Median salary: $100,000 vs. $62,726)
   
**Salary Prediction for 2024**

1. Top Growth: Research Scientist (+$281,058) and ML Software Engineer (+$197,000)
2. Biggest Drop: NLP Engineer (-$145,000) and Head of Data Science (-$144,950)
3. Prediction Model: Multiple Linear Regression
   
**Methodology**
1️⃣ Data Cleaning
✔ Removed 1,171 duplicate rows
✔ Standardized job titles (e.g., "ML Engineer" → "Machine Learning Engineer")
✔ Converted work year to categorical format

2️⃣ Exploratory Data Analysis (EDA)
✔ Boxplots, histograms, and correlation heatmaps
✔ Analyzed salary trends by job title, location, company size
✔ Identified highest paying jobs by country

3️⃣ Predictive Modeling (2024 Salary Forecast)
✔ Multiple Linear Regression model trained on job title, experience, employment type, location
✔ Predicted 2024 salaries
