# IPsec_project
# IPsec Site-to-Site VPN Lab

## Project Information

**Course:** CMU-CS 376 – Elements of Network Security  
**Student:** Cao Thi Vuong Anh  
**Student ID:** 30209232987  

**Project Title:**  
Research on IPsec and Implementation of a Site-to-Site VPN for Securing Connectivity Between Two Branches in a Virtualized Environment.

## Overview

This project studies and implements an IPsec Site-to-Site VPN between two virtualized network gateways.

The lab was built using Ubuntu Server, strongSwan, Oracle VirtualBox, and Wireshark.

The implementation focuses on:

- IKEv1 Main Mode
- IKEv1 Quick Mode
- ESP Tunnel Mode
- Pre-Shared Key authentication
- Packet analysis using Wireshark
- PSK mismatch and tunnel recovery

## Network Topology

- GW-A WAN: `10.10.10.1/24`
- GW-A LAN: `192.168.10.1/24`
- GW-B WAN: `10.10.10.2/24`
- GW-B LAN: `192.168.20.1/24`

Protected networks:

`192.168.10.0/24 <-> 192.168.20.0/24`

## Repository Structure

```text
1_Report/
2_Configuration/
3_PCAP/
4_Evidence/

