# 66 - Lab - AWS Command Line Interface

#### Quick understanding 

* Tools which allows you to work with AWS Resources via the AWS CLI - Good for IT admins that write scripts that work with AWS resources
* Generate Access keys are needed to work with CLI

You have to first download and install the AWS CLI onto your machine for this to work. To generate access keys you need to go into security credentials then go to access keys. It is stated in the previous labs that its not recommend using the root account. So if you have an account that is generic for a specific resource such as s3 - you can go into the user and go to security and generate access key from there. When creating a access key the option to show the secret key path is only visible at this time only. Once created you can also mark this key as inactive just incase if a developer goes on holidays. 

Steps to work with AWS CLI

* Install AWS CLI
* Create access key &gt; Ensure that thats copied. This is done through security credentials
* Open Powershell
* Run aws configure 
* Enter in Access key and security ID
* Once this is done you're able to run commands through AWS CLI





