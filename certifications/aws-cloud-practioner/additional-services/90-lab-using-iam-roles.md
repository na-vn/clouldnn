# 90 - Lab - Using IAM Roles

#### Quick Understanding 

* IAM Roles is actually an identity in IAM that is created within your AWS account 
* IAM Role has specific permissions
* IAM Role is not associated with a person
* It does not have any long term credentials such as password associated with it
* You can assume a role
* When you assume a role, temporary security credentials are assigned for the role session

#### Some Terms and Concepts

* AWS Service Role - Here the role is allowed to perform actions in the account on your behalf. You can go ahead and use the role to access the desired service 
* AWS Service Role for EC2 Instance - This is a special Role that can be assigned to an EC2 instance. This Role allows the EC2 instance to access other services in AWS
* AWS Service-linked Role - This Role is used by AWS services to access other AWS services
* Cross Account Access - This allows access to resources in one account to a trusted principle in a different account

When you want to connect to the S3 bucket from an EC2 instance using CLI, you will need to create the IAM role which has access to S3 permissions then plug it into the EC2 instance as the IAM role. 





