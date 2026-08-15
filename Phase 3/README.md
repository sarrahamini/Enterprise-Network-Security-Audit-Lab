# Phase 3 — Network Security Audit

## Overview

This phase focused on assessing the security of the network using **Nmap** for network and service enumeration and **Wireshark** for network traffic analysis.

A **Metasploitable 2** virtual machine was used as the target system in a controlled lab environment.

## Objectives

* Identify active hosts and open ports.
* Enumerate running services and their versions.
* Perform operating system detection.
* Analyze network traffic generated during security testing.
* Identify potential security weaknesses.
* Document findings and provide security recommendations.

## Security Assessment

The following Nmap scans were performed:

* Host Discovery
* Service & Version Detection
* Operating System Detection
* Aggressive Scan
* Full TCP Port Scan
* SYN Scan

The assessment identified multiple open TCP ports and services running on the target system.

## Traffic Analysis

**Wireshark** was used to capture and analyze network traffic between the Kali Linux machine and the Metasploitable 2 target during the Nmap security assessment.

The captured traffic was examined to understand how network scanning activity appears at the packet level.

## Tools Used

* **Kali Linux**
* **Nmap**
* **Wireshark**
* **Metasploitable 2**

## Screenshots & Report

Screenshots documenting the security assessment and traffic analysis are available in the `Screenshots` folder.

The complete findings, analysis, and recommendations are documented in the **Final Report.pdf**.

## Outcome

The security audit provided hands-on experience with network reconnaissance, service enumeration, port scanning, operating system detection, and packet-level traffic analysis in a controlled enterprise network environment.
