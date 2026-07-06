**Data Science Salary Analysis (2023-2024)**

## Business Relevance
Compensation benchmarking and workforce analytics are core 
functions at HR tech, fintech, and SaaS companies. This 
project demonstrates the ability to extract actionable 
insights from structured HR data — directly applicable to 
people analytics, market intelligence, and compensation 
planning roles.


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
1. Data Cleaning
✔ Removed 1,171 duplicate rows
✔ Standardized job titles (e.g., "ML Engineer" → "Machine Learning Engineer")
✔ Converted work year to categorical format

2. Exploratory Data Analysis (EDA)
✔ Boxplots, histograms, and correlation heatmaps
✔ Analyzed salary trends by job title, location, company size
✔ Identified highest paying jobs by country

3. Predictive Modeling (2024 Salary Forecast)
✔ Multiple Linear Regression model trained on job title, experience, employment type, location
✔ Predicted 2024 salaries

## Key Findings

### Compensation Benchmarking
**Why it matters:** Knowing which roles command premium 
salaries helps companies stay competitive in talent 
acquisition — a core use case in HR analytics platforms.

Top 5 Highest Paying Jobs (2023):
1. Data Science Tech Lead - $375,000
2. Cloud Data Architect - $250,000
3. Principal Data Scientist - $198,171
4. Director of Data Science - $195,140
5. ML Software Engineer - $192,420

---

### Salary Growth Trends
**Why it matters:** Year-over-year salary growth signals 
demand shifts in the labor market — useful for workforce 
planning and budget forecasting.

- Average salary grew from $93,353 (2020) to $146,724 
  (2023) — a 57% increase over 3 years
- Large companies pay 59% more than small companies 
  (Median: $100,000 vs $62,726)

---

### 2024 Salary Predictions
**Why it matters:** Forward-looking compensation forecasts 
help organizations plan hiring budgets and retention 
strategies before market shifts occur.

- Top Growth: Research Scientist (+$281,058), 
  ML Software Engineer (+$197,000)
- Biggest Drop: NLP Engineer (-$145,000), 
  Head of Data Science (-$144,950)
- Model: Multiple Linear Regression trained on job title, 
  experience, employment type, and location


## Known Limitations
- Dataset covers 2020-2023; 2024 predictions are 
  extrapolations based on historical trends
- Multiple Linear Regression assumes linear relationships 
  — a gradient boosting model (XGBoost) would likely 
  improve prediction accuracy
- Geographic salary differences may reflect cost of living 
  rather than true compensation variation
