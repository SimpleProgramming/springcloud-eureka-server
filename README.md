# Spring Cloud Eureka Server

A Simple Spring Cloud Eureka Server Example

Eureka server is a REST based service used to locate mutiples services deployed in your distributed network

let me give you an example, let us say Im a large retailer XYZ in a country. I have multiple data-centers across the county

and i have deployed my java client component in these data-centers

So what are the disadavantages we might face in a distributed architecture

     What happens when some servers goes down? you have to manually reroute the traffic right?
     How would you load balance this cluster?
     What if some catastrophic event happens, like multiple instances are going down and something unusual happens?

and if you are in cloud, it get way more complicated, In cloud we know that the IP addresses will keep on changing (unless you register and have a static ip address)
so how will the systems keep track of different instances available in this cluster?

these are some real world problems that we face in distributed networks

this is where Eureka Server comes into picture and saves us

Eureka Server solves these problems for you

     It automatically registers an instance to it, and keeps track of that instance.
     It provides load balancing of the cluster
     In series of catastrophic fail overs, it goes into self preservation mode and safe guards your system

So, a Eureka server is used for registry all the server instances and your java client component is the eureka client
