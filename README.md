# Networking-Projects- Packet tracer
Projects to help me develop networking skills and practice and implement what im learning. 


project 1
## Inter-LAN Routing Project (Packet Tracer)

### Objective
Build and troubleshoot a multi-LAN network using a single router and multiple switches.

### Topology
- 1 Router (Cisco 2911)
- 3 Switches (2950)
- 4 PCs
- 3 separate IP networks

### Addressing Summary
- LAN 1: 13.0.0.0/8
- LAN 2: 187.77.0.0/16
- LAN 3: (if applicable)

### Issue Encountered
PCs on different networks could not ping each other.

### Root Cause
Incorrect default gateway configured on LAN 2 (187.255.255.254).

### Resolution
Updated default gateway to 187.77.255.254. Connectivity restored.
