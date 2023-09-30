# CIT 114
# Networking and Content Delivery

It is to create and increase a network of contacts which is created using names, addresses where you can
connect different devices so that computers connect to a network, in short, networking is a key in work life which
It serves to have a circle of quality contacts.

# Computer Network

Computer networking is the interconnection of multiple devices, dominated by hosts, which are connected in multiple
routes with the sole purpose of sending and receiving data, there are also multiple devices that help in communication
between two or more devices which are known as network devices (Router, Switch, Hub and Bridge). however
This is the design pattern where the devices are interconnected and are called network topology (Bus, Star, Mesh,
Ring and Daisy chain.

OSI stand for Open Systems Interconnection is for transmitting messages and is a reference model that specifies standards.
of protocols for communication which is defined in seven layers.

# The OSI Model layers are as follows:
1. Layer 7 - Application: closest to the end user.
2. Layer6- Presentation: establishes context between application-layer entities,in which the application-layer
entities may use different syntax and semantics 
3. Layer 5- Session: controls the dialogues (connections) between computers.
4. Layer 4 - Transport: provides the functional and procedural means of transferring variable-length data sequences
 from a source to a destination host, while maintaining the quality of service functions.
5. Layer 3 - Network: provides the functional and procedural means of transferring variable length data sequences
(called packets) from one node to another connected in "different networks".
6. Layer 2 - Data Link: Provides node-to-node data transfer—a link between two directly connected nodes
7.  Layer 1 - Physical: Responsible for the transmission and reception.

There are two important components in creating networks since the first thing is to know where to go in a network which
It requires an IP address. Computers also translate numbers into something that can be understood, such as Binary.

#  Microsoft: Understanding TCP/IP addressing and subnetting basics
When you are going to configure the TPC/IP protocol on computers, it requires you to have an IP address, a subnet mask
and also a default gateway.

# Glossary
1. Broadcast address -- An IP address with a host portion that is all ones.
2. Host -- A computer or other device on a TCP/IP network.
3. Internet -- The global collection of networks that are connected together and share a common range of IP addresses.
4. InterNIC -- The organization responsible for administration of IP addresses on the Internet.
5. IP -- The network protocol used for sending network packets over a TCP/IP network or the Internet.
6. IP Address -- A unique 32-bit address for a host on a TCP/IP network or internetwork.
7. Network -- There are two uses of the term network in this article. One is a group of computers on a single physical network segment; the other is an IP network address range that is allocated by a system administrator.
8. Network address -- An IP address with a host portion that is all zeros.
9. Octet -- An 8-bit number, 4 of which comprise a 32-bit IP address. They have a range of 00000000-11111111 that correspond to the decimal values 0- 255.
10. Packet -- A unit of data passed over a TCP/IP network or wide area network.
11. RFC (Request for Comment) -- A document used to define standards on the Internet.
12. Router -- A device that passes network traffic between different IP networks.
13. Subnet Mask -- A 32-bit number used to distinguish the network and host portions of an IP address.
14. Subnet or Subnetwork -- A smaller network created by dividing a larger network into equal parts.
15. TCP/IP -- Used broadly, the set of protocols, standards and utilities commonly used on the Internet and large networks.
16. Wide area network (WAN) -- A large network that is a collection of smaller networks separated by routers. The Internet is an example of a very large WAN.

# Internet Gateway
It is an internet gateway, where it allows communication between VPC and the Internet.

Network Address Translation (NAT)

1. NAT Gateway: is a network address translation gateway where it allows instances
of the private subnet connects to the Internet or other services.

3. NAT Instance: is a network address translation which a public VPC subnet allows that private subnet instances initiate outgoing IPv4 traffic
4. to the Internet or other services.
   
In this module I learned about what Networking is about, what its function is, internet protocols among others, where it is
It is important to understand the information on how to create a network in AWS, how to create subnets, select IP address range and how
configure route table and network gateways and what applications to use in AWS to create infrastructure and specify IP address range.

What is the difference between Nat gateway and Nat Instance?
