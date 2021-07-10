# 68 - Lab - Cloudwatch

#### What will we be doing 

* View metrics
* Create alarm
* See Dashboards
* See billing alarm
* look at logs

#### Metrics

When you go into Metrics under Cloudwatch, you will notice at the bottom it will list you resources that you have used. These are the metrics you can use against your resources. If you haven't used S3 before, the metric of S3 wont show up. Once you have chosen a metric to graph, you cacn select the predefine metrics thats already listed in AWS. YOu can choose from CPU utilisation, Network packets etc. You can choose from a range of selection to view. You can also save the graph and select which days to graph.

#### Dashboards

You can create dashboards in cloudwatch by selecting dashboards and creating dashboard. From there you can choose from types of dashboards such as text, graph, Numbers, lines etc. These are called widgets. From there you will need to choose the resource you're creating the dashboard from then choosing the metric. 

#### Alarms

You can create an alarm by selecting Create alarm in the Alarms section in Cloud watch. It will then ask you to select the Resource then the metric you want to base the alarm on. You can also configure how the alarm is triggered. Example could be the CPU utilisation over 20% it will trigger the alarm. You will need to name the alarm also. When you create an alarm you can also create what the the next step of action could be. 

Billing alarms needs to be activated by checking the Receive billing alerts in preferences. Once that is done, you can start creating a billing alarm in cloudwatch. You're able to create 10 free alarms in the free tier. 

Logs can be view in the cloudwatch section. Lambda functions have integration with Cloudwatch, so the logs that are generated from Lambda can be viewed here. 



