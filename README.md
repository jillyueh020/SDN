# SDN LAB
Goal: Connect the network card with OpenvSwitch  

●Equipment: 1VM (Virtual Box with Ubuntu 16.04), 3 Network cards, 1 stream generator (NuDOG 301C)    
●Preparation:
 1. Install Open vSwitch on Ubuntu
 2. Have a concept of SDN
 3. Get familiar with the Open vSwitch: [English tutorial](https://github.com/openvswitch/ovs/blob/master/Documentation/tutorials/ovs-advanced.rst)  /  [Chinese version](https://github.com/OSE-Lab/Learning-SDN/tree/master/Switch/OpenvSwitch/Walkthrough)
 4. Get familiar with the NuDOG
 5. Let's start

## SDN Introduction
SDN, Software Defined Network
basically using the software to control the hardware within the network system to have better network performance.

### Why SDN?
1. The closed systems in the network system devices (routers, switches):
   --> make the web administrators spending time on getting used to different systems provided by different suppliers
   --> unable to flexibly adjust (may have to shut down the network service to change the settings or protocol)

2. The network environment nowadays
   --> Interent Ossification: the network system devices just like our bone or the traffic system in our lives would exist very long time.
   --> Highly Internet usage, people can't live without the Internet
   
● That comes the SDN:
  Using software to remotely control the control plan
    
 ### The Architecture of the SDN
