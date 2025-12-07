# Vendor Performance Analysis

A beginner-friendly end-to-end Python project involving data ingestion, logging, SQLite database handling, exploratory analysis, and vendor performance reporting.

This is my first complete data analytics project, where I learned and implemented:

Python scripting

Logging for debugging & monitoring

Data visualization

SQL operations using sqlite3

Jupyter Notebook analysis workflows


## The project evaluates the performance of different vendors based on sales, purchase data, and profit margins.

<img width="761" height="356" alt="image" src="https://github.com/user-attachments/assets/9b88eac6-2717-4e48-8f6f-2116b4ddfe45" />


# Tools & Technologies

- Python (Pandas, Matplotlib, Logging)

- SQLite3 (first time using it)

- Jupyter Notebook

- Data Cleaning / Transformation

- Data Visualization

# Features of This Project
✔ 1. Data Ingestion into SQLite

Using ingestion_db.py, raw data is cleaned, transformed, and inserted into a SQLite database (inventory.db).
This helped me learn:

How to create tables with SQLite

How to insert data programmatically

Running SQL queries from Python

✔ 2. Logging for debugging

Implemented Python’s built-in logging library to:

Track ingestion steps

Capture errors

Maintain logs inside the /logs folder

This was my first experience using logging in a real project.

✔ 3. Exploratory Data Analysis (EDA)

Performed in:
Exploratory Data Analysis.ipynb

Includes:

Checking missing values

Exploratory statistics

Sales distribution

Identifying top-performing vs low-performing vendors

Detecting patterns in purchases, margins, and sales trends

✔ 4. Vendor Performance Analysis

Performed in:
Vendor Performance Analysis.ipynb

This notebook includes:

Vendor-wise summary metrics

Profit margin comparisons

Visualization of overall performance

Filtering vendors based on sales thresholds

Confidence interval calculations for profit margins

✔ 5. Summary Generation Script

get_vendor_summary.py calculates:

Total sales

Profit margin

Top vs low performers

Cleaned dataset outputs

This script can be reused for future datasets.

# Example Visualizations

<img width="1138" height="680" alt="image" src="https://github.com/user-attachments/assets/2232fa2d-ffbe-42c0-990d-251156c2d93c" />
<img width="1309" height="778" alt="image" src="https://github.com/user-attachments/assets/01b8afd9-eb06-4358-b841-7ddf4fcad863" />
<img width="1260" height="734" alt="image" src="https://github.com/user-attachments/assets/ee479d0c-f759-4cc3-b644-f1f886d18237" />
<img width="1387" height="775" alt="image" src="https://github.com/user-attachments/assets/ccd0b4a6-4243-49d6-acb0-758163af875a" />


# What I Learned from This Project

✨ How to structure a real Python project

✨ Writing modular Python scripts

✨ Using sqlite3 to run SQL queries from Python

✨ Logging best practices

✨ Combining Python and SQL for data analysis

✨ Visualization techniques for business insights

✨ Building and organizing a full GitHub-ready project

# How to Run the Project

Clone the repository

Install Python dependencies (mainly Pandas)

Run ingestion_db.py to build the database

Open the notebooks to explore analysis

# Future Improvements

Automate daily vendor performance reporting

Add dashboards using Power BI/Tableau

Convert scripts into a pipeline

Integrate SQLAlchemy for better database handling
