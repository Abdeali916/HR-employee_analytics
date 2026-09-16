# HR Analytics Dashboard --- Employee Attrition Analysis

An HR analytics project built with **Power BI** to analyze employee
attrition and identify the workforce factors most associated with
employee turnover.

The project uses an HR employee dataset containing **1,480 employee
records and 38 attributes**. The data was cleaned and prepared in
**Power BI** before building the analytical dashboard.

## Business Objective

The main objective is to help HR and management understand:

-   How significant employee attrition is
-   Which employee groups have the highest attrition
-   Whether overtime is associated with higher turnover
-   How salary level relates to attrition
-   Which job roles have the highest attrition
-   Whether age is associated with employee turnover
-   How department and education background relate to attrition
-   Where HR should prioritize retention efforts

## Data Preparation

The raw HR dataset was cleaned and prepared in **Power BI / Power
Query** before analysis.

The project workflow was:

**Raw Data → Power BI Cleaning & Transformation → Data Model → DAX
Measures → Dashboard → Business Insights**

The source workbook contains 1,480 employee records and 38 columns. The
supplied source contains 7 duplicate rows and 57 missing-value cells;
these should be treated during the Power BI cleaning stage before the
final dashboard is interpreted.

Typical preparation activities for this project include checking data
types, duplicate records, missing values, category consistency, and
preparing analytical fields such as age groups, salary slabs, attrition
indicators, and KPI measures.

## Dashboard

The Power BI report contains KPI cards and visual analysis for:

-   Employee count
-   Attrition rate
-   Average age
-   Attrition count
-   Average salary
-   Average years at company
-   Attrition by education field
-   Attrition by age group
-   Attrition by job role and job satisfaction
-   Attrition by salary slab
-   Attrition by education field
-   Attrition by years at company
-   Attrition by gender
-   Department slicer

## Key KPIs

  KPI                              Result
  -------------------------- ------------
  Employees                         1,480
  Attrition count                     238
  Attrition rate                    16.1%
  Average age                  36.9 years
  Average monthly income         R\$6,505
  Average years at company      7.0 years

## Main Findings

### 1. Overall attrition is 16.1%

Out of 1,480 employees, 238 have an `Attrition = Yes` status.

This establishes employee turnover as a meaningful HR issue and provides
the baseline against which different employee segments can be compared.

### 2. Overtime is strongly associated with attrition

Employees working overtime have an attrition rate of approximately
**30.6%**, compared with **10.4%** among employees who do not work
overtime.

The observed attrition rate is therefore almost **3 times higher** for
the overtime group.

**Business implication:** HR should investigate workload, burnout,
scheduling, staffing levels, and compensation for employees regularly
working overtime.

### 3. Younger employees show higher attrition

The **18--25** age group has an attrition rate of approximately
**35.8%**, the highest among the age groups.

The 36--45 group has the lowest rate at approximately **9.1%**.

**Business implication:** early-career employees may require stronger
onboarding, career-development, mentoring, and progression programs.

### 4. Lower salary bands have higher attrition

Employees earning **up to 5k** have an attrition rate of approximately
**21.6%**, while employees in the **15k+** salary slab have an attrition
rate of only about **3.8%**.

**Business implication:** compensation competitiveness, career
progression, and perceived earning potential should be investigated for
lower-paid employees.

### 5. Sales Representatives have the highest job-role attrition

The highest observed job-role attrition rates include:

  Job Role                      Attrition Rate
  --------------------------- ----------------
  Sales Representative                   39.3%
  Laboratory Technician                  23.8%
  Human Resources                        23.1%
  Sales Executive                        17.6%
  Research Scientist                     16.0%
  Healthcare Representative               6.8%
  Manufacturing Director                  6.8%
  Manager                                 4.9%
  Research Director                       2.5%

**Business implication:** Sales Representatives should be a priority
segment for retention investigation.

### 6. Sales has the highest department attrition rate

  Department                 Employees   Attrition Rate
  ------------------------ ----------- ----------------
  Sales                            450            20.7%
  Human Resources                   63            19.0%
  Research & Development           967            13.8%

Sales has both a large workforce and the highest department-level
attrition rate in this dataset.

### 7. Single employees have higher attrition

Single employees have an attrition rate of approximately **25.4%**,
compared with **12.4%** for married employees and **10.4%** for divorced
employees.

This is an observed association, not evidence that marital status causes
attrition.

### 8. Education field also shows differences

The highest observed attrition rates by education field are:

-   Human Resources: 25.9%
-   Technical Degree: 24.2%
-   Marketing: 22.4%
-   Life Sciences: 14.7%
-   Medical: 13.4%
-   Other: 13.3%

These differences can help HR identify groups for deeper investigation,
but education field alone should not be treated as a causal driver.

## Recommendations

### Priority 1 --- Address overtime risk

Review overtime frequency and workload for high-risk teams. Consider
staffing changes, workload balancing, manager interventions, and
employee well-being programs.

### Priority 2 --- Retain early-career employees

Build stronger onboarding, mentoring, training, internal mobility, and
career-path programs for younger employees.

### Priority 3 --- Investigate compensation

Review pay competitiveness and promotion opportunities in the lower
salary bands, especially for roles with simultaneously high attrition.

### Priority 4 --- Focus on Sales Representatives

Perform a deeper investigation into sales targets, commission
structures, workload, manager quality, travel requirements, and career
progression.

### Priority 5 --- Build a proactive attrition-risk dashboard

The next version could add employee-level risk segmentation using
factors such as overtime, job satisfaction, income, tenure, promotion
history, distance from home, and manager tenure.

## Important Analytical Note

This project identifies **associations**, not causal relationships.

For example, the fact that overtime employees have higher attrition does
not prove overtime directly causes employees to leave. HR should combine
this analysis with employee surveys, exit interviews, workload
information, compensation benchmarks, and manager-level analysis.

## Tools Used

-   Microsoft Power BI
-   Power Query
-   DAX
-   Excel / CSV source data
-   Data cleaning and transformation
-   Exploratory data analysis
-   KPI design
-   Business intelligence dashboarding

## Portfolio Skills Demonstrated

**Data Cleaning → Data Transformation → Data Modeling → DAX → KPI
Development → Visualization → Business Analysis → Recommendations**

## Future Improvements

-   RFM-style employee segmentation is not applicable here; instead use
    employee attrition-risk segmentation.
-   Add overtime intensity and workload measures.
-   Analyze attrition by manager.
-   Analyze promotion gaps.
-   Add satisfaction-score analysis.
-   Build employee cohorts by joining year.
-   Create a statistical/model-based attrition prediction layer.
-   Add Power BI drill-through pages for department and job-role
    investigation.

## Dataset

The dataset is a publicly available HR analytics dataset commonly used
for employee attrition analysis. If redistributing the source data,
retain the original dataset attribution and applicable terms.

## Project Files

``` text
HR-Analytics/
├── README.md
├── FINDINGS.md
├── Abbu.pbix
└── HR_Analytics.xlsx
```
