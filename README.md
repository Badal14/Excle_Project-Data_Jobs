# 📊 AI & Data Science Job Salary Analysis Using Excel

## 📌 Project Overview

This project analyzes an AI & Data Science job salary dataset containing **5,000 records** using Microsoft Excel.

The objective is to explore salary patterns and understand how factors such as **job title, experience level, company size, industry, education, employment type, remote work, AI-tool usage, job switching, and management responsibilities** influence compensation and other workplace outcomes.

The project demonstrates practical Excel data analysis skills including **data cleaning, statistical analysis, Pivot Tables, Pivot Charts, lookup functions, and business-oriented analysis**.

---

## 🎯 Business Problem

The AI and Data Science job market contains a wide range of roles, experience levels, industries, company sizes, and compensation structures.

Job seekers and organizations may want to understand:

- Which AI/Data Science roles offer higher salaries?
- How does experience affect compensation?
- Does company size influence salary?
- Which industries offer better compensation?
- Does higher education correspond to higher salaries?
- How does remote work relate to employment patterns?
- Do employees who manage people earn more?
- Does changing jobs affect salary?
- Is AI-tool adoption associated with automation concerns?
- Does having "ML" in a job title relate to higher compensation?

This project uses Excel-based analysis to answer these questions.

---

# 📂 Dataset

The dataset contains:

- **5,000 job records**
- **27+ original variables**
- Salary and compensation information
- Employee and company information
- Experience and education information
- AI-tool usage information
- Job satisfaction information
- Remote-work information
- Career-related information

### Important Variables

| Category | Variables |
|---|---|
| Job Information | Job Title, Experience Level, Employment Type |
| Company | Company Size, Company Location, Industry |
| Education | Education Level |
| Experience | Years of Experience |
| Compensation | Salary USD, Bonus %, Equity % |
| Work Pattern | Remote Ratio, Weekly Hours |
| AI Usage | AI Tools Usage, AI Tool Hours |
| Career | Job Switching, Upskilling Hours |
| Management | Team Size, Manages People |
| Employee Sentiment | Job Satisfaction, AI Automation Fear |
| Recruitment | Interviews to Offer |
| Skills | Primary Language, Certifications |

---

# 🛠️ Tools & Technologies

- Microsoft Excel
- Excel Tables
- Excel Formulas
- Data Cleaning
- Pivot Tables
- Pivot Charts
- Statistical Analysis
- Lookup Functions
- Data Summarization
- Data Visualization
- Business Analysis

---

# 🔄 Project Workflow

The analysis followed these major steps:

### 1. Data Preparation

- Reviewed the original dataset
- Structured the data into an Excel table
- Cleaned and organized the dataset
- Created helper fields where required
- Standardized country-related information
- Prepared the dataset for analysis

### 2. Data Cleaning

A dedicated **Cleaned Data** worksheet was created containing the prepared dataset.

The cleaned dataset contains **5,000 records and 32 analytical columns**.

Additional derived fields include:

- Country names
- Months
- Weekly minutes
- AI-tool minutes per week
- Management indicators
- AI-related indicators

### 3. Statistical Analysis

Statistical analysis was performed on important numerical variables.

The analysis includes:

- Mean
- Median
- Mode
- Standard Error
- Standard Deviation
- Sample Variance
- Kurtosis
- Skewness
- Range
- Minimum
- Maximum
- Sum
- Count

Key measures analyzed include:

- Team Size
- Certifications
- Weekly Working Hours
- AI Tool Usage
- Salary
- Equity
- Bonus
- Job Satisfaction
- Interviews to Offer
- Upskilling Hours
- AI Automation Fear

### 4. Pivot Table Analysis

Pivot Tables were created to answer business questions related to:

- Job titles
- Experience levels
- Company sizes
- Industries
- Education
- Remote work
- Employment type
- Bonus compensation
- Management responsibility
- AI-tool usage
- Job switching
- ML-related job titles

---

# 📊 Key Business Questions

The project answers several analytical questions.

### Q1. How does average salary differ across job titles?

Analyzed the average salary for different AI and Data Science roles including:

- AI Engineer
- Data Engineer
- Data Scientist
- Machine Learning Engineer
- Data Analyst
- Research Scientist
- MLOps Engineer
- LLM Engineer
- Data Science Manager
- Analytics Engineer

---

### Q2. How does average pay change by experience level and company size?

Compared salary across:

- Entry
- Mid
- Senior
- Lead
- Executive

and company sizes:

- Small
- Medium
- Large

This helps identify how experience and company size interact with compensation.

---

### Q3. Which industries pay more?

Compared average salaries across industries including:

- Technology
- Finance
- Healthcare
- Consulting
- Energy
- Manufacturing
- Retail
- Government
- Education
- Media

---

### Q4. Does education influence salary?

Compared average salary across education levels such as:

- Bachelor's
- Master's
- PhD
- Bootcamp
- Self-taught

while considering different experience levels.

---

### Q5. How is employment distributed across remote-work levels?

Analyzed employee counts across:

- On-site
- Hybrid
- Fully Remote

and different employment types:

- Full-time
- Part-time
- Contract
- Freelance

---

### Q6. How does bonus compensation vary by experience and company size?

Analyzed average bonus percentages across:

- Experience levels
- Company sizes

This provides insight into compensation structure beyond base salary.

---

### Q7. Do people managers earn more?

Compared average salary based on whether an employee:

- Manages people
- Does not manage people

The analysis was further segmented by experience.

---

### Q8. Does AI-tool usage relate to automation concerns?

Compared AI automation fear scores between:

- Daily AI-tool users
- Non-daily AI-tool users

across different industries.

---

### Q9. Do employees who switched jobs earn more?

Compared average salary between:

- Employees who switched jobs in the previous year
- Employees who did not switch jobs

The comparison was performed across experience levels.

---

### Q10. Does having "ML" in a job title correspond to higher salary?

Compared average salary for roles based on whether the job title contains an ML-related designation.

---

# 📈 Key Findings

Some notable observations from the analysis include:

- The overall average salary in the dataset is approximately **$98,605**.
- Salary varies significantly across job titles and experience levels.
- Executive and Lead positions generally show substantially higher average compensation than Entry-level roles.
- Technology and Finance show relatively strong average salary levels among the analyzed industries.
- Larger companies generally show higher average compensation across several experience levels.
- Education and experience interact strongly with salary rather than acting as isolated factors.
- AI-tool usage and automation concerns show differences across industries.
- Management responsibility can be associated with different compensation levels depending on experience.
- Job switching does not necessarily result in higher salary across every experience level.

> Note: These findings describe patterns in this dataset and should not be interpreted as causal relationships.

---

# 📊 Excel Analysis Techniques Used

## Data Cleaning

- Removing/organizing unnecessary fields
- Standardizing data
- Creating helper columns
- Data validation
- Data preparation

## Formulas & Functions

- IF
- Nested IF
- SUM
- SUMIF / SUMIFS
- COUNTIF / COUNTIFS
- AVERAGE
- Lookup functions
- Logical functions

## Lookup Functions

- VLOOKUP
- HLOOKUP
- XLOOKUP

## Pivot Tables

- Average salary analysis
- Employee count analysis
- Experience-level analysis
- Industry comparison
- Company-size comparison
- Remote-work analysis

## Statistical Analysis

- Mean
- Median
- Mode
- Standard Deviation
- Variance
- Skewness
- Kurtosis
- Range
- Minimum
- Maximum

---

# 📁 Workbook Structure

The Excel workbook contains multiple worksheets:

```text
AI-Data-Science-Job-Salary-Analysis.xlsx

│
├── ai_ds_job_salaries_2026
│   └── Original dataset
│
├── Cleaned Data
│   └── Cleaned and prepared dataset
│
├── Statistical Analysis
│   └── Descriptive statistical analysis
│
├── Helper
│   └── Helper/reference data
│
└── PV-Tables
    └── Business questions and Pivot Table analysis
