# Palo Alto

## 01. Platform and Architecture

* Palo Alto Networks Portfolio overview
  - Palo Alto Networks Approach to Cybersecurity
  - Network Security = NGFW, VM-Series NGFM, CN-Series NGFW
* Next-generation firewall architecture
  - Palo Alto Networks Single-Pass Architecture
  - Palo Alto Networks Firewall Architecture = Control Plane, Data Plane
  - Zero Trust Architecture
* Firewall offerings
  - Flexible Architecture
  - PA-Series Next-Generation Firewalls
  - Virtual Systems
  - VM-Series Capacities
  - CM-Series Firewall

## 02. Firewall Initial Configuration

* Initial System Access
  - Administrative Access Tools = Web Interface, Panorama, SSH/Console CLI, REST/XML API
* Configure management network setting
  - MGT Interface Configuration
  - Configure Access to DNS and NTP Services
  - Service Routes = MGT port
* Activate a firewall, and management licenses and software
  - Activate a Firewall
  - Manage Firewall Licenses
  - PAN-OS Software Updates, Dynamic Updates

## 03. Firewall Configuration

* Configuration management
  - Configuration Type = Running, Candidate
  - Configuration operations
  - Full Commit, Per-Admin Commit
  - Transaction Locks and Multiple Administrators
* View firewall logs

## 04. Firewall Administrator Accounts

* Firewall authentication and authorization
  - Administrator Accounts and Roles
  - Create Custom Role-Based Admin Roles
* Create a local firewall administrator account
  - Local Administrator, User, User Database, Local Database
* Create a non-local firewall administrator account
* Create a firewall administrator account for non-interactive login
  - User Certificate

## 05. Connecting Security Zones

* Security Zones overview
  - Network Segmentation, Security Policy
* Network interfaces and security zones
* Interfaces Types
  - Tap, Virtual Wire, Layer 3, Layer 3 Subinterfaces
* Virtual routers and Layer 3 interfaces

## 06. Security Policies

* Security policy fundamental concepts
  - Flow Logic
  - Sessions and Flows
  - Security Policy Rule Types = Intrazone, interzone, universal
  - Rule Shadowing
* Security policy administration

## 07. NAT Policies

* Network address translation
* Source NAT configuration
  - Static IP, Dynamic IP, DIPP (Dynamic IP and port)
* Destination NAT configuration

## 08. Application Identity

* App-ID reduces the attack surface
  - Port-based vs Next-Generation Firewalls
  - IPS vs App-ID
  - App-ID and TCP
  - App-ID and UDP
* App-ID concepts and operation
* Configure App-ID objects
* Unknown and encrypted application traffic
  - Control Application on SSL-secure Ports or Non-Standard Ports
  - Identify Applications in Decrypted SSL Traffic or Encrypted SSL Traffic
* Migrating to an App-ID-based Security Policy
  - Application-Based Policies (Port-Based Rule)
* Updating App-ID

## 09. Security Profiles

* Security Profile overview
  - Threat Log
* Vulnerability Protection Security Profiles
  - Vulnerability Exception
  - Inline Cloud Analysis
* Antivirus Security Profiles
* Anti-Spyware Security Profiles
  - Anti-Spyware Exception
  - DNS Signature Match Protection
  - Sinkhole Operation
  - DNS Exceptions
  - Inline Cloud Analysis
* File Blocking Profiles
* Data Filtering Profiles
* Attaching Security Profiles to Security policy rules

## 10. URL Filtering

* Advanced URL Filtering Overview
  - URL Category: Policy vs Profile
* Configuring Advanced URL Filtering Security Profiles
* Attaching Advanced URL Filtering Profiles to Policy Rules

## 11. Wildfire

* WildFire Concepts
  - WildFire Threat Intelligence Cloud
* Configure and manage WildFire
* WildFire reporting

## 12. User Identity

* User-ID overview
  - User-ID Component = Palo Alto Networks firewall, PAN-OS integrated, Windows-based, Palo Alto Networks Terminal Services agent
* User mapping methods overview
* Configure User-ID
  - User-ID per Zone
* PAN-OS integrated agent configuration
* Configure group mapping
* User-ID and Security policy

## 13. Encrypted Traffic

* SSL/TLS review
* Certificate management
  - PKI
  - Certificate Hierarchy
* SSL/TLS decryption
* SSH decryption
* Other decryption methods and features
  - Port Mirroring, Network Packet Broker, Hardware Security Module (HSMs)

## 14 Logs and Reports

* In the Dashboard
* In the ACC (Application Command Center)
* In the logs
  - Traffic log, Threat log, URL Filtering Log, WildFire Submissions Log, Data Filtering Log, Unified Log
* In App Scope reports
* In predefined reports
* In custom reports
