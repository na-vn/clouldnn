# 40 - Route53

#### Introduction

* Registered domain names
* Route traffic through AWS resources.
* Check health of your resources.

Example - When you have a EC2 instance that is deployed with web server. The user that access this will type in the URL the website to access this. But the Pubic domain name is something long. Having Route53 in place will elminate this and provide the domain name for the user to access. Things that needs to be done are creating a hosted zone, register the nameservers in the domain registrar and create resource record in hosted zone. 

Routing policies

* Simple Routing policy - Used for single resource
* Failover Routing policy - Used for active-passive failover.
* Geolocation Routing policy - Routes traffic based on location of users.
* Weighted routing policy - Route traffic to different resources based on weightage.
* Latency Routing Policy - Routes traffic to different regions based on latency.
* 
#### 



