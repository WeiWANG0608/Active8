# Active8

This is the script of C++ code.
To run it, neet to under ns3 tree. 
Can use ./waf

In wifimesh.cc
can get the animation, but the traffic generator can only generate Cbr.


In wifimesh2.cc
Now the code can work, however the simulation result seems ok.
Need to add poisson process of packet size. 


In wifimesh3.cc
Now the code can generate poisson traffic, the packet size follows poisson distribution with mean=1024 bytes.
We can increase the load by increasing the number of packet arriving per second with “cmd line”.
Results is in Performance.xlsx 


In wifimesh4.cc
Now there are double sources and double sinks. the packet size follows poisson distribution with mean=1024 bytes.
We can increase the load by increasing the number of packet arriving per second with “cmd line”.
The animation is included now with 50 seconds. 
Results is in Performance.xlsx 

In wifimesh5.cc
The packet size is originally 1024 bytes, however we can change it by "cmd line".
Now the arrival process is poisson process with the average arrival rate 20 packets/s.  We can change it by "cmd line".
Results is in Performance.xlsx 


Now i start to build a new mesh network using Zigbee.
However, it is kind of complicated. Cause the mesh network in NS3 currently mainly support WifiPHY, but not 802.15.4.
https://www.nsnam.org/wiki/Lr-wpan
So ineed to figure out other method to compile mesh, 802.15.4 and csma/ca together.
