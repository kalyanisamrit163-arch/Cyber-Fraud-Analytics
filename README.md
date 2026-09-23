# Cyber Fraud Analytics Dashboard

## Project Overview

Cyber fraud has become an important challenge with the increasing use of digital payments. This project analyzes cyber fraud data to identify fraud trends, financial losses, and differences across States/UTs.

The project was developed as part of the BharatCares Internship Final Project.

## Problem Statement

The objective of this project is to analyze cyber fraud data and convert raw data into useful insights that can support fraud monitoring, prevention, financial recovery, and awareness activities.

## Objectives

* Analyze year-wise cyber fraud cases.
* Analyze the amount involved in cyber fraud.
* Compare cyber fraud incidents across States/UTs.
* Analyze lien and refunded amounts.
* Calculate lien and refunded percentages.
* Identify important trends and high-risk areas.
* Present insights through a Power BI dashboard.

## Dataset

The project uses two datasets:

1. Year-wise digital payment fraud data for 2020-21 to 2024-25.
2. State/UT-wise cyber fraud data reported through the National Cybercrime Reporting Portal (NCRP).

### Data Source

Ministry of Home Affairs, Government of India — Rajya Sabha Unstarred Question No. 1517, answered on 12 March 2025.

The state-wise data is from the Annexure titled:

"State-wise statistics on NCRP related to cyber fraud cases since inception to 28.02.2025."

## Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* SQL / MySQL
* Power BI
* Jupyter Notebook

## Project Workflow

Raw Data → Data Cleaning → Data Analysis → Visualization → Insights → Business Recommendations

## Analysis Performed

### Year-wise Analysis

* Total fraud cases
* Total amount involved
* Average fraud cases per year
* Average amount involved per year
* Highest fraud case year
* Highest amount involved year
* Year-over-year percentage change

### State-wise Analysis

* Total incidents
* Amount reported
* Lien amount
* Refunded amount
* Lien percentage
* Refunded percentage
* Top States/UTs by incidents
* Top States/UTs by amount reported
* Top States/UTs by lien percentage
* Top States/UTs by refunded percentage

## Key Insights

* The highest number of fraud cases in the year-wise dataset was recorded in 2023-24.
* The highest amount involved in the year-wise dataset was also recorded in 2023-24.
* Uttar Pradesh recorded the highest number of incidents among the States/UTs analyzed.
* Maharashtra recorded the highest amount reported among the States/UTs analyzed.
* Maharashtra also recorded the highest lien amount.
* Gujarat recorded the highest refunded percentage among the listed States/UTs.
* Fraud cases decreased by 53.98% in 2024-25 compared with 2023-24.

## Business Recommendations

* Focus fraud-prevention efforts on regions with high incident volumes.
* Prioritize monitoring of areas reporting high financial losses.
* Strengthen early detection and lien mechanisms.
* Improve coordination between banks, law-enforcement agencies, and cyber-fraud reporting systems.
* Increase public awareness about digital payment fraud and safe online practices.
* Use data-driven monitoring to identify changing fraud trends and emerging risk areas.

## Dashboard

The Power BI dashboard provides an interactive view of:

* Total Incidents
* Amount Reported
* Lien Amount
* Refunded Amount
* State/UT-wise incident comparison
* State/UT-wise amount comparison
* Lien percentage
* Refunded percentage
* State/UT filter

## Project Files

```text
Cyber_Fraud_Analytics/
│
├── Cyber_Fraud_Analytics.ipynb
├── requirements.txt
├── README.md
└── Project_Report.pdf
```

## How to Run the Project

### 1. Install Python

Install Python 3.x on your system.

### 2. Install Required Libraries

Open Command Prompt or Terminal in the project folder and run:

```bash
pip install -r requirements.txt
```

### 3. Open the Notebook

Open:

```text
Cyber_Fraud_Analytics.ipynb
```

using Jupyter Notebook or JupyterLab.

### 4. Run the Notebook

Run the cells in sequence to perform data preparation, analysis, calculations, and visualizations.

## Output

The project produces:

* Year-wise fraud trend analysis
* Year-wise financial loss analysis
* State-wise incident analysis
* State-wise amount analysis
* Top 5 State/UT comparisons
* Key insights
* Business recommendations
* Power BI interactive dashboard

## Conclusion

The project demonstrates how Python, SQL, and Power BI can be used together to transform cyber fraud data into meaningful analytical insights. The analysis helps identify important fraud trends, financial exposure, and differences across States/UTs, supporting data-driven monitoring and prevention strategies.

## Author

Kalyani 

BCA Graduate | Data Analytics Enthusiast
