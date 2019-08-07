# Planes
Forwarding Plane, Control Plane and Management Plane are a common concept to distinguish different aspects of a network device. Separating the functions allows a more flexible design and implementation.
## Forwarding Plane
(Sometimes called "Data Plane") I prefer the term Forwarding Plane because the intention is clearer: Forwarding... 

Functions include:
  * Receiving information from the network, making a decision, if required re-write some information and send to other machines. This is called transit traffic or forwarding.
  * QoS, Quality of Service includes decisions whether to prioritize traffic or in case of congestion drop traffic. QoS can be deployed on the egress queue or -with some limitations- on the ingress queue.
  * Encapsulation/Decapsulation of tunnels or tunnel-like forwarding schemes. E.g. GRE, CAPWAP or VXLAN. This is usually implemented on the ingress or egress interface as the first or last action. 
  
  To be continued...
