# 58 - Simple Notification Service

#### Quick Understanding

* Manage the delivery of messages.
* Different endpoints can subscribe to the Simple notification service.
* Consumers can receive messages via different protocols.

A simple notification service is setup with a Topic. A consumer will publish message to the topic which the topic can distribute to either Email or HTTP. These endpoints are known as subscribers.  

* Create a topic
* Subscribe to a topic
* You can have multiple subscribers to the topic
* A subscriber can be a Lambda function, HTTP/s endpoint, Email, SQS queue or message.
* You can enable encryption for messages.



