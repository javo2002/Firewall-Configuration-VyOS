# VyOS Firewall and Routing Lab

## About
This project involved configuring and securing a **VyOS router** with three Ethernet interfaces to manage traffic between a **local corporate network**, a **DMZ (Demilitarized Zone)**, and a **simulated Internet connection**. Firewall rules and routing policies were implemented to optimize network security, segment traffic, and ensure efficient communication between networks. The lab demonstrates hands-on experience with network routing, firewall configuration, and subnet management using VyOS and Unix/Linux command-line tools.

---

## Tools and Technologies Used
- **VyOS Router**: For routing, firewall, and network configuration.
- **Unix/Linux Command Line**: For configuring and managing the VyOS router.
- **Graphical Desktop Systems**: For testing and validating network configurations.
- **Basic Networking Tools**: Ping, traceroute, and DNS utilities.
- **Firewall Configuration Tools**: VyOS command-line tools for setting up firewall rules.
- **Network Simulation**: Simulated local network (10.12.0.x), DMZ (10.11.0.x), and Internet connection.

---

## Key Features
- **Multi-Interface Configuration**: Configured three Ethernet interfaces on the VyOS router for the local network, DMZ, and Internet.
- **Firewall Rules**: Implemented strict firewall rules to control traffic between the local network, DMZ, and Internet, preventing unauthorized access.
- **Routing Policies**: Set up routing policies to ensure efficient and secure communication between subnets.
- **Network Segmentation**: Secured the DMZ by isolating it from the local corporate network while allowing controlled access to external traffic.
- **Testing and Validation**: Used graphical desktop systems to test and validate network configurations, ensuring proper functionality of firewall rules and routing policies.

---

## Logical Network Diagram
![Logical Architecture Diagram](./images/Network.png)

---

## Steps to Reproduce
1. **Set Up VyOS Router**:
   - Configure three Ethernet interfaces:
     - `eth0`: Connected to the simulated Internet.
     - `eth1`: Connected to the DMZ (10.11.0.x).
     - `eth2`: Connected to the local corporate network (10.12.0.x).
   - Set up firewall rules to control traffic between networks.
   - Configure routing policies to manage traffic flow.

2. **Test Connectivity**:
   - Use `ping` and `traceroute` to test connectivity between the local network, DMZ, and Internet.
   - Validate DNS resolution and network performance.

3. **Implement Firewall Rules**:
   - Create rules to block unauthorized access to the local network from the DMZ and Internet.
   - Allow necessary traffic (e.g., HTTP/HTTPS) to the DMZ for external access.

4. **Monitor and Troubleshoot**:
   - Use VyOS command-line tools to monitor network traffic and troubleshoot issues.
   - Verify that firewall rules and routing policies are functioning as intended.

---

## Skills Demonstrated
- **Network Configuration**: Setting up and managing network interfaces, subnets, and routing.
- **Firewall Management**: Implementing and optimizing firewall rules for network security.
- **Network Segmentation**: Securing the DMZ and isolating it from the local network.
- **Troubleshooting**: Diagnosing and resolving network connectivity issues.
- **Command-Line Proficiency**: Using Unix/Linux commands to configure and manage the VyOS router.

---

## Future Enhancements
- **Integration with SIEM Tools**: Enhance monitoring by integrating VyOS with tools like Splunk or ELK Stack.
- **VPN Configuration**: Set up a VPN for secure remote access to the local network.
- **Automation**: Use scripts to automate firewall rule updates and network monitoring.

---
