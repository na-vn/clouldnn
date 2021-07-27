# 109 - AWS Snowball devices

#### What is AWS Snowball devices

* You can use AWS Snowball service to transfer data between physical storage devices and Amazon Simple storage service
* A Snowball device is used to transfer large amounts of data 
* It should be the prefered choice if data is being transferred over 10TB of data
* Snowball devices are physical devices
* Ruggered in nature 
* They are protected by the AWS KMS, This helps to protect the data in transit 
* The company does not need to buy or maintain their own hardware devices
* Snowball device is its own shipping container 
* With the Snowball device you can import and export data into Amazon S3
* Snowball edge you get durable local storage, local compute with AWS Lambda, you can use with cluster of devices 

#### How does this process work?

* Create a job in Snowball family management console
* The Snowball device is then sent to the customer 
* Data is then transfered to the snowball device
* Then ship the container back to AWS
* AWS will transfer the data on to Amazon S3 



