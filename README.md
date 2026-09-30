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
| ![Product](Products_Analysis.png) | ![Ops](Operation_Service.png) |

## Key Business Insights
*(Brief summary, all changes are June 2026 vs. May 2026. For deeper analysis, see the attached report.)*
- How to read the numbers: the dashboard is filtered to June 2026 and compares it with May 2026. Because the data ends on 25 June, the dashboard compares 25 days with 31. All percentages below are like-for-like (June 1–25 vs. May 1–25) unless marked otherwise, so they differ from the screenshots, which show the dashboard's full-May comparison.
- **Revenue Trend:** The dashboard shows revenue down 18.7% in June, but this compares 25 days of June with the full month of May. Like-for-like, revenue rose 6.8% and revenue per day is flat (~€9.9K), while net profit margin held at 18.3%. Revenue per day did fall ~25% between February and May, so the earlier decline is real but stabilized in June.

- **Completion Rate:** The completed order rate fell to 71.5% (from a 78–82% range) while placed orders rose 8.3%, worth about €26K of June revenue. The drop is sharpest at Berlin Mitte (−17.2 pts), while Frankfurt (−14.6 pts), on Website (−17.9 pts), and Otto (−12.6 pts), pointing to channel- and process-level issues rather than weak demand. Causes remain hypotheses (no cancellation-reason data).

- **Regional & Channel Shifts:** Central is the only region with lower revenue (−21.4%), while North (+16.2%) and South (+28.4%) grew; Amazon (+85.7%) gained while Website (−22.8%) lost.

- **Product Strategy:** Apple generates 62.08% of revenue. The MacBook Air M3 fell 19.0% at an unchanged price, while smartphones grew 22.5% (iPhone 15 +23.2%), an opportunity to diversify beyond Apple.
## Project Assets
- **[Business Insights & Action Plan Report](SmartRetail_Insights.pdf)**: Comprehensive analysis using the "What - So What - Now What" framework.
- **[Power BI Dashboard](SmartRetail_Dashboard.pbix)**: Contains Data Model and DAX Measures.
