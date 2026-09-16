# HR Analytics --- Key Findings

## Executive Summary

The HR dataset contains **1,480 employees**. The analysis identifies an
overall attrition rate of **16.1%**, with particularly high observed
attrition among employees who work overtime, younger employees,
lower-paid employees, Sales Representatives, and employees in the Sales
department.

The strongest practical signal in the analysis is the relationship
between **overtime and attrition**: 30.6% of overtime employees have
attrition compared with 10.4% of non-overtime employees.

These findings should be treated as **associations**, not proof of
causation.

------------------------------------------------------------------------

## 1. Overall Workforce

-   Employees: **1,480**
-   Employees with attrition: **238**
-   Employees without attrition: **1,242**
-   Overall attrition rate: **16.1%**
-   Average age: **36.9 years**
-   Average monthly income: **R\$6,505**
-   Average years at company: **7.0 years**
-   Average total working years: **11.3 years**

------------------------------------------------------------------------

## 2. Attrition by Overtime

  -----------------------------------------------------------------------
  Overtime           Employees with    Total Employees     Attrition Rate
                          Attrition                    
  -------------- ------------------ ------------------ ------------------
  No                            110              1,062              10.4%

  Yes                           128                418              30.6%
  -----------------------------------------------------------------------

The attrition rate among overtime employees is almost **3×** the rate
among non-overtime employees.

### Interpretation

Overtime is one of the clearest segments for further HR investigation.

### Recommended action

Review workload, staffing, schedules, manager practices, and employee
well-being in teams with high overtime.

------------------------------------------------------------------------

## 3. Attrition by Age

  Age Group     Attrition Rate
  ----------- ----------------
  18--25                 35.8%
  26--35                 19.0%
  36--45                  9.1%
  46--55                 11.8%
  55+                    17.0%

The **18--25** group has the highest observed attrition.

### Interpretation

Early-career employees may be more mobile and may have different
expectations around growth, learning, compensation, and career
progression.

### Recommended action

Strengthen onboarding, mentoring, career development, training, and
internal mobility programs.

------------------------------------------------------------------------

## 4. Attrition by Salary

  Salary Slab     Attrition Rate
  ------------- ----------------
  Upto 5k                  21.6%
  5k--10k                  11.0%
  10k--15k                 14.0%
  15k+                      3.8%

The lowest salary slab has substantially higher attrition than the
highest salary slab.

### Interpretation

Compensation and career progression may be important areas to
investigate, particularly for lower-paid employees.

### Recommended action

Review salary competitiveness, promotion pathways, incentives, and role
progression.

------------------------------------------------------------------------

## 5. Attrition by Job Role

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

### Key finding

**Sales Representative** has the highest observed attrition rate at
approximately **39.3%**.

### Recommended action

Investigate sales targets, compensation/commission structure, travel,
workload, manager support, and career progression.

------------------------------------------------------------------------

## 6. Attrition by Department

  Department                 Employees   Attrition   Attrition Rate
  ------------------------ ----------- ----------- ----------------
  Sales                            450          93            20.7%
  Human Resources                   63          12            19.0%
  Research & Development           967         133            13.8%

### Key finding

Sales has the highest department-level attrition rate and also has a
substantial employee population.

### Recommended action

Prioritize Sales for deeper retention analysis.

------------------------------------------------------------------------

## 7. Attrition by Marital Status

  Marital Status     Attrition Rate
  ---------------- ----------------
  Single                      25.4%
  Married                     12.4%
  Divorced                    10.4%

Single employees show approximately twice the attrition rate of married
employees.

### Caution

This is an observed association. It should **not** be interpreted as
marital status causing attrition.

------------------------------------------------------------------------

## 8. Attrition by Education Field

  Education Field      Attrition Rate
  ------------------ ----------------
  Human Resources               25.9%
  Technical Degree              24.2%
  Marketing                     22.4%
  Life Sciences                 14.7%
  Medical                       13.4%
  Other                         13.3%

Human Resources and Technical Degree backgrounds show the highest
observed attrition rates.

------------------------------------------------------------------------

## 9. Attrition by Gender

  Gender     Attrition Rate
  -------- ----------------
  Male                17.0%
  Female              14.7%

The male attrition rate is somewhat higher in this dataset, but the
difference is much smaller than the differences observed for overtime,
age, salary, or job role.

------------------------------------------------------------------------

## 10. Satisfaction and Tenure

The dashboard includes analysis of attrition across job satisfaction and
years at company.

Average values by attrition status show that employees who left tend to
have:

  Metric                           Stayed       Left
  ---------------------------- ---------- ----------
  Age                                37.5       33.7
  Monthly Income                 R\$6,829   R\$4,813
  Years at Company                    7.4        4.0
  Job Satisfaction                   2.78       2.47
  Environment Satisfaction           2.77       2.46
  Job Involvement                    2.77       2.51
  Work-Life Balance                  2.78       2.66
  Years with Current Manager          4.4        2.8

### Interpretation

Employees who left are, on average, younger, lower-paid, have shorter
company tenure, slightly lower satisfaction/involvement measures, and
shorter tenure with their current manager.

These variables are useful candidates for a future employee
attrition-risk model.

------------------------------------------------------------------------

# 11. Highest-Priority Employee Segments

Based on the observed data, the following segments deserve deeper
investigation:

1.  **Overtime employees** --- 30.6% attrition
2.  **18--25 employees** --- 35.8% attrition
3.  **Sales Representatives** --- 39.3% attrition
4.  **Employees earning up to 5k** --- 21.6% attrition
5.  **Sales department** --- 20.7% attrition
6.  **Single employees** --- 25.4% attrition

The strongest retention strategy should focus on the **intersection** of
these characteristics rather than treating each factor independently.

For example:

> Young + overtime + low salary + Sales Representative

could represent a particularly important risk segment if the underlying
employee counts are large enough.

------------------------------------------------------------------------

# 12. Business Recommendations

### Recommendation 1 --- Reduce avoidable overtime

Identify teams and roles with persistent overtime and investigate
workload and staffing.

### Recommendation 2 --- Strengthen early-career retention

Introduce structured mentoring, career paths, training, and progression
opportunities.

### Recommendation 3 --- Review lower salary bands

Evaluate compensation competitiveness and progression opportunities for
lower-paid employees.

### Recommendation 4 --- Target Sales Representative retention

Investigate sales targets, incentives, travel, manager support, and
workload.

### Recommendation 5 --- Use satisfaction and tenure as early-warning signals

Employees with low satisfaction and short tenure should be considered
for proactive engagement, while respecting employee privacy and avoiding
punitive use of risk scores.

------------------------------------------------------------------------

# 13. Limitations

-   The dataset is observational.
-   Attrition relationships are correlations/associations, not causal
    proof.
-   The data does not contain qualitative exit-interview information.
-   Salary is represented by monthly income/salary slabs rather than
    complete compensation packages.
-   The dataset does not directly measure workload intensity beyond
    available variables such as overtime.
-   The source data contains duplicate rows and missing values; cleaning
    was performed as part of the Power BI preparation workflow.
-   Small groups, such as Human Resources, should be interpreted
    cautiously because their sample size is much smaller than R&D or
    Sales.

------------------------------------------------------------------------

# 14. Next-Level Analysis

The next version of this project could include:

-   Attrition prediction using machine learning
-   Employee risk scoring
-   Manager-level attrition
-   Tenure cohorts
-   Promotion-gap analysis
-   Overtime intensity
-   Salary progression
-   Satisfaction trends
-   Interaction analysis between overtime, salary, age, and job role
-   Statistical significance testing
-   Power BI drill-through pages for high-risk segments

------------------------------------------------------------------------

## Final Conclusion

The analysis indicates that employee attrition is not evenly distributed
across the workforce.

The most important observed patterns are concentrated around **overtime,
early-career employees, lower salary levels, Sales Representatives, and
the Sales department**.

The business should therefore move from a broad "reduce attrition"
strategy to a **targeted retention strategy** focused on the employee
segments where attrition is highest.
