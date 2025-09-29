# BigDataAnalytics

A curated collection of **PySpark notebooks and examples** demonstrating common Big Data transformations and analytics workflows using Spark.

## Overview

This repository provides **hands-on examples and exercises** focusing on using **PySpark RDDs** and **DataFrames** to effectively explore, transform, and analyze large datasets. The primary goal is to help learners understand how to use Apache Spark for core data processing tasks, including data inspection, sampling, and fundamental analytics.

---

## Contents

The notebooks are ordered to follow a progressive learning path:

| # | Notebook Title | Key Concepts Demonstrated |
| :---: | :--- | :--- |
| **1** | **DataTransformation Using PySpark RDD** | Basic RDD transformations (`map`, `filter`, `flatMap`). |
| **2** | **Collect() Operation with RDD** | Understanding the `collect()` action, its use cases, and the critical implications for memory usage. |
| **3** | **Sample() and takeSample() Methods** | Illustrates different techniques for sampling data from RDDs using `sample()` and `takeSample()`. |
| **4** | **Exploring Structure And Contents of CSV File** | Loading CSV data (as RDD or DataFrame), inspecting schema, headers, and basic metadata. |
| **5** | **Viewing Data And Selecting Columns** | Demonstrates selecting specific columns, filtering rows, and viewing sample content using DataFrames. |
| **6** | **Analytical Operations on CSV File** | Performing core DataFrame operations: aggregations, `groupBy`, filtering, and simple statistical computations. |
| **7** | **Salary Data Analysis Case Study** | A practical case study using a small salary dataset to perform real-world analysis (e.g., computing average salary, grouping by department/role). |

---

## Learning Outcomes

By working through these examples, you will be able to:

* Gain **Familiarity** with basic **RDD transformations** and **actions**.
* Understand when to use **`collect()`** and the implications of data size.
* Develop the ability to **sample large datasets** efficiently.
* Acquire skills to **inspect and manipulate CSV data** with Spark DataFrames.
* Gain **Experience** performing essential **aggregations, filtering, and basic analytics**.
* Apply analytics logic to a small **real-world dataset** (salary data).

---

## Requirements & Setup

To run these notebooks locally, you'll need the following:

### Requirements

* **Python 3.x**
* **PySpark**
* **Jupyter Notebook** (Highly recommended for interactive exploration)
