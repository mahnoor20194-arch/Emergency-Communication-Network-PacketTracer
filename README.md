# 📡 Emergency Communication Network System

A resilient and fault-tolerant network infrastructure designed using **Cisco Packet Tracer** to provide critical communication channels during emergency and disaster recovery scenarios.

---

## 📌 Project Overview

During emergencies (e.g., natural disasters, grid failures), standard communication networks often fail. This project models a robust emergency network architecture that guarantees reliable data transmission, low-latency communication, and high availability between command centers, emergency responders, and field units.

### Key Features
* 🔄 **Network Redundancy & High Availability:** Implemented redundant links and routing to prevent single points of failure.
* 🌐 **VLAN Segmentation:** Segregated traffic into separate Virtual LANs (e.g., Admin, Medical Services, Field Operations, VoIP).
* 🔒 **Network Security:** Applied Access Control Lists (ACLs) to secure sensitive emergency database servers and restrict unauthorized access.
* 📞 **VoIP & Wireless Services:** Configured IP phones and wireless access points for rapid field deployment and communication.
* 🛣️ **Dynamic Routing:** Utilized dynamic routing protocols (OSPF/EIGRP) for fast route convergence during link failures.

---

## 🛠️ Network Technologies & Protocols Used

* **Simulation Tool:** Cisco Packet Tracer
* **Routing Protocols:** OSPF / EIGRP / Static Routing
* **Switching Concepts:** VLANs, Trunking (802.1Q), Inter-VLAN Routing, Spanning Tree Protocol (STP)
* **Addressing & Security:** IPv4 Addressing, Subnetting (VLSM), DHCP, NAT, Standard/Extended ACLs

---

## 📂 Repository Structure

```text
Emergency-Communication-Network/
├── topology/            # .pkt Packet Tracer file
├── screenshots/         # Network diagrams and ping/simulation tests
├── documentation/       # Project report / Network layout documentation
└── README.md            # Project documentation
