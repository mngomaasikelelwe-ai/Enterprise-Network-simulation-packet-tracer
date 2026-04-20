# Enterprise Network Design – Cisco Packet Tracer

#Summary

This project demonstrates the design and implementation of a multi-department enterprise network using Cisco Packet Tracer. The network includes VLAN segmentation, dynamic IP allocation, routing protocols, and security configurations.

## 🏢 Network Structure

The network is divided into multiple departments and floors:

* Developers Network (192.168.0.0/28)
* Business Analysts Network (192.168.0.32/27)
* Second Floor VLANs:

  * VLAN 10 – Test Engineers
  * VLAN 20 – UI Designers
  * VLAN 30 – Shared Resources
* Third Floor Server Network (192.168.1.0/24)

## ⚙️ Technologies Implemented

* DHCP (Dynamic Host Configuration Protocol)
* DNS Server Configuration
* VLAN Segmentation
* Inter-VLAN Routing
* Static & Dynamic Routing (RIP v2 and OSPF)
* NAT (Network Address Translation)
* Access Control Lists (ACLs)

## 🌐 Key Features

### DHCP & DNS

* Automated IP address assignment per department
* Central DNS server resolving internal web services

### VLAN Implementation

* Departmental isolation using VLANs
* Controlled communication between VLANs
* Shared resource access (e.g., printer)

### Routing

* RIP v2 configured on developer router
* OSPF configured on shared router
* Route redistribution implemented
* Backup routes configured using administrative distance

### 🔐 Security

* Extended ACLs for traffic filtering
* VLAN-based access restrictions
* NAT for internal-to-external communication
* Basic network segmentation for security

### 🌍 Server Environment

* Web Server
* System Log Server
* Staging Server

## 🧪 Testing & Validation

* Successful DHCP allocation across departments
* DNS resolution for internal web server ([www.production.com](http://www.production.com))
* VLAN communication restrictions verified
* NAT translation confirmed
* ACL deny/permit rules tested

## 🛡️ Security Improvements (Proposed)

* DMZ implementation for staging server
* Split-horizon DNS for internal/external users
* SIEM integration for event monitoring
* Control-plane and data-plane protection policies

## 📁 Files Included

* Packet Tracer file (.pkt)
* Network documentation (PDF)
* Screenshots of configurations and testing

## 🚀 Skills Demonstrated

* Network design and subnetting
* Routing protocol configuration (RIP & OSPF)
* VLAN and switching concepts
* Network security implementation (ACLs, NAT)
* Troubleshooting and testing
* ## 🧩 Packet Tracer Simulation

## 📸 Network Simulation Screenshots

Here is the full network simulation setup:

![Network Simulation](screenshots/network.png)
## 📸 Network Simulation Project

### 🖧 Topology, Configuration & Testing

This project demonstrates:
- Network topology design
- Router configuration
- Connectivity testing

![Full Simulation](screenshots/network.png)

Download and open the full network simulation:
Viewing requires cisco packet tracer to open pkt files

## 👩🏽‍💻 Author

Asikelelwe Awonke Mngoma
