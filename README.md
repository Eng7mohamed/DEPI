# Computer Networking Project

## Overview

This project demonstrates a simulated network infrastructure designed using Cisco Packet Tracer. The topology includes VLANs, routers, switches, servers, and other network devices to provide connectivity and simulate a functional enterprise network.

##Features

### VLAN Configuration:
VLAN 40 (HR): 192.168.40.0/24
VLAN 60 (IT): 192.168.60.0/24
VLAN 70 (Finance): 192.168.70.0/24
VLAN 80 (Engineering): 192.168.80.0/24

### Routing:
Multiple routers are configured to connect internal and external networks.
Tunnel interface 192.168.6.0/30 ensures communication between different sites.

### Servers:
DHCP server: Provides dynamic IP addressing.
DNS server: Handles domain resolution.
FTP server: Manages file transfers.
Email server: Simulates internal email communication.

### Wireless LAN Controller:
Provides wireless connectivity for mobile devices.

### Inter-Site Connectivity:
Uses Serial and Tunnel interfaces for WAN connectivity between branches.

## Requirements

### To open and use this project, you need:

Cisco Packet Tracer (version 8.2 or later)

## Getting Started

Download and install Cisco Packet Tracer.
Clone this repository using:
bash
Copy code

git clone https://github.com/your-username/DEPI.git

Open the .pkt file in Cisco Packet Tracer.
Explore the configurations, test connectivity, and modify as needed.

## Network Details

### IP Addressing:
192.168.10.0/24: Main network
192.168.11.0/30: Inter-router link
192.168.7.0/30: Tunnel interface
### Devices:
Routers: Connected via serial interfaces for WAN simulation.
Switches: Distribute traffic within VLANs.
PCs and Printers: Connected to VLANs for end-user simulation.
