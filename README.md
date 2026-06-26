# Stripe Fintech Revenue Operations and Growth Analytics

An executive-level Tableau dashboard analyzing Stripe's revenue trajectory, product mix, enterprise market penetration, and competitive positioning from 2020 to 2025 using publicly available data from Stripe's annual letters and third-party financial reporting.

<img width="1920" height="1324" alt="Image 6-26-26 at 12 08 AM" src="https://github.com/user-attachments/assets/6e7e2d2a-44e5-4471-9302-2b32ba18720d" />

**View the live dashboard:** [Tableau Public](https://public.tableau.com/views/StripeFintechRevenueGrowthAnalytics/Dashboard1)

---

## Project Overview

This project was built to demonstrate the kind of source of truth reporting infrastructure a founding data analyst would develop at an early-stage fintech company — clean, trusted metrics that cross-functional teams can use daily for business decisions. The dashboard covers five analytical views across Stripe's core growth and revenue operations metrics.

---

## Dashboard Views

**1. Net Revenue vs Total Payment Volume (2020–2025)**
Dual-axis chart tracking Stripe's net revenue growth from $1.0B in 2020 to $5.84B in 2025 alongside total payment volume scaling from $0.35T to $1.9T. Annotated with Stripe's first profitable year milestone in 2024 with $2.2B free cash flow.

**2. Product Revenue Mix by Annual Run Rate**
Horizontal bar chart breaking down Stripe's product suite by annual run rate. Stripe Payments drives ~90% of net revenue at $4.6B. Stripe Billing hit a $500M run rate in 2024 and is on track for $1B in 2026, managing 200M active subscriptions across 300,000 companies.

**3. Enterprise Market Penetration by Segment**
Horizontal bar chart showing Stripe's penetration across key enterprise and technology segments. Highlights include 90% of DJIA companies, 80% of Nasdaq 100, 78% of Forbes AI 50, and 60% of Fortune 500 using Stripe as of 2024.

**4. Fintech Competitive Revenue Benchmarking**
Side-by-side comparison of Stripe vs PayPal, Square (Block), Adyen, and Checkout.com on 2024 net revenue and YoY growth. Stripe growing 4x faster than PayPal at 28% YoY vs 7%.

**5. KPI Summary Cards**
Eight headline metrics at a glance: $1.4T TPV, $5.1B net revenue, 38% YoY TPV growth, 28% YoY revenue growth, $2.2B free cash flow, 300,000 companies on Billing, 200M active subscriptions, $159B valuation.

---

## Key Findings

- Stripe achieved first full-year profitability in 2024 with $2.2B in free cash flow, a 2x increase from 2023
- Total payment volume grew 38% YoY in 2024 to $1.4T, equivalent to 1.3% of global GDP
- Stripe Billing is the fastest-growing product line, on track to hit $1B annual run rate in 2026
- Stripe is growing 4x faster than PayPal (28% vs 7% YoY) despite already being at $5.1B in net revenue
- Enterprise penetration is exceptionally deep — 90% of DJIA and 80% of Nasdaq 100 companies use Stripe

---

## Data Sources

- Stripe Annual Letter 2024 (stripe.com)
- Stripe Annual Letter 2025 (stripe.com)
- Axios reporting on Stripe 2024 financials (March 2025)
- Sacra.com Stripe revenue estimates
- Third-party analysis confirmed by multiple sources

Note: Stripe is a private company. Revenue figures are third-party confirmed estimates, not audited financials.

---

## Tools Used

- Tableau Public — dashboard design and visualization
- Microsoft Excel / CSV — data structuring and preparation
- Public financial data — Stripe annual letters and third-party reports

---

## Files in This Repository

- `stripe_revenue_tpv.csv` — revenue and TPV data 2020-2025
- `stripe_product_revenue.csv` — product mix by annual run rate
- `stripe_customer_penetration.csv` — enterprise segment penetration
- `stripe_key_metrics.csv` — headline KPI metrics
- `stripe_competitive_landscape.csv` — competitive benchmarking data

---
