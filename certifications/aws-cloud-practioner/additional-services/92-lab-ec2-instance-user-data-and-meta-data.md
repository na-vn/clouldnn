# 92 - Lab - EC2 Instance - User Data and Meta Data

#### Quick Understanding 

* What is Instance meta data
* What is Instance user data
* How to work with meta data and user data 

#### What is Instance meta data

* The data is about the instance
* You can run commands on the EC2 instance to get data on the instance
* The data is is available on a local service that runs on http://169.254.169.254/

#### What is Instance user data

* The user data for an EC2 instance can be used to run scripts on an EC2 instance when it is first launched. 
* You can pass either shell scripts or cloud-init directives 

![](../../../.gitbook/assets/image%20%2870%29.png)

When creating a EC2 instance at the bottom you can see where its listed User. What this field will do is that it will allow you to run a script or install whatever you're wanting upon startup.







