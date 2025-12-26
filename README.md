# Panic Attack Analysis – Power BI Dashboard

A professional Power BI dashboard built on a Snowflake cloud data warehouse to analyze panic attack patterns across symptoms, lifestyle factors, triggers, medical history, and demographics.

# Project Objective

The objective of this project is to:


* Analyze panic attack trends using structured mental health data.

* Identify relationships between sleep, triggers, lifestyle habits, and panic severity

* Demonstrate an end-to-end BI workflow using Snowflake + Power BI

* Build an interactive dashboard for data-driven mental health insights
---

 ## Data Source

### Platform: Snowflake Cloud Data Warehouse

### Integration: Power BI (Import / DirectQuery)

### Data Type: Structured mental health & behavioral data

### Snowflake ensures:

Scalable cloud storage

Fast analytical queries

Secure and centralized data access

 Dashboard Screenshots

## Screenshots are stored in folder

 * No of symptums by patience

* Panic attack symptoms 

Dizziness, trembling, chest pain, sweating, and shortness of breath

* Lifestyle & Behavioral Insights

Sleep hours vs number of patients

Panic attack duration (minutes)

Alcohol consumption per week

### Age Group & Trigger-Based Analysis: 

* Adolescent vs Adult comparison

### Triggers: Caffeine, Phobia, PTSD, Social Anxiety, Stress, Unknown

### Metrics: Average sleep hours, panic scores, panic frequency

### Screenshots help users quickly understand dashboard design and insights without opening Power BI.

#### Dashboard Features
#### Symptoms Analysis

Analyzes patient counts for key panic attack symptoms:

Dizziness

Trembling

Chest Pain

Sweating

Shortness of Breath

Visualized using comparative bar charts (True vs False).

##  Lifestyle & Behavioral Insights

* Sleep Duration vs Patient Count

* Panic Attack Duration (Minutes)

* Alcohol Consumption (Drinks per Week)

* Helps understand how daily habits influence panic attack patterns.

### Interactive Filters

#### * Dynamic slicers allow filtering by:

*Panic Score Level (High / Medium / Low)*

*Gender (Male / Female / Non-binary)*

*Triggers (Caffeine, Phobia, PTSD)*

*Medical History (Anxiety, Depression, None)*

 *Age Group & Trigger-Based Analysis*

 *Compares Adolescents vs Adults across:*

*Caffeine*

*Phobia*

*PTSD*

*Social Anxiety*

*Stress*

**Metrics:**

**Average Sleep Hours**

**Average Panic Scores**

**Average Panic Attack Frequency**

### **Power BI – Snowflake Connection Steps**

Follow these steps to connect Power BI Desktop with Snowflake:

1️. Open Power BI Desktop

2. Click Get Data

3. Select Snowflake from data sources

4. Enter Snowflake Details

Provide:

Server: <account_identifier>.snowflakecomputing.com

Warehouse: <warehouse_name>

Database: <database_name>

Schema: <schema_name>

Choose:

Import (recommended for performance)
OR

DirectQuery (for real-time data)

3️. Authenticate

Select authentication method:

Username & Password

OR OAuth / Key Pair (enterprise setup)

4️. Load Data

Select required tables or views

Load data into Power BI

Perform transformations (if needed) in Power Query

5️. Build Model & Visuals

Create relationships

Write DAX measures

Design interactive dashboard

 Key Insights

Lower sleep duration often correlates with higher panic scores

PTSD, caffeine, and social anxiety show higher panic frequency

Panic behavior varies across age groups

Lifestyle habits such as alcohol intake may influence panic severity

### **Tech Stack**

*Power BI Desktop*

**Snowflake Cloud Data Warehouse**

*DAX (Measures & Calculations)*

*Data Modeling & Visualization*

Project Structure
Panic-Attack-PowerBI-Analysis/
│
├── Panic_Attack_Analysis.pbix
├── README.md
├── dashboard_overview.png
├── symptoms_analysis.png
├── lifestyle_insights.png
└── age_trigger_analysis.png

# Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMjhiZTBkMTUtNDc3NC00MGU2LWI4MmYtMjIzYTUyNjcxYjExIiwidCI6ImYwYzJhZDgxLTcxNTUtNGMzYy04OTAyLTNiNDZhYmVlNzIyZSIsImMiOjZ9
## How to Use

**Clone this repository**

**Open Panic_Attack_Analysis.pbix in Power BI Desktop**

**Configure Snowflake credentials**

Refresh data

Explore the dashboard using slicers

## **Use Cases**

**Mental health analytics & awareness**

**Academic and internship projects**

**BI portfolio demonstration**

**Cloud analytics using Snowflake**

**Healthcare data storytelling**

## Conclusion

This project demonstrates how Snowflake + Power BI can transform mental health data into interactive, actionable insights, supporting informed analysis and decision-making.

 *Connect*

If you found this project useful:

*Star the repository*

## Fork it for learning

**Feedback and improvements are welcome**
