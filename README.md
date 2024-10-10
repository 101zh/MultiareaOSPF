# Multiarea OSPF Configuration with IPv4 & IPv6

## Contents

## Background

## Topology

These are the topologies for both IPv4 and IPv6, each link is labeled with the network number and subnet mask of the link. Then each interface is labeled with the 4th octet of the usable IP address within the subnet of that link.\
Additionally, the PCs can have any IP that is within the subnet of the link that they are on. **DHCP is not setup**.

### <center>IPv4 Topology</center>

![IPv4 Topology Image](Images\IPv4.Topology.png)

### <center>IPv6 Topology</center>

![IPv4 Topology Image](Images\IPv6.Topology.png)

## Address Table

|Device Name|Interface|IPv6 Address         |IPv4 Address|IPv4 Subnet Mask|
|:----------|:--------|:--------------------|:-----------|:--------------:|
|R1         |G0/0/0   |2001:db8:acad:b::2/64|192.168.1.2 |255.255.255.0   |
|R1         |G0/0/1   |2001:db8:acad:e::1/64|192.168.20.1|255.255.255.0   |
|R2         |G0/0/0   |2001:db8:acad:b::3/64|192.168.1.3 |255.255.255.0   |
|R2         |G0/0/1   |2001:db8:acad:a::1/64|192.168.0.1 |255.255.255.0   |
|R3         |G0/0/0   |2001:db8:acad:a::2/64|192.168.0.2 |255.255.255.0   |
|R3         |G0/0/1   |2001:db8:acad:d::1/64|192.168.3.1 |255.255.255.0   |
|R5         |G0/0/0   |2001:db8:acad:c::2/64|192.168.2.2 |255.255.255.0   |
|R5         |G0/0/1   |2001:db8:acad:f::1/64|192.168.30.1|255.255.255.0   |
|S1         |F0/1     |2001:db8:acad:d::2/64|192.168.3.2 |255.255.255.0   |
|S1         |F0/2     |2001:db8:acad:c::3/64|192.168.2.3 |255.255.255.0   |

## Device Overview

This Topology Consists of...

- Five 4321 routers running Cisco IOS XE Software, Version 16.9 Universal K9
- One Cisco 3560 POE-38 running C3560-IPSERVICESK9-M Version 12.2(44)SE5
