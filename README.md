# Medallion-Architecture-with-PySpark
This project demonstrates the implementation of a Medallion Architecture on Microsoft Fabric using PySpark, based on a hands-on course activity from the DP-700 (Microsoft: Designing and Implementing a Data Platform) course.

Bronze Layer: Ingested raw retail data into the Lakehouse.

Silver Layer: Cleaned and transformed the data by removing duplicates and ensuring consistency.

Gold Layer: Built a star schema for analytical purposes, including:

Dimension tables: Date, Customer, Product

Fact table: Sales

The project showcases data cleansing, transformation, and dimensional modeling in Fabric, enabling downstream analytics and reporting.
