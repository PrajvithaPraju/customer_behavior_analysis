# customer_behavior_analysis
Data Analytics project show cashing customer behavior analysis using python , sql and power bi 
This project demonstrates a complete data analytics lifecycle, starting from data loading and cleaning in Python to business insights visualization in Power BI.
The goal is to analyze customer shopping patterns, understand revenue trends, and build an interactive dashboard that supports data-driven decision-making.

DATASET
Name: customer_shopping_behavior.csv
Source: Public dataset (can be replaced with company-provided data)
Description:
Contains information about customers, their demographics, product categories, purchase amounts, and discounts.
Size: ~10,000 records, 10+ attributes
Objective:
Identify customer segments, understand spending habits, and uncover factors that influence total revenue.


TOOLS TECHNOLOGY
| Tool / Technology                               | Purpose                                                     |
| ----------------------------------------------- | ----------------------------------------------------------- |
| **Python (Pandas, NumPy, Matplotlib, Seaborn)** | Data loading, cleaning, and exploratory data analysis (EDA) |
| **PostgreSQL**                                  | Running SQL queries and extracting deeper insights          |
| **Power BI**                                    | Building an interactive dashboard and data visualization    |
| **Gamma App**                                   | Creating professional presentation slides                   |
| **Jupyter Notebook / VS Code**                  | Code development and workflow execution                     |


PROJECT WORKFLOW
1. Data Loading
* Imported dataset using pandas.read_csv()
* Inspected structure, column names, and data types
* Displayed sample records for initial understanding

2. Data Cleaning
* Handled missing and duplicate values
* Standardized column names and data types
* Removed outliers to ensure accurate analysis

3. Exploratory Data Analysis (EDA)
* Used Matplotlib and Seaborn for visual analysis.
* Explored:
* Gender-wise and age-wise purchase patterns
* Relationship between discounts and total spending
* Top-performing product categories
* Derived insights for business recommendations

4. SQL Analysis (PostgreSQL)
* Imported the cleaned dataset into PostgreSQL
* Wrote SQL queries to answer key business questions:
* Total revenue by gender
* Customers who used discounts but spent above average
* Top 5 cities by purchase amount
* Product categories contributing most to revenue

5. Power BI Dashboard
* Connected PostgreSQL database to Power BI
* Built an interactive dashboard showcasing:
* Total revenue by gender, city, and product
* Average purchase amount and discount usage
* Top customers and spending trends
* Added filters and slicers for better interactivity

6. Report & Presentation
* Summarized key insights into a PDF report
* Created a Gamma presentation highlighting:
* Business problem
* Methodology and tools
* Insights & visualizations
* Recommendations for business growth

KEY INSIGHTS AND RESULTS
^ Female customers contributed the highest total revenue.
^ Discount usage increased total purchase volume.
^ Top 10% customers generated nearly 40% of total revenue.
^ Product category trends revealed peak demand during festive months.
^ Insights provided a roadmap for targeted marketing and customer retention strategies.

HOW TO RUN THE PROJECT
1. Clone the Repository
   https://github.com/PrajvithaPraju/customer_behavior_analysis
2. Install Required Libraries
   pip install -r requirements.txt
3. Run the Jupyter Notebook
* Open data_analysis.ipynb
* Execute cells step-by-step to load, clean, and analyze the data
4. Set Up PostgreSQL
* Create a new database
* Import cleaned dataset (cleaned_customer_data.csv)
5.Run queries from queries.sql
* View Power BI Dashboard
* Open customer_dashboard.pbix in Power BI Desktop
* Refresh data connection to PostgreSQL

-> Deliverables
* data_analysis.ipynb — Python notebook for EDA
* queries.sql — SQL scripts for PostgreSQL analysis
* customer_dashboard.pbix — Power BI dashboard
* final_report.pdf — Summary of findings and insights
* presentation.gamma — Gamma presentation link

  ~ Author
  ~ Prajvitha Praju
 📧 prajvithapraju1@gmail.com
 💼 https://www.linkedin.com/in/prajvithap/
 📊 Aspiring Data Analyst | Python | SQL | Power BI
