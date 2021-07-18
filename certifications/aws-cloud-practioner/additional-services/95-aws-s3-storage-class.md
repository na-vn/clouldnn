# 95 - AWS S3 Storage class

#### Quick Understanding 

* The Amazon S3 Standard Storage Class
* The Amazon S3 Intelligent Tiering Class
* The Amazon S3 Standard-Infrequent Access
* The Amazon S3 Zone-Infrequent Access 
* About S3 Glacier 

#### The Amazon S3 Standard Storage Class

* This is the default storage class assigned to an object
* This is the ideal storage class for objects that are accessed frequently 
* It delivers low latency and high throughput 
* It is resilient against events that could affect an entire Availability zone
* It is secure - Has support for SSL of data in transit and at rest

#### The Amazon S3 Intelligent Tiering Class

* Here AWS S3 will move data to the most cost effective tier 
* This will be based on Amazon S3 monitoring the access patterns for an object 
* There is no performance impact or operational overhead
* This is ideal when there is unpredicted access patterns for you data 

#### The Amazon S3 Standard-Infrequent Access

* This is ideal for data to be accessed infrequently 
* This type of storage is ideal for data requirements  such as long term storage and backups.
* It delivers low latency and high throughput 
* It is resilient against events that affect the entire Availability zone 
* It is secure - Has support for SSL of data in transit and at rest.
* But there is a small retrieval fee for the data. Hence this is ideal for data that is not accessed frequently 

#### The Amazon S3 Zone-Infrequent Access

* Here the difference is that the data is stored in one Availability zone 
* Hence the data storage cost are less than the Amazon S3 Standard-Infrequent access 
* Ideal again for use case of storing secondary backup copies of your data.
* You will be charged for the retrival of your data 

#### Amazon S3 Glacier

* This is a low-cost storage option that is designed for data archiving 
* There service is built for high availability and durability 
* Data cost are much lower
* Retrieve data can take time 
* Data retrieve can take minutes to hours.

![](../../../.gitbook/assets/image%20%2879%29.png)













