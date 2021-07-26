# 102 - AWS VPN

#### Quick Understanding 

* VPN - Virtual Private Network
* In AWS you use AWS VPN to connect your on premise data center to AWS 
* You can create site-to site VPN connection 
* Then all the traffic between the on premise data center and AWS would flow via the VPN connection

![](../../../.gitbook/assets/image%20%2880%29.png)

Here you have a VPC and EC2 instances on AWS network, then you have a on premise data center which you want to have a connection to. You would create a VPN gateway then a routing gateway inside AWS to connect to the customer gateway This routing gateway will have a public facing IP address.

* Virtual Private gateway - This is the VPN concentrator on the Amazon side of the site to site VPN connection 
* The virtual private gateway is attached to the VPC
* The customer side you would have a hardware or software device that can route traffic on the internet 
* You can create customer gateway in AWS that would represent the customer routing device 



