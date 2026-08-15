# Phase 1 — Network Design & Configuration

## Overview

This phase focused on designing and configuring the enterprise network environment for the **Enterprise Network Security Audit Lab** using Cisco Packet Tracer.

The objective was to create a structured enterprise network that could later be hardened and security-audited using security tools such as Nmap and Wireshark.

## Objectives

* Design an enterprise-style network topology.
* Configure routers and switches.
* Connect multiple departmental systems.
* Configure internal network services.
* Establish communication between network devices.
* Create a functional network environment for the later security-audit phases.

## Tools Used

* **Cisco Packet Tracer**

## Network Design

The network was designed with a central router connected to multiple switches representing different parts of the enterprise network.

The environment includes:

* **Router**
* **Switch 1**
* **Switch 2**
* **HR workstations**
* **Finance workstations**
* **IT workstations**
* **Web Server**
* **DNS Server**

### Logical Structure

```text
                         Internet
                            |
                         Router
                            |
                +-----------+-----------+
                |                       |
             Switch 1                Switch 2
                |                       |
          +-----+-----+           +-----+-----+
          |           |           |           |
         HR          HR        Finance      Finance
         PC           PC          PC           PC
                                   
                         +----------------+
                         |                |
                        IT              Servers
                        PCs          Web / DNS
```

*The diagram above represents the logical structure of the network. The actual topology is available in the Packet Tracer file.*

## Configuration

During this phase, the network devices were configured to establish connectivity across the enterprise environment.

The configuration included:

* Connecting the router and switches.
* Connecting departmental hosts to the appropriate switches.
* Assigning IP addressing to network devices and hosts.
* Configuring the Web Server.
* Configuring the DNS Server.
* Establishing network communication between devices.
* Testing connectivity using appropriate network tests.

## Screenshots

Screenshots documenting the network design and configuration are included in the `Screenshots` folder.

They provide visual evidence of:

* Network topology
* Device configuration
* IP addressing
* Server configuration
* Connectivity testing

## Project Files

| File/Folder          | Description                                          |
| -------------------- | ---------------------------------------------------- |
| `Packet Tracer file` | Complete Phase 1 network topology and configuration  |
| `Screenshots/`       | Screenshots documenting the design and configuration |

## Outcome

At the end of Phase 1, a functional enterprise network environment was established in Cisco Packet Tracer.

This network serves as the foundation for the next phases of the project, where security hardening and network security auditing will be performed.

## Next Phase

**Phase 2 — Network Hardening**

The next phase focuses on improving the security of the network by implementing measures such as device password protection, secure configurations, port security, disabling unused ports, and other network-hardening techniques.

