# customer_behaviour_analysis



## 🧭 Overview
This project demonstrates a complete **data analysis workflow** — from loading raw data in Python to building an interactive dashboard in Power BI.
The goal is to extract meaningful insights from the dataset through data cleaning, exploratory data analysis (EDA), SQL querying, and visualization.

---

## 🗂️ Dataset

* **Name:** Customer Shopping Behaviour Dataset
* **Size:** ~3,900 rows, 18 columns 

---

## 🧰 Tools & Technologies Used

* **Python** – Data loading, cleaning, and exploratory analysis
* **Pandas – Data manipulation and transformation
* **MySQL** – Querying and structured data analysis
* **Power BI** – Dashboard creation and visualization
* **Jupyter Notebook (VS Code)** – Development environment
* **Git & GitHub** – Version control and collaboration

---

## ⚙️ Project Steps

### 1. **Data Loading**

* Imported the dataset into Python using `pandas.read_csv()`.
* Performed initial inspection (`df.info()`, `df.describe()`, `df.head()`).

### 2. **Data Cleaning**

* Handled missing values and removed duplicates.
* Standardized column names and corrected data types.
* Treated outliers and inconsistent records.

### 3. **Exploratory Data Analysis (EDA)**

* Generated summary statistics and visualized distributions.
* Analyzed customer demographics, purchase patterns, and product trends.
* Identified key insights using charts (bar plots, heatmaps, etc.).

### 4. **SQL Integration**

* Loaded the cleaned dataset into **MySQL** using SQLAlchemy.
* Performed SQL queries for deeper business insights.
* Example:

  ```sql
  SELECT Gender, COUNT(*) AS Customers
  FROM customer_behavior
  GROUP BY Gender;
  ```

### 5. **Dashboard Creation**

* Imported the processed dataset into **Power BI**.
* Built interactive visuals showing:

  * Sales by region and gender
  * Product-wise performance
  * Year-over-year customer trends
  * Top contributing categories

### 6. **Business Insights**
Clothing category contributes the most to revenue and number of customers across all age groups.
Senior customers, though fewer in number, are the second-highest contributors to revenue.
Subscribed customers contribute only 27% of total revenue, their average purchase amount is similar to that of non-subscribed customers.

---

## 📈 Power BI Dashboard
![Dashboard Preview](https://github.com/Kartik565/CUSTOMER-BEHAVIOR-ANALYSIS/blob/main/Customer_behaviour_dashboard_ss.png)

---

