# Smart Street Camera — Network Architecture

A resilient and secure network architecture designed for a **Smart Street Camera System** that detects road accidents in real time and sends alerts to users and responders.

The network connects roadside cameras, AI processing servers, administrative systems, firewalls, DMZ services, and external users. The architecture was implemented and validated in **EVE-NG Community Edition** using real vendor operating-system images.

## Key Features

* VLAN segmentation for cameras, AI systems, administration, management, servers, screens, and DMZ services
* Inter-VLAN routing using Layer 3 switches
* HSRP gateway redundancy
* OSPF dynamic routing
* LACP / EtherChannel link redundancy
* Rapid-PVST+ for Layer 2 loop prevention
* Dual-core and redundant network design
* Active/Standby Firewall HA
* DMZ architecture with Reverse Proxy, WAF, and API Gateway
* Least-privilege firewall policies and network isolation
* Local edge AI processing for low-latency accident detection

The design focuses on **high availability, security, scalability, redundancy, and real-time performance**.
