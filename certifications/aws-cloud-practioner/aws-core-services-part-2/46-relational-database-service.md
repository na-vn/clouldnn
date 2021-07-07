# 46 - Relational Database Service

#### Introduction

* Allows you to setup relational database in AWS.
* Has support for MYSQL, Oracle, MariaDB, PostrgeSQL and Microsoft SQL server.
* A lot of administrative jobs are managed by AWS

Normally you would spin up an EC2 instance, install the database of your choice MYSQL then you would need to configure MYSQL. With RDS with the help of the wizard, it will deploy the MYSQL solution for you. 

#### Features

* Scale the underlying instance hosting the database instance at anytime.
* Monitoring aspects such as Cloudwatch are in place.
* Enable automatic backups.
* You can create snapshots of your database at anytime.
* Enable high availbility of your database using Multi A-Z feature which means that when its enabled, one of your database is hosed in one availability zone gets copied to a secondary database in another availability zone. If one database fails it will failover to the second. 





