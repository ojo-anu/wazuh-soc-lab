# Wazuh Multiple Endpoint Monitoring Lab

## Overview
This project demonstrates how a Wazuh SIEM environment can monitor multiple endpoints from a single manager.

In this lab, both an Ubuntu server and a Windows system were connected to the Wazuh manager. This allows centralized monitoring of logs, security events, and system activity across different operating systems.

## Lab Environment

Wazuh Manager: Wazuh SIEM running on a virtual machine

Endpoint 1:
Ubuntu Server with Wazuh Agent installed

Endpoint 2:
Windows Operating System with Wazuh Agent installed

Network:
VirtualBox internal network

## Implementation Steps

1. Installed Wazuh Manager on a dedicated virtual machine.
2. Installed and configured the Wazuh agent on an Ubuntu server.
3. Installed the Wazuh Windows agent on a Windows machine.
4. Registered the Windows agent with the Wazuh manager using an authentication key.
5. Verified both endpoints were successfully connected and reporting to the Wazuh dashboard.

## Detection Capability

With multiple endpoints connected, Wazuh can monitor:

System logs  
Authentication attempts  
File integrity changes  
Security alerts  
Network activity  

This setup simulates a real Security Operations Center (SOC) environment where a SIEM monitors multiple hosts.

## Result

Both the Ubuntu server and Windows endpoint appeared as active agents in the Wazuh dashboard, confirming successful centralized monitoring.

## Screenshots

See the screenshots folder for evidence of agent registration and monitoring.
