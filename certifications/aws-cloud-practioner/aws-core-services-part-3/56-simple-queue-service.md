# 56 - Simple Queue Service

#### Quick Understanding 

* Hosted Queue service.
* Fully managed, secure and durable. Dont need to manage the underlying infrastructure. 
* Used to decouple components of a distributed applications

#### How does it work

An organisations such as Youtube has components which the user sends and uploads a video to the service. Theres another component of Youtube that Processes the video. If the component that processes the video goes down it would be the User would not know this has happened. So to fix this, a Simple queue service would be added next to the components that are sending videos and processing. 

* Standard queues - Normal queues in AWS service. 
* FIFO - preserve the order of the queues. First in/First out
* Visibility timeout - This is the amount of time a message becomes invisible after being read. The steps in which messages are read is that the producer sends out the message, consumer process that message and the message is then deleted. But happens if the consumer goes down after the producer has sent the message. it means that the consumer has not read the message and the message could be deleted therefore visibility timeout step is required. 



