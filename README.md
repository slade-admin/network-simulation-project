# Network Simulation Project

This repository contains a Cisco Packet Tracer network simulation demonstrating basic LAN setup, router-to-router connections, and RIP dynamic routing. The project is designed for educational purposes and as a networking portfolio example.

## Topology Overview

The network consists of:

- Two LANs
  - LAN1: 192.168.1.0/24
  - LAN2: 192.168.2.0/24
- Two Routers
  - Router0 connected to LAN1 and Router1
  - Router1 connected to LAN2 and Router0
- Router-to-Router Link
  - Subnet: 10.0.0.0/30
  - Router0: 10.0.0.1
  - Router1: 10.0.0.2
- PCs
  - PC0 and PC1 on LAN1
  - PC2 and PC3 on LAN2
- Switches connecting PCs to routers

Topology Diagram: topology.png

## Files

topology.png - Diagram of the network layout
proj2.pkt - Saved Cisco Packet Tracer simulation file
configuration.txt - Full router interface configurations and RIP commands README.md - Project description and setup guide.

## Router Configuration

- All router interfaces have no shutdown applied.
- Router IPs and subnet masks are set as per network diagram.
- RIP v2 is configured to dynamically advertise all networks.
- Static routes are not required due to RIP.
