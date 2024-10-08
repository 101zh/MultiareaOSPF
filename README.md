# Multiarea OSPF Configuration with IPv4 & IPv6

## Contents

## Background

## Topology

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
