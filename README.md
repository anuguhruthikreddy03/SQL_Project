🌍 Energy Consumption Analysis (SQL Project)
📘 Overview

This project focuses on analyzing global energy consumption patterns using structured data stored in a MySQL database.
The goal is to uncover correlations between energy usage, emissions, GDP, population, and economic growth — providing insights into sustainable energy and policy planning.

🎯 Objective

The objective of this project is to analyze worldwide energy consumption using data from the EIA organization.
By exploring metrics such as energy production, consumption, emissions, GDP, and population, the project identifies key global trends and relationships between economic power and environmental impact.

🧩 Database Design
ER Diagram Explanation

The database consists of six interconnected tables:

Table Name	Description
country	Contains country names and unique IDs. Acts as the central reference table.
emission	Stores emission details by country, energy type, year, and per capita metrics.
population	Tracks population data by country and year.
production	Contains data on energy production by country, energy type, and year.
gdp_dd	Records GDP values by country and year.
consum	Tracks energy consumption data segmented by country, energy type, and year.

All tables are connected through the country attribute, ensuring relational integrity and enabling powerful analytical queries.

🔍 Key Analysis Questions

Some of the major business and analytical questions answered using SQL include:

What is the total emission per country for the most recent year?

What are the top 5 countries by GDP?

Compare energy production vs. consumption by country and year.

Which energy types contribute most to emissions globally?

How have global emissions and GDP changed over time?

What is the emission-to-GDP ratio by year?

How does population growth affect total emissions?

Which countries have reduced their per capita emissions the most in the last decade?

🧮 SQL Techniques Used

Complex JOIN operations across multiple tables

Use of aggregate functions (SUM, AVG, MAX, etc.)

Implementation of GROUP BY, ORDER BY, and HAVING clauses

Subqueries and CTEs for intermediate calculations

Window functions for trend analysis

Analytical queries to compare GDP, population, and emission growth rates

📊 Key Insights

A strong positive correlation exists between GDP and energy consumption — economic growth drives energy demand.

Countries with lower emission-to-GDP ratios demonstrate sustainable growth and better energy efficiency.

Population growth significantly influences total emission levels.

Transition to renewable energy and energy efficiency programs are crucial for reducing global emissions.



💡 Conclusion

The analysis highlights the urgent need for sustainable energy policies that balance economic development with environmental protection.
By leveraging SQL and data analytics, this project demonstrates how structured data can guide evidence-based decisions for a greener and more energy-efficient future.
