📊 Client Revenue SQL Analytics System
🚀 Overview

This project demonstrates business analytics using structured relational databases and SQL queries.

A normalized SQLite database was designed to simulate a digital agency's client and project data. Analytical queries were executed to extract revenue insights and business intelligence.

🎯 Business Problem

Digital agencies need to analyze:

Revenue by city

Revenue by industry

Project distribution

High-performing markets

This project simulates a relational database system to derive these insights using SQL.

🛠 Tech Stack

Python

SQLite

SQL (Joins, Aggregations, Window Functions)

Pandas

Google Colab

🧱 Database Design

Two normalized tables were created:

Clients Table

client_id (Primary Key)

client_name

industry

city

Projects Table

project_id (Primary Key)

client_id (Foreign Key)

project_type

project_cost

start_date

payment_status

The tables are linked using a foreign key relationship.

📈 Key SQL Features Demonstrated

INNER JOIN

GROUP BY

ORDER BY

Aggregation Functions (SUM, COUNT)

Subqueries

Window Functions (RANK)

📊 Sample Business Insights

Identified top revenue-generating cities.

Ranked cities based on total revenue.

Analyzed project distribution across industries.

Calculated overall revenue performance.

📂 Project Structure

client-revenue-sql-analytics/
│
├── sql_analysis.ipynb
├── agency.db
├── queries.sql
├── requirements.txt
└── README.md

🔮 Future Improvements

Add more complex analytical queries

Connect to PostgreSQL

Build Power BI dashboard on top of database

Deploy analytics dashboard using Streamlit

👨‍💻 Author

Abhilash R. Marathe
Computer Science Engineer | Data & GenAI Enthusiast
Founder – WebQuicks Technologies

LinkedIn: https://www.linkedin.com/in/abhilash-marathe-aa4331140/
