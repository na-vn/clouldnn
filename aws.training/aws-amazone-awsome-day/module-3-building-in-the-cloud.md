# Module 3: Building in the cloud

This module talks about AWS EC2, EBS, VPC makes it easier for organisations to use familiar technology to build their network

Monitoring AWS - CloudWatch. It monitors AWS resources, applications running on AWS. Collects and tracks standard metrics and custom metrics. Set alarms and send notifications and automatically make changes base on rules you define 

Cloud watch injects metrics from AWS resources and customer applications in which you can create alarms. It allows you to manage alarms efficiently.

Dynamic scaling with Amazon EC2 AutoScaling which adjusts the capacity as needed, scale out for spikes, scale in during off peak, replace unhealthy instances and pay for what you only use

Autoscalling works by using CloudWatch alarms we can watch a certain metric over the ec2 instances like CPU.

Fleet management with Amazon EC2 Auto Scaling monitors the health of running instances. 

Elastic Load Balancing it automatically distributes traffic across multiple targets. 3 types of Load Balancing that Amazon provides - Application, Network, Classic are the layers within the ELB

Application Load Balancing is a layer 7 http https load balancing web application and supports part base routing. EC2 instance as targets

Network Load Balancing is layer 4 load balancing for application tcp udp tls. Its good for application that needs single static IP that needs to route traffic to.

Amazon RDS is a database service that makes it easy to set up operate and scale a relational database in the cloud. It suppose SQL, oracle,MySQL etc. Easily scale able, automatic software patching and backups. Database snapshots. 

Amazon Auroa - Enterprise-class relational database built to nationally and take the advantages of the elasticity of the cloud . Supports SQL, 5x faster.

Amazon DynamoDB is a fast and flexible NoSQL database service for any scale thats fully managed, low latency queries, fine grained access control and regional and global options. DaynamoDB use cases such as server less Web Applications. Micro services data store Mobile backed, Ad tech Gaming 

AWS Database Migration Service migrates database to AWS quick;y and securely.

AWS CloudFormation is a service that makes it easy to create repeatable and deplorable models of your infrastructure. You would code your template which includes Subnet, gateway and VPC 

AWS Beanstalk setup web applications. You provide Beanstalk the code which beanstalks will take care the rest.

AWS Direct Connect is a dedicated network connection from your premises to AWS which reduce network cost, creates consistent network performance. Provides private connectivity to your Amazon VPC and scales easily. 

Amazon Route 53 is highly available and scalable Domain Name System web service where you can register domain names, router internet traffic to the resources for your domain and check health of your resources 

Amazon Elastic File System EFS is a scalable elastic, cloud-native file system for linux that is dynamic elasticity, scalable performance shared file storage and fully managed. 

AWS Outpost brings AWS on premises - 

AWS Local Zones are new type of AWS infrastructure. AWS Wave length extends AWS infrastructure to the 5G networks.

VMware Cloud on AWS - VMware software-defined data center SDDC technologies you know and trust, delivered as a service on the cloud.

AWS Lambda to run code without servers by uploading your code to AWS Lambda, set your code to trigger from an event source. Lambda runs your code only when triggered. Supports multiple programming languages.

Amazon Simple notification service SNS which broadcast and deliver messages with durability, automatically scale your workload, Amazon CloudFront a fast secure and global content delivery network CDN, supports S3 ELB EC2. 205 Edge location around the world. CloudFront delivers content to users. Its a lazy loading system and its only used when requested.

Amazon ElastiCache is a service that makes it easy to deploy.. operate and scale and in memory data store. Fully managed Redis or Memcached-compatible in-memory.

![](../../.gitbook/assets/image%20%286%29.png)

