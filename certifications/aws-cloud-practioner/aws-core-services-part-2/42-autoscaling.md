# 42 - Autoscaling

#### Introduction - How it works

* Allows you to scale EC2 instances on demand
* Create Autoscaling groups
* Create conditions for auto scaling process

Example - An organisation has an EC2 instance with an application deployed and has a number of users that are accessing it. Once users are accessing the EC2 instance the CPU on EC2 is reaching 80% which reaches the limit. You can add Autoscaling on the EC2 instance which expands the capacity on the EC2 instance which can be called scaled out by capacity based on demand. So perhaps the EC2 instance is not being used as much anymore you con add a condition to autoscale down.  

* First define a launch configuration - This defines the types of instances that needs to  be part of the autoscaling group. 
* You can then define the scaling group
* then perform a manual scaling
* You can also perform a schedule scaling 
* You can also scale based on metrics





