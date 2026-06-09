# Bajaj-Retail-Intelligence
🛒 Bajaj Retail Intelligence Dashboard
A comprehensive, interactive Power BI dashboard built to monitor, analyze, and optimize retail performance across Bajaj's product portfolio and store network.

2. Short Description / Purpose
The Bajaj Retail Intelligence Dashboard is a data-driven Power BI report designed to deliver end-to-end visibility into retail operations — from sales revenue and profit margins to customer behavior and regional store performance. Built for retail managers and sales teams, this dashboard transforms raw transactional data into actionable intelligence, enabling faster decisions, smarter inventory planning, and targeted sales strategies across Bajaj's retail ecosystem.

3. Tech Stack
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Primary platform for report development and interactive visualizations.
📂 Power Query – Data ingestion, transformation, and cleaning layer for shaping raw retail data into structured models.
🧠 DAX (Data Analysis Expressions) – Used for calculated KPIs, dynamic measures, conditional formatting, and time-intelligence functions (YTD, MoM growth, etc.).
📐 Data Modeling – Relationships established across sales, product, customer, and store tables to enable seamless cross-filtering and drill-through analysis.
📁 File Format – .pbix for development; .png for dashboard previews and documentation.


4. Data Source
Source: Bajaj Retail Internal Data Systems
The dataset covers transactional retail records including:
TableKey FieldsSales TransactionsOrder ID, Date, Revenue, Quantity, DiscountProduct CatalogProduct ID, Category, Sub-category, Unit Price, CostCustomer MasterCustomer ID, Segment, Region, Acquisition ChannelStore / Region DataStore ID, City, Region, Zone, Store Type
The data spans multiple financial periods and covers Bajaj's retail presence across key geographies, enabling both historical trend analysis and real-time performance monitoring.

5. Features / Highlights
🔴 Business Problem
Bajaj's retail operations span multiple product categories, customer segments, and store locations — making it challenging for retail managers and sales teams to get a consolidated, real-time view of performance. Key operational questions such as:

Which product categories are driving the most revenue — and which are eroding margins?
Which regions or stores are underperforming against targets?
Which customer segments are most valuable, and how are they trending?
Where should sales effort be prioritized for maximum impact?

…were previously difficult to answer without time-consuming manual reporting across disconnected data sources.

🎯 Goal of the Dashboard
To deliver a single, interactive intelligence platform that:

Gives retail managers an instant snapshot of business health through live KPIs.
Enables drill-down analysis across regions, stores, product categories, and customer segments.
Identifies profit leakages and margin risks before they escalate.
Supports daily and strategic decision-making — from floor-level sales tactics to regional expansion planning.


📊 Walkthrough of Key Visuals
Key KPIs (Top Banner)

Total Revenue
Total Units Sold
Gross Profit Margin (%)
Revenue vs. Target Achievement (%)
Month-over-Month (MoM) Growth Rate
Number of Active Stores

Sales Trend Analysis (Line Chart)
Displays revenue and units sold over time (daily / monthly / quarterly toggle), helping managers identify peak periods, seasonal patterns, and declining trends early.
Product Category Breakdown (Bar / Donut Chart)
Ranks product categories and sub-categories by revenue contribution and profit margin — instantly revealing which lines drive growth and which are underperforming.
Regional / Store Comparison (Map + Matrix)
An interactive geographic map overlaid with revenue bubbles by region, supported by a store-level matrix showing sales, target achievement %, and rank — enabling fair and transparent performance benchmarking.
Profit & Margin Analysis (Waterfall / Scatter Chart)
Breaks down gross profit by product, category, and store. A scatter plot highlights high-revenue but low-margin combinations — flagging priority areas for pricing or cost review.
Customer Segmentation (Pie / Funnel Chart)
Segments customers by value tier (Premium, Regular, Occasional) and acquisition channel. Shows revenue share by segment and tracks retention vs. new customer ratios over time.

💡 Business Impact & Insights

Sales Prioritization: Regional managers can instantly identify top-performing stores and replicate their success strategies in underperforming locations.
Margin Recovery: The profit analysis view surfaces low-margin categories, enabling pricing and procurement teams to act proactively.
Customer Strategy: Segment-level revenue data helps design targeted promotions — rewarding high-value customers and re-engaging occasional buyers.
Target Tracking: Live revenue vs. target KPIs keep sales teams aligned and accountable throughout the month.
Inventory Planning: Category-level sell-through data supports smarter stock replenishment decisions, reducing overstock and stockout risks.


6. Screenshots / Demos

📌https://github.com/Thejukesani/Bajaj-Retail-Intelligence/blob/main/Screenshot%202026-06-09%20131705.png

ViewDescriptionoverview_page.pngMain KPI banner and summary dashboardregional_map.pngGeographic store performance mapproduct_analysis.pngCategory-level revenue and margin breakdowncustomer_segments.pngSegment-wise customer value distribution

7. How to Use

Open Bajaj_Retail_Intelligence.pbix in Power BI Desktop.
Use the Region / Zone slicer to filter all visuals by geography.
Use the Date Range slicer to switch between monthly, quarterly, or custom periods.
Click any product category bar to cross-filter all visuals to that category.
Hover over map bubbles to view store-level tooltips with KPI snapshots.
Use drill-through on any store name to navigate to the detailed store performance page.
