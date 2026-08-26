# Customer-Behavior-Data-Analyst-Portfolio-Project
Data Analytics Project Showcasing
# 📊 Data Analytics Project

## Overview

This project demonstrates an end-to-end **Data Analytics workflow**, starting from dataset loading and exploration in Python to SQL-based analysis, Power BI visualization, and final reporting.

The project focuses on extracting meaningful insights from raw data through **data cleaning, exploratory data analysis (EDA), SQL queries, and interactive dashboards**.

---

## 📁 Dataset

The project uses a structured dataset containing customer/purchase-related information.

The dataset is:

* Loaded and analyzed using Python
* Cleaned to handle missing values and inconsistencies
* Used for SQL-based analysis
* Connected to Power BI for visualization
* Used to generate the final report and presentation

---

## 🛠️ Tools & Technologies

| Tool                                | Purpose                      |
| ----------------------------------- | ---------------------------- |
| **Python**                          | Data loading, cleaning & EDA |
| **Pandas**                          | Data manipulation            |
| **NumPy**                           | Numerical operations         |
| **Matplotlib / Seaborn**            | Data visualization           |
| **PostgreSQL / MySQL / SQL Server** | SQL analysis                 |
| **Power BI**                        | Dashboard & visualization    |
| **Gamma**                           | Project presentation (PPT)   |
| **Jupyter Notebook**                | Python-based analysis        |

---

## 🔄 Project Steps

### 1. Data Loading

The dataset was imported into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")
```

### 2. Exploratory Data Analysis (EDA)

Performed initial analysis to understand the dataset:

* Checked dataset dimensions
* Examined data types
* Identified missing values
* Checked duplicate records
* Analyzed numerical and categorical columns
* Studied distributions and relationships between variables

### 3. Data Cleaning

The dataset was prepared for analysis by:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Cleaning inconsistent values
* Renaming columns where required
* Preparing the final dataset for SQL and Power BI

### 4. SQL Analysis

The cleaned data was imported into a relational database and analyzed using SQL.

SQL queries were used to answer business questions such as:

* Revenue by customer demographics
* Top-performing products
* Average purchase amount
* Customer subscription behavior
* Shipping method comparison
* Product ratings
* Customer purchasing patterns

The project can be implemented using **PostgreSQL, MySQL, or SQL Server**.

### 5. Power BI Dashboard

The analyzed data was connected to Power BI to create an interactive dashboard.

The dashboard includes:

* KPI cards
* Revenue and sales analysis
* Customer segmentation
* Product performance
* Purchase behavior
* Interactive filters and slicers
* Charts and visualizations

### 6. Report

A detailed project report was prepared covering:

* Business problem
* Dataset description
* Data cleaning process
* EDA findings
* SQL analysis
* Dashboard insights
* Key conclusions

### 7. Presentation

A professional presentation was created using **Gamma** to summarize the project, methodology, dashboard, and key business insights.

---

## 📊 Dashboard

The Power BI dashboard provides an interactive view of the analyzed data.

**Key areas covered:**

* Overall sales/revenue
* Customer demographics
* Product performance
* Purchase trends
* Subscription analysis
* Shipping preferences
* Customer ratings

> Add your Power BI dashboard screenshot here.

```text
![Power BI Dashboard](images/dashboard.png)
```

---

## 📈 Results & Key Insights

The analysis helped identify important patterns in customer behavior and sales performance.

Key outcomes include:

* Identified high-performing products and customer segments
* Compared purchasing behavior across different customer categories
* Analyzed revenue and purchase trends
* Evaluated the impact of discounts and subscriptions
* Compared different shipping methods
* Identified products with higher customer ratings
* Created an interactive dashboard for easier business decision-making

---

## ▶️ How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy
```

### Step 3: Run the Python Notebook

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run the EDA and data-cleaning notebook.

### Step 4: Set Up the Database

Import the cleaned dataset into your preferred database:

* PostgreSQL
* MySQL
* SQL Server

Then execute the SQL queries provided in the `SQL` folder.

### Step 5: Open the Power BI Dashboard

Open the `.pbix` file using Power BI Desktop and refresh the data connection if required.

### Step 6: View the Report & Presentation

The project report and Gamma presentation are available in their respective project folders.

---

## 📂 Project Structure

```text
Data-Analytics-Project/
│
├── Dataset/
│   └── dataset.csv
│
├── Python/
│   └── EDA_and_Cleaning.ipynb
│
├── SQL/
│   └── analysis_queries.sql
│
├── PowerBI/
│   └── dashboard.pbix
│
├── Report/
│   └── project_report.pdf
│
├── PPT/
│   └── project_presentation.pdf
│
├── Images/
│   └── dashboard.png
│
└── README.md
```

---

## 🎯 Conclusion

This project demonstrates an end-to-end **Data Analytics pipeline**, from raw data preparation and exploratory analysis to SQL-based business analysis, Power BI visualization, reporting, and presentation.

It showcases practical skills in **Python, SQL, Data Cleaning, EDA, Power BI, Data Visualization, and Business Intelligence**.

## 👤 Author

**Banti Kumar Singh**

* GitHub: `https://github.com/your-username`
* LinkedIn: `https://linkedin.com/in/your-profile`
