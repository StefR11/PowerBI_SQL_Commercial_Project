# PowerBI_SQL_Commercial_Project
Power BI / SQL Server Project
Within this manged project, I imagined that I have just been hired as a BI Analyst by a multi-national grocery chain with locations in Canada, Mexico and the US. I worked through the entire BI workflow from connecting the raw CSV files,  shaping the data, building a relational model, creating calculated columns and measures with DAX to finally designing an interactive report to visualise data. At first, this was supposed to be a Power BI project, thereafter I enjoyed writing DDL, DML & DQL queries by using MS SQL Server in order to match the Power BI data cleansing & shaping as well as DAX and make the project more exhaustive. 
I have attached to this project all of the Power BI and SQL screenshots including the visual reporting  and relevant visual transcript in details.
The relational Database named Commercial Project is composed of the Transaction_data and Return_data which are the fact tables and are linked on a STAR-schema basis to the following dimension tables: Stores, Customers, Products, Calendar.
The Relationships in the STAR SCHEMA  follow one-to-many cardinality with PK on the lookup (dimension) side and FK on the data (fact) side. Filters are all one way and filter context follows downstream from lookup tables to data tables. Data tables are connected via shared lookup tables. There is also the lookup table REGIONS which is not connected to any of the data tables, therefore I referenced it to the lookup table STORES on a SNOWFLAKE SCHEMA basis. 
With regards to building the report , I have created 9 dashboards where I introduced visualisation best practices, and explored powerful features like bookmarks, parameters, tooltips and so on. The type of data I have worked with is mainly geospatial, hierarchical and time-series data with the end users of the visual reporting to be the analyst, manager and executive. 
The goals that I have set up for the dashboards are tracking KPI’s (Revenue, Profit, Transactions and Returns), comparing regional performance, analysing product-level trends and identifying high-value customers. As for AI topics I decided to cover two of my favourite ones i.e. decomposition trees for data exploration & root causes analysis and key influencer visuals to identity the factors that drive specific outcomes for the business. 



