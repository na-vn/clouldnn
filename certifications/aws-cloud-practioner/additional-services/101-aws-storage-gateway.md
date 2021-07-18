# 101 - AWS Storage Gateway

#### What is AWS Storage Gateway 

* This service helps to connect on premise software appliance to cloud based storage
* This helps to scale your storage with the use of AWS Cloud

So if a company has a application hosted in the datacenter which now needs more storage, they can use AWS Storage gateway to extend their storage for the application which will be hosted on the cloud. ☁️ 

* File Gateway - This provides File interface into Amazon S3 service
* Volume Gateway - This allows you to mount cloud based storage volumes using Internet Small Computer system interface iSCSI  
* Tape Gateway - This provides cloud based virtual tape storage 

![](../../../.gitbook/assets/image%20%2878%29.png)

* To use the File Gateway you need to download the VM image for the file gateway
* Then you need to activate the file gateway
* Once the gateway is activated you can create and configure the file shares that are linked to the S3 service
* The file shares can be accessed via the NFS or SMB protocol 

![](../../../.gitbook/assets/image%20%2877%29.png)

* Here you can used either cached or stored volumes 
* With cached volumes the S3 is used as the primary data store 
* The frequently accessed data is cached locally on the storage gateway 
* With stored volume, the primary data is stored locally 
* The data is then backed up onto AWS

#### Understanding Tape Gateway

* Provides durable, cost effective solution for archiving in AWS
* Here you can used virtual tape library to store data on virtual tape 
* The tape gateway is already preconfigured with media changer and tape drives 



