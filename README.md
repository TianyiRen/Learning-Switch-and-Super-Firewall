SDN_hw1
=======

COMS E6998-10 Fall 2014 Software Defined Networking Homework 1

UNI: tr2400

Implementations: 
1. Learning Switch module
2. Super Firewall that can detect and block elephant flow

Compile and Run:
$ ant 
$ ./floodlight.sh

Set up virtual network
$ sudo mn	--topo	single,6	--mac	--switch	ovsk	--controller	remote	

In mininet virtual machine: 
mininet> h1 ping h2 -s 1024 
mininet> xterm h1 h2

In Xterm terminal:
# tcpdump -XX -n -i h1-eth0
# ping -c3 10.0.0.2



