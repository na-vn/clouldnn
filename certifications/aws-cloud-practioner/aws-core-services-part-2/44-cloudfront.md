# 44 - Cloudfront

#### Introduction

* Used for effective distribution of content to users across the world
* Distributes content with the help of edge locations.
* Users receive content from the closest edge location

Example - An organisation has an EC2 instance which has a Web application deployed in the region Ohio. We have users all across the world that access this which means they dont have the same runtime when accessing it because they are further away from the region. Adding Cloudfront infront of the EC2 will add Edge locations across the world where the EC2 instance will point to it so the users can access the EC2 instance from the edge location closer to them. Therefore when the user wants to access the EC2 instance, it will pickup the Cloudfront service which then will point the information to the closest Edge location to the user.

#### Process

* A user tries to access the Web application on the EC2 instance.
* The request is routed to the nearest edge location. 
* If the web content is in the cache of the edge location it will be sent to the user.
* If the web content is not present on the edge location it will need to send a request to the origin EC2. 
* As soon as the first byte is received from the edge server, it starts sending the data to the user. 
* The data then gets cache for further use.



