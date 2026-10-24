# Telecom Revenue & Profitability Dashboard

## Project Overview
This project presents an interactive Power BI dashboard designed to analyze telecom business performance across revenue, profitability, customer behavior, payment patterns, and customer service.

The dashboard consolidates information from customer, usage, billing, regional, and service-ticket datasets to help identify business trends and areas for further investigation.

## Objectives
- Monitor revenue, profit, profit margin, and Average Revenue Per User (ARPU).
- Compare performance across regions, markets, customer segments, plans, and devices.
- Analyze payment behavior and customer service performance.
- Examine customer satisfaction and ticket resolution.
- Identify customers exhibiting potential churn-risk signals.

## Tools & Technologies
- **Power BI Desktop** — Dashboard development and data modelling
- **Power Query** — Data cleaning and transformation
- **DAX** — Measures, calculated columns, and KPI calculations

## Dataset Overview
The project uses five tables:

- **Telecom_Customers:** Customer attributes and customer-level metrics.
- **Telecom_Usage_Fact:** Telecom usage, billing, revenue, profit, and payment information.
- **Telecom_Tickets:** Customer service tickets, resolution status, and satisfaction scores.
- **RegionalPeople:** Regional information for regional analysis.
- **Calendar:** Date dimension for time-based analysis.

## Data Preparation & Modelling
- Reviewed data types and addressed data-quality issues.
- Examined missing values, including tickets without a recorded closure date.
- Established relationships between customer, usage, ticket, regional, and calendar tables.
- Created a Calendar table to support time-based analysis.
- Developed DAX calculations for business KPIs and customer risk classification.

## Dashboard Features
The dashboard includes:
- Main Business Performance Dashboard
- Market and Regional Analysis
- Collections and Payment Analysis
- Retention and Churn-Risk Analysis
- Discounts and Profit Margins
- Tickets and Customer Satisfaction
- Plans and Device Analysis
- Market, Customer, and Plan Details

Interactive slicers and drill-through pages support more detailed exploration of the data.

## Key Insights
- Overall revenue and profitability can be monitored through consolidated KPIs.
- Discount levels and profit margins vary across plans, highlighting opportunities to review discount strategies.
- Regional ARPU varies, providing opportunities to investigate pricing and plan mix.
- Customer service metrics help identify areas for further investigation.
- The rule-based churn-risk indicator helps flag customers for additional review.

## Limitations
- Churn risk is a rule-based proxy derived from ticket activity, payment behavior, and customer satisfaction; it does not represent confirmed customer churn.
- The findings reflect the available dataset and its quality.
- Observed relationships should not be interpreted as proof of causation.

## Project Deliverables
- Power BI dashboard (`.pbix`)
- Project presentation

## Learning Outcomes
This project provided practical experience in data preparation, relational data modelling, DAX, interactive dashboard development, KPI validation, and translating data into business insights.
