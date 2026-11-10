# NetSentinel – Intelligent Network Segmentation & Firewall Rule Optimizer

NetSentinel is a Linux-based network security project designed to monitor network traffic, enforce firewall policies, and identify opportunities to improve firewall rule efficiency.

The project uses **Linux network namespaces and nftables** to create an isolated network environment with separate client, firewall, and server segments. It applies firewall rules to control communication between network segments, allowing authorized traffic while blocking restricted connections.

A **Python FastAPI backend** collects firewall rule counters and network traffic statistics, while a **React-based dashboard** displays firewall rules, packet and byte counts, traffic history, and optimization findings in a user-friendly interface.

### Key Features
- Network segmentation using Linux network namespaces.
- Firewall policy enforcement using nftables.
- Allow and block rules for specific network services.
- Real-time collection of firewall packet and byte counters.
- Traffic history visualization through a React dashboard.
- Identification of unused firewall rules using zero-hit analysis.
- Firewall rule monitoring and optimization insights.
- REST API integration using Python FastAPI.

### Technologies Used
- **Operating System:** Linux (Ubuntu)
- **Firewall:** nftables
- **Backend:** Python, FastAPI
- **Frontend:** React.js, Vite
- **Networking:** Linux Network Namespaces, TCP/IP
- **Data Visualization:** React and SVG charts

### Project Objective
The main objective of NetSentinel is to demonstrate how network segmentation, firewall monitoring, and rule optimization can improve network security, visibility, and traffic control in a controlled Linux environment.

This project is intended for learning and demonstrating practical network security, Linux firewall administration, and full-stack development.
