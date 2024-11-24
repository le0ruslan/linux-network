# Linux Network Configuration and Analysis

## Overview

This project focuses on configuring and analyzing Linux network settings in virtualized environments. It explores various network topics, from basic IP address calculations to advanced routing, firewall configuration, and NAT implementation. The project was completed in a step-by-step manner, with detailed documentation provided in the accompanying `report.md`.

## Key Tasks Completed

### Part 1: IP Address and Mask Calculations
- Used the **ipcalc** tool to perform calculations related to network addresses, prefixes, and binary masks.
- Identified public and private IPs, valid gateways, and addressed localhost behavior.

### Part 2: Static Routing
- Configured static routes between two virtual machines using manual and persistent methods.
- Verified connectivity using `ping` and documented configurations in `netplan` files.

### Part 3: Connection Speed Analysis
- Utilized **iperf3** to measure the connection speed between machines.
- Converted various speed units for better understanding and documented results.

### Part 4: Firewall Configuration
- Set up firewalls using **iptables** with different strategies on two machines.
- Restricted and allowed specific traffic types (e.g., SSH, HTTP, ICMP) and verified the configurations using **nmap**.

### Part 5: Static Network Routing
- Created a network of five machines (workstations and routers).
- Configured IP forwarding, default routes, and static routes for seamless connectivity.
- Analyzed routing paths using **traceroute** and captured traffic with **tcpdump**.

### Part 6: DHCP Configuration
- Configured **DHCP** services on routers for dynamic IP assignment.
- Tested address allocation based on MAC addresses and described DHCP server options.

### Part 7: NAT Implementation
- Implemented **SNAT** and **DNAT** for internal and external network communication.
- Configured Apache web servers to test NAT functionality and verified connections with `telnet`.

### Part 8: SSH Tunneling
- Demonstrated **SSH tunnels** for secure access to services behind closed networks.
- Configured and tested local and remote TCP forwarding to access a web server.

## Report and Documentation
The full report (`report.md`) includes:
- Detailed steps for each task.
- Screenshots of commands and configurations.
- Explanations of network behaviors and technologies.

## Key Learnings
- Practical knowledge of Linux networking tools and configurations.
- Understanding of routing, firewalls, NAT, DHCP, and tunneling mechanisms.
- Hands-on experience in troubleshooting and optimizing network connectivity.

## Note
Virtual machine image dumps were created during the process but are **not included in the repository** as per project guidelines.

---
For detailed explanations and outputs, please refer to `report.md`.
