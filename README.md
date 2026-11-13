# LACP EtherChannel & STP Network Redundancy

## 📌 Project Overview

This project demonstrates the implementation of **EtherChannel using LACP (Link Aggregation Control Protocol)** in a redundant switched network environment using Cisco Packet Tracer.

The network consists of three interconnected switches arranged in a triangular topology, with multiple physical connections between switches. LACP is configured to combine parallel physical links into logical Port-Channel interfaces, improving aggregate bandwidth and providing link redundancy.

Spanning Tree Protocol (STP) is also used to prevent Layer 2 switching loops while maintaining network stability.

This project demonstrates practical networking knowledge, switch configuration, link aggregation, redundancy, and network troubleshooting.

## 🎯 Project Objectives

- Implement EtherChannel using LACP.
- Configure LACP Active and Passive negotiation modes.
- Combine multiple physical links into logical Port-Channels.
- Understand bandwidth aggregation and link redundancy.
- Configure and analyze Spanning Tree Protocol (STP).
- Verify network connectivity between different switches.
- Test network resilience by disconnecting physical links.

## 🖥️ Network Topology

The network uses a three-switch triangular topology with six end devices.

**Network Components:**
- 3 Cisco Layer 2 Switches
- 6 End Devices (PCs)
- 3 EtherChannel connections
- Multiple physical Ethernet links
- LACP for link aggregation
- STP for loop prevention

## ⚙️ Technologies & Concepts

- Cisco Packet Tracer
- EtherChannel
- Link Aggregation Control Protocol (LACP)
- LACP Active and Passive Modes
- Port-Channel Configuration
- Spanning Tree Protocol (STP)
- Layer 2 Switching
- Network Redundancy
- Network Troubleshooting
- ICMP (Ping Testing)

## 🔧 Key Configurations

### 1. EtherChannel Configuration

Configured three separate EtherChannels between the interconnected switches using LACP.

Each EtherChannel combines multiple physical Ethernet interfaces into one logical interface.

### 2. LACP Configuration

Implemented LACP negotiation using Active and Passive modes to establish and maintain EtherChannel links.

### 3. Spanning Tree Protocol

Analyzed STP operation in the triangular network topology to understand root bridge selection, port roles, and loop prevention.

### 4. Network Connectivity Testing

Verified communication between PCs connected to different switches using ICMP ping commands.

### 5. Link Redundancy Testing

Disconnected individual physical links from active EtherChannels to observe network behavior and verify that the remaining member links could continue forwarding traffic.

## 🧪 Verification Commands

The following Cisco IOS commands were used to verify network configurations and operational status.

| Command | Purpose |
|---|---|
| `show etherchannel summary` | Verify EtherChannel status |
| `show interfaces trunk` | Check trunk interfaces |
| `show spanning-tree` | Analyze STP operation |
| `show running-config` | Verify switch configurations |
| `ping` | Test end-to-end connectivity |

## 📸 Project Screenshots

Screenshots demonstrating the network implementation and verification will be included here.

- Network Topology
- EtherChannel Configuration
- EtherChannel Verification Output
- Spanning Tree Protocol Output
- Successful Ping Results
- Link Failure and Recovery Testing

## 📂 Project Files

```text
LACP-EtherChannel-STP/
│
├── README.md
│
├── Packet-Tracer/
│   └── LACP-EtherChannel-STP.pkt
│
└── Screenshots/
    ├── network-topology.png
    ├── etherchannel-summary.png
    ├── spanning-tree.png
    ├── ping-results.png
    └── redundancy-test.png
```

## 📚 Key Learning Outcomes

Through this project, I gained practical experience in:

- Configuring and managing EtherChannel connections.
- Understanding LACP negotiation mechanisms.
- Working with logical Port-Channel interfaces.
- Understanding the relationship between EtherChannel and STP.
- Identifying and troubleshooting switching issues.
- Testing network redundancy and link failure recovery.

## 🛠️ Tools Used

**Cisco Packet Tracer**

--- 
## Project Files
- [Packet Tracer Project](./LACP EtherChannel & STP Network Redundancy.pkt)
- [Screenshots](./Screenshots/)

*Developed as a personal networking project to strengthen practical knowledge of switching, link aggregation, and network redundancy.*
