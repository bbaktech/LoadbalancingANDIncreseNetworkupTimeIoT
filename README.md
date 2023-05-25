# LoadbalancingANDIncreseNetworkupTimeIoT
BBAK Technologies – Ph: +91-9353205447, email: bbaktech@gmail.com
Project Title: Increase Network Up Time, Load Balance and Efficient routing Model for heterogeneous Wireless Sensor Networks

Issues:
 “Cluster Head (CH) closer to the base station (BS) tends to die very fast in 
comparison with far away nodes due to inter-cluster communication”
,
 within the Cluster the Cluster Head tends to die very fast in comparison other nodes 
because it must act as collection centre to collect date from all the node and forward
to Base Station (some time it uses other CH as relay to forward to BS)
Solution:
CH Selection: To avoid these issues, we propose model where each nod has capacity to act 
as CH. CH is selected based on power availability at Node on regular intervals.
This avoids Burdon on single node, Burdon is shared by each node in a cluster at different 
intervals and will achieve load balancing. This module will be very reliable because if any CH 
go’s down due unavoidable circumstances other node will take the position as CH in next 
interval. Because of this all the node in a cluster will get active. 
Simulation Considerations:
 There are two types of nodes (some are with more power, some with less power)
 Cluster formation based on distance from BS, physical location,
 CH is selected with in the cluster based on its RANK (based on energy condition), it
will be dynamic, current CH for a given cluster will lose CH position as it loses energy 
during operation, new node with in the cluster will take position as CH
 Simulation done on slots,
 sensers send the information to CH at each slot,
 CH will aggregate collected information from Sensers and transmit to BS via selected 
path.
 Path is determined dynamically based on availability of the intermediate CH, their 
distance and energy condition.
 Life time of each node is recorded.
 Total Network UP time recorded.
 Energy auditing is based on:
o 1Unit for sensing and transmit to CH
o 2Unit for aggregate and send to BS.
o 1Unit for forwarding received aggregated data by Intermediate CH to BS
