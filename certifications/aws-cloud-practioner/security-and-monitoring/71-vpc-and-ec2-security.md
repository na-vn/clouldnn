# 71 - VPC and EC2 Security

#### Network access control list

* Used to protect traffic in subnet hosted in VPC
* Gives an extra layer of security at the subnet/network level

An organisation has a VPC with an EC2 and a subnet inside it. Say you want to control what traffic can flow out of the subnet and what traffic can flow in to the EC2, you would use the Network access control list to manage this. 

* There are inbound and outbound rules that can be defined.
* Each rule can define which protocol, Port range and source ton deny or allow traffic

#### Security Groups

* These are associated with the network interfaces attached to the EC2 instances 
* These can be used to decide what traffic can flow into and out of EC2 instance 
* There are inbound and outbound rules that can be defined
* Security groups are used on an instance level to protect the traffic 
* Each rule can define which protocol, port range and source.

In VPC you can open up Network ACL and see what ACL is already in place. You will notice you have one Network ACL listed that has 2 or 3 subnets. By default if you check the inbound and outbound connections. AWS will allow all traffic to come in and all traffic outbound. 

You can go in EC2 and check the Security groups because Security is on the instance level. By default the traffic that is inbound to the EC2 instance is denied and not allowed. In order to have traffic coming from the internet you will need to create a rule in place where HTTP port 80 from 0.0.0.0/0 can be accessed. 



#### 



