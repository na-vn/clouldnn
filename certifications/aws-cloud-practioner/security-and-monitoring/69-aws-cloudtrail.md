# 69 - AWS Cloudtrail

#### Quick Understanding 

* Used from a governance and compliance perspective. 
* All actions taken in the AWS account are recorded by this service.
* Actions taken either from the console, CLI, SDK and API.

Security is important aspect. AWS cloudtrail logs all the actions taken by all users in the account across all services and across all regions. Better way to put this is Cloudtrail is an audit trail. It can see things such as Detect unauthoirsed access, Someone shutting down an EC2 instance, Someone starting a EC2 instance or someone has logged in as root. 

* Cloudtrail is automatically enabled as a service when the account has been created.
* The service records events which can be view in the event history
* These events history gets retained for 90 days. 
* You can create something called a trail if you want it to be over 90 days
* The trail can be sent to s3 buckets



