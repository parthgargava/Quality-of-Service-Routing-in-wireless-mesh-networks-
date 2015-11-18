# Quality-of-Service-Routing-in-wireless-mesh-networks-


ACKNOWLEDGMENT


We express our heartfelt gratitude to the entire faculty of Department of Computer Science, Jaypee Institute of Information Technology University, for their keen interest, encouragement, methodical approach, timely suggestions, enthusiastic guidance and faith in us. We deem it our privilege to have carried out the project under their able guidance.

Our sincere thanks to our teacher Mr.Adarsh Kumar for clearing our theoretical concepts regarding the subject which made the foundation of this project and providing relevant guidance in our endeavors.





















PROBLEM STATEMENT
	
The main objective of this project is to study the quality of service routing in a wireless mesh network topology using the different routing protocols which are AODV, DSDV and DSR. With the help of these protocols, we do a comparative analysis to understand the quality of communication between the different nodes communicating in terms of latency, throughput and various other factors. 
We accomplish the mentioned objective is by using Wireless Mesh Networks. The topology will be simulated using Network Simulator (NS2). The simulation results show that the mesh network using routing protocol can provide quality of service support and react dynamically to the network status changes with low control overheads.


	






















INTRODUCTION

	A wireless mesh network (WMN) is a mesh network implemented over a wireless network system with low cost, high scalability, easy maintenance and reliable services. These networks are multihop systems in which devices help each other in transmitting packets through the network. A node can send and receive messages, and also functions as a router and can relay messages for its neighbors. 

	The mesh network offers several communication paths throughout the network. Such networks are categorized by dynamic self-organization, self-configuration and self-healing. Mesh networks have promise for reliability because they are using completely decentralized approach, when a single node drops its neighbors simply finds another path around it. The network layer and its routing functionality must be tailored to support mobile nodes, dynamic topologies and changing link capacity, which characterizes the wireless mobile environment.


 
Fig.-Wireless mesh network with one default route out of the mesh and a single route to every mesh node.
	
There are different operational requirements for different applications, such as: Scalability, security, quality of service QoS, nodes mobility, robustness and power management. Routing protocols can use different methods to compute the path length, distribute the routing information and coordinate the nodes. Therefore, the choice of the operational requirements for the application and the methods and strategies to achieve them makes variety of Routing Protocols.

Quality of service (QoS) refers to resource reservation control mechanisms rather than the achieved service quality. Quality of service is the ability to provide different priority to different applications, users, or data flows, or to guarantee a certain level of performance to a data flow. 
	
When looking at packet-switched networks, Quality of Service is affected by various factors, which can be divided into "human" and "technical" factors. Human factors include: stability of service, availability of service, delays, user information. Technical factors include: reliability, scalability, effectiveness, maintainability, Grade of Service.

Many things can happen to packets as they travel from origin to destination, resulting in the following problems as seen from the point of view of the sender and receiver:

1) Throughput
	
Due to varying load from other users sharing the same network resources, the bit-rate (the maximum throughput) that can be provided to a certain data stream may be too low for real time multimedia services if all data streams get the same scheduling priority.

2) Dropped packets
	
The routers might fail to deliver (drop) some packets if they arrive when their buffers are already full. Some, none, or all of the packets might be dropped, depending on the state of the network, and it is impossible to determine what will happen in advance. The receiving application may ask for this information to be retransmitted, possibly causing severe delays in the overall transmission.

3) Delay
	
It might take a long time for a packet to reach its destination, because it gets held up in long queues, or takes a less direct route to avoid congestion. 

4) Jitter
	
Packets from the source will reach the destination with different delays. A packet's delay varies with its position in the queues of the routers along the path between source and destination and this position can vary unpredictably. This variation in delay is known as jitter and can seriously affect the quality of streaming audio and/or video.





5) Out-of-order delivery
	
When a collection of related packets is routed through the Internet, different packets may take different routes, each resulting in a different delay. The result is that the packets arrive in a different order than they were sent. This problem requires special additional protocols responsible for rearranging out-of-order packets to an isochronous state once they reach their destination.

6) Error
	
Sometimes packets are misdirected, or combined together, or corrupted, while en route. The receiver has to detect this and, just as if the packet was dropped, ask the sender to repeat itself.
