# 81 - AWS CodeDeploy

#### Quick Understanding

* Deployment service used in AWS
* Used to automate deployments 
* You can automate deployments to Amazon EC2 Instances, On Premise instances, Lambda function or Amazon ECS Services

![](../../../.gitbook/assets/image%20%2866%29.png)

You can deploy code from S3 buckets, Github Repo, Bitbucket repo and deploy them in CodeDeploy over to EC2 instance, Lambda function or on prem servers.

#### Deployment workflow for an AWS Lambda function deployment

Step 1

* Create service role - 
* For AWS Lambda you choose the AWSCodeDeployRoleforLambda policy
* Create application
* For the application you need to specify that you want to deploy to Lambda 

Step 2

* Create deployment group
* Type Deployment. 
* All-at-once - All traffic is diverted to the new lambda function
* Linear deployment - The traffic is shifted in equal increments in terms of minutes. 
* Canary - Traffic is shifted every 2 increments.

Step 3

* Create deployment 
* Specify the deployment details









