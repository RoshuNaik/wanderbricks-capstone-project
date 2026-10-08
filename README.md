# wanderbricks-capstone-project

End-to-end SQL analytics project built in Databricks using the Wanderbricks dataset, covering business analysis from data exploration to advanced SQL insights.

WanderBricks --- Databricks Data Exploration & SQL Analytics
📌 Project Overview
WanderBricks is a data analytics capstone project focused on
exploring and analyzing a multi-table accommodation and booking dataset
using Databricks SQL.
The project works with structured data related to users, amenities,
hosts, properties, and bookings. The analysis uses SQL queries to
understand customer activity, property performance, host and rating
patterns, and booking trends.
The project demonstrates an end-to-end analytics workflow: exploring
source tables, writing SQL queries, extracting meaningful patterns, and
presenting query outputs through visualizations.
🎯 Project Objectives
- Explore and understand the structure of the WanderBricks dataset.
- Perform data exploration using Databricks.
- Analyze users, amenities, hosts, properties, and bookings using SQL.
- Identify useful patterns and trends from the available data.
- Analyze property-level revenue performance.
- Examine rating-range distributions.
- Track booking-status trends over time.
- Convert SQL analysis into clear and interpretable visual outputs.
🛠️ Tools & Technologies
- Databricks --- Data exploration and SQL execution
- SQL --- Data querying, filtering, aggregation, grouping, and
  analysis
- GitHub --- Version control and project documentation
- Databricks Notebooks --- Organizing table-level exploratory
  analysis
- Data Visualization --- Presenting analytical query outputs
🗂️ Dataset & Tables
The project uses the samples.wanderbricks dataset in Databricks.
The main tables explored in the project include:
  Table          Purpose
  users        User/customer information
  amenities    Amenities associated with properties
  hosts        Host-related information
  properties   Property/listing information
  bookings     Booking and booking-status information
The repository also contains table-specific exploratory notebooks
covering the available WanderBricks data.
🔍 Data Exploration
The project follows a table-by-table exploration approach.
Exploration includes:
- Understanding table structures and columns
- Checking records and data types
- Identifying missing/null values
- Examining categorical distributions
- Aggregating numerical fields
- Investigating trends over time
- Comparing property and booking-related metrics
The repository's 01_data_exploration section contains
Databricks/Jupyter notebooks for table-level exploration.
🧮 SQL Analysis
SQL is the core analytical component of the project.
The queries use common analytical SQL techniques such as:
- SELECT
- WHERE
- GROUP BY
- HAVING
- ORDER BY
- Aggregate functions such as SUM(), COUNT(), and AVG()
- Date/month-based analysis
- Conditional filtering and categorization
- Multi-table analysis where required
The analysis is designed to answer practical business questions around
users, properties, hosts, amenities, revenue, ratings, and bookings.
Note: The README intentionally describes the analysis at a project
level rather than reproducing every SQL query, so the documentation
remains accurate to the repository's notebooks.

📊 Visualizations
The project produced three key analytical visualizations from the
Databricks outputs.
1. Property Revenue Analysis
This horizontal bar chart compares total revenue (SUM(revenue))
across selected properties/titles.
It helps identify properties contributing relatively higher and lower
revenue within the analyzed records.
 <img width="1063" height="213" alt="visualization1" src="https://github.com/user-attachments/assets/da64c57c-0f6a-49bd-bb8d-33d49cf127f8" />

Key observation
The visualization shows noticeable differences in revenue between
properties, with Serviced Residence in Singapore and Hotel in
Singapore among the higher-revenue properties displayed, while several
other properties fall closer to the 140K--155K range.
2. Rating Range Analysis
This bar chart compares the number of records/hosts represented across
different rating ranges.
The categories shown are:
- Below 3.5
- 3.5--3.99
- 4.0--4.49
- 4.5+
 <img width="1063" height="133" alt="visualization2" src="https://github.com/user-attachments/assets/1733c842-0241-4c1b-90f7-6fc96cf86c0c" />

Key observation
The displayed counts are relatively close across the rating categories,
with the below 3.5 category having the highest displayed count and
the 3.5--3.99 category having the lowest.
3. Monthly Booking Status Trend
This time-series visualization tracks booking statuses by month,
including:
- Completed
- Cancelled
- Pending
- Confirmed
The chart covers the period from December 2022 to March 2024.
 <img width="1063" height="125" alt="visualization3" src="https://github.com/user-attachments/assets/a0ce379f-e4d8-4095-be8d-e17d8afcc5e7" />

Key observation
The visualization shows that booking activity changes considerably
month-to-month, while the four booking statuses follow different
patterns. This type of analysis can help identify changes in booking
volume and status behavior over time.
📁 Project Structure
A simplified view of the project structure is:
WanderBricks/
│
├── 01_data_exploration/
│   ├── amenities EDA notebook
│   ├── booking EDA notebook
│   ├── hosts EDA notebook
│   ├── properties EDA notebook
│   ├── reviews EDA notebook
│   └── user table EDA notebook
│
├── visualization1.jpeg
├── visualization2.jpeg
├── visualization3.jpeg
└── README.md
File names may vary slightly in the repository; the structure above
represents the main organization of the project.

🔄 Project Workflow
WanderBricks Dataset
        ↓
Databricks Environment
        ↓
Table Exploration
        ↓
Data Quality & Structure Checks
        ↓
SQL Queries
        ↓
Aggregation & Analysis
        ↓
Business Insights
        ↓
Visualizations
💡 Business Questions Explored
The project focuses on questions such as:
1. Which properties generate higher revenue?
2. How are records distributed across different rating ranges?
3. How does booking activity change over time?
4. How do completed, cancelled, pending, and confirmed bookings compare
   by month?
5. What patterns can be identified from users, hosts, properties,
   amenities, and bookings?
6. What useful insights can be extracted from structured accommodation
   data using SQL?
📈 Key Skills Demonstrated
Data Analytics
- Exploratory Data Analysis
- Data understanding and profiling
- Trend analysis
- Aggregation and comparison
- Business-oriented insight generation
SQL
- Data filtering
- Grouping and aggregation
- Sorting
- Conditional analysis
- Date-based analysis
- Multi-table analytical thinking
Databricks
- Working with Databricks datasets
- Using notebooks for data exploration
- Running SQL-based analysis
- Translating query results into visualizations
Data Visualization
- Selecting appropriate chart types
- Comparing categorical values
- Showing time-based trends
- Communicating analytical findings visually
🚀 How to Use the Project
1. Open the project in Databricks.
2. Access the samples.wanderbricks dataset.
3. Open the notebooks inside 01_data_exploration.
4. Run the exploratory SQL cells.
5. Review the generated query outputs.
6. Recreate or extend the analytical queries as required.
7. Use the resulting datasets to build visualizations and derive
   insights.
🔮 Possible Future Enhancements
- Build an interactive Power BI or Tableau dashboard.
- Add deeper host and property performance analysis.
- Perform customer segmentation.
- Analyze booking cancellation behavior in greater detail.
- Create KPI tracking for revenue, bookings, ratings, and property
  performance.
- Add advanced SQL analysis using joins, subqueries, CTEs, and window
  functions where appropriate.
🏁 Conclusion
The WanderBricks capstone project demonstrates how Databricks and
SQL can be used to transform raw multi-table accommodation data into
meaningful analytical insights.
By exploring users, amenities, hosts, properties, and bookings, the
project covers the complete foundation of a practical data analytics
workflow --- from data exploration and SQL querying to visualization and
business interpretation.
This project strengthened practical skills in SQL, Databricks,
exploratory data analysis, analytical thinking, and data
visualization.
👩‍💻 Author
Roshan Jadhav
GitHub: github.com/roshunaik
