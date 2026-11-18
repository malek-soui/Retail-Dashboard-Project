\# Retail Sales Analysis \& Interactive Power BI Dashboard



An end-to-end retail data analytics project involving data cleaning, transformation, business intelligence, and customer segmentation using Power BI.



\## Project Overview



This project analyzes approximately 1.07 million transaction records from a UK-based online gift retailer between December 2009 and December 2011.



The objective was to transform raw, inconsistent sales data into a reliable dataset and develop an interactive Power BI dashboard to monitor sales performance, understand customer behavior, and identify business opportunities.



\## Business Objectives



\- Clean and prepare large-scale retail transaction data.

\- Analyze sales performance across time, products, and countries.

\- Identify valuable customer segments using RFM analysis.

\- Monitor returns and sales trends.

\- Provide actionable business recommendations.



\## Dataset



\- \*\*Source:\*\* UCI Machine Learning Repository – Online Retail II

\- \*\*Period:\*\* December 2009 – December 2011

\- \*\*Original records:\*\* 1,067,371 rows

\- \*\*Currency:\*\* British Pound Sterling (GBP)



The original dataset is not included in this repository. Refer to `01\_data/README.md` for dataset information.



\## Data Cleaning \& Preprocessing



Data preparation was performed using Power Query (M).



The cleaning process included:



| Data Issue | Rows | Action |

|---|---:|---|

| Cancelled transactions | 19,494 | Separated into a returns table |

| Invalid quantities | 3,457 | Removed |

| Zero or negative prices | 2,750 | Removed |

| Non-product entries | 4,312 | Removed |

| Exact duplicates | 33,669 | Removed |



\*\*Results:\*\*

\- Original dataset: 1,067,371 rows.

\- Clean sales dataset: 1,003,689 rows.

\- 19,494 cancelled transaction rows were preserved separately.

\- Every cleaning operation was documented in an Excel cleaning log.



Transactions without Customer IDs were retained for sales analysis and excluded only from customer segmentation.



\## Dashboard Features



The Power BI report contains two interactive pages.



\### 1. Sales Overview



\- Total revenue, order count, customer count, average order value, and return rate.

\- Monthly revenue trends.

\- Top 10 products by revenue.

\- Revenue distribution by country.

\- Interactive year and country filters.



!\[Sales Overview](04\_screenshots/01\_sales\_overview.png)



\### 2. Customer Segmentation (RFM)



\- Recency, Frequency, and Monetary analysis.

\- Customer segmentation using quintile-based scoring.

\- Revenue contribution by customer segment.

\- Identification of high-value and at-risk customers.

\- Detailed At Risk customer table.



!\[Customer Segments](04\_screenshots/02\_customer\_segments.png)



\### Interactive Filtering



Dashboard visuals and KPIs respond dynamically to country and year selections.



!\[Filtered Dashboard](04\_screenshots/03\_filtered\_view.png)



\## Key Business Insights



\### Sales Performance



| Metric | Result |

|---|---:|

| Total Revenue | £19.66M |

| Orders | Approximately 40K |

| Average Order Value | £497.41 |

| Identified Customers | 5,853 |

| Return Rate (by value) | 7.77% |



\### Customer Analytics



\- \*\*Champions:\*\* 1,258 customers (approximately 21% of identified customers) generated £11.59M, representing approximately 68% of revenue from identified customers.

\- \*\*At Risk:\*\* 709 customers associated with approximately £1.53M in revenue represent a potential customer retention opportunity.



\### Other Findings



\- Sales show strong seasonality, with revenue peaking in November.

\- The UK represents the largest share of revenue.

\- Ireland, the Netherlands, and Germany are among the next important markets.



\## Business Recommendations



1\. \*\*Recover At Risk Customers:\*\* Launch targeted retention campaigns for the 709 identified customers.

2\. \*\*Protect Champions:\*\* Introduce loyalty benefits and personalized offers for high-value customers.

3\. \*\*Prepare for November:\*\* Plan inventory and supply ahead of the seasonal sales peak.

4\. \*\*Diversify Markets:\*\* Develop opportunities in other European markets.

5\. \*\*Investigate Returns:\*\* Analyze return patterns by product and customer to identify possible quality or description issues.



\## Tools \& Technologies



\- \*\*Power BI:\*\* Interactive dashboard development and data visualization.

\- \*\*Power Query (M):\*\* Data cleaning and transformation.

\- \*\*DAX:\*\* Business measures and customer segmentation calculations.

\- \*\*Microsoft Excel:\*\* Cleaning documentation and data validation.



\## Repository Structure



```text

Retail-Dashboard-Project/

│

├── 01\_data/

│   └── README.md

│

├── 02\_powerbi/

│   └── Retail\_Dashboard.pbix

│

├── 03\_documentation/

│   ├── Cleaning\_Log.xlsx

│   ├── Client\_Report\_AR.pdf

│   └── Case\_Study\_AR\_EN\_FR.md

│

├── 04\_screenshots/

│   ├── 01\_sales\_overview.png

│   ├── 02\_customer\_segments.png

│   └── 03\_filtered\_view.png

│

├── README.md

└── .gitignore

```



\## How to Explore the Project



1\. Browse the dashboard screenshots in `04\_screenshots/`.

2\. Open `02\_powerbi/Retail\_Dashboard.pbix` using Microsoft Power BI Desktop.

3\. Review the cleaning operations in `03\_documentation/Cleaning\_Log.xlsx`.

4\. Read the detailed business findings in `03\_documentation/Client\_Report\_AR.pdf`.

5\. Explore the multilingual case study in `03\_documentation/Case\_Study\_AR\_EN\_FR.md`.



\## Important Notes



\- December 2011 is incomplete because the dataset ends at the beginning of the month. Its decline should not be interpreted as a real sales downturn.

\- The 7.77% return rate is calculated by value, not by the number of returned orders.

\- RFM analysis covers 5,853 customers with available Customer IDs and approximately £17.08M in revenue. Sales without Customer IDs remain included in overall revenue.

\- Cancelled transactions were separated into a returns table rather than treated as valid sales.



\---



\*\*Project Category:\*\* Data Analytics | Business Intelligence | Retail Sales Analysis



\*\*Author:\*\* Malek Soui

