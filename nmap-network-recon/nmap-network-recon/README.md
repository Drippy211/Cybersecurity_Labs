# Nmap Network Reconnaissance Lab

## Overview

This lab documents a basic network reconnaissance exercise performed in my Kali Linux virtual machine.

The objective was to use Nmap to identify the network status, TCP ports, and available services on an authorized local lab system.

## Lab Environment

- Operating System: Kali Linux
- Virtualization: Oracle VirtualBox
- Network Interface: eth0
- Target: My own Kali Linux VM
- Target IP: 10.0.2.15
- Network: 10.0.2.0/24
- Tool: Nmap 7.99

## Objective

The objectives of this exercise were to:

1. Verify that Nmap is installed and working.
2. Perform TCP port reconnaissance.
3. Identify available services.
4. Save the scan results for documentation.
5. Interpret the results from a defensive security perspective.

## Commands Used

Check Nmap version:

```bash
nmap --version
