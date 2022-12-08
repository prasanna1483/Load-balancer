# Load-balancer Documentation
Load balancer routes requests to the registered targets or instances in one or more availability zones.
Two or three availabiity zones  has to be enabled for the load balancer.
Target group should be created to route requests to the registerred targets.

# Types of Load Balancers
Application Load Balancer: ALB functions at the application layer,seventh layer of the OSI .
ALB is used to route Http and Https traffic.

Network Load Balancer: NLB functions at the transport layer, fourth layer of OSI model.
NLB is used for ssh and db

#Routing Algorithm
The default routing algorithm is round robin



