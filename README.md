Assignment 1.1 (Unit 1)

Part 1: 
Research and identify real-world data sources and integration with tools like Power BI or modern data platforms.

Today, organizations collect information from multiple sources. These data sources are then integrated into modern data platforms or business intelligence tools like Power BI, Tableau, Google BigQuery, and Snowflake to generate insights and visualize them for better understanding.
1. Real-world Data Sources
•	Retail & E-commerce Data: Online stores such as Amazon, Flipkart, and Shopify store customer purchase history, product demand, inventory levels, and returns. This data is essential for sales forecasting and personalized recommendations.
•	Healthcare Data: Hospitals and diagnostic centers collect Electronic Health Records (EHRs), lab results, patient demographics, and real-time health data from IoT devices (e.g., wearable heart-rate monitors).
•	Social Media & Web Data: Platforms like Twitter, Instagram, and Google Trends provide sentiment analysis data and consumer behavior patterns.
•	Financial & Banking Data: Transactions, stock market feeds, and credit card usage provide insights for fraud detection and financial forecasting.
•	Public Datasets & Government Data Portals: Open-source datasets from portals such as Kaggle, WHO, World Bank, and data.gov offer structured and unstructured data for analysis.


2. Modern Data Platforms for Integration
•	Power BI: A widely used visualization tool by Microsoft that allows users to connect to multiple data sources (Excel, SQL, APIs, CSVs, cloud databases) and create interactive dashboards.
•	Google BigQuery: A cloud-based data warehouse for analyzing huge datasets in seconds.
•	Snowflake: A scalable cloud platform that supports real-time analytics.
•	Apache Spark & Databricks: Used for big data processing and advanced analytics across distributed systems.
3. Importance of Integration with BI Tools
•	Combines Multiple Sources: Data from different platforms (databases, APIs, files) can be merged in one place.
•	Real-time Insights: Dashboards help managers monitor KPIs instantly.
•	Data-driven Decision Making: Businesses can track sales, customer engagement, and growth patterns to improve strategy.
•	Predictive Analytics: Advanced BI integration helps forecast demand, identify trends, and reduce risks.









Part 2:
Design a mini project that maps a data lifecycle (capture to visualization) for a real-world problem in the retail/healthcare domain. (80% marks)

Mini Project: Data Lifecycle using E-commerce Dataset:

1. Capture (Data Collection)
•	What it means: Gathering data from various sources.
•	In our case: We capture data from Kaggle (Ecommerce.csv). Originally the data was captured by the owner from a retail store in London who mainly deal in wholesale via point on sale system.
•	Tool used: Python (Pandas).

2.  Storage 
•	What it means: Securely storing the collected raw data.
•	In our case: Store the cleaned dataset into MySQL for centralized access.
•	Tool used: MySQL + SQLAlchemy connector.

3. Processing (Cleaning and Transforming)
•	What it means: Converting raw data into usable format.
•	In our case: Remove duplicates, handle missing values, create new features (TotalAmount).
•	Tool used: Python (Pandas).

4. Analysis (Extract Insights)
•	What it means: Run queries or logic to understand data.
•	In our case: Use SQL queries and excel for getting insights.

5. Visualization (Present Insights)
•	What it means: Present data in understandable formats.
•	In our case: Use Power BI connected to MySQL.
•	Dashboards:

Final Data Lifecycle Path (with tools)
➡ Capture → (Python, Kaggle CSV)
➡ Storage → (MySQL: Raw Table)
➡ Processing → (Python, Pandas → MySQL Processed Table)
➡ Analysis → (SQL Queries inside MySQL / Power BI)
➡ Visualization → (Power BI Dashboards connected to MySQL)












