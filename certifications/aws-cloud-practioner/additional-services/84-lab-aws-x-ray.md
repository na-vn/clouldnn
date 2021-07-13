# 84 - Lab - AWS X-ray

#### Quick Understanding

* Service used to collect data about your request
* You can uses this tool to optizmise your applications
* You can use this for your application or even Lambda Functions

#### What can you see when you use X-ray with Lambda

* There is a service map that is provided to show you where data is going 
* It gives you an entire service map of  your request 
* It also gives you the average time spent on each request. 
* You can see individual traces of your application
* You can use X-Ray SDK to instrument your application
* You can use X-Ray from Lambda, you have to enable it. 
* If you want to send information about other request, you need to add an instrument code.

When in Lambda and have a code ready, at the bottom it allows you to tick enable X-Ray on the code. When this is ticked and you run the test, you can go over to X-ray, traces which will show you the service map



