# 99 - NAT instances and NAT Gateway

#### Quick Understanding 

* Network Address Translation can be used to enable instances in the private subnet to initiate outbound IPv4 traffic to the internet 
* NAT instance is provisioned in the public subnet
* NAT instance needs to have internet access
* There is a special AMI available to create NAT instance 

![](../../../.gitbook/assets/image%20%2872%29.png)

An organisation has a VPC with a Private and public subnet where the database server is under the private and the Web server is under the public. As we know the database shouldnt have access to the internet and if it needs to download something from the internet  a NAT instance should be place in the public subnet for it to get requests from the database server to the internet.

#### What is a NAT Gateway

* This is a managed version of the NAT Instance
* Here you get high availability NAT service 
* You can scale up to 45 Gbps
* Completely managed by AWS 





