# 91 - Identity Access management Best Practice

#### Best Practice

* Try never to use the same access key as the Root account 
* If you do have the root access keys, Delete the access key
* Dont share the AWS root username and password or access keys to anyone
* Create seperate IAM users in your AWS account 
* You can group users together in IAM groups.
* When it comes to assigning permissions, assign permissions based on least privledge 
* Only grant permissions as required 
* Create custom managed policies for your permissions
* Perform regular reviews of your user access
* Perform regular reviews of your custom managed policies 
* Configure a strong password for your users
* Enable MFA for your users 
* Use roles whenever adequate - When using EC2 instance, use IAM roles to grant access. 
* Rotate the credentials regularly when it comes to your users. 



