Fraud Detection Dashboard (Power BI)

An interactive Power BI dashboard analyzing fraud patterns across financial transactions — payment methods, devices, locations, and transaction types.

<img width="1957" height="1221" alt="image" src="https://github.com/user-attachments/assets/6d6c4509-d433-4999-b17d-220cd3afb068" />

Dataset

~50,000 financial transaction records with a ~4.92% fraud rate, originally used in a fraud detection ML project (Decision Tree / Random Forest classification) during the Newtech Data Analysis bootcamp. This dashboard explores the same dataset visually in Power BI.

What's Inside
Fraudulent By Payment Methods — pie chart breaking down fraud share across Debit Card, Net Banking, UPI, Credit Card, and Unknown
Transaction Time & Used Devices — transaction volume and average time-of-day by device (Mobile, Desktop, Tablet, Unknown)
KPI cards — Total Fraud Cases, Previous Fraudulent Transactions, Total Transaction Amount
Location & User ID filters — interactive slicers to drill into specific cities or users
Count of Transaction ID, Amount, Type — area chart of transaction volume and value by type (ATM Withdrawal, Bank Transfer, POS Payment, Bill Payment, Online Purchase)
Key Insights
Debit card transactions carry the largest share of fraud (25.25%), followed by net banking (23.92%) and UPI (21.26%)
301 fraud cases in the current view, against 12K previously flagged fraudulent transactions in the historical field
Total transaction volume across the dataset: ~17.88M
Tools

Power BI Desktop

Files
Fraud_PowerBi.pbix — open in Power BI Desktop to explore interactively
dashboard-preview.png — static preview of the dashboard
Related Project

Same dataset, explored a different way — see my Streamlit fraud detection dashboard (ML classification, second place at Newtech bootcamp).
