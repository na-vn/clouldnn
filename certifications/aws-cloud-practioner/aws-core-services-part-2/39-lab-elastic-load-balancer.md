# 39 - Lab - Elastic Load Balancer

#### How to

* Create 2 EC2 instances
* Install apache on these instances
* Change Homepage
* Create load balancer - 3 types of load balancers, Application, Network and classic
* Place EC2 Instances behind load balancer

When creating a load balancer you need to choose which type of balancer you're wanting. Once chosen, you will need configure things such as, Name, internet facing or internal, add listeners, Availbility zones, tags, then it goes through security groups. Once you've configured the settings you will need to register which EC2 instance assigned to the load balancer. Once its regiestered, you will need to select the load balance dns which will direct you to the correct EC2 instance that doesnt have much traffic on it. Easy! So summary it is to distrubute request to your backend EC2 instances.





