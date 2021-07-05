# 31 - Service Continuity

#### Introduction

This is mainly for a service that is running within AWS that generates high revenue for the company. If this service goes down it will cause a problematic loss for the company. Some of the important aspects that needs to be looked at is.

* Fault tolerance - if a fault is caused at the infrastructure level, you need to ensure services are made available. 
* High Availability - if infrastructure goes down, you need to ensure the right measures are put in place so applications is still available.
* This all goes down to how you design the architecture of the application.

There are some services in AWS that is available for Service continuity for applications and infrastucture. 

* Availability zones - are a host of data centers that can be hosted your resources in AWS. Make sure you deploy them across different availability zone. 
* Region Zones - For higher availability and DR, deploy secondary solutions to multiple regions.
* Elastic load balancer - for distrubute traffic to your EC2 instance.

#### Important design concepts

* Always decouple your components of your applications.
* Don't have tight integration 
* Always design with failure in mind
* Always make use of features in AWS.
* 




