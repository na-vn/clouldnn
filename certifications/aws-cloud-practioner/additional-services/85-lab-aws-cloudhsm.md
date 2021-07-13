# 85 - Lab - AWS CloudHSM

#### Quick Understanding

* Hard security modules on the cloud
* These are devices that can be used to process cryptographic operations 
* Provides secure storage for your cryptographic keys 

#### What can you do

* Generate, store, import, export and manage cryptographic keys including symetric keys and asymetric keys
* So instead of having your own program on premis, you can do this all with this service. 
* Use symmetric and asymmetric algorithms to encrypt and decrypt data
* Cryptographically sign data
* Generate cryptographically secure random data

#### What are the steps are we going to perform

* Step 1 - Create our cluster. When you create a cluster you need to specify VPC and Subnets
* Step 2 - Initialise the cluster. Here you specify the subnet for the EC2 instance 
* Step 3 - Create an EC2 Instance in one of the subnets 
* Step 4 - Download Certificate and sign it
* Step 5 - After downloading it we upload it to the cluster and inistialise it 
* Step 6 - Install the client on the EC2 instance 
* Step 7 - Upload the certificate on the server and configure the IP address of the HSM cluster
* Step 8 - Connect to the cluster
* Step 9 - List the users available 
* Step 10 - Create a crypto User







