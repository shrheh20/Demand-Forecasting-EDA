# Comprehensive Sales Analysis and Demand Forecasting
I built this project to showcase my end‑to‑end analytics workflow—from raw CSV files to a polished, interactive Tableau dashboard—while extracting business‑ready insights that an executive team could act on. You’ll see my:
<ul>
  <li>Proficient Tableau design for constructing cohesive, multi-dimensional dashboards.</li>
  <li>Narrative data storytelling, converting complex quantitative outputs into actionable executive insights.</li>
</ul>

<h2>Principal Insights</h2>

<h3>Geographic Concentration:</h3> California constitutes approximately 26% of national order volume, suggesting opportunities for targeted marketing interventions.
<h3>Portfolio Diversification:</h3> Post-pandemic recovery was predominantly driven by protein and beverage segments, providing a buffer against broader economic disruptions.
<h3>Cost Transmission Mechanisms:</h3> A fuel price escalation in 2021 coincided with an approximate 7% increase in average selling prices, mitigating margin compression.
<h3>Seasonality Effects:</h3> Persistent elevation of Q3 sales volumes suggests cyclical resource optimization needs.



<h2>1️⃣ Geographic Reach & Product Mix</h2>

![Story 1](https://raw.githubusercontent.com/shrheh20/Demand-Forecasting-EDA/main/images/story1.png)
<ol>
  <li><h3>Visualization</h3> A choropleth map displaying order volume per U.S. state, supplemented by a treemap identifying the principal revenue-generating product categories.</li>
  <li><h3>Significance</h3> Identifies regional concentration (e.g., California accounting for 446,665 orders) and pinpoints high-revenue products such as Beer and Sauces.</li>
  <li><h3>Technical Process</h3> Geospatial joins coupled with Pareto filtering to emphasize top-decile SKUs.</li>
</ol>

<h2>2️⃣ Temporal Dynamics and Macroeconomic Perturbations</h2>

![Story 2](https://raw.githubusercontent.com/shrheh20/Demand-Forecasting-EDA/main/images/story2.png)

<ol>
  <li><h3>Visualization</h3> A time series plot illustrating weekly sales dynamics, highlighting the COVID-19 downturn and subsequent recovery. Dual-axis plots juxtapose sales trends with CPI and fuel price fluctuations.</li>
  <li><h3>Significance</h3> Correlates macroeconomic variables with business resilience, demonstrating limited volume contraction despite inflationary pressures.</li>
  <li><h3>Technical Process</h3> The time series decomposition using statsmodels is complemented by computed percentage differentials and dynamic annotations.</li>
</ol>

<h2>3️⃣ Pricing Strategies and Unit Economics</h2>

![Story 3](https://raw.githubusercontent.com/shrheh20/Demand-Forecasting-EDA/main/images/story3.png)

<ol>
  <li><h3>Visualization</h3> Analysis of year-over-year variations in average selling price for a flagship product (Sake), with a quarterly examination of quantity and pricing dynamics.</li>
  <li><h3>Significance</h3> Showcases strategic price adjustments to safeguard revenue, and underscores seasonal patterns pertinent to operational planning.</li>
  <li><h3>Technical Process</h3> Computation of weighted average prices, integrated into Tableau with parameter-driven interactivity.</li>
</ol>

<h2>Prospective Enhancements</h2>
<h3>Forecasting:</h3> Implementation of SARIMA and gradient boosting models for forward-looking state-level sales predictions.
<h3>Customer Segmentation:</h3> Application of Recency, Frequency, Monetary (RFM) analysis to classify B2B clients.
<h3>Interactive Deployment:</h3> Tableau Public dashboard integration into a Streamlit web application.







