# Virtualization

## VMware vSphere: Install, Configure, Manage

### 1. Course Introduction

### 2. Introduction to vSphere and the Software-Defined Data Center

1. Overview of vSphere and Virtual Machines
   * Types of Virtualization = Server, Network, Storage, Desktop
   * vSphere Client = vSphere Web Client, vSphere Client, and VMware Host Client
   * Provisioned Virtual Disks = Thick and Thin
   * Virtual Network
   * Miscellaneous Devices
2. Share Resources: Overview of ESXi
   * ESXi = hypervisor

### 3. Creating Virtual Machines

* OVF Templates
* VMware Tools

### 4. vCenter Server

1. Centralized Management: Overview of vCenter Server
2. vCenter Server Appliance
3. Deploying vCenter Server Applicance
4. Managing the vCenter Server Inventory
5. vCenter Server Roles and Permissions
6. Backing Up and Restoring vCenter Server Appliance
7. Monitoring vCenter Server Appliance

### 5. Configuring and Managing Virtual Networks

1. Introduction to vSphere Standard Switches
   * Virtual Switch Connections = Virtual machine port groups, VMkernel port, Uplink ports
   * Adding ESXi Networking
   * Standard Switch vs Distributed Switch
2. Configuring Standard Switch Policies
   * Traffic-shaping
   * NIC teaming and failover

### 6. Configuring and Managing Virtual Storage

1. Storage Concepts
2. Fibre Channel Storage
3. iSCSI Storage (Internet Small Computer System Interface)
   * Challenge Handshake Authentication Protocol (CHAP)
4. VMFS Datastores (Virtual Machine File System)
5. NFS Datastores (Network File System)
6. vSAN Datastores
   * Hybervisor-concerged, software-defined storage for virtual environments
   * vSphere Virtual Volumes
   * RDM (Raw Device Mapping)

### 7. Virtual Machine Management

1. Creating Templates and Clones
2. Working with Content Libraries
   * Benefits = Sharing and Consistency, Storage Efficiency, Secure Subscription
3. Modifying Virtual Machines
4. Migrating Virtual Machines
   * Types = Colds, Suspended, vSphere vMotion, vSphere Storage vMotion, Shared-nothing vSphere vMotion
   * EVC (Enhanced vMotion Compatibility)
5. Creating Virtual Machine Snapshots
   * Snapshots enable you to preserve the state of the virtual machine so that you can repeatedly return to the same state.
   * Type = VMFSsparse, SEsparse, vsanSparse

### 8. Resource Management and Monitoring

1. Virtual CPU and Memory Concepts
2. Resource Controls and Resource Pools
3. Monitoring Resource Use
4. Using Alarms

### 9. vSphere HA, vSphere Fault Tolerance, and Protecting Data

1. Introduction to vSphere HA (High Availability)
2. vSphere HA Architecture
3. Configuring vSphere HA
4. Introduction to vSphere Fault Tolerance
5. vSphere Replication

### 10. vSphere DRS (Distributed Resource Scheduler)

### 11. vSphere Update Manager

### 12. vSphere Troubleshooting

### TDI (Tactical Data Infrastructure)

* Purpose:
  - TDI aims to enhance cyber defense capabilities by providing tools for identifying and mitigating cyber threats within the Army's tactical network.

* Functionality:
  - Active Hunt and Defense: TDI offers capabilities to proactively identify and defend against cyber threats.
  - Mission Impact Analytics: The system provides commanders with insights into the potential impact of cyber events on their mission.
  - Ease of Use: TDI is designed to be user-friendly, allowing local defenders to effectively assess and manage cyber threats.

* TSI (Tactical Server Infrastructure)
  - A program focusing on delivering server hardware platforms that host the Command Post Computing Environment (CPCE).
  - Enterprise software for various Army units, ranging from Battalion to Army Service Component Command. 

* Security Onion
  - A free, open-source Linux distribution used for threat hunting, network security monitoring, and log management
