# Enterprise Network Design & Routing Simulation — Cisco Packet Tracer

## Overview
A multi-department enterprise network topology designed and simulated using Cisco Packet Tracer, 
focused on optimizing throughput, internal traffic segmentation, and secure routing between 
departments.

## Files in this Repository
- `enterprise-network-vlan-ospf.pkt` — Full Packet Tracer simulation file
- `topology-screenshot.png` — Network topology overview

## Design Components

**1. VLAN Segmentation**
- Configured multiple VLANs to logically separate departments and reduce broadcast domains
- Implemented Trunking (802.1Q) to carry multiple VLANs across switch links

**2. Inter-VLAN Routing**
- Configured Inter-VLAN routing using Router-on-a-Stick and Layer 3 Switching methods
- Enabled seamless communication between isolated department VLANs where required

**3. Dynamic Routing**
- Implemented single-area OSPF for automated path selection and rapid network convergence
- Configured for link redundancy to minimize downtime during link failures

**4. Access Control**
- Applied Standard and Extended Access Control Lists (ACLs) to restrict unauthorized 
  access to administrative network segments
- Enforced department-level traffic policies

## Skills Demonstrated
- VLAN design and configuration
- Trunking (802.1Q)
- Router-on-a-Stick / Layer 3 Inter-VLAN Routing
- OSPF dynamic routing protocol
- Standard & Extended ACLs
- Network segmentation and broadcast domain reduction

## How to View
Open the `.pkt` file using [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) 
(free with a Cisco Networking Academy account) to explore the full topology, device configurations, 
and simulation.

## Author
**Rejish C.S.**  
CCNA Certified | AWS Certified Solutions Architect – Associate  
[LinkedIn](https://linkedin.com/in/rejish-cs-712590240)
