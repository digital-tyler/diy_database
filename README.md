# diy_database

### Building a DIY database to store and analyze a sample dataset (dvd rentals). We will be using a local postgresql database, and then importing a sample dataset consisting of 15 tables. Then, we will import this data into Jupyter notebook to query with SQL and produce summary statistics with Python and data science packages.

#### This repo focuses leveraging a database from scractch - key components of this exercise are as follows: 
* Install and implement PostgreSQL, an open-source relational database management system (RDMS) locally on my machine
  * Import sample database, dealing with fictional DVD rental data
* Establish a virtual environment - this ensures that my analysis could be reproduced by any observer, without any assumption of pre-installed software or modules not explicitly installed in my repo
* Connect PostgreSQL with Jupyter Notebooks on my local machine, for querying and analyzing the database. There are three key tasks here:
  * Leverage SQL to extract, manipulate, and aanalyze the data from the database. A rudimentary forecast using simple regression is also performed, to estimate future DVD rental volume
  * __(WIP)__Leverage Python for statistical analysis and graphical representation of the data. The simple regression analysis is recreated, along with an examination of whether our simple regression analysis is sophisticated enough to capture the behavior of our data

#### There are a few key files in this repo that will be useful for recreating this analysis on a clean installation of macOS:
* database_sample_data.ipynb: The theme of this notebook is SQL; the following are the main sections of this file:
  * Setting up a SQL connection within Jupyter Notebook for querying our DVD database
  * Using SQL to get a feel for the data availble in our 15-table database
  * Using SQL to create a simple regression model, consisting of historical data and calculated slope / trend data
  * A forecast for the next 6 months, based on our historical dataset - we use SQL here, although a language pike Python will undoubtedly be easier to produce forecasts
* Python file: coming soon!