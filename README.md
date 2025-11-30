# DEPI_Project
Enterprise Network Design and Implementation Using  Huawei Datacom Technologies
# University Network System – Graduation Project (DEPI)

## 1. Project Overview
This project presents the design and simulation of a University Network System using Huawei eNSP simulator.
The network is designed to connect different university buildings such as Administration, Faculties, Labs,
and Data Center with secure, scalable, and efficient communication.

## 2. Project Objectives
- Design a reliable university campus network.
- Implement structured network segmentation.
- Ensure efficient communication between departments.
- Simulate a real enterprise-level university network using Huawei devices.

## 3. Network Topology
The network topology was implemented using Huawei eNSP and includes:
- 3 Routers (AR1220, AR2220, AR3260)
- 10 Access Switches (S3700)
- 2 Core/Distribution Switches (S5700)
- 18 PCs representing different university users
- 2 Servers (Application Server & Database Server)

The topology file is available in:
`network/finalprojectdepi.topo`

## 4. Network Design & Features
- VLAN segmentation for different university departments.
- IP addressing and subnetting for each VLAN.
- Inter-VLAN routing to enable communication between departments.
- Centralized core layer for traffic aggregation.
- Servers deployed in a dedicated Data Center segment.

## 5. Tools & Technologies
- Huawei eNSP Simulator
- Huawei Routers and Switches
- TCP/IP, VLANs, and Routing Concepts

## 6. How to Run the Project
1. Install Huawei eNSP.
2. Clone this repository:

