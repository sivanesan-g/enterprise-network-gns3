# Enterprise Network Design & Implementation (Cisco)

## Project Overview
This project demonstrates the design and implementation of a multi-router enterprise network using Cisco technologies. The network was built to simulate a real-world enterprise environment with routing, switching, IP addressing, VLAN segmentation, DHCP services, and NAT for connectivity and optimization.

## Objectives
- Design a multi-router enterprise topology
- Configure dynamic routing using OSPF and EIGRP
- Implement VLANs for network segmentation
- Enable Inter-VLAN Routing for communication between VLANs
- Configure NAT (Static, Dynamic, and PAT)
- Deploy DHCP services for automatic IP assignment
- Achieve full network connectivity and routing optimization

## Technologies Used
- Cisco Routers
- Cisco Switches
- GNS3 / Cisco Packet Tracer
- OSPF
- EIGRP
- VLANs
- Inter-VLAN Routing
- NAT
- DHCP

## Network Features
- Multi-router enterprise topology
- Dynamic routing with OSPF and EIGRP
- VLAN-based segmentation
- Inter-VLAN communication
- Static NAT
- Dynamic NAT
- PAT (Port Address Translation)
- DHCP IP address allocation
- End-to-end connectivity verification

## Topology
Example topology:

        [R1] ------- [R2] ------- [R3]
          |                         |
          |                         |
        [SW1]                     [SW2]
        /   \                     /   \
     VLAN10 VLAN20           VLAN30 VLAN40

> You can replace this with your actual topology screenshot from GNS3 or Packet Tracer.

## Configuration Modules

### 1. Routing
- Configured OSPF for dynamic route exchange
- Configured EIGRP for internal routing communication
- Verified route propagation across routers

### 2. VLANs and Inter-VLAN Routing
- Created VLANs to separate departments/users
- Assigned switch ports to respective VLANs
- Configured router-on-a-stick or Layer 3 routing for Inter-VLAN communication

### 3. NAT
- Configured Static NAT for fixed address mapping
- Configured Dynamic NAT using address pools
- Configured PAT for multiple hosts sharing a single public IP

### 4. DHCP
- Created DHCP pools for different subnets
- Assigned default gateway and DNS settings
- Verified automatic IP allocation to end devices

## Verification
The following tests were performed:
- Ping between routers
- Ping between VLANs
- Routing table verification
- NAT translation verification
- DHCP lease verification
- End-to-end connectivity testing

## Results
- Full connectivity achieved across all routers and VLANs
- OSPF and EIGRP routing worked successfully
- NAT translations operated correctly
- DHCP assigned IP addresses automatically
- Network performed as expected in the simulated enterprise environment

## Skills Demonstrated
- Enterprise network design
- Routing and switching
- Dynamic routing protocol configuration
- VLAN and Inter-VLAN implementation
- NAT and DHCP deployment
- Network troubleshooting and verification

## Screenshots
Include:
- Topology diagram
- Router configurations
- VLAN configuration
- Routing table output
- NAT translation output
- DHCP binding output
- Successful ping test results

## Future Improvements
- Add ACLs for traffic filtering
- Implement HSRP/VRRP for redundancy
- Add firewall integration
- Introduce BGP for advanced routing scenarios
- Add network monitoring and logging

## Author
**Sivanesan G**  
Junior Network & Security Engineer  
[LinkedIn](https://www.linkedin.com/in/sivanesan-g)  
[GitHub](https://github.com/sivanesan-g)
