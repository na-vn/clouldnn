# 48 - Dynamo DB

#### Introduction

* Fully managed NoSQL database on AWS.
* Provides better performance and scalability 
* In DynamoDB you directly start working with tables. You dont need to install anything, configure anything it starts directly with the database.
* A table is a collection of items.
* Each item is a collection of attributes.
* JSON data.

#### Features

* There are 2 different types of primary keys that are supported. 
* Simple primary key - Partition key. Here the value of the attribute is sent to an internal hash function. The hash function decides where the physical storage of the item is stored
* Composite key - Partition and sort key. So if items are stored in the same partition, you can decide on another key which can be used to sort the items in the partition. 
* Read and write throughput - This is primary used to decide on the cost aspect for the table 
* Read Throughput represented as capacity units. One Read Capacity unit is one strongly consistent read request, or two eventually consistent read request for up to 4KB in size.
* Write Throughput - One write Capacity unit is one write for an item up to 1KB.

When not to use DynamoDB - if you're going to perform complex queries on data. If you want to perform table joins dont user DynamoDB.

* 


