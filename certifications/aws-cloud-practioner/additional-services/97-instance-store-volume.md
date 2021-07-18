# 97 - Instance store volume

#### Undersstanding 

* This is storage that is located on the disk that are physically attached to the host computer 
* This is ideal for storage that stores information that changes frequently - Buffers and cache 
* The size of the store volume depends on the instance type
* You can't detach an instance store volume and attach on to another one 
* The data on the instance store only persist during the lifetime of the instance 
* The data on the instance store is lost during the following scenarios. Any sort of failure, instance stopped, instance hibernates or the instance is terminated 

![](../../../.gitbook/assets/image%20%2876%29.png)

When creating an EC2, you can see in the column EBS which advise which storage is allocated to the service. If you scroll down you can see that its choosing SSD which means its an instance store. You can also go ahead and add storage and choose EBS but jut FYI that the instance storage will be faster as its attached to the host computer as a physical storage.





