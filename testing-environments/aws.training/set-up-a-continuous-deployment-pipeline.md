---
description: >-
  Amazon Elastic Container Service (Amazon ECS) is the Amazon Web Service you
  use to run Docker applications on a scalable cluster. In this tutorial, you
  will learn how to run a Docker-enabled sample ap
---

# Set up a Continuous Deployment Pipeline



[https://aws.amazon.com/getting-started/hands-on/continuous-deployment-pipeline/](https://aws.amazon.com/getting-started/hands-on/continuous-deployment-pipeline/)

We need to create Amazon ECS service first. Open up console and navigate to ECS.Click on create ECR,To simplify the process of setting up and configuring EC2 instances for this tutorial, you will spin up a sample environment using AWS Elastic Beanstalk. Elastic Beanstalk lets you easily host web applications without needing to launch, configure, or operate virtual servers on your own. It automatically provisions and operates the infrastructure \(e.g. virtual servers, load balancers, etc.\) and provides the application stack \(e.g. OS, language and framework, web and application server, etc.\) for you.

f you have created an Elastic Beanstalk application before, click: **Create New Application** on the upper-right corner. Name your application and create a new web server environment. Select PHP as your platform and Single Instance as your environment type. If you are planning to remote login to your instances, select a key pair. Otherwise, leave default values for the remaining options and create the environment for your continuous deployment pipeline

![](../../.gitbook/assets/screenshot-from-2020-11-08-23-28-27.png)

![](../../.gitbook/assets/screenshot-from-2020-11-08-23-28-27%20%281%29.png)

Elastic Beanstalk will begin creating a sample environment

![](../../.gitbook/assets/screenshot-from-2020-11-08-23-32-48.png)

Visit repo and fork out code 

{% embed url="https://github.com/aws-samples/aws-codepipeline-s3-codedeploy-linux" %}

Now open CodePipline and create new Pipeline. name your pipline then connect to GitHub repo then pull from account

![](../../.gitbook/assets/screenshot-from-2020-11-08-23-35-21.png)

