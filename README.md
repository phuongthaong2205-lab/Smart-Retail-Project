# Smart Retail: E-Commerce Performance Dashboard

## Project Context
Smart Retail is a fictional e-commerce chain. In this project, I designed an interactive Power BI dashboard to analyze sales performance, track key operational metrics, and uncover the root causes of recent revenue fluctuations.
## Data Source
Fictional dataset provided as a course exercise by DUA Edu (Data Upgrade Ability).
All DAX measures, data model, dashboard design and insights below are my own work.
## Tools & Techniques
- **Tool:** Power BI, Power Query, DAX
- **Focus:** Data Visualization, Data Modeling, Business Intelligence, Storytelling
## Data Model & DAX
- Flat file model (Order → Store → Product → Channel), 4 dashboard pages: Executive Overview, Sales Performance, Product Analysis, Operations & Service
- Key DAX measures: Total Revenue, Gross Profit, Net Profit Margin, % Revenue Variance vs. Prior Period, Average Order Value, Completed Order Rate
## Dashboard Preview
| Executive Overview | Sales Performance |
|---|---|
| ![Overview](Overview_Dashboard.png) | ![Sales](Sales_Performance.png) |
| **Product Analysis** | **Operations & Service** |
| ![Product](Product_Analysis.png) | ![Ops](Operations_Service.png) |

## Key Business Insights
*(Brief summary, all changes are June 2026 vs. May 2026. For deeper analysis, see the attached report.)*

- **Revenue Trend:** In June 2026, revenue fell 18.7% month-over-month (€304.70K → €247.68K), the 4th consecutive monthly decline, while net profit margin held steady at 18.3%. The slump is a volume problem, not a margin problem: placed orders fell 15.0% and the completion rate fell 8.1 points, partly offset by a 6.5% rise in average order value.

- **Localized Operational Issue:** Berlin Mitte's completion rate fell from 85.4% to 68.1% (the sharpest drop in the chain), alongside a 65.9% drop in website revenue. Website and Otto also declined across several stores while Amazon grew, pointing to channel- and process-level issues (e.g., order handling, stock synchronisation) rather than weak demand in one city.

- **Service & Operations:** The average rating rose 8.5% to 3.15, but this is largely a return to normal after May's low (2.90). The completed order rate fell 8.1 points to 71.49% (−10.2% in relative terms), making fulfilment and cancellations the priority to investigate. The dataset has no cancellation-reason field, so causes remain hypotheses.

- **Product Strategy:** Apple generates 62.08% of revenue. The MacBook Air M3 fell 44.0% (€100.0K → €56.0K) at an unchanged price, accounting for about 77% of the chain's revenue decline. Smartphones grew 7.7% (iPhone 15 +6.3%, Galaxy S24 +10.5%), an opportunity to diversify beyond Apple.
## Project Assets
- **[Business Insights & Action Plan Report](SmartRetail_Insights.pdf)**: Comprehensive analysis using the "What - So What - Now What" framework.
- **[Power BI Dashboard](SmartRetail_Dashboard.pbix)**: Contains Data Model and DAX Measures.
