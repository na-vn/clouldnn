# 72 - Additional Security

#### AWS Web Application firewall

* It has integrations with AWS Loadbalancing, Cloudfront distributions or the API gateway
* Using this service you can create Web Access control list to filter the traffic that flows into your infrastructure
* You can create rules to stop traffic coming from a specific IP address. 
* You can create a rules to stop traffic based on header vaule on the incoming request. 

An organisation will have 2 EC2 instances with web applications running on it. A load balancer sits in front of the EC2 instances with users connecting to it. When this happens attacks might happen such as SQL injections, hacking etc. So what you can do is add a Web Application firewall infront of the load balancer.

#### AWS Shield

* AWS Shield can be used to protect from DDoS attacks
* AWS Shield 🛡 standard is given free for some of the AWS services such as the Web application firewall 
*  AWS Shield🛡 advance which provides better support against DDoS attacks which comes at an extra price. It comes with support with AWS and imediate mitigation when using the advance feature. 

#### AWS Artifact

* You can use this service to download AWS Security and compliance documents
* If your company is doing an audit and wants to know if AWS is compliant with ISO certification or Service Organistion control SOC you can refer to the AWS artifact service 











