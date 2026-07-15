
# Project Information

**Project Name:** Executive Revenue Intelligence Dashboard

**Category:** Revenue Operations (RevOps)

**Business Function:** Executive Reporting • Revenue Intelligence • Sales Analytics

**Project Type:** AI-Powered Executive Revenue Dashboard & Business Intelligence Automation

**Built With:** Make.com, HubSpot CRM, Supabase, Google Sheets, Gemini AI, Slack, Gmail

**Dashboard Ready For:** Power BI / Looker Studio

**Status:** ✅ Production-Ready Portfolio Project

---

# Executive Revenue Intelligence Dashboard

An AI-powered Revenue Operations (RevOps) automation that consolidates data from Sales, Customer Success, Marketing, and Operations into a centralized executive dashboard, automatically generates business KPIs, identifies revenue risks, and delivers AI-generated executive summaries to leadership.

---

# 💡 Architect's Note

While building my previous RevOps automations, I realized something important.

Each workflow solved a specific operational problem:

* Lead Qualification improved lead quality.
* Revenue Leakage Detector protected pipeline value.
* Pipeline Forecasting predicted future revenue.
* Customer Health Score Engine identified churn risks.

But executives don't make decisions by opening four different systems.

They need a single source of truth.

The Executive Revenue Intelligence Dashboard was built to solve exactly that challenge.

Instead of manually collecting reports from HubSpot, Customer Success platforms, spreadsheets, finance tools, and product databases, this automation continuously gathers data, calculates key revenue metrics, generates executive insights using AI, and updates a centralized dashboard.

The objective isn't simply to build another dashboard—it's to create an automated Revenue Intelligence layer that enables leadership to make faster, data-driven decisions with complete visibility across the revenue organization.

This project represents another step in my transition from Enterprise Sales into Revenue Operations, where technology, data, and automation work together to improve business performance.

---

# Primary Objective

Build an AI-powered Executive Revenue Intelligence system that automatically combines sales, customer success, marketing, and operational data into a centralized dashboard, providing leadership with real-time business visibility, predictive insights, and actionable recommendations.

---

# Overview

Modern B2B companies generate massive amounts of revenue data every day.

Sales teams manage pipelines inside HubSpot.

Customer Success tracks health scores.

Marketing measures lead generation.

Finance monitors recurring revenue.

Support teams handle customer issues.

Executives often spend hours gathering information from multiple systems before weekly meetings.

By the time reports are completed, the data is already outdated.

This automation eliminates manual reporting by continuously collecting business metrics from multiple sources, calculating executive KPIs, generating AI-powered business summaries, updating a centralized dashboard, and notifying leadership automatically.

Instead of spending time preparing reports, executives spend time making decisions.

---

# Business Problem

Revenue leaders often struggle with fragmented business data spread across multiple platforms.

Common challenges include:

* Sales pipeline data stored in CRM
* Customer health information stored separately
* Revenue leakage tracked in spreadsheets
* Marketing performance reported independently
* Finance metrics managed in another system
* Executives spending hours creating weekly reports
* No single source of truth for revenue performance
* Delayed visibility into business risks
* Reactive instead of proactive decision-making

Without centralized reporting, organizations struggle to identify revenue risks early and align cross-functional teams around shared business goals.

---

# Solution

The Executive Revenue Intelligence Dashboard acts as the central reporting layer across the entire Revenue Operations ecosystem.

Every scheduled execution automatically:

✔ Retrieves pipeline data from HubSpot CRM

✔ Collects Customer Health Scores from Supabase

✔ Retrieves Revenue Leakage reports from Google Sheets

✔ Combines operational data into a unified dataset

✔ Calculates executive KPIs

✔ Generates AI-powered business insights using Gemini AI

✔ Updates executive dashboard metrics

✔ Sends Slack notifications to leadership

✔ Delivers executive reports via email

The result is a continuously updated Executive Revenue Intelligence System that enables leadership teams to monitor business performance without manual reporting.

---

# Workflow Architecture

```text
Scheduler
      │
      ▼
HubSpot CRM
(Pipeline & Deals)
      │
      ▼
Supabase
(Customer Health Data)
      │
      ▼
Google Sheets
(Revenue Leakage Reports)
      │
      ▼
Combine Business Data
      │
      ▼
Calculate KPIs
      │
      ▼
Gemini AI
(Executive Analysis)
      │
      ▼
Update Dashboard
      │
 ┌───────────────┬───────────────┐
 ▼               ▼               ▼
Google Sheets   Slack        Gmail
Dashboard       Alert        Executive Report
```

---

# Workflow Screenshot

**Executive Revenue Intelligence Dashboard**

<img width="1861" height="858" alt="Executive-Revenue-Intelligence-Dashboard-Make" src="https://github.com/user-attachments/assets/09fe1172-19e0-40df-b5f6-16442c63db3a" />
<img width="1830" height="861" alt="Executive-Revenue-Intelligence-Dashboard-Make-07-15-2026_03_39_PM" src="https://github.com/user-attachments/assets/aa31b3be-cf58-4cc3-8772-1dea28ee8701" />
<img width="1878" height="862" alt="Executive-Revenue-Intelligence-Dashboard-Make-07-15-2026_03_38_PM" src="https://github.com/user-attachments/assets/c3463b93-414a-4cc9-ab2e-28ac1b976fa8" />


---

# Business Systems Connected

This automation combines data from multiple business functions into one Executive Intelligence layer.

| Business Function   | Data Source   | Example Metrics                    |
| ------------------- | ------------- | ---------------------------------- |
| Sales               | HubSpot CRM   | Pipeline, Deals, Revenue, Win Rate |
| Customer Success    | Supabase      | Health Score, Churn Risk, Renewals |
| Revenue Operations  | Google Sheets | Revenue Leakage, Pipeline Risks    |
| Marketing           | CRM / Sheets  | Leads, MQL, SQL, Conversion        |
| Executive Reporting | Gemini AI     | AI Summary & Strategic Insights    |

---

# Core Business Value

Instead of asking:

* "How is Sales performing?"
* "How many customers may churn?"
* "Where is revenue leaking?"
* "Are we on track this quarter?"

Executives receive one centralized dashboard that answers all of these questions automatically using live business data.

---

# Executive Dashboard Sections

The Executive Revenue Intelligence Dashboard provides leadership with a centralized, real-time view of the entire revenue organization by consolidating data from Sales, Customer Success, Marketing, and Revenue Operations.

---

# Dashboard Modules

## 1. Revenue Overview

Provides a high-level summary of overall business performance.

### Displays

* Total Pipeline Value
* Closed Won Revenue
* Closed Lost Revenue
* Forecast Revenue
* Revenue Growth %
* Monthly Revenue Trend
* Quarterly Revenue Progress

**Business Question Answered**

> "Are we on track to achieve our revenue target?"

---

## 2. Pipeline Health

Measures the health and efficiency of the sales pipeline.

### Displays

* Total Active Deals
* Pipeline Coverage
* Pipeline Velocity
* Stuck Opportunities
* Revenue Leakage Count
* Average Sales Cycle
* Stage-wise Deal Distribution

**Business Question Answered**

> "Is our sales pipeline healthy?"

---

## 3. Revenue Forecast

Provides predictive visibility into expected revenue.

### Displays

* Forecast This Month
* Forecast Next Quarter
* Weighted Pipeline
* Forecast Accuracy
* Expected Monthly Revenue
* Revenue Gap to Target

**Business Question Answered**

> "How much revenue can we realistically expect?"

---

## 4. Customer Health

Monitors customer retention and expansion opportunities.

### Displays

* Healthy Customers
* Moderate Risk Customers
* High Churn Risk Accounts
* Expansion Opportunities
* Average Customer Health Score
* Renewal Status

**Business Question Answered**

> "Which customers require immediate attention?"

---

## 5. Sales Performance

Measures individual and team sales performance.

### Displays

* Revenue Per Sales Representative
* Win Rate
* Close Rate
* Quota Attainment
* Average Deal Size
* Sales Activities
* Meetings Completed

**Business Question Answered**

> "Which sales reps are performing well and who needs support?"

---

## 6. Marketing Performance

Tracks the contribution of marketing towards revenue generation.

### Displays

* Total Leads
* Marketing Qualified Leads (MQL)
* Sales Qualified Leads (SQL)
* Opportunities Created
* Conversion Rate
* Customer Acquisition Cost (CAC)

**Business Question Answered**

> "Is marketing generating quality pipeline?"

---

## 7. Revenue Leakage

Imports data directly from the Revenue Leakage Detector automation.

### Displays

* Stuck Deals
* Inactive Opportunities
* Missing Follow-ups
* Revenue at Risk
* Pipeline Leakage Trend

**Business Question Answered**

> "Where are we losing revenue?"

---

## 8. AI Executive Insights

Gemini AI automatically analyzes all business metrics and produces a concise executive report.

### Example

> Revenue performance remains healthy with strong pipeline coverage. However, Enterprise pipeline has declined by 15%, six strategic customers are showing high churn probability, and revenue leakage increased this week due to inactive opportunities. Leadership should prioritize enterprise renewals, accelerate stalled opportunities, and increase Customer Success engagement.

**Business Question Answered**

> "What should leadership focus on this week?"

---

# Complete Workflow

```text
Scheduler
      │
      ▼
Retrieve Sales Data
(HubSpot CRM)
      │
      ▼
Retrieve Customer Health
(Supabase)
      │
      ▼
Retrieve Revenue Leakage
(Google Sheets)
      │
      ▼
Merge Business Data
      │
      ▼
Calculate Business KPIs
      │
      ▼
Generate Executive Summary
(Gemini AI)
      │
      ▼
Update Dashboard
      │
 ┌──────────────┬──────────────┐
 ▼              ▼              ▼
Google Sheets  Slack       Gmail
Dashboard      Alert       Executive Report
```

---

# Automation Workflow

## Step 1 — Scheduler

The automation runs automatically at a predefined schedule (every morning, every 15 minutes, or daily depending on business requirements).

**Purpose**

* Keep dashboard data current
* Eliminate manual reporting
* Ensure executives always view the latest metrics

---

## Step 2 — HubSpot CRM

Fetches sales pipeline data.

### Retrieves

* Active Deals
* Closed Won Deals
* Closed Lost Deals
* Deal Value
* Deal Stage
* Close Date
* Deal Owner
* Pipeline Status

This data becomes the foundation for revenue analytics.

---

## Step 3 — Supabase

Retrieves customer success data generated by the Customer Health Score Engine.

### Retrieves

* Customer Health Score
* Churn Probability
* Product Usage
* Expansion Opportunities
* Renewal Status

This provides visibility into post-sales customer performance.

---

## Step 4 — Google Sheets

Retrieves operational reports from previous RevOps automations.

Examples include:

* Revenue Leakage Report
* Pipeline Risk Report
* Follow-up Monitoring
* CRM Hygiene Reports

This adds operational intelligence to executive reporting.

---

## Step 5 — Aggregate Business Data

Data from all systems is merged into one centralized dataset.

The workflow aligns customer records, deal information, operational metrics, and customer success indicators into a single executive reporting model.

---

## Step 6 — Calculate Executive KPIs

Business metrics are automatically calculated.

Examples include:

* Pipeline Coverage
* Forecast Revenue
* Win Rate
* Revenue Growth
* Average Deal Size
* Churn Rate
* Pipeline Velocity
* Expansion Revenue
* Revenue Leakage Percentage

These KPIs become the core metrics displayed on the dashboard.

---

## Step 7 — Generate AI Executive Summary

Gemini AI receives all calculated business metrics and produces a concise executive report.

The summary includes:

* Executive Snapshot
* Revenue Risks
* Customer Risks
* Sales Performance
* Strategic Recommendations
* Weekly Priorities

This transforms raw numbers into actionable business insights.

---

## Step 8 — Update Dashboard

The latest KPIs are written to the reporting layer.

Supported dashboards include:

* Google Sheets
* Power BI
* Looker Studio

Executives can monitor business performance in real time.

---

## Step 9 — Notify Leadership

The completed dashboard and AI-generated summary are automatically distributed.

### Slack

* Executive alert
* Weekly summary
* Revenue warning notifications

### Gmail

* Executive report
* Weekly PDF dashboard
* Leadership performance summary

---

# End-to-End Business Flow

```text
Collect Business Data
        │
        ▼
Clean & Merge Data
        │
        ▼
Calculate Revenue KPIs
        │
        ▼
Generate AI Insights
        │
        ▼
Update Executive Dashboard
        │
        ▼
Notify Leadership
        │
        ▼
Support Faster Executive Decisions
```

---
# KPI Calculation Engine

One of the most valuable components of this automation is the KPI Calculation Engine.

Instead of simply displaying CRM data, the workflow transforms raw operational data into executive-level business metrics that leadership can use for strategic decision-making.

The KPI engine continuously calculates revenue, sales, customer success, and operational performance indicators before updating the Executive Dashboard.

---

# Revenue KPIs

These metrics provide an overall picture of business performance.

| KPI                 | Description                                      |
| ------------------- | ------------------------------------------------ |
| Total Pipeline      | Total value of all active opportunities          |
| Closed Won Revenue  | Revenue generated from successfully closed deals |
| Closed Lost Revenue | Total value of lost opportunities                |
| Forecast Revenue    | Expected revenue based on weighted pipeline      |
| Revenue Growth %    | Month-over-month revenue growth                  |
| Average Deal Size   | Average revenue generated per closed deal        |

---

# Sales KPIs

Measures the efficiency and effectiveness of the sales team.

| KPI                  | Description                                      |
| -------------------- | ------------------------------------------------ |
| Win Rate             | Percentage of deals successfully won             |
| Close Rate           | Opportunities converted into customers           |
| Pipeline Coverage    | Pipeline value compared with revenue target      |
| Pipeline Velocity    | Speed at which deals move through the pipeline   |
| Average Sales Cycle  | Average number of days required to close a deal  |
| Sales Activity Count | Calls, meetings, emails and follow-ups completed |

---

# Customer Success KPIs

Measures customer retention and long-term revenue health.

| KPI                     | Description                                |
| ----------------------- | ------------------------------------------ |
| Average Health Score    | Overall customer health                    |
| Healthy Customers       | Customers with Health Score above 80       |
| Moderate Risk Customers | Health Score between 50–79                 |
| High Risk Customers     | Health Score below 50                      |
| Churn Rate              | Percentage of customers predicted to churn |
| Expansion Opportunities | Accounts ready for upsell or cross-sell    |

---

# Marketing KPIs

Tracks marketing contribution to revenue generation.

| KPI                       | Description                                      |
| ------------------------- | ------------------------------------------------ |
| Leads Generated           | Total incoming leads                             |
| MQL                       | Marketing Qualified Leads                        |
| SQL                       | Sales Qualified Leads                            |
| Opportunities Created     | Leads converted into pipeline                    |
| Lead Conversion Rate      | Percentage of leads converted into opportunities |
| Customer Acquisition Cost | Cost required to acquire one customer            |

---

# Revenue Operations KPIs

These KPIs measure operational efficiency.

| KPI                   | Description                             |
| --------------------- | --------------------------------------- |
| Revenue Leakage Count | Number of identified revenue risks      |
| Stuck Deals           | Opportunities inactive beyond threshold |
| Missing Follow-ups    | Deals requiring sales engagement        |
| CRM Hygiene Score     | Data quality across CRM                 |
| Duplicate Records     | Duplicate customer or company records   |
| Missing Information   | Incomplete CRM records                  |

---

# Example KPI Calculations

## Pipeline Coverage

Measures whether the existing pipeline is sufficient to achieve the sales target.

```text
Pipeline Coverage =
Total Pipeline Value
÷
Revenue Target
```

Example

```text
Pipeline = $2,500,000

Quota = $1,000,000

Coverage = 2.5x
```

---

## Win Rate

```text
Win Rate =
Won Deals
÷
Total Closed Deals
```

Example

```text
Won Deals = 48

Closed Deals = 80

Win Rate = 60%
```

---

## Forecast Revenue

Weighted pipeline based on deal probability.

```text
Forecast Revenue =
Deal Amount × Probability
```

Example

```text
$100,000 × 70%

Forecast = $70,000
```

---

## Revenue Growth

```text
(Current Revenue − Previous Revenue)

÷

Previous Revenue
```

Example

```text
Previous Month

$800,000

Current Month

$920,000

Growth

15%
```

---

## Churn Rate

Uses Customer Health Score Engine output.

```text
High Risk Customers

÷

Total Customers
```

Example

```text
15

÷

300

=

5%
```

---

## Expansion Opportunity %

```text
Expansion Ready Customers

÷

Total Customers
```

---

# AI Executive Summary

One of the most valuable parts of this project is the AI-generated Executive Summary.

Rather than asking leadership to interpret dozens of KPIs manually, Gemini AI transforms operational metrics into clear business recommendations.

---

## AI Input

The workflow automatically sends calculated KPIs to Gemini AI.

Example input:

```text
Revenue Pipeline:
{{Pipeline Coverage}}

Win Rate:
{{Win Rate}}

Revenue Growth:
{{Revenue Growth}}

Customer Health:
{{Average Health Score}}

Churn Risk:
{{Churn Rate}}

Revenue Leakage:
{{Leakage Count}}
```

---

## System Prompt

```text
You are an expert Chief Revenue Officer (CRO).

Analyze the business performance using the supplied metrics.

Provide:

• Executive Snapshot
• Top Revenue Risks
• Customer Health Analysis
• Sales Performance Summary
• Strategic Recommendations

Keep the report concise, executive-friendly and data-driven.
```

---

## Example AI Output

> Revenue performance remains healthy with pipeline coverage above target. However, enterprise deal velocity has slowed by 14%, customer churn risk has increased among strategic accounts, and revenue leakage has risen due to inactive follow-ups. Leadership should prioritize high-value renewals, accelerate stalled enterprise opportunities, and improve Customer Success engagement over the next seven days.

---

# Technology Stack

## Automation Platform

* Make.com

---

## CRM

* HubSpot CRM

---

## Database

* Supabase

---

## Reporting

* Google Sheets
* Power BI *(Recommended)*
* Looker Studio *(Recommended)*

---

## Artificial Intelligence

* Google Gemini AI

---

## Communication

* Slack
* Gmail

---

## Future Integrations

* Stripe
* Xero
* Salesforce
* Snowflake
* BigQuery
* PostgreSQL

---

# System Architecture

```text
HubSpot CRM
        │
        ▼
Supabase Database
        │
        ▼
Google Sheets Reports
        │
        ▼
KPI Calculation Engine
        │
        ▼
Gemini AI
        │
        ▼
Executive Dashboard
        │
 ┌─────────────┬─────────────┐
 ▼             ▼             ▼
Power BI   Looker Studio   Google Sheets
        │
        ▼
Slack + Gmail
```

---

# Skills Demonstrated

Through this project, the following Revenue Operations capabilities are demonstrated:

### Revenue Operations

* Executive Revenue Reporting
* Revenue Intelligence
* Business KPI Design
* Cross-functional Reporting
* Revenue Analytics

### Automation

* Multi-source Data Integration
* Scheduled Automation
* Data Aggregation
* Business Logic
* AI Workflow Automation

### Analytics

* Executive Dashboard Design
* Sales Analytics
* Customer Analytics
* Revenue Forecasting
* Operational Reporting

### AI

* Executive Business Analysis
* AI-generated Strategic Insights
* Automated Decision Support
* Prompt Engineering for Business Reporting

---

# Business Rules

The dashboard continuously calculates executive-level KPIs by combining data from multiple Revenue Operations systems.

### Revenue Health

```
Pipeline Coverage = Total Pipeline / Revenue Target
```

---

### Forecast Health

```
Weighted Forecast =
Σ (Deal Value × Stage Probability)
```

---

### Customer Health

```
Health Score < 50
↓

High Churn Risk
↓

Notify Customer Success Team
```

---

### Revenue Leakage

```
Inactive Deal > Defined Threshold
↓

Revenue Leakage

↓

Include in Executive Dashboard
```

---

### Sales Performance

```
Win Rate =
Closed Won /
(Closed Won + Closed Lost)
```

---

### Customer Expansion

```
Health Score > 80

AND

Expansion Opportunity = TRUE

↓

Recommend Upsell
```

---

### Executive Summary

Gemini AI reviews all dashboard KPIs and generates:

* Executive Snapshot
* Revenue Risks
* Growth Opportunities
* Recommended Weekly Priorities

---

# Dashboard Metrics

## Revenue

* Total Revenue
* Forecast Revenue
* Pipeline Coverage
* Revenue Growth %
* ARR
* MRR

---

## Sales

* Total Pipeline
* Total Deals
* Win Rate
* Average Deal Size
* Sales Cycle
* Forecast Accuracy

---

## Customer Success

* Customer Health Score
* Churn Risk
* Healthy Accounts
* Expansion Opportunities
* Renewals
* NPS

---

## Revenue Operations

* Revenue Leakage
* Pipeline Health
* CRM Hygiene
* Duplicate Records
* Missing Data
* Pipeline Velocity

---

## Marketing

* Leads
* MQL
* SQL
* Opportunity Conversion
* CAC
* Conversion Rate

---

# Workflow Screenshot

**Executive Revenue Intelligence Dashboard**

> *(Insert your Make.com workflow screenshot here)*

```md
<img width="1500" alt="Executive Revenue Intelligence Dashboard" src="YOUR_IMAGE_LINK_HERE">
```

---

# Dashboard Screenshot

> *(Insert your Power BI / Looker Studio dashboard here once completed.)*

---

# Challenges Solved

## Challenge 1

Executive data scattered across multiple systems.

### Solution

Unified Revenue Intelligence Dashboard.

---

## Challenge 2

Manual KPI reporting every week.

### Solution

Fully automated KPI aggregation.

---

## Challenge 3

Leadership lacked real-time business visibility.

### Solution

Live Executive Dashboard with AI insights.

---

## Challenge 4

Revenue risks discovered too late.

### Solution

Continuous monitoring and proactive reporting.

---

## Challenge 5

Disconnected Sales, Customer Success, and Marketing metrics.

### Solution

Cross-functional Revenue Operations reporting.

---

# Business Impact

Estimated Benefits

✔ Single source of truth for executive reporting

✔ Real-time revenue visibility

✔ Improved forecasting accuracy

✔ Earlier detection of churn risks

✔ Faster executive decision-making

✔ Better sales and customer success alignment

✔ Reduced manual reporting effort

✔ Increased operational efficiency

✔ Improved revenue predictability

✔ AI-generated strategic recommendations

---

# RevOps Components Demonstrated

This project showcases expertise across multiple Revenue Operations domains:

### Revenue Operations

* Executive Revenue Intelligence
* KPI Automation
* Cross-functional Reporting
* Revenue Forecasting
* Revenue Governance

---

### Sales Operations

* Pipeline Analytics
* Sales Performance Reporting
* Forecast Accuracy
* Pipeline Health

---

### Customer Success

* Customer Health Monitoring
* Churn Prediction
* Expansion Opportunity Detection

---

### Business Intelligence

* Executive Dashboards
* Data Aggregation
* KPI Engineering
* Operational Reporting

---

### AI Automation

* Executive Summaries
* Strategic Recommendations
* Revenue Risk Analysis

---

# Business Value

This dashboard enables executives to answer questions such as:

* Are we on track to hit revenue targets?
* Which deals require immediate attention?
* Which customers are likely to churn?
* Where are revenue leaks occurring?
* Which teams are performing best?
* What should leadership prioritize this week?

Instead of reviewing multiple systems separately, leadership receives one centralized, AI-powered view of the entire revenue organization.

---

# Future Improvements (Version 2)

* Power BI Interactive Dashboard
* Looker Studio Dashboard
* Predictive Revenue Forecasting
* AI Trend Analysis
* Territory Performance Analytics
* Executive Mobile Dashboard
* Benchmark Reporting
* Department-Level Drilldowns
* Natural Language Dashboard Queries
* Historical Trend Comparisons

---

# Learning Outcomes

Through this project I learned:

* Executive KPI design
* Revenue Operations reporting
* Cross-system data aggregation
* Business metric calculation
* AI-powered executive reporting
* Dashboard architecture
* Revenue forecasting concepts
* Customer Success analytics
* Business Intelligence fundamentals
* Leadership-focused automation design

---

# Project Portfolio Position

This project serves as the executive reporting layer of my Revenue Operations portfolio.

It consolidates insights generated from previously built automation systems, including:

* Lead Qualification Engine
* Revenue Leakage Detector
* Pipeline Forecasting Engine
* Customer Health Score Engine (Churn Prevention)

By bringing these systems together into a unified executive dashboard, it demonstrates the ability to transform operational data into strategic business intelligence for leadership teams.

---
