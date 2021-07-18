# 100 - Public, Private Elastic IP addresses

#### Quick Understanding 

* What are Public IP Addresses
* What are Private IP addresses
* What are Elastic IP addresses
* How are the addresses used

#### What are Private IP addresses

* IP address that is not reachable over the internet
* Used for communication between instances and VPC
* When you launch an instance in a VPC, AWS automatically assigns a private IP address to the instance 
* This is selected from the IP address range that is available from the subnet 

#### What are Public IP addresses

* This is an IP address that is reachable over the internet
* By default, in the default VPC, a public IP address is assigned to the instance 
* You can decide not to allocate public IP to the instance 
* A public IP address is assigned to an instance from Amazons pool of IPv4 addresses
* The instance public IP address is realeased when the instance is stopped, hibernated or terminated.

#### What is Elastic IP Addresses

* If you don't want the public IP address to change, use Elastic IP Addresses.
* Elastic IP address is a static IP address that doesnt change over time 
* You would go ahead an create a Elastic IP address then assign it to an instance 
* You can also disassociate a Elastic IP address from a resource and associate it to different resource  

#### How is it used

![](../../../.gitbook/assets/image%20%2875%29.png)









### 



