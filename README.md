# SQL Window Functions Campaign Analysis

## Overview

This project focuses on analyzing monthly digital marketing campaign performance using PostgreSQL.

The analysis combines advertising data from Facebook Ads and Google Ads and applies date functions, Common Table Expressions (CTEs), and window functions to evaluate campaign performance over time.

## Objectives

- Combine Facebook Ads and Google Ads data.
- Aggregate advertising metrics by month and UTM campaign.
- Calculate monthly advertising performance metrics.
- Compare current month performance with the previous month.
- Analyze percentage changes in CPM, CTR, and ROMI.

## SQL Concepts

- Common Table Expressions (CTEs)
- UNION
- Date Functions (DATE_TRUNC)
- Window Functions
- LAG()
- PARTITION BY
- ORDER BY
- Aggregate Functions (SUM)
- CASE WHEN
- GROUP BY

## Key Metrics

- Total Cost
- Number of Impressions
- Number of Clicks
- Conversion Value
- CTR (Click-Through Rate)
- CPC (Cost Per Click)
- CPM (Cost Per 1,000 Impressions)
- ROMI (Return on Marketing Investment)

## Month-over-Month Analysis

The project calculates percentage changes in:

- CPM
- CTR
- ROMI

These calculations compare each campaign's current monthly performance with its previous available monthly record using the LAG() window function.

## Data Sources

- facebook_ads_basic_daily
- google_ads_basic_daily

## Tools

- PostgreSQL
- SQL

## Project Outcome

The project demonstrates how SQL date functions and window functions can be used to analyze marketing campaign trends and measure performance changes over time.
