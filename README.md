# Smart Logistics and Supply Chain Analytics using Apache Spark

## Project Overview

This project implements a **Smart Logistics and Supply Chain Analytics System** using **Apache Spark (PySpark)**. The objective is to analyze logistics data, perform data processing, generate business insights, and build a simple machine learning model to predict shipment delivery status.

The project demonstrates the use of Apache Spark for handling large datasets efficiently through RDDs, DataFrames, Spark SQL, ETL operations, and Spark MLlib.

---

## Objectives

* Initialize Apache Spark and load logistics datasets.
* Perform RDD transformations and actions.
* Implement Key-Value operations and persistence.
* Perform DataFrame operations such as filtering, grouping, joining, and aggregation.
* Perform Exploratory Data Analysis (EDA) using Spark SQL.
* Develop a simple ETL pipeline.
* Build and evaluate a Machine Learning model using Spark MLlib.

---

## Technologies Used

* Apache Spark
* PySpark
* Python
* Jupyter Notebook
* Spark SQL
* Spark MLlib

---

## Dataset Used

The project uses the following datasets:

* shipments.csv
* warehouse.csv
* gps_tracking.csv
* fuel.csv
* customers.csv

---

## Project Structure

```text
Smart_Logistics_Project/
│
├── Smart_Logistics_Apache_Spark_Q1_Q7.ipynb
├── datasets/
│   ├── shipments.csv
│   ├── warehouse.csv
│   ├── gps_tracking.csv
│   ├── fuel.csv
│   └── customers.csv
├── outputs/
├── README.md
```

---

## Implementation

### Q1 – Spark Initialization and Data Loading

* Create Spark Session
* Load all datasets
* Display schema and sample records

### Q2 – RDD Implementation

* Create RDD
* Apply Transformations
* Apply Actions

### Q3 – Key-Value Operations

* Pair RDD
* reduceByKey()
* sortByKey()
* Persistence using cache()

### Q4 – DataFrame Operations

* Filtering
* Grouping
* Aggregation
* Joins

### Q5 – Exploratory Data Analysis

* Regional shipment analysis
* Shipment status analysis
* Average shipment weight
* Spark SQL queries

### Q6 – ETL Pipeline

* Remove duplicate records
* Remove null values
* Convert date columns
* Rename columns
* Save cleaned dataset

### Q7 – Machine Learning

* Decision Tree Classifier
* Train-Test Split
* Prediction
* Accuracy Evaluation
* F1 Score Evaluation

---

## Machine Learning Evaluation Metrics

The model performance is evaluated using:

* Accuracy
* F1 Score

---

## How to Run

1. Install Apache Spark and Python.
2. Install PySpark.
3. Place all CSV files in the project directory.
4. Open the Jupyter Notebook.
5. Run all cells sequentially.

---

## Expected Output

The project generates:

* Cleaned logistics dataset
* Regional shipment reports
* Delivery status analysis
* Warehouse analysis
* ETL output dataset
* Machine Learning predictions
* Accuracy and F1 Score

---

## Learning Outcomes

After completing this project, the following Apache Spark concepts are demonstrated:

* Spark Session
* RDD Operations
* Transformations and Actions
* Pair RDD
* Persistence
* Spark DataFrames
* Spark SQL
* ETL Pipeline
* Spark MLlib
* Model Evaluation

---

## Future Improvements

* Real-time shipment tracking using Spark Streaming.
* Interactive dashboards using Power BI or Tableau.
* Route optimization using advanced machine learning algorithms.
* Cloud deployment using AWS or Azure.

---

## Author

**Name:** *Your Name*

**Course:** PGCP – Artificial Intelligence

**Subject:** Apache Spark

**Institution:** *Your College Name*
