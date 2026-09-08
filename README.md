# Distributed Group System experiment
The goal of this project is build a module that implements a group of hosts
in the same LAN (Local Area Network) that connect with each other via UDP multicast messages
using Boost Library API to create a group that supports join and leave the group.
Despite de UDP is not communication protocol that supports confiability and ordering of messages,
this project, works succefully as an experiment.


## About the code
The code is private and available just for job interviews of the owner.

## About demonstrations
Here we have three terminals running your own process.

![Demonstration](https://github.com/mtquadros/distributed_system_mid/blob/master/demonstration.gif)

## Notes: Some features until the moment,
1. Any host in same local network can join and leave the distributed group of hosts;
2. Once a host joins the group it knows all others members and vice versa and a new leader is elected;
3. The leader has always the biggest UUID;
4. Once the member leaves the group it "forget" all other members and the other members forget it.
5. The command join is activated by typing number, as well command leave by typing 2.

## About demonstration
1. If the demonstration is not clear because the size, i just zoom the screen. Lost the definition
   but still can be observable.


## Work in progress,
1. Improve the information on the screen for debugging and demonstration of the
features;
2. Fix bugs;
3. Implement new distributed building block features;
4. Implement a interface for applications.
