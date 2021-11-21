# Python-Network-Sniffer

This Project is about sniffing the IP header and finding it all theinformation that can be known from it such as Header Length, SubnetMask, Number of Hosts,Number of Valid Host, Number of Networks,Network Id, Default Gateway, Wild- Card address, Broadcast Id, etc.This is a Python Program program that can run on Linux terminal.The user needs to start the script and the sniffer records all the data as mentioned above.
<br>

<h2>Purpose of the project</h2>


Created as a mini-project for Computer Networks Lab 2021 (SRM University - 5th semester).

The purpose of the this project is to develop an easy-to-use Network Sniffer that lets individuals use it to figure out “Is it the
network or a specific application that’s causing slowdowns for users?”. 

<h2>Description</h2>


A network sniffer “sniffs” or monitors network traffic for information (e.g., where it’s coming from, which device, the protocol used, etc.). Network administrators can use this information to help optimize their environment. Networks function as a collection of “nodes,” such as your smartphone, laptop, server, etc., which transfer information over a networked connection. To speed these transfers along their route, networks use packets of data—chunks of data that are broken down and then reassembled after transmission is complete—to help avoid network congestion.The IP header contains all important information on all packets present in a network. We aim to track down the packets and use their IP headers to display information like version, destination ip, MAC ; source IP and MAC addresses, the data, TCP segement etc.

<h2>Use of the Project</h2>

Tracking packet response times for both networks and applications means you can more easily answer the question, “Is it the network or a specific application that’s causing slowdowns for users?” . Network sniffers can be used to monitor traffic on a particular network and helps in better analysis.

<h2>Components of a Network Sniffer</h2>

To capture the information over the network sniffer uses the
following components:


<b>Hardware – </b>
Sniffers use standard network adapters to capture network traffic.


<b>Capture Driver –</b>
Capture Driver captures network traffic from Ethernet wire, filters that
network traffic for information that you want, and then stores the filtered
information in a buffer.


<b>Buffer – </b>
When a sniffer captures data from a network, it stores data in a buffer.
There are 2 ways to store captured data –
You can store data until the buffer is filled with information
It is the round-robin method in which data in the buffer is always replaced
by new data that is captured.


<b>Decoder –</b>
The information that travels over the network is in binary format, which
is not readable. you can use a decoder to interpret this information and
display it in a readable format. A decoder helps you analyze how
information is passed from one computer to other.


<h2> Output Screenshots </h2>

![image](https://user-images.githubusercontent.com/74721898/142782276-e1e182ff-0aab-4bc8-81ae-00ab6435fa6f.png)

![image](https://user-images.githubusercontent.com/74721898/142782290-f6657f96-0dfb-4dff-a08d-a1937248e5c3.png)

![image](https://user-images.githubusercontent.com/74721898/142782302-1b75f614-8b08-4555-92ed-69f6815c29ab.png)



Information about the TCP/IP header was obtained.
Data field contains the link to the resource requested
Version followed here is IPv4
The Header is length is default at 5
Source and Destination MAC Addresses help identify the
networks between which the communication is taking place.
Port Addresses identify the application where the data is
being sent to
TTL gives the Time to live for the packet
<h2>Result</h2>

A Network sniffer was implemented in python on the linux
terminal to capture data like header length, checksum,
source and destination address, data field etc.

<h2>Project By</h2>

Varun Sangwan
Abhinav
