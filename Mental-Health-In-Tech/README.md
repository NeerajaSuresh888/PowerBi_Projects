# Mental Health in Tech — Power BI Dashboard

## Project Overview
Analyzed 1,467 real survey responses from tech workers across 40+ countries 
to uncover mental health trends, treatment patterns, and workplace stigma 
in the technology industry.

## Dataset
- **Source:** OSMI Mental Health in Tech Survey 2016
- **Link:** https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey
- **Rows:** 1,467 respondents
- **Columns:** 63 original → cleaned to 55

## Tools Used
- Microsoft Power BI Desktop
- Power Query (M Code)
- DAX (Data Analysis Expressions)
- Power BI Service

## Technical Work Done
- Cleaned raw messy CSV in Power Query — renamed 55 columns, 
  collapsed 40+ freetext gender values into 3 categories using M code
- Filtered invalid age entries, corrected data types
- Created dedicated Measures table with 5 custom DAX measures
- Built unique Stigma Score (0–2 scale) measuring workplace psychological safety
- Applied cross-filter interaction controls on KPI cards
- Built 4-page interactive dashboard published to Power BI Service

## Dashboard Pages
| Page | Title | Business Question |
|------|-------|-------------------|
| 1 | Executive Overview | What is the overall situation? |
| 2 | Burnout & Treatment | Who is seeking treatment and who isn't? |
| 3 | Company Culture & Stigma | How safe is the workplace? |
| 4 | Geography Deep Dive | Where is support strongest? |

## Key Insights
- 57% of tech workers have sought mental health treatment
- Females in mid-size companies seek treatment at significantly higher rates
- 38% report work is often affected when mental health goes untreated
- Anxiety and Mood Disorders are the most commonly diagnosed conditions
- 70% of respondents are male — highlighting a gender gap in tech

## Dashboard Preview
### Executive Overview
![Executive Overview](overview.png)
### Burnout & Treatment
![Burnout](burnout.png)
### Workplace Support
![Workplace](workplace.png)
### Personal & Risk Factors
![Risk](risk.png)
### Stigma & Disclosure
![Stigma](stigma.png)

## Live Dashboard
[Link to be added after publishing to Power BI Service]

## Files in This Repository
- `Mental_Health_PowerBI_Dashboard.pbix` — Power BI dashboard file
- `Mental_Health_PowerBI_Presentation.pptx` — Project presentation
- `OSMI_Mental_Health_in_Tech_Survey_2016.csv` — Raw dataset
- `README.md` — Project documentation
