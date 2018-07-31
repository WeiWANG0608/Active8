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
