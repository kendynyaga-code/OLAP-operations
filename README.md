Kendi Nyaga - 807

Data Warehouse Project

📌 Project Overview

This project demonstrates the process of building a **basic data warehouse system** using **Python, Pandas, and SQLite**.
The goal is to showcase the key concepts of data warehousing, including:

* Storing structured data in a relational database (SQLite).
* Extracting and transforming data using Python and Pandas.
* Loading data into database tables.
* Performing exploratory data analysis (EDA).
* Visualizing trends using Matplotlib and Seaborn.

This notebook acts as a simple prototype for understanding **ETL (Extract, Transform, Load) processes** in a data warehouse environment.

 🎯 Learning Objectives

By the end of this project, you should be able to:

1. Understand how a data warehouse can be created with lightweight tools.
2. Establish a connection to a relational database using Python.
3. Store and retrieve tabular data in SQL tables.
4. Perform descriptive analysis and identify missing values.
5. Visualize data to derive insights.

 ⚙️ Tools & Libraries

* **Python 3.10+**
* **SQLite3** – lightweight relational database used as the warehouse.
* **Pandas** – for handling structured datasets and transforming them.
* **Matplotlib & Seaborn** – for data visualization.
* **NumPy** – numerical computing.
* **Datetime** – working with timestamps.

 🗂️ Project Structure

```
Data warehouse.ipynb   # Main Jupyter Notebook (contains all code and analysis)
data_warehouse.db      # SQLite database file generated during execution
README.md              # Documentation file (this file)
```
 🛠️ Installation & Setup

1. Install required libraries:

   ```bash
   pip install pandas matplotlib seaborn numpy
   ```

2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook "Data warehouse.ipynb"
   ```

3. Run the notebook cells step by step.

 🔄 Workflow Description

1. **Database Setup**

   * Connect to SQLite (`data_warehouse.db`).
   * Create helper functions for executing queries and fetching data.

2. **Data Preparation**

   * Build a sample employee dataset with columns:

     * `id` (unique identifier)
     * `name` (employee name)
     * `age` (employee age)
     * `salary` (monthly salary)
   * Load the dataset into the warehouse as the `employees` table.

3. **Exploratory Data Analysis**

   * Use Pandas to display dataset head, summary statistics, and missing values.
   * Provide insights about the dataset.

4. **Visualization**

   * Generate bar charts to show employee salary distribution.
   * Other options: line plots or scatter plots for comparisons.

 📊 Sample Output

Example results from running the notebook:

* **Database Table:**

  ```
  (1, 'Alice', 24, 50000)
  (2, 'Bob', 30, 60000)
  (3, 'Charlie', 22, 55000)
  (4, 'David', 35, 70000)
  (5, 'Eva', 28, 65000)
  ```

* **Summary Statistics:**

  ```
  count       5.000000
  mean       28.000000
  std         4.690416
  min        22.000000
  max        35.000000
