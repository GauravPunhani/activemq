This repository caters to exploring activemq in depth 
and trying different real time scenarios.

Clustering : 
1. Competing consumers

2 Broker clusters Network of Brokers - If one broker has producer , and one has consumers , then messages should move from producers to consumers
	across brokers , thus providing failover...
	
3. Master slave - helpful in case of broker going down when it got the message.

4. Replicated message stores -- 