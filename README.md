Power BI Supply Chain Dashboard

This project presents a comprehensive Supply Chain Analytics Dashboard built using Power BI and simulated data. The dashboard enables users to analyze supplier performance, manage inventory effectively, monitor deliveries, and make data-driven predictions about stockouts and reorder needs.

📊 Key Features

Overview Page with KPIs and trends

Supplier Performance Page to evaluate efficiency

Inventory Management Page with real-time stock alerts

Delivery & Orders Page for regional analysis

Forecasting Tools to predict stockouts and reorder requirements

📈 KPIs and DAX Formulas

The dashboard utilizes a variety of KPIs to derive insights. Detailed DAX formulas and explanations are provided in Documentation/KPIs_and_DAX_Explained.md.

Examples include:

Average Supplier Rating

Average Delivery Time

Total Shipping Cost

Inventory Turnover Rate

Stockout Forecasting

Reorder Prediction

Late Delivery Rate

Orders Trend Over Time

Delivery Timeliness by Region

📁 Dataset

All data used in the report is simulated and can be found in the Data/ folder:

suppliers.csv

inventory.csv

orders.csv

delivery.csv

These files were created to represent realistic supply chain operations.

🔮 Forecasting

Implemented using Power BI’s built-in forecasting tools and DAX logic to:

Calculate Days Until Stockout

Predict Reorder Need based on lead time and usage trends

See: Forecasting/forecasting_dax.md

🖼️ Screenshots

All visual report pages are saved in the Screenshots/ folder for quick review:

Overview KPIs

Supplier Insights

Inventory Health Gauges

Delivery Time Charts

💪 Tools Used

Power BI Desktop

Power Query for ETL

DAX (Data Analysis Expressions)

Simulated CSV Data

🚀 Getting Started

Clone the repository

Open the SupplyChainDashboard.pbix file in Power BI Desktop

Load the data from the Data/ folder

Explore and customize the dashboard as needed
