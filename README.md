# Biz_Consultancy_Project

Data Wrangling and Analysis Project

Overview

This project involves comprehensive data wrangling, imputation, structuring, and analysis of meeting and login data sourced from an AWS S3 bucket. The primary goal was to clean and organize the data for effective analysis, providing insights into client demographics, business performance, product usage, and profitability.

Key Features

Data Wrangling

Data Extraction: Extracted meeting data from an AWS S3 bucket into Excel and separated the address column into distinct Pin code, City, and State columns.

Data Cleaning: Removed special characters from business names and addresses, corrected spelling mistakes, and addressed anomalies in date formats.

Data Imputation: Utilized the mode for imputing blank values in various columns, including meeting dates, calling dates, and Telecaller/BDM names.

Data Structuring

Created a unified Business ID to connect various tables, facilitating relational database creation in MySQL.

Normalized business categories and product proposals for better analysis.

Developed four distinct tables to structure the data effectively:

Table 1: Business details

Table 2: Meeting and calling details

Table 3: Business and product categories

Table 4: Sales and payment details

Data Analysis Using Power BI

Analyzed demographic profiles of clients, identifying prevalence in districts like Nagpur, Bhopal, and Chandrapur.

Examined business performance year and month-wise, noting peak sales in 2019 and 2023.

Investigated client types, profitability, and product usage.

Assessed major expenses and explored strategies for improving profitability and customer service.

Evaluated the performance of Telecallers and Business Development Managers (BDMs) across different client segments.

Challenges Faced

Varied formats of Pin codes and dates required intricate cleaning and normalization processes.

Ensured the accuracy of state names associated with cities and corrected data inconsistencies.

Structured the data into a usable format, requiring significant time and effort to achieve high data quality.

Conclusion

This project demonstrates the application of data wrangling techniques and analytical tools to derive valuable insights from complex datasets. The results aim to enhance business decision-making processes and identify opportunities for growth and improvement.

Technologies Used

Python

Excel

MySQL

Power BI
