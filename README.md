# Global Retail Performance Dashboard

**Tools:** Tableau · Excel  
**Domain:** Business Intelligence · Retail Analytics  
**Type:** Interactive dashboard with KPI tracking

---

## Overview

This project builds an interactive Tableau dashboard for a global retail company operating across 10 countries, 3 customer segments, and 3 product categories. The dataset spans 2022 to 2024 and covers 21,900 orders, $3.2M in total sales, and 2,726 unique customers.

The focus was on building a dashboard that gives management a clear picture of financial health — not just top-line revenue, but margins, costs, returns, and customer behavior — so decisions can be made from data rather than gut feel.

---

## Business Questions

- How is the business performing across segments and categories?
- Where are costs concentrated and how do they affect margins?
- What is the return rate and how does it impact profitability?
- How are key financial ratios trending over time?
- Which customer segments are most valuable?

---

## Data

| File | Description |
|---|---|
| `Performance_Vis_Data.xlsx` | Order-level sales data, metrics by segment, cost breakdown by quarter |

The dataset includes order ID, date, segment (Consumer, Corporate, Home), category (Furniture, Office Supplies, Technology), sales value, returns, customer ID, country, and on-time delivery status.

---

## KPIs Tracked

### Financial Metrics
| KPI | Value |
|---|---|
| Total Sales | $3.2M |
| Total Orders | 21,900 |
| Gross Profit Margin (GPM) | 26% |
| Operating Profit Margin (OPM) | 12% |
| Return on Assets (ROA) | 7% |
| Return on Equity (ROE) | 19% |

### Customer Metrics
| KPI | Value |
|---|---|
| Unique Customers | 2,726 |
| Repeat Customer Rate | 46.7% |
| On-Time Delivery Rate | 90.7% |
| Total Returns | 1,674 |

### Segment Breakdown
| Segment | GPM | OPM |
|---|---|---|
| Consumer | 38% | 12% |
| Corporate | 24% | — |
| Home | 16% | — |

---

## Cost Breakdown

The dashboard tracks costs across 5 categories:

| Cost Type | Share |
|---|---|
| Operational | 30% |
| Product | 25% |
| Marketing | 20% |
| Shipping | 15% |
| Returns | 10% |

Operational costs are the largest driver of margin compression — a key finding for management attention.

---

## Dashboard Design

The dashboard was built in Tableau with the following views:

- **Summary KPI cards** — Sales, Orders, Customers, Returns with sparkline trends
- **Sales & Costs bar chart** — Quarterly net sales vs. costs from 2022–2024, with peak in Q4 2024 ($58K net)
- **Segment donut chart** — Revenue share by Consumer, Corporate, and Home segments
- **Cost breakdown bar** — Horizontal stacked bar showing cost distribution across all 5 types
- **Margin gauges** — GPM, OPM, ROA, ROE displayed as circular progress indicators

---

## Key Findings

1. Consumer segment drives volume but Home Office generates the best margins — worth focusing on for profitability rather than just revenue growth.
2. Operational costs at 30% of total costs are the biggest lever for margin improvement.
3. Return rate of 1,674 orders represents ~7.6% of total orders — worth investigating by product category and region.
4. On-time delivery at 90.7% is strong but the 9.3% gap likely contributes to return rate and customer churn.
5. Q4 consistently outperforms — sales planning and inventory should reflect this seasonality.

---
