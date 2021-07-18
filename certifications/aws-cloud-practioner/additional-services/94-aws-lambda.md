# 94 - AWS Lambda

#### Quick Understanding 

* This is a serverless compute service 
* You can go an run code without the need to provision or manage the underlying infrastructure 
* Also you can pay for the compute time you use.
* It supports a number of runtimes Node.js, Python, Ruby, Java, .Net and Go
*  The underlying service will automatically scale the infrastructure based on demand

![](../../../.gitbook/assets/image%20%2874%29.png)

Here an organisation is using S3 service and has unprocessed videos stored inside the bucket. What we can do is have an event trigger the Lambda function to run its code which can process the videos into another S3 bucket. 



