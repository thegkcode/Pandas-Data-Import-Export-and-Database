 <h1 align="center">Pandas Data Import, Export & Database Operations</h1>

<p align="center">
  <i>Exploring data handling, file operations, and database connectivity with Python Pandas.</i>
</p>


---

## 📌 Overview

This repository contains practical Jupyter Notebook sessions demonstrating how to work with different data sources and file formats using **Python and Pandas**.

It also explores retrieving data from MySQL databases, performing basic data operations, and exporting DataFrames into multiple formats.

## 📚 Notebooks & Topics Covered

### 📄 1. Working with CSV Files

**Notebook:** `working-with-csv.ipynb`

Topics covered:
- Reading local CSV files using `pd.read_csv()`
- Reading CSV files directly from URLs using Requests and StringIO
- Reading TSV and other delimited files using the `sep` parameter
- Using `index_col` and `header` parameters
- Selecting specific columns with `usecols`
- Converting a single-column DataFrame into a Series using `squeeze()`
- Skipping rows and limiting the number of rows with `skiprows` and `nrows`
- Handling different file encodings
- Skipping malformed lines using `on_bad_lines`
- Specifying column data types using `dtype`
- Parsing date columns using `parse_dates`
- Understanding the `converters` and `na_values` parameters
- Loading large datasets in chunks using `chunksize`

### 📊 2. Working with Excel & Text Files

**Notebook:** `working-with-excel.ipynb`

Topics covered:
- Reading Excel files using `pd.read_excel()`
- Accessing specific worksheets using `sheet_name`
- Setting an index column using `index_col`
- Importing tab-separated text files using `pd.read_csv()`

### 🔗 3. Working with JSON & MySQL Database

**Notebook:** `working-with-json-and-database.ipynb`

**🌐 JSON Operations**
- Reading JSON files using `pd.read_json()`
- Fetching JSON data directly from an API URL
- Loading JSON data into Pandas DataFrames

**🗄️ MySQL Database Operations**
- Connecting Python to MySQL using `mysql.connector`
- Reading SQL query results into Pandas DataFrames using `pd.read_sql_query()`
- Retrieving records from database tables
- Filtering records using SQL WHERE conditions
- Working with tables such as `country`, `city`, and `countrylanguage`

### 📤 4. Exporting Data using Pandas

**Notebook:** `pandas-data-export.ipynb`

**📄 Export to CSV**
- Exporting DataFrames using `to_csv()`
- Grouping IPL delivery data by batsman
- Creating pivot tables for batsman-wise and team-wise analysis

**📊 Export to Excel**
- Exporting DataFrames using `to_excel()`
- Creating Excel worksheets with custom sheet names
- Writing multiple DataFrames into separate sheets using `ExcelWriter`

**🌐 Export to HTML**
- Converting DataFrame analysis results into HTML tables using `to_html()`

**🔄 Export to JSON**
- Transforming grouped data using `groupby()` and `unstack()`
- Exporting processed data using `to_json()`

**🗄️ Export to MySQL**
- Connecting to MySQL using PyMySQL and SQLAlchemy
- Exporting Pandas DataFrames to MySQL tables using `to_sql()`
- Working with the `if_exists` parameter

## 🛠️ Technologies & Libraries

| Technology | Purpose |
|---|---|
| 🐍 Python | Programming language |
| 🐼 Pandas | Data manipulation and file operations |
| 🌐 Requests | Fetching data from URLs |
| 📓 Jupyter Notebook | Interactive coding environment |
| 🗄️ MySQL | Database operations |
| 🔌 mysql-connector-python | Python-MySQL connectivity |
| 🔗 PyMySQL | MySQL database connectivity |
| ⚙️ SQLAlchemy | Database integration |

## 🎯 Learning Objectives

Through these practice sessions, the repository demonstrates foundational skills in:

- 📂 Reading data from multiple file formats
- 🔍 Understanding and using Pandas read functions
- 🧹 Handling different data types and file encodings
- 🔄 Working with structured and semi-structured data
- 🗄️ Performing basic SQL queries through Python
- 📤 Transforming and exporting DataFrames
- 🔗 Connecting Python applications with MySQL databases

---

## 👨‍💻 About Me

<p align="center">
  <b>Gaurav Kumar</b><br/>
  Computer Science Undergraduate | Aspiring Data Analyst<br/><br/>
  <a href="https://github.com/thegkcode">
    <img src="https://img.shields.io/badge/GitHub-thegkcode-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <i>“Every dataset has a story to tell — the right tools help uncover it.”</i> ✨
</p>
