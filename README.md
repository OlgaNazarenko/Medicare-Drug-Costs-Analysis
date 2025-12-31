# Medicare-Drug-Costs-Analysis

## Overview
Analyzing Medicare Part D spending growth from 2019-2023 to asnwer: Which manufacturers and products are driving costs? This project examines spending by drug and manufacturer, pricing changes across units/ claims/ beneficiaries, brand-generic shifts, outlier medications, and fastest-growing drugs by price-per-dose. 

## 🎯 Project Goals

To answer the following question:
Where are Medicare drug costs rising faster, and which manufacturers and products are driving the growth?

Sub-questions:
1. What is total spend by year and drug? By manufacturer?
2. How is average spend per dose unit changing? Per claim? Per beneficiary?
3. What is the brand vs. generic share and how is it shifting?
4. Which products trigger the outlier flag and why?
5. Which drugs have the highest 2019-2023 CAGR in price-per-dose?


## 🗂 Dataset

**Dataset**: Medicare Quarterly Part D Spending by Drug 
**Source**: [Data.CMS.gov](https://data.cms.gov/summary-statistics-on-use-and-payments/medicare-medicaid-spending-by-drug/medicare-part-d-spending-by-drug)


## 🛠️ Tools and Methods

Languages & Libraries:
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

Tools:
- Git & GitHub
- VS Code

## 📌 Key Insights

1. Escalating Drug Costs

The top 20 drugs accounted for 91B in 2019 and surged to 214B in 2023—a 135% increase

Average spend per claim rose from 124.44 (2019) to 170.57 (2023), representing a 37% increase

Eliquis dominates Medicare spending, growing 150% from 14.6B (2019) to 36.5B (2023)

2. Market Shifts and New Entrants

Diabetes drugs have surged: The number of diabetes medications in the top 20 increased from 4-5 (2019) to 8 (2023)

GLP-1 agonists are driving growth: Ozempic skyrocketed from outside the top 20 in 2019 to #2 by 2023 ($18.4B), while Mounjaro debuted at #18 ($4.7B)

Jardiance experienced remarkable growth: 6x increase from $2.9B → $17.7B, jumping from #15 to #3

3. Distribution Patterns

Most drugs remain affordable: ~6,800 drugs cost under $100 per claim in 2023

However, ultra-expensive drugs ($5K+ per claim) grew 71%, nearly doubling from 685 (2019) to 1,170 (2023)

High-cost specialty drugs are growing faster than low-cost generics, indicating a shift toward expensive specialty medications

4. Market Consolidation

The same drugs dominate spending year-over-year, showing market stability at the top

Patent expiration impacts are evident: Lyrica dropped out of the top 20 after 2019, while Revlimid fell from #2 to #10

Cancer drugs are declining in rank while metabolic treatments gain prominence

Implications:
The pharmaceutical landscape is shifting dramatically toward diabetes and metabolic treatments, with newer, more expensive specialty drugs driving unprecedented Medicare spending growth. This trend suggests continued upward pressure on Medicare Part D costs in coming years.