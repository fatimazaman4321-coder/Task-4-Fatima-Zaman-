# E-Commerce Sales Dashboard - Power BI | Decode Lab Internship

 📊 Dashboard Overview
This is an interactive Power BI Dashboard built as part of my Decode Lab Internship. It visualizes e-commerce sales data from 2023-2025 to track revenue trends, marketing performance, order status, and coupon impact. The dashboard helps stakeholders make data-driven decisions quickly.
 🎯 Business Questions Answered
- How has total revenue trended over 2023-2025?
- Which referral source drives the most revenue?
- What is the distribution of order statuses?
- How do different coupon codes perform in terms of sales?
- What quantity levels are most common per order?
🛠️ Tools & Techniques Used
- Microsoft Power BI Desktop: Data modeling, DAX measures, visualization
- Charts Used: Line Chart, Donut Charts, Bar Charts, Card Visuals, pie chart
- Data Transformations: Cleaned in Power Query, relationships defined in Model view
- Interactivity: Slicers, cross-filtering between visuals
 📈 Dashboard Breakdown & Key Insights
1. Revenue Trend: `Sum of TotalPrice by Year`
- Visual: Line Chart
  Insight: Revenue shows a declining trend from 2023 to 2025. This signals a need to investigate causes: market competition, customer churn, or seasonal factors.
2. Marketing Performance: `Sum of TotalPrice by ReferralSource`
- Visual: Donut Chart  
- Top Sources: Instagram `28.38%` with $47.52K revenue, followed by Google `21.28%` and Facebook `21.25%`
- Insight: Instagram is the highest ROI marketing channel and should receive increased ad spend.
 3. Order Fulfillment: `Count of OrderID by OrderStatus`
- Visual: Donut Chart
- Status Split: Pending `22.35%`, Shipped `20%`, Delivered `19.41%`, Cancelled `18.82%`
- Insight: ~23% orders are still pending. Ops team should review fulfillment delays.
 4. Product Purchase Pattern: `Count of Product by Quantity`
- Visual: Bar Chart
- Insight: Most customers buy in quantities of 1, 4, and 5. Quantity = 4 is the most frequent. Useful for inventory bundling strategies.
 5. Coupon Effectiveness: `Sum of TotalPrice by CouponCode`
- Visual: Bar Chart
- Top Performers: `no coupon` generates highest revenue, followed by `FREESHIP`, `WINTER15`, `SAVE10`
- Insight: Organic purchases without coupons drive more revenue. `FREESHIP` is the most effective discount code.
6. KPI Cards
- Total Orders/Products: 36 products tracked
- Average Order Value: Fluctuates between 107.04 to 1.51K based on filters
📁 Project Files
- Power BI File: `Ecommerce_Sales_Dashboard.pbix`
- Data Source: `project_1_decodelab.xlsx` - Cleaned dataset from Project 1
- Screenshots: Dashboard views added to repo for quick preview
💡 Business Recommendations
1. Address Revenue Decline: Run customer feedback surveys for 2024-2025 drop
2. Double Down on Instagram: Allocate 40% of marketing budget to Instagram ads
3. Improve Order Fulfillment: Target <10% pending orders by optimizing logistics  
4. Rethink Discount Strategy: Test `FREESHIP` vs `SAVE10` A/B to maximize profit margins
👩‍💻 Author
Fatima Zaman  
Data Analysis Intern @ Decode Lab  
Project 3: Power BI Dashboarding | Skills: Data Viz, DAX, Business Intelligence
---
*This dashboard demonstrates proficiency in Power BI, data storytelling, and translating business questions into visual insights.*# Task-4-Fatima-Zaman-
Project for DecodeLab internship 
