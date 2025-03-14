# Project: Virtual HomeLab Setup with Hyper-V using Windows 11 Pro

## Table of Contents
1. [Project Overview](#overview)
2. [Objectives](#objectives)
3. [Network Topology](#network-topology)
4. [Hardware Setup](#Hardware-Setup)
5. [Lab Environment Setup](#lab-environment-setup)
    - [Prerequisites](#prerequisites)
    - [Network Diagram](#network-diagram)
    - [Installation and Setup](#installation-and-setup)
6. [Results](#results)
7. [Contributing](#contributing)
8. [Conclusion](#conclusion)
9. [Contact](#contact)

____

## Project Overview

This project involves setting up a home lab using Hyper-V on a Windows 11 Pro machine, with a focus on creating a secure and scalable environment. 
The lab will consist of multiple virtual machines (VMs), including Kali Linux, Windows Server 2022, an Ubuntu Server for Splunk, an Email Server, and an Elastic Monitoring Server. Additionally, the lab will integrate a pfSense firewall to manage traffic between the internal and external networks, ensuring both security and performance.

The physical environment will include a laptop connected wirelessly to the network and a desktop connected via Ethernet, representing different client devices accessing the virtualized services.



## Objectives

- Create a virtualized lab using Hyper-V.
- Deploy multiple VMs for different use cases like penetration testing, monitoring, and server management.
- Secure the network using pfSense firewall to control traffic between internal VMs and the physical network.
- Learn and demonstrate system administration, network security, and log management.
- Utilize multiple devices to simulate a real-world environment.



## Network Topology 

![Network Topology](https://github.com/TcyberSec/Virtual-HomeLab-Setup-with-Hyper---V-/blob/main/Network%20Topology.png)

## Hardware Setup

### Host Machine
- **Operating System**: **Windows 11 Pro**
- **Virtualization Platform**: **Hyper-V**
- **CPU**: 8 cores
- **RAM**: 32 GB
- **Storage**: 500 GB SSD

### Physical Machines
- **Laptop**: **Windows 11 Home**, connected wirelessly.
- **Desktop**: **Windows 11 Pro**, connected via Ethernet.
