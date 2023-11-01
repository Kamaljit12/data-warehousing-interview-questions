# Data WareHousign Interview Questions
# 1. What is a Data Warehouse?
A data warehouse is a large store of data collected from a wide range
of sources within a company and used to guide management
decisions. It is subject-oriented, integrated, time-variant, and
non-volatile collection of data.
# 2. What is Data Modelling?
Data modelling is the process of creating a data model for the data to
be stored in a database. It visually represents data objects, the
associations between different data objects, and the rules governing
these associations.
# 3. What are the types of Data Models?
There are mainly three types of data models: Conceptual, Logical, and
Physical. The Conceptual Model defines WHAT the system contains.
The Logical Model defines WHAT the system does, and the Physical
Model defines HOW the system performs.
# 4. What is the difference between a Database and a Data Warehouse?
A Database is a collection of related data organized in a structured
way. It is designed to handle transactions and enables real-time
processing. On the other hand, a data warehouse is designed for
analysis and query processing and is intended to support decision
making. It contains historical data derived from transaction data but can
include data from other sources.
# 5. What are Fact Tables and Dimension Tables in a Data Warehouse?
Fact tables store quantitative information for analysis and are often
de-normalized. It contains foreign keys referring to candidate keys in
Dimension tables. Dimension tables store dimensions of a fact, such as
product, location, time, etc., and are often denormalized.
# 6. What is ETL?
ETL stands for Extract, Transform, Load. It's a process of extracting
data from source systems, transforming it into a format that can be
analyzed, and then loading it into a data warehouse or similar system.
# 7. What is a Star Schema?
Star schema is a relational schema whose design represents a
multidimensional data model. The star schema consists of one or more
fact tables referencing any number of dimension tables. The star
schema gets its name from the physical model's resemblance to a star
shape with a fact table in the middle and the dimension tables
surrounding it representing the star's points.
Grow Data Skil s
# 8. What is a Snowflake Schema?
Snowflake schema is a variant of the star schema model, where some
dimension tables are normalized, thereby further splitting the data into
additional tables. This reduces data redundancy, but at the cost of
more complex queries and reduced query performance.
# 9. What is a Surrogate Key?
A Surrogate Key is a substitution for the natural primary key. It is a
unique identifier for each record in a table. It is beneficial because it is
simple, stable, and allows changes to natural keys.
# 10.What is OLTP vs OLAP?
OLTP (Online Transactional Processing) is a system that manages
transaction-based applications in the real-time scenario that can be
used for online database modifying operations. OLAP (Online
Analytical Processing) is a system designed for analysis of business
data for strategic decision-making.
# 11. What is a Data Mart?
A Data Mart is a subset of a data warehouse that relates to specific
business line. Data marts are managed by a specific department within
an organization.
# 12.What is a Normalization?
Normalization is the process of organizing data to minimize
redundancy. It usually divides a database into two or more tables and
defines relationships between the tables.
# 13.What is De-normalization?
Denormalization is the process of adding redundancy to speed up
complex queries involving multiple table joins. It is used in the data
warehouse to simplify the complex queries and enhance the
performance of data fetching.
# 14.What is ER Diagram?
ER Diagram or Entity-Relationship Diagram is a visual representation
of entities and relationships. It describes how data is related to each
other. In ER Modeling, the database structure is represented
graphically.
# 15.What is a Fact Constellation Schema?
Grow Data Skil s
Fact Constellation Schema or Galaxy Schema is a model that consists
of multiple fact tables sharing dimension tables, viewed as a collection
of stars.
# 16.What is Data Mining?
Data Mining is a process to extract information from a data set and
transform it into a comprehensible structure for further use.
# 17.What is a Slowly Changing Dimension (SCD)?
Slowly Changing Dimensions (SCDs) are dimensions in which data
changes slowly, rather than changing on a time-based, regular
schedule.
# 18.What are the types of SCDs?
There are three types of SCDs, defined as SCD Type 1 (overwrite),
SCD Type 2 (history), and SCD Type 3 (new column).
# 19.What is a Factless Fact Table?
Factless Fact Table is a fact table that does not have any measures. It
is essentially an intersection of dimensions (it contains nothing but
dimensional keys).
# 20.What is Dimensional Modelling?
Dimensional Modeling (DM) is a data structure technique optimized for
Data Warehousing tools. The concept of DM is to have a table in a
center surrounded by several other lookup tables each joined by a
foreign key. It provides a way to improve query performance in
relational databases.
