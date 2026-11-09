# 📊 Employee Absenteeism Analytics | Mega Supermart

**Turning workforce data into actionable business insights through Python, exploratory data analysis and statistical testing.**

![Python](https://img.shields.io/badge/Python-Analytics-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![SciPy](https://img.shields.io/badge/SciPy-Statistical%20Analysis-8CAAE6)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

---

## 🎯 Executive Summary

Why do some workforce segments experience higher absenteeism than others?

This project analyses the 2025 Mega Supermart HR dataset to identify workforce absence patterns, evaluate differences between employee groups and translate statistical evidence into practical HR recommendations.

**Key discovery:** Part-time employees recorded a higher mean absence rate than full-time employees (3.94% vs. 2.23%), with a statistically significant difference (Welch's t-test, p < 0.001).

The analysis demonstrates how data analytics can support more targeted workforce planning and evidence-based HR decisions.

## 📈 Key Findings at a Glance

| Performance Indicator | Result |
|---|---:|
| Total employees | 1,200 |
| Valid absence-rate records | 1,198 |
| Weighted absence rate | 2.52% |
| Highest departmental absence rate | 3.38% |
| Part-time mean absence rate | 3.94% |
| Full-time mean absence rate | 2.23% |
| Identified high-absence outliers | 63 |
| High-absence cases in three workforce segments | **82.54%** |

## 🔍 Five Insights from the Data

**01 | Departmental Differences**

Customer Service recorded the highest weighted absence rate (3.38%), approximately 2.36 times the Operations rate.

**02 | Employment Type Matters**

Part-time employees had a higher mean absence rate (3.94%) than full-time employees (2.23%). Welch's independent-samples t-test identified a statistically significant difference (p < 0.001).

**03 | Absenteeism Is Concentrated**

Customer Service part-time, Sales part-time and Sales full-time accounted for 82.54% of identified high-absence cases.

**04 | Demographic Relationships Are Weak**

Age and length of service showed statistically significant but very weak negative correlations with absence rates. Statistical significance does not necessarily imply practical importance.

**05 | Data Quality Was Validated**

All 1,198 valid absence-rate records passed the reported validation checks, achieving 100% agreement.

## 🧪 Analytical Approach

The project combines exploratory analysis, statistical testing and business interpretation.

| Analytical Technique | Purpose |
|---|---|
| Data cleaning and validation | Establish data reliability |
| Exploratory Data Analysis | Identify workforce patterns |
| Pearson & Spearman correlation | Examine variable relationships |
| IQR outlier detection | Identify unusually high absence rates |
| Welch's t-test | Compare employment-type groups |
| Chi-square test | Examine categorical associations |
| Cramér's V | Evaluate association strength |
| Data visualisation | Communicate analytical findings |

**Technology Stack**

Python · Pandas · NumPy · Matplotlib · Seaborn · SciPy · Jupyter Notebook

## 💡 Business Recommendations

The findings suggest five practical areas for management attention:

1. **Departmental focus:** Prioritise attendance pattern reviews in Customer Service and Sales.
2. **Workforce planning:** Examine scheduling and working arrangements for part-time employees.
3. **Targeted investigation:** Review high-absence cases individually, considering relevant employee circumstances.
4. **Employee engagement:** Explore opportunities to strengthen early-stage engagement and attendance support.
5. **Data-driven monitoring:** Establish consistent HR reporting and ongoing absenteeism monitoring.

**Business takeaway:** Effective workforce management requires more than identifying absence rates. It requires understanding patterns, evaluating evidence and translating findings into appropriate action.

## 📂 Repository Structure

```text
employee-absenteeism-analysis/
│
├── README.md
├── requirements.txt
├── notebooks/
│   └── employee_absenteeism_eda.ipynb
├── visuals/
│   ├── absenteeism_by_department.png
│   ├── absenteeism_by_employment_type.png
│   └── absenteeism_correlation.png
├── reports/
│   └── EDA_Report.pdf
└── data/
    └── README.md
```

## 🚀 Reproduce the Analysis

**1. Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/employee-absenteeism-analysis.git
cd employee-absenteeism-analysis
```

**2. Install dependencies**

```bash
pip install -r requirements.txt
```

**3. Launch Jupyter Notebook**

```bash
jupyter notebook
```

Open the notebook in the `notebooks/` directory and run the analysis.

See `data/README.md` for dataset access and usage instructions.

## 👩‍💻 Skills Demonstrated

- Python-based data analytics
- Data cleaning and quality validation
- Exploratory data analysis
- Statistical hypothesis testing
- Data visualisation and interpretation
- Business insight development
- Evidence-based decision support

---

*Portfolio project | HR Analytics | Exploratory Data Analysis | Statistical Analysis | Business Intelligence*

*Note: This is an educational portfolio project. Only synthetic, anonymised or authorised data should be published. Statistical outliers are indicators for further investigation, not evidence of employee misconduct. Findings describe associations and group differences, not proven causal relationships.*
