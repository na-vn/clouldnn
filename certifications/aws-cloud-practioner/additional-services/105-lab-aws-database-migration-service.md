# 105 - Lab - AWS Database migration service

#### Quick Understanding 

* This is a cloud service that helps migrate data between relational databases, data warehouse, NoSQL data stores and other data stores as well
* You can also use data stores on your on premise data centers
* You can perform on going replications, in addition to one time migrations 
* It has supports for source data stores such as Oracle, MicrosoftSQL Server, MYSQL, MariaDB, Azure SQL Database.
* It has support for target data stores such as Oracle, MicrosoftSQL Server, MYSQL, Amazon RDS Instance, Amazon DynamoDB

![](../../../.gitbook/assets/image%20%2881%29.png)

When creating an EC2 having MSSQL on it and having a table with rows in it. You're wanting to migrate it over to Amazon RDS using the AWS DMS you will need to have a replication instance. When using the DMS, it will need the source endpoint, replication instance and target endpoint. 





