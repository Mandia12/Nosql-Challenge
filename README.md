## Overview

This project focuses on importing and managing data within a MongoDB database using Python. The data, sourced from a JSON file, is imported into a MongoDB database called **"uk_food"** in a collection named **"establishments"**. The project includes various operations such as data retrieval, updates, deletions, and organization, all performed using PyMongo.

## Steps

1. **Data Import:**
   * The JSON file is imported into MongoDB using `mongosh`.
   * The data is stored in a new database named **"uk_food"** and within a collection called **"establishments"**.

2. **Data Manipulation with PyMongo:**
   * A Jupyter Notebook file (`.ipynb`) is used to interact with the MongoDB database.
   * The `pymongo` library is utilized to perform various operations, including accessing, updating, deleting, and organizing data within the collection.

3. **Exploratory Data Analysis:**
   * The file named **"NoSQL_Analysis"** contains queries that explore the database.
   * Some queries make use of MongoDB aggregation pipelines to retrieve specific data.
   * The retrieved data is then converted into Pandas DataFrames for further analysis and visualization.

## Tools

* **MongoDB** for NoSQL database management.
* **PyMongo** for interfacing with MongoDB using Python.
* **Pandas** for data manipulation and analysis within Python.
* **Jupyter Notebook** for running and documenting the analysis.

## How to Use

1. Clone this repository to your local machine.
2. Use `mongosh` to import the provided JSON file into a new MongoDB database.
3. Open the `.ipynb` file in Jupyter Notebook to perform the data manipulation and analysis tasks.
4. Explore the data using the queries provided in the **"NoSQL_Analysis"** notebook.
