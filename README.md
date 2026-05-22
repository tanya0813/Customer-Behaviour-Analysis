# Customer-Behaviour-Analysis
📌 Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to uncover insights into customer spending patterns, product preferences, and purchasing behavior to support data-driven business decisions.
The project combines Python (data cleaning), SQL (analysis), and Power BI (visualization) to create an end-to-end analytics solution.

📂 Repository Structure
📁 Data/                              # Raw dataset
📄 Customer.sql                       # SQL queries for analysis
📄 Customer_DataCleaning.ipynb        # Data preprocessing and feature engineering
📄 Customer Behavior Dashboard.pbix   # Power BI dashboard
📄 README.md                          # Project documentation


🛠️ Tools & Technologies

Python (Pandas, NumPy) – Data cleaning & preprocessing
PostgreSQL (SQL) – Data analysis and business queries
Power BI – Dashboard and data visualization


🔍 Dataset Summary


Total Records: 3,900


Total Features: 18


Key Attributes:

Customer demographics (Age, Gender, Location, Subscription)
Purchase details (Product, Category, Price, Season)
Behavior insights (Discount usage, Purchase frequency, Ratings)



Data Quality:

Missing values handled in Review Rating
Columns standardized for consistency




⚙️ Data Processing (Python)
Performed in Customer_DataCleaning.ipynb:

Data loading and exploration (info(), describe())
Missing value imputation using median (category-wise)
Column renaming into snake_case
Feature engineering:

Age group segmentation
Purchase frequency calculation


Removed redundant columns
Exported cleaned data to PostgreSQL


🧠 Business Analysis (SQL)
Key insights extracted using SQL queries:

Revenue comparison by gender
High-spending customers using discounts
Top-rated products
Shipping type impact on spending
Subscriber vs non-subscriber behavior
Discount-heavy products
Customer segmentation:

New
Returning
Loyal


Top products per category
Repeat purchase behavior analysis
Revenue contribution by age group


📊 Dashboard (Power BI)
An interactive dashboard was built to visualize:

Customer segments and KPIs
Revenue trends
Product performance
Purchase behavior patterns
Filter-based interactive insights


💡 Key Business Insights

Discount usage does not always reduce spending — high-value customers still buy more
Loyal customers contribute significantly to revenue
Subscription users show better engagement and higher spending
Certain products are highly dependent on discounts
Specific age groups drive the majority of revenue


🚀 Business Recommendations

Increase focus on subscription programs
Implement loyalty rewards for repeat customers
Optimize discount strategies to maintain profit margins
Promote top-rated and best-selling products
Use targeted marketing based on age groups and behavior


▶️ How to Run

Clone the repository

git clone <Repolink>

Run Jupyter Notebook for data cleaning
Execute SQL queries in PostgreSQL
Open .pbix file in Power BI Desktop


✅ Conclusion
This project demonstrates a full data analytics workflow — from raw data cleaning to advanced business insights and visualization — helping organizations better understand customer behavior and improve decision-making.
