# Just a collection of resources I made or found that I may have to keep referring back to.

I try to put in references/links/citations and whatnots where possible.

## Database-related Things
#### PGSQL Things
I made these for my [SQL project with Lighthouse Labs](https://github.com/kangelamw/Ang-SQL-Project).

> *I like them, someone else might, too.*

To better understand the data at a glance, I created the following User-Defined Functions (UDFs):
  1. [`overview_of_each_column('tablename')`](./dbs/PGSQL/udfs/overview_of_each_column.md)
      - It takes in a table and for each column, shows the count/total number of rows, null values and distinct values.
      - It helps in identifying which columns to use in a table.
  2. [`numbers_summary('tablename')`](./dbs/PGSQL/udfs/numbers_summary.md)
      - It takes in a table and for each numeric column it finds, it shows the five number summary of the column.
      - The **<u>Five Number Summary</u>** gives us an overview of the variability in the data. This function calculates for the MIN, MAX, AVG, Quartiles 1 (25th percentile), 2(median) and 3(75th percentile), and the Interquartile Range (Q3-Q1)

#### ERD for these [Popular DBs](./dbs/common_erds.md), which I made myself using Canva.
- Northwind DB
- Chinook DB

#### One-offs...
- [Crows Foot Notation](./dbs/crows_foot_notations.md)

## Math things
#### I had ChatGPT give me these [Math Symbols](./maths/symbols.md) and what they're for.
- General Symbols
- Linear Algebra Notations
- Statistics and Probability Symbols
- Greek Letters Used Frequently
- Summation and Calculus Notations

### One-offs...
- [Variability](./img/VARIABILITY.png)

## Machine Learning things
- [What is Machine Learning?](./machine_learning/as_defined_by_MIT.md)
- Machine Learning [etc.](./machine_learning/machine_learning_etc.md)