# 75 - Labs - AWS OpsWorks

#### Quick understanding

* Configuration management service
* Allows to force the desired state of your infrastructure.
* Allows you to integrate exisiting tools such as Puppet and Chef

An Organisation might have an environment which has components such as Windows server 2016 as their underlying OS running IIS 5.7, with Redhat enterprise and running MYSQL 6. They can names this stack as a production stack. Then they can also have another stack with Windows Server 2019 as their underlying OS running IIS 10, with Redhat enterprise running MYSQL10 and can name this stack as Development stack. Having to manage the components manually would be the method if they didnt run on cloud but AWS OpsWorks can come into play using Puppet or Chef to Manage the updates on the components. 

When using OpsWorks you can create a sample stack which automatically assigns an EC2 instance with the stack and deploy a Node.js app in the stack. There are options when creating the stack in OpsWorks. You can create a sample stack, Chef 12 or Chef 11 stack which gives you more options and configuration options. Once you created a stack, you can see that there are Layers of the stack, What apps are on the stack, Instances and other configurations. One of the configrations of the layers are recipies which allows you to deploy, setup, configure, Undeploy or shutdown the layer if they are ticked. When creating the layer, the default status is stopped. 



