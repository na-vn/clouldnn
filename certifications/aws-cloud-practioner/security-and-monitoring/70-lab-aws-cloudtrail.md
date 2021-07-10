# 70 - Lab - AWS Cloudtrail

#### What we will be doing 

* View event history
* Create a trail

In the Cloudtrail section, stated in the introduction it is enabled automatically when the account has been created. In here you will see the all the events that has happened since the account has been created for 90 days. Things like, what has been created, what has been subscribed, who has done what. 

Creating a trail will be more persistent and will be visible for longer than 90 days. When you create one, you're able to select it to cover all regions or not. Then you're able to select Data events to track such as S3 or lambda function, you will then need to select the storage location of the trail. Once this has been created, the function of the trail has now been created and listed in the S3 bucket that you've created. You can now test this by performing some actions such as rebooting or stopping an instance. Once you've performed this, you can go into S3 and search for you bucket that you've created. Once you're in there you should be able to see AWS logs folder and the region folder. This is where the logs are stored in which you will be able to see the logs on what you've performed. 



