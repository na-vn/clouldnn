# 54 - Lab - Cloudformation

#### What are we doing

* Allows you to spin up infrastructure in AWS via templates.
* Good way to control your infrastructure via code.

When creating infrastructure, organisations might want to spin up things like EC2 instance, Load balancer, Autoscaling. In the normal world you would probably go ahead and create these resources one at a time. But say that you need to multiple infrastructure with this same setup. Cloudformation will alllow you to create a template of these settings then it will send it to cloudformation then create a stack which will spin up this Environment. This allows you to use the template over again and it is quick. 

* The template itself is JSON or YMAL
* Resources - this defines the resources that needs to be created.
* Parameters - Send values to the template at runtime.
* Output - you can store the output that you can reuse. 

When creating the template - you can choose on the left hand side which resources you're wanting for the stack. Once you select EC2 and move it to the center, it creates a JSON code already for you. Here you can validate the stack and create. Once its created, the next screens which allow you to create IAM roles etc. once created 



