# Distributed Group System
The goal of this project is to build a module that provide to group of hosts
in the same LAN (Local Area Network) an API for programming for building
distributed applications with crash fault tolerance.
Each host atached to the module is able to participe of the distributed 
system group.

## About the code
The code is in C++ language (at least 11).
The code is private and available just for job interviews of the owner.
If you have insterest, please contat me.
E-mail: mauricio@google.com
Linkedin: www.linkedin.com/in/mtquadros

## About demonstrations
The demonstrations will be available by video whwich enough support for audio,
So will able to make teh explanations.

## Notes: Some features until the moment,
1. Any host in same local network can join the distributed group of hosts;
2. Once a host joins the group it knows all others members and the all the others new th new member;
3. If the member leaves the group it "forget" all other members of the gruop and all other members of group "forget it".
4. Once a host joins the group, the new leader elected 

## Work in progress,
1. Atomic Broadcast
3. Implement new distributed building block features;
4. Implement the fault tolerance to crash failures;
5. Implement a interface for applications.
