# 📊 Blinkit Sales & Customer Satisfaction Analysis

_An analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution to identify key insights and opportunities for optimization using SQL, Python, and Power BI._

---

## ☑️ Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#key-findings--recommendations">Key Findings & Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>📂 Overview</h2>

This project provides a comprehensive analysis of Blinkit's sales data. The primary goal is to evaluate sales performance across different product categories, outlet types, and locations. The analysis uses SQL for data cleaning and querying, Python for exploratory data analysis, and Power BI to create an interactive dashboard that visualizes key performance indicators (KPIs) and trends.

---
<h2><a class="anchor" id="business-problem"></a>❓Business Problem</h2>

The main objective is to analyze Blinkit's sales performance, customer satisfaction, and inventory distribution to uncover actionable insights. This project aims to answer key business questions such as:

- What are the top-performing product categories and outlet types?

- How do sales vary by outlet size, location, and establishment year?

- What is the relationship between product fat content and sales?

- How can we use customer ratings to improve product offerings?

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

The dataset used for this analysis is BlinkIT Grocery Data.csv. It contains transactional data for various products sold through different Blinkit outlets. Key columns include:

**Item_Fat_Content:** The fat content of the product (e.g., Low Fat, Regular).

**Item_Type:** The category of the product (e.g., Snack Foods, Fruits and Vegetables).

**Outlet_Identifier:** A unique ID for each outlet.

**Outlet_Location_Type:** The type of city where the outlet is located (e.g., Tier 1, Tier 2).

**Outlet_Size:** The size of the outlet (e.g., Small, Medium, High).

**Outlet_Type:** The type of outlet (e.g., Supermarket Type1, Grocery Store).

**Total_Sales:** The total sales revenue from the product.

**Rating:** The customer rating for the product.

---
<h2><a class="anchor" id="tools--technologies"></a>🛠️ Tools & Technologies</h2>

1. Data Cleaning & Manipulation: SQL

2. Data Analysis & Visualization: Python (Pandas, Matplotlib, Seaborn)

3. Dashboarding: Power BI

4. Environment: Jupyter Notebook, SQL Server / other database environment

---
<h2><a class="anchor" id="project-structure"></a>📖 Project Structure</h2>

**BlinkIT Grocery Data.csv:** The raw dataset.

**Query Doc.docx:** Contains all SQL queries used for data cleaning and analysis.

**Blinkit Analysis.ipynb:** Jupyter Notebook with Python code for exploratory data analysis.

**Blinkit Analysis.pptx:** A presentation outlining the business requirements and project goals.

**Blinkit Dashboard.pbix:** The interactive Power BI dashboard for visualizing the findings.

---
<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

The primary data cleaning step involved standardizing the Item_Fat_Content column to ensure consistency. The following transformations were applied using SQL:

**Mapped variations like 'LF' and 'low fat' to 'Low Fat'.**

**Mapped 'reg' to 'Regular'.**

This ensures that aggregations and filtering based on fat content are accurate and reliable.

---
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

An EDA was conducted to explore the relationships between different variables and sales performance. Key analyses included:

**Calculating KPIs:** Total Sales, Average Sales, Total Number of Items, and Average Rating.

Analyzing total sales by Item_Fat_Content and Item_Type.

Evaluating sales performance across different Outlet_Location_Type, Outlet_Size, and Outlet_Type.

Assessing the percentage of sales contribution by Outlet_Size.

---
<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

An interactive dashboard was created in Power BI to present the findings. The dashboard provides a high-level overview of key metrics and allows users to drill down into specific dimensions. It features visualizations for:

Total Sales, Average Sales, Number of Items, and Average Rating.

Sales distribution by Item Type, Fat Content, Outlet Size, and Outlet Location.

A comprehensive breakdown of all metrics by Outlet Type.

---
<h2><a class="anchor" id="how-to-run-this-project"></a>⚙️ How to Run This Project</h2>

Load Data: Import the BlinkIT Grocery Data.csv into your preferred database (e.g., SQL Server, MySQL).

Clean Data: Run the SQL queries in Query Doc.docx to clean the Item_Fat_Content column.

Perform Analysis:

Execute the analysis queries from Query Doc.docx.

Run the Blinkit Analysis.ipynb notebook in a Jupyter environment to perform the Python-based analysis.

View Dashboard: Open Blinkit Dashboard.pbix in Power BI Desktop to explore the interactive visualizations.

---
<h2><a class="anchor" id="key-findings--recommendations"></a>Key Findings & Recommendations</h2>

*Outlet Performance:* Supermarket Type3 outlets located in Tier 3 cities generate the highest sales, suggesting a focus on expanding or optimizing these high-performing store formats and locations.

*Product Insights:* Products with "Low Fat" content show significant sales, indicating a strong consumer preference for healthier options. Blinkit should consider expanding its low-fat product range.

*Outlet Size:* Medium-sized outlets contribute the most to total sales. Strategic planning should consider this when opening new stores.

*Recommendation:* Focus marketing and inventory efforts on top-selling item types like Snack Foods and Fruits & Vegetables. Develop targeted promotions for underperforming outlet types like Grocery Stores to boost their sales.

---
<h2><a class="anchor" id="author--contact"></a>📞 Author & Contact</h2>

**Harshad Mourya**<br>
Data Analyst<br>
📧 Email: mouryaharshad@gmail.com<br>
🔗 [LinkedIn](https://www.linkedin.com/in/harshad-mourya/)