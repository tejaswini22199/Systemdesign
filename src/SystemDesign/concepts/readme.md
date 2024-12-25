## Distributed Systems

## Scaling 

* Horizontal Scaling
  * Adding another machine with same or different processing power like existing one to handle the load /
  growing requests.
  * This system is called as Distribution System. Because your load is handled by multiple systems. 
* Vertical Scaling
  * Adding additional resources like processing power, RAM, storage to the existing machine to handle
  the load / growing requests.

### Advantages of Horizontal Scaling: 

* Horizontal scaling is much easier and cost friendly than vertical scaling because the cost of the smaller
  machines is lesser than the cost of the bigger machines.
  And when the number of requests reduces, horizontal scaling allows you to shut down machines that are no longer
  needed. 
* Initially Horizontal scaling can be expensive compared to vertical scaling but after a point when there are more
  requests coming, horizontal scaling is much cost-effective than vertical scaling 
* Horizontal scaling is fault-tolerant because you can route the requests to other service if the current
  service doesn't respond. But in vertical scaling, the server is in one location and if it goes down due to
  some issue in that area, there is no way to make it work in less time. But in horizontal scaling, these machines
  are present in different locations.  so, even if one goes down, we can re-route.
  (We might see more latency though as the location of machine is very far)
* Low latency in case of horizontal scaling : because in vertical scaling, the single machine is at a very
  far location. so it will take a lot of time for the response to arrive. But in case of horizontal scaling,
  there is high possibility that there is a server nearby. 

## Distributed Data Stores:

* Two types of dB. 1. RDMS 2. NO SQL