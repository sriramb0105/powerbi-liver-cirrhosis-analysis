**Liver Cirrhosis Clinical Analysis Dashboard**

**Overview**

This project analyzes a 25,000-patient liver cirrhosis dataset from the Mayo Clinic Primary Biliary Cirrhosis (PBC) Trial using Power BI.

The objective is to transform complex clinical trial data into interactive dashboards that help clinicians, researchers, and healthcare administrators identify patterns in disease progression, symptom prevalence, biomarker deterioration, survival outcomes, and treatment effectiveness.

**Problem Statement**

Clinical datasets contain thousands of patient records and multiple biomarkers, making it difficult to identify meaningful patterns without advanced statistical expertise.

This project addresses that challenge by creating interactive Power BI dashboards that enable users to:

Monitor disease progression
Analyze symptom severity
Evaluate survival outcomes
Assess treatment effectiveness
Identify high-risk patient groups

**Dataset Information**
**Source**
Mayo Clinic Primary Biliary Cirrhosis Trial (1974–1984)
Kaggle Dataset
**Dataset Characteristics**
Metric	Value
Patients	25,000
Clinical Variables	19
Disease Stages	3
Study Period	1974–1984
Status Categories	Censored, Deceased, Transplant

**Tools & Technologies**
Power BI Desktop
Power Query
DAX
Data Modeling
Healthcare Analytics
Data Visualization

**Dashboard Pages**

**1. Patient Overview**

Key metrics:

Total Patients: 25,000
Mortality Rate: 37.8%
Average Follow-up Days: 1,887
Female Patients: 88.5%

Insights:

Majority patients are female
Average age: 50.3 years
Nearly equal distribution across disease stages

**2. Symptom Prevalence Analysis**

Symptoms analyzed:

Hepatomegaly
Spider Angiomata
Ascites
Edema

Key Findings:

Hepatomegaly increases from 18.1% to 60.4% across stages
Severe edema associated with 90.8% mortality
Ascites significantly increases in Stage 3

**3. Symptom Impact Analysis**

Key Findings:

Hepatomegaly doubles mortality risk
Mortality with hepatomegaly: 55.2%
Mortality without hepatomegaly: 26.7%
Severe edema patients survive only 716 days on average

**4. Biomarker Analysis**

Biomarkers monitored:

Bilirubin
Albumin
Platelets
Copper

Key Findings:

Bilirubin increases by 79%
Platelets decrease by 21%
Albumin falls below normal levels in Stage 3
Copper exceeds clinical threshold from Stage 2

**5. Severity Score Analysis**

Custom MELD-inspired Severity Score:

Severity Score = Bilirubin + (5 − Albumin) + (Prothrombin − 10)

Key Findings:

Stage	Avg Severity Score
Stage 1	4.45
Stage 2	5.25
Stage 3	7.25

Severity increases by 62.9% from Stage 1 to Stage 3.

**6. Survival Outcome Analysis**

Key Findings:

Stage	Avg Follow-up Days
Stage 1	2,285
Stage 2	1,923
Stage 3	1,455
Mortality rises from 22.6% to 54.7%
Patients aged 65+ show 51.6% mortality
Stage 3 patients lose approximately 830 survival days

**7. Treatment Effectiveness**

Treatment Comparison:

Drug vs Placebo

Key Findings:

Drug provides +377 survival days in Stage 1
Mortality rates are similar overall
Treatment advantage disappears in Stage 3
Early intervention is the critical treatment window

**Power BI Features Implemented**
**Power Query**
Data Cleaning
Data Transformation
Data Type Correction
Value Standardization

**DAX Measures**

Mortality Rate
Average Follow-up Days
Severity Score
Drug Survival Analysis
Biomarker Averages

**Interactive Features**
Slicers
Drill-down Analysis
Dynamic KPIs
Tooltips
Cross-filtering

**Key Business Value**
**Clinical Value**
Identifies high-risk symptoms
Supports patient risk stratification
**Treatment Value**
Helps identify optimal treatment timing
**Research Value**
Reusable severity scoring framework
**Educational Value**
Simplifies clinical trial interpretation through visualization

**Project Screenshots**



Project Files
Liver-Cirrhosis-Analysis
│
├── Dashboard.pbix
├── Dataset.xlsx
├── README.md
├── Presentation.pptx
└── Dashboard Screenshots

**Limitations**
Historical dataset (1974–1984)
Observational study
No Kaplan-Meier survival analysis
No Cox Regression modeling
Correlation does not imply causation

**Author**

**Sriram B**

Data Analyst | Power BI Developer | Data Science Enthusiast

GitHub: (https://github.com/sriramb0105)

LinkedIn: (https://www.linkedin.com/in/sriram-b-129b003ba/)
