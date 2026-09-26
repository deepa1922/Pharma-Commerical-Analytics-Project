# 💊 Pharma-Commercial-Analytics
This project involves analyzing a comprehensive simulated pharma commercial dataset using Power BI. The goal is to uncover insights about prescribing behavior, patient treatment persistency, and competitive market dynamics to help pharma brands improve market access, patient retention, and sales strategy.

## 📊 Project Overview
As a Pharma Commercial Analyst, I analyzed 74,000+ records covering:

* Weekly prescriptions across 300 doctors and 4 competing GLP-1 diabetes drugs (Ozempic, Mounjaro, Trulicity, Rybelsus)
* Patient-level treatment history across 2,500 patients
* Insurance/formulary coverage, sales call activity, and payer type
* Doctor specialty, prescribing segment, and geographic territory

## 🎯 Business Objectives

1. Understand how prescribing behavior varies by doctor segment, specialty, and territory
2. Identify how insurance coverage affects prescribing volume
3. Determine what drives patient persistency (staying on treatment)
4. Track competitive market share dynamics over time
5. Quantify the impact of sales engagement on prescribing

## 🧩 Key Analysis Areas
1. Prescriber & Territory Insights

* Prescribing volume by state, specialty, and doctor segment (High/Medium/Low)
* Sales call activity vs. prescribing correlation

2. Patient Journey & Persistency Analysis

* Treatment duration (days on therapy) by payer type and starting drug
* Early-refill and dose-titration patterns

3. Competitive & Market Access Analysis

* Insurance/formulary coverage impact on prescribing
* Market share trend across all 4 competitors over time

## 📌 Key Tools Used

* Power BI for visualization and dashboarding
* DAX for calculated metrics (e.g., Days on Therapy, Market Share %, HCP Segment)
* Power Query for data cleaning and shaping
* SQL (MySQL) as the connected source database

## 📌 Key Insights

* Insurance coverage was the strongest driver of prescribing — prescriptions ran ~3x higher when a drug had favorable coverage, and this issue was specific to one drug, not the whole market.
* Uninsured (cash-pay) patients discontinued treatment ~4-5x faster than insured patients — the strongest patient-level finding.
* A competitor overtook the category leader in market share over a 2-year period, growing from ~30% to ~41%.
* Sales call volume rose alongside a market access disruption, suggesting a reactive commercial response.
* Endocrinologists drive the large majority of prescribing volume, though general-medicine specialties remain a meaningful secondary channel.

## ✅ Recommendations

* Prioritize protecting or restoring favorable insurance coverage, since it has the single biggest effect on prescribing.
* Introduce affordability support programs (e.g., co-pay assistance) for uninsured patients to improve treatment persistency.
* Focus sales and territory resources on top-performing states and doctor segments.
* Monitor the competitor gaining share closely, given the recent market leadership change.

📊 Power BI Dashboard
Click below to view the interactive dashboard:
![Executive Overview](
)
