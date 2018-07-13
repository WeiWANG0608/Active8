# Active8

This is the script of C++ code.
To run it, neet to under ns3 tree. 
Can use ./waf

The problem now is that, if there are maximun 12 mesh nodes, it can work well, however, when the number of nodes is over that, 
then there is an error "Max Packets per trace is exceeded".

After i modified the code: giving a huge number to the parameter MaxPktPerTrace, then the code just cannot stop.

I will still try to figure out the solution.


After running the code, there are Throughput and Delay showed in the terminal.
