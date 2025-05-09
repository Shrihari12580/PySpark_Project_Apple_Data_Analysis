# PYSPARK END TO END PROJECT FOR APPLE DATA ANALYSIS

# Description :

This project utilizes Apache Spark with PySpark on Databricks to build a real-world end-to-end data engineering solution.  In order to detect particular purchase behaviors, such as acknowledging customers who buy AirPods right away after buying an iPhone or those who only buy iPhones and AirPods, it focuses on studying customer transaction data related to Apple products.
 The project uses the Factory Design Pattern to build ETL pipelines with modular code.  It consists of using PySpark for data transformation and analysis, broadcast joins, repartitioning, and predicate pushdown for performance improvement, and Delta Lake for data storage.


# Factory Design Pattern :

Python's Factory Design Pattern is a creational design pattern that focuses object creation logic in a single location known as a factory. The client code requests the factory to generate an object based on input or context rather than implementing constructors to instantiate classes directly. this approach improves system flexibility and maintainability. 
This usually involves creating a base class or interface in Python, implementing multiple concrete subclasses, and then implementing a factory class or method that, based on the input, returns instances of those subclasses. When the exact kind of object to be created depends on configuration or dynamic circumstances, this pattern can be extremely helpful.

# Key Features :

•	Platform Specifications : Databricks Community Edition

•	Framework/Language : PySpark , Python

•	Design : Factory Design Pattern-based modular ETL
