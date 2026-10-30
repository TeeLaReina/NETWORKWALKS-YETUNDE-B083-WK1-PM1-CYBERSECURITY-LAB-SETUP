# NETWORKWALKS-YETUNDE-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP
Cybersecurity home lab setup - VirtualBox NAT Network, Kali Linux static IP, shared folder, snapshot baseline. NetworkWalks WK1-PM1.

## Overview
Cybersecurity home lab setup on VirtualBox - Week 1, Project Module 1.
Configured a Kali Linux VM on an isolated NAT Network with static IP,
internet connectivity, shared folder, and snapshot baseline.

## Lab Environment
- **Host OS:** Windows 10
- **Hypervisor:** Oracle VirtualBox
- **VM:** Kali Linux (KaliP)
- **Network:** NAT Network - NetworkWalks (10.0.0.0/24)
- **VM Static IP:** 10.0.0.2/24
- **Gateway:** 10.0.0.1
- **DNS:** 8.8.8.8, 8.8.4.4

## Steps Completed
1. Created isolated NAT Network (NetworkWalks, 10.0.0.0/24)
2. Attached Kali VM to NAT Network
3. Enabled Bidirectional Clipboard and Drag-and-Drop
4. Configured Shared Folder (Downloads) with Auto-mount
5. Set static IP (10.0.0.2/24) via nmcli
6. Verified internet connectivity (ping 8.8.8.8 - 0% packet loss)
7. Took VirtualBox snapshot: NetworkWalks-WK1-PM1-Baseline

## Tools Used
- Oracle VirtualBox
- Kali Linux
- nmcli (NetworkManager CLI)

## Screenshots
See `/screenshots` folder for evidence of each step.
