# 27 - Lab - Clean up resources

Its important to be able to clean up resources that you dont need. Just ensure that t2.micro don't charge you when the service is running but other might charge. If an EC2 instance is micro and the volume attached to it exceeds the free tier, even though the EC2 instance is stopped you will still be charged for that volume as these are 2 seperate resources. Another feature when you're terminating a EC2 instance with an attached storage, you can keep the EBS volumes in question and attach it to another EC2 instance that you spin up later. 

