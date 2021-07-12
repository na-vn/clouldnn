# 79 - Lab - AWS Redshift

#### Quick Understanding

* When using Redshift, you have to create a cluster first.
* In the Cluster there will be a Leader Node and Compute node. 
* The leader node will be taking all queries and then is tasked to pass those to the compute nodes.
* The compute nodes are the ones that process information in parallel. 

![](../../../.gitbook/assets/image%20%2857%29.png)

#### Query Editor

* Inbuilt query editor - inline editor - Size of the node needs to be the following - DC1.8xlarge, DC2.large, DC2.8xlarge, 
* You can download SQL workbench but when using you need to have Java installed. Also need Redshift JDBC driver 

When creating in the management console, you need to create the cluster which then tells you to name the cluster, DB name, master username and password. Then it will ask you to fill in the node details, You can choose if it has encryption, VPC name, Subnet group, security group and create cloudwatch alarms. SQL workbench then needs to be installed then the Redshift JDBC driver installed also. Once thats installed, you can launch SQL workbench and enter in the DB name, Drivers, username and password and test the connection. If the connection fails have a look at the security group that the cluster is in and ensure that all traffic is allow inbound. 

![](../../../.gitbook/assets/image%20%2858%29.png)

If you want to query a file from a bucket follow the steps below

* Create bucket
* Upload file into bucket
* Change the permission on the bucket as its defaulted as blocked.
* Go onto the file, mark the file as public
* Then go onto bucket policy, Policy generator, Change to S3 bucket policy, principle as \*, tick on all the actions then add ARN name, Add statement. 
* Then copy the code into bucket policy and select save. This will allow redshift to connect to the bucket. 
* You also need to ensure that the IAM role Redshift is allocated in the cluster for it to have access. 



