🎯 Objective

A Power BI dashboard to analyze marketing campaign performance using given dataset.

📌 KPIs Calculated (DAX)

CTR = DIVIDE(SUM(Clicks), SUM(Impressions)) * 100
CPC = DIVIDE(SUM(Spend), SUM(Clicks))
CPM = DIVIDE(SUM(Spend) * 1000, SUM(Impressions))
ROI = DIVIDE(SUM(Revenue) - SUM(Spend), SUM(Spend)) * 100

📈 Visuals Included

KPI Cards → CTR, CPC, CPM, ROI

Bar Chart → Spend by Campaign

Bar Chart → Conversions by Campaign

Line Chart → CTR by Campaign

Line Chart → ROI by Campaign

🛠 Tools Used

Power BI Desktop

DAX

✅ Key Insight

Diwali Offer performed best in ROI and conversions

Summer Sale showed lowest CTR and ROI
