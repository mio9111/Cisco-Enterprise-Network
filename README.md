# Enterprise Campus Network Design

A Cisco Packet Tracer project that simulates a small enterprise network using a hierarchical design (Core - Distribution - Access).

---

## Project Overview

This project demonstrates the implementation of a secure and scalable enterprise network using Cisco Packet Tracer.

The network includes:

- VLAN segmentation
- Inter-VLAN Routing
- DHCP Relay
- Static Routing
- NAT
- Internet Simulation
- Extended ACLs
- Hierarchical Network Design

---

## Network Topology

> Add a screenshot of the network topology here.

![Topology](Images/topology.png)

---

## Network Architecture

The network follows Cisco's Hierarchical Network Design.

- Core Layer
- Distribution Layer
- Access Layer

---

## VLAN Design

| VLAN | Department | Network | Gateway |
|------|------------|---------|---------|
|10|HR|192.168.10.0/24|192.168.10.1|
|20|Finance|192.168.20.0/24|192.168.20.1|
|30|Sales|192.168.30.0/24|192.168.30.1|
|40|IT|192.168.40.0/24|192.168.40.1|
|50|Servers|192.168.50.0/24|192.168.50.1|
|99|Management|192.168.99.0/24|192.168.99.1|

---

## Technologies Used

- Cisco Packet Tracer
- Layer 2 Switching
- Layer 3 Switching
- VLAN
- Trunk (802.1Q)
- Inter-VLAN Routing
- DHCP
- DHCP Relay
- Static Routing
- NAT
- ACL

---

## Network Services

- DHCP Server
- Internet Simulation
- NAT Translation
- Access Control Lists

---

## Security

The following security policies were implemented:

- HR cannot access Finance
- Finance cannot access HR
- HR cannot access Sales
- Finance cannot access Sales
- IT has full access
- Internet access is allowed

---

## Testing

The following tests were completed successfully:

- VLAN Connectivity
- DHCP Address Assignment
- Inter-VLAN Routing
- Internet Access
- NAT Translation
- ACL Verification

---

## Project Structure

```text
Documentation/
Images/
Configs/
PacketTracer/
README.md
