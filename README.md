🎯 Project Title: MM Store Performance Dashboard – Retail Sales Monitoring
📝 General Info:
Domain: Retail & Food & Beverage

Company: Marou

Dashboard Designer: Nuong

Data Owner: Du

Tool Used: Power BI

Data Source: Internal retail transaction system (daily sales, targets, store info)

Project Date: April 2025

💡 Project Objective:
To build a dashboard that provides a comprehensive overview of store performance across different locations, enabling the business team to:

Track sales and transaction metrics by day, store, and region

Compare performance against monthly targets

Identify best and worst-performing stores

Take timely actions to improve sales where necessary

📌 Key Features of the Dashboard:
1. Top-Level KPIs (Header)
YTD Revenue: Total revenue from January to current month

% YTD Achievement: How YTD actual revenue compares with YTD target

MTD Revenue: Revenue in the current month (up to today)

% MTD Achievement: MTD revenue performance vs. target (target is pro-rated by number of days)

MTD Transaction Count: Total number of transactions in the month

2. Store-Level Breakdown
Revenue by Store: Ranked list of all stores with revenue and %TGT

Color-Coded Performance Legend:

🟩 >100% (Target Achieved)

🟨 80–100% (On Watch)

🟥 <80% (Underperforming)

This enables quick identification of underperforming stores such as “Ben Nghe - HUE” (68% TGT).

3. Regional Revenue Contribution
Stacked bar chart showing revenue by region and by store type (e.g., Flagship, Café, Station).

South region is leading with highest revenue contribution.

4. Store Quadrant Map (Positioning Matrix)
X-Axis: Average Transaction Value

Y-Axis: Total Transactions (MTD)

Stores plotted to identify:

High value, high transaction stores (e.g., The Nhon – HN, Calmette – HCM)

Low value, low transaction stores (potential for action)

5. Daily Revenue and Transaction Trends
Clustered column chart for daily tracking of:

Revenue (in millions VND)

Number of transactions

Helps identify peak days and low-performing days.

6. Top 5 Food & Beverage Items by Revenue (Last Day)
Lists top-performing products such as:

MINI BAR SET (3.5B VND)

SIGNATURE HOT, 6 NAPO BOXES, etc.

7. Slicer Panel for Interaction
Filters available for:

Month

Region

Store Type

Store Name
→ Managers can view tailored insights for a specific store or area.

🔍 Advanced Logic Used:
Pro-Rated Monthly Target Calculation: Based on number of days in month

Dynamic % Achievement Calculation: Using DAX for Actual/Target comparisons

Store Segmentation via Quadrant Logic: Transaction vs. Value

Conditional Formatting: Automatic color change based on % Target

✅ Business Impact:
Operations Team: Easily identified stores needing support or intervention

Sales Team: Focused efforts on high-potential stores during the month

Leadership: Real-time view of revenue progress towards monthly and yearly targets

Marketing: Understood product trends to guide promotions

✨ What I Learned:
How to structure a multi-layered retail dashboard using performance KPIs, visuals, and interactivity

How to implement color-coded alerts and quadrant segmentation for decision-making

Importance of user-friendly navigation (filters + layout) for non-technical users
