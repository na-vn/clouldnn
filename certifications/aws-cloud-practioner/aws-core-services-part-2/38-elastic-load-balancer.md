# 38 - Elastic Load Balancer

#### Introduction

* Distributes request to your underlying EC2 instances
* The Elastic Load Balancer is a managed service.
* There are different types of Load Balancers

Example: An organisation has an EC2 instance that has a web server deployed on it which has users interacting with it. Lets say the application is an ecommerce application that you want to promote over a specific period of time which anticipates high load and the EC2 is running on 80% CPU capacity. Things you can do it change the instance type, changing the CPU memory or storage adding 8 CPU instead of 4. Although this can be done but there will be a limit. 

The prefered way to fix this having 2 EC2 instances with the web server deployed on them. inserting a load balancer in between the EC2 instances and users will direct traffic and request to difference EC2 instances to balance the load.



