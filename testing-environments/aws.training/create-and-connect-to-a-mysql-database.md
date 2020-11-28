# Create and Connect to a MySQL Database

In this step, we will use Amazon RDS to create a MySQL DB Instance with db.t2.micro DB instance class, 20 GB of storage, and automated backups enabled with a retention period of one day

Select your region and pen up RDS from console, then select create database.

You have a few options here but in this example i will be choosing Standard, MYSQL and free teir.

![](../../.gitbook/assets/image%20%2819%29.png)

![](../../.gitbook/assets/image%20%2821%29.png)

Ensur you fll out the database name, and password.

![](../../.gitbook/assets/image%20%2820%29.png)

Under storage, type fille them in and untick autoscalling. 

![](../../.gitbook/assets/image%20%2817%29.png)

Under Connectivity section you want to tick Public and select Create new

![](../../.gitbook/assets/image%20%2824%29.png)

Under additional settings you can select backup retention to 1 day and uncheck enable monitoring

![](../../.gitbook/assets/image%20%2818%29.png)

Once you're done, click on Create database







