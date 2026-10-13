# Customer-Segmentation-RFM-Dashboard-Project-4

# Customer Segmentation (RFM) Dashboard (MySQL + Python + Power BI)

**Business question:** Which customers are most valuable, who is slipping away, and what should marketing do for each group?

**Data:** UK Online Retail dataset (Kaggle), [date range]. 5.88K customers, £17.74M total spend.

## Tools
[Python / MySQL: say which step used which], Power BI

## Method
- Recency = days since last order, Frequency = [number of orders / invoices], Monetary = total spend (£).
- Customers were scored [1 to 5 by quintile / fixed thresholds] on each measure and grouped into segments by rule: Champions, Loyal Customers, At Risk, Hibernating, New / Promising.
- Segment cut-offs are a design choice, not a fact.

## Key findings
- Champions are about [27]% of customers but about 70% of spend (£12.43M).
- Hibernating is the largest group (2.1K customers) but a tiny share of spend.
- The highest-spending At Risk customers are worth a targeted win-back effort (the dashboard lists the top 10 by spend).

## Recommendations
- **Champions:** loyalty rewards and early access.
- **At Risk:** win-back campaign, starting with the top 10 by spend.
- **Hibernating:** low-cost email only.
- **New / Promising:** second-purchase offer.

## Limitations
- Segment rules are choices, so different cut-offs would move customers between groups.
- Recommendations are untested. A real campaign would need an A/B test.

## Dashboard
![RFM dashboard](<img width="1366" height="768" alt="Screenshot (309)" src="https://github.com/user-attachments/assets/3f2c9aef-e269-44a5-a2f3-a5dae47891b2" />
)

## Repo contents
`sql/` · `python/` · `powerbi/rfm_dashboard.pbix` · `screenshots/`
