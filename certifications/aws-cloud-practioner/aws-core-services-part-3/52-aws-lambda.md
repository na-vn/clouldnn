# 52 - AWS Lambda

#### Understanding

* Serverless compute service in AWS.
* Here you wont need to maintain infrastructure. 
* Supports host of programming such as Go, Node.js, Python, Ruby, Java and .Net.

An organisation which has a script that needs to be hosted on a server normally would spin up a EC2 instance, install the OS and have the script which sits on the server. This can cost alot as you'll need to be paying for the EC2 instance and also manage the security patches on the OS level. Instead you can deploy the code onto Lambda service which the infrastructure is managed FOR you. You'll need to just deploy the code, run the code whenever you want and be charged for only when you use your code.

Things to consider

* this is managed by AWS. So you can't log on to a server to look at your code.
* Maximum memory that can be utulized is 3GB.
* There is a timeout function which is maximum of 15 minutes.





