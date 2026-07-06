# Startup Valuation & Growth Analysis

A Power BI data analytics project that evaluates startup growth and valuation potential using funding history, investor participation, and operational activity.

## Project Overview

Traditional valuation methods often fail for early-stage startups due to limited financial data. This project uses funding behavior and business activity to classify startups into different growth tiers.

The analysis is built using Power BI and a historical Crunchbase dataset.

---

## Business Problem

Investors need better ways to evaluate startups when financial statements are unavailable.

This project analyzes:

- Funding history
- Funding stage progression
- Investor participation
- Milestone activity

to identify startups with strong long-term growth potential.

---

## Dataset

**Source**

Crunchbase Historical Dataset (Snapshot up to December 2013)

Tables Used

- Companies
- Funding Rounds
- Investments

---

## Data Preparation

- Removed duplicated funding calculations
- Used Funding_Rounds as the source of truth
- Cleaned missing funding values
- Standardized date fields
- Built a star schema model

---

## KPIs

- Total Funding Raised
- Funding Rounds
- Funding Stage
- Funding Frequency
- Investor Participation
- Milestones
- Growth Classification

---

## Dashboard Features

- Funding Trend Analysis
- Investor Activity
- Startup Comparison
- Growth Tier Classification
- Interactive Filters
- KPI Cards

---

## Key Insights

### High Growth

- Glam Media
- RockYou
- Prosper

Characteristics

- Funding above $100M
- Strong investor participation
- Continuous funding rounds

---

### Mid Growth

- OpenX
- Justin.tv

Characteristics

- Efficient fundraising
- Strong stage progression
- Healthy milestone activity

---

### Low Growth

- Yapta
- Wetpaint

Characteristics

- Limited funding momentum
- Longer funding gaps
- Lower growth potential

---

## Tools Used

- Power BI
- Power Query
- DAX
- Data Modeling

---

## Project Files

- startup evaluation.pbix
- Startup Valuation Report
- Dashboard Screenshots

---

## Future Improvements

- Add revenue metrics
- Include startup exits
- Predict startup success using Machine Learning
