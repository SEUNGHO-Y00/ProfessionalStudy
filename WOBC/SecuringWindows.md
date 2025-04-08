Securing Windows
Introduction to Windows Forensics
Day 1: Windows Forensics Overview
1. Fundamentals of Digital Forensics = Chain of custody, Write-blocking, Volatility order
* Chain of Custody = Collection, Transfer, Analysis, Storage, Presentation
* Write-Blocking Technology = Hardware Write-Blockers, Software Write-Blockers
*  Volatility Order in Digital Forensics = Most (CPU), Highly (RAM), Moderately (Windows Logs), Less (Hard disk data), Least (Backups)
2. Forensic Tools Overview = FTK Imager v4.5 (Creates forensic disk image), Autopsy 4.19 (Open-source), Magnet AXIOM 6.0 (Commercial End to End)
3. Legal Frameworks for Forensics = GDPR (EU), HIPPA (US)
* GDPR = Lawful Processing Requirements, Data Minimization Principles, Non-Compliance Penalties, Investigation Documentation
* HIPAA = PHI, Security Requirements, Breach Notification, Documentation Standards
4. Key Considerations in Digital Forensics = Data Integrity, Tool interoperability, Legal Documentation
* Data Integrity = Initial Hash Generation, Write-Protected Acquisition, Working Copy Creation, Verification Hashing, Documentation
* Tool Interoperability = Evidence Acquisition, Initial Analysis, Advanced Analysis, Reporting
* Legal Documentation = Chain of Custody Forms, Acquisition Logs, Analysis Records, Tool Validation Document
5. Windows Registry Forensics = Registry Structure, Forensic Value, Analysis Tools
* Structure = Hives (HKEY_LOCAL_MACHINE, HKEY_CURRENT_USER) / Keys, Values, and Data
* Analysis of Registry Data = User Activity, System Configuration, Security Settings
6. USB Device Forensics = Device Connection, Driver Installation, File Operations, Device Removal
7. Windows Event Log Analysis = Security Logs (4624/4625), System Logs (7045/7040), Application Logs (11707/11708), PowerShell Logs (4103/4104)
8. Browser Forensics in Windows = History Cookies, downloads, form data, and cached
9. Windows File System Forensics = NTFS Features, Deleted File recovery, Metadata Analysis
10. Windows Memory Forensics = Memory Acquisition, Process Analysis, Network Connections, Registry Hives, String Extraction
11. Windows Prefetch Analysis = stores data about executed applications to reduce load times
12. Windows Jump Lists Forensics = track recently and frequently accessed files and applications
13. Windows Timeline/Activity History Forensics = Local Storage, Cloud Synchronization, Application Usage, Web Activity
14. Windows Shellbags Forensics = a hidden treasure trove of information stored within the windows registry
15. Windows LNK File Analysis = windows shortcut files containing a binary shell link structure
16. Windows Volume Shadow Copy Service (VSS) = point-in-time snapshots of volumes
17. Windows Recycle Bin Forensics = $I, $R
18. Windows Thumbnail Cache Forensics = Thumbnail Creation for images, video, and documents
19. Windows Search Index Forensics = in an ESE database
20. Windows Event Tracing (ETW) Forensics = System, Application, Security, Custom
21. Windows Hibernation File Analysis = a compressed copy
22. Windows Pagefile Analysis = Virtual and temporarily memory management
23. Windows User Assist Registry Forensics
24. Windows SRUM forensics = System Resource Usage Monitor, application resource usage, network activity, and energy consumption
25. Windows Amcache Forensics = application execution and installation history, crucial evidence
26. Windows BAM/DAM Forensics = Background Activity Moderator, Desktop Activity Moderator
27. Windows PowerShell Forensics
28. Windows Scheduled Tasks Forensics
29. Windows Services Forensics
30. Windows Autoruns Forensics
31. Windows Event Log Tampering Detection = Log clearing, Service Manipulation, File Analysis, Timeline Gaps
32. Windows Forensics Reporting Writing = Executive Summary, Technical Details, Evidence Timeline, Conclusions, Appendices

Day 2: Advanced Windows Artifact Analysis & Memory Forensics
1. Types of Evidence = Real (Physical), Documentary (Hearsay), Best, Secondary, Direct, Conclusive, Circumstantial, Corroborative, Opinion, Exculpatory
2. Rule of Evidence = Authentic, Accurate (Reliable), Complete, Convincing (Believable), Admissible (Fragile /  Relevant, Material, Competent)
3. Evidence Collection = identified, collected, packaged, secured, and maintained correctly
4. A Criminal Investigation = Information, Instrumentation, Interviewing
5. Registry Analysis: Key Hives & Locations
6. Registry Analysis Tools = Registry Explorer, Autopsy Plugins
7. Event Logs: Critical Logs & Analysis = Security (4624/4625), System (7035/7036), Application (1000/1001)
8. Event Log Analysis Tools = LogParser, Event Viewer
9. Prefetch Files Analysis
10. $MFT Analysis = Extract File Record Entries, Identify Anti-Forensic Activity, Parse with MFTECmd, Timeline Analysis
11. $UsnJrnl
12. $LogFile
13. Jump Lists Analysis = Locate Jump Lists, Parse with JLECmd, Review Output, Correlate Findings
14. Shellbags Analysis
15. Memory Forensics Overview
16. RAM Acquisition Tools = FTK Imager, Magnet RAM Capture
17. DUMPIT = Create a memory dump of a live system
18. RAMP Acquisition Best Practices = Minimize System Impact, Document Process, Hash RAMP Dump, Secure Storage
19. Volatility Framework
20. Critical Volatility Plugins = Process List, Network Connections, Dump Malware
21. Reporting & Legal Compliance
22. GDPR / HIPAA Compliance
23. Redaction Workflow = Identify Sensitive Data, Use Magnet AXIOM, Review Redactions, Document Process
24. Report Encryption = Encryption Standard, 7-Zip Method, Password Management, Documentation
25. Tool-Generated Reports = Autopsy, Magnet AXIOM
26. Key Consideration: Chain of Custody = Documentation Requirements, Evidence Handling, Timestamps, Transfer Records
27. Tool Validation = Cross-Verification, Tool Testing
28. Legal Pitfalls: GDPR Compliance = Article 6 Requirements, Data Minimization, Right to be Informed, Cross-Border Transfers
29. Legal Pitfalls: HIPAA Compliance = Encryption Requirements, Minimum Necessary Standard, Business Associate Agreements, Breach Notification
30. References: Windows Forensics Cookbook = Chapter 2: Artifacts, Chapter 5: Memory
31. Cheat Sheets and Quick References = Volatility Command Reference, Registry Quick Guide
32. Registry Analysis Deep Dive = Identify key registry locations, Extract relevant keys, Analyze Timestamps
33. Advanced Event Log Analysis = Expert Analysis, Pattern Recognition, Event Filtering, Log Collection
34. Memory Acquisition Challenges = Volatility, Size Constraints, Anti-Forensics, Administrative Access, Encryption
35. Volatility Framework Advanced Usage

Day 3: Windows System Security & Configuration
1. Local Security Policy = machine-level security setting
2. Group Policy = Inside the MS Windows Server, Organizational Unit (OU), Domain, Local
3. Key Security Policies = Account Policies, Audit Policies, User Rights
4. Group Policy Structure = Computer Configuration, User Configuration
5. Group Policy Management Tools = Group Policy Management Console (GPMC), PowerShell Cmdlets, Group Policy Results (RSOP)
6. Configuring Security via Group Policy = Learning objective, Password & Account Policies, Audit Policies & Logging, Software Restriction, Administrative Templates
7. Password & Account Policies = Access Path, Key Settings, PowerShell Enforcement
8. Audit Policies & Logging = Enable Advanced Auditing, Critical Events, PowerShell Command
9. Software Restriction & AppLocker = Block Untrusted Executables, AppLocker Configuration
10. Security Hardening via PowerShell = Disabling Insecure Protocols, Windows Defender Configuration, Firewall Rule Management
* Disabling Insecure Protocols = SMBv1 Disabling, LM & NTLMv1 Authentication, TLS 1.0/1.1 Deprecation, PowerShell Remote Hardening
11. Security Baseline Alignment = Security Frameworks, Validation Tools
12. Policy Inheritance = Conflict Resolution, Enforcement, Block Inheritance
13. Backup & Recovery = Export GPO, Verification, Disaster Recovery
14. Common Pitfalls = Policy Refresh Latency, Missing Security Templates, Troubleshooting Failed Application
15. Microsoft Documentation Resources = Group Policy PowerShell Cmdlets, Windows Defender Configurations, Security Baselines
16. Advanced Group Policy Management = WMI Filtering, Item-Level Targeting, Loopback Processing
17. Security Templates = pre-configured
18. Registry-Based Policy Setting = Administrative Templates, Central Store, Custom Templates
19. Security Filtering = specific security principals (users, groups, computers)
20. PowerShell Desired State Configuration = using MOF files
21. Windows Defender Advanced Threat Protection
22. Local Security Authority Subsystem Service = Security Enforcement, Login Verification, Access Token Creation, Credential Guard
23. Device Guard = Advanced application control solution
24. BitLocker Drive Encryption = Full volume encryption
25. Windows Firewall Profiles = Domain, Private, Public, Configuration
26. User Account Control (UAC) = unauthorized changes by requiring elevation
27. Windows Event Forwarding
28. PowerShell Constrained Language Mode
29. Just Enough Administration (JEA) = Role-based access, powershell remoting, Configuration
30. Windows Defender Application Control
31. Advanced Threat Analytics = User Behavioral Analytics, Mean Time to Detection, Real-time Monitoring

Day 4: Network Security Configuration
1. Introduction to Windows Firewall = Role of Windows Firewall, Automation Capabilities
2. Comparison with Other Firewalls = Hardware Firewalls, Software Firewalls, Cloud-Based Firewalls
3. Creating and Managing Firewall Rules = Inbound Rules, Outbound Rules
4. Configuring Specific Rules = Identify Requirements, Create Rule, Define Parameters, Test and Monitor
5. Using Predefined Rule = Access Predefined Rules, Enable Common Service Rules, Customize Predefined Rules
6. Connection Security Rules = IPsec Implementation, Beneficial Scenarios, Authentication Options
7. Windows Firewalls with Advanced Security (WFAS) = Granular Control, Group Policy Integration, Advanced Features
8. Monitoring and Troubleshooting Firewall = Enable Loggin, Review Event Logs, Analyze Patterns, Adjust Rules
9. Windows Firewall GUI
10. Command-Line Tools for Firewall Management = netsh advfirewall command, wf.msc & firewall.cpl, automation scripts
11. PowerShell Cmdlets for Firewall Management
12. Overview of Common Network Protocols = RDP, SMB, HTTP/HTTPS, LDAP/LDAPS
13. Importance of Securing Windows Protocols = Data Protection, Attack Prevention, Access Control, Compliance
14. Network Level Authentication (NLA) = Enhanced Security Against Vulnerabilities, Technical Implementation, Automation & Deployment
15. Encryption for RDP Sessions = Data protection, Configuration Options, TLS Implementation
16. Best Practices for RDP Security = Strong Passwords & Account Security, Network Level Restrictions, Multi-Factor Authentication
17. Overview of SMB Protocol = File Sharing Protocol, Network Communication, Protocol Versions
18. SMB Signing and Encryption = SMB Signing, Packet Verification, SMB Encryption, Data Protection
19. Best Practices for SMB Security = Disable SMBv1, Enable SMB Signing, Implement Encryption, Restrict Access
20. Group Policy for Protocol Security = Centralized Management, RDP Security Settings, SMB Configuration
21. PowerShell for Protocol Security
22. Introduction to Virtual Private Networks (VPNs) = Secure Tunneling, Remote Access, Privacy Protection
23. Types of VPN Protocols = PPTP, L2TP/IPsec, SSTP, IKEv2
24. Setting up a VPN in Windows = Access Network Settings, Add VPN Connection, Configuration Advanced Security Settings, Connect, Test, and Troubleshoot
25. VPN Client and Server Settings = Client Configuration, Server Setup, Connection Policies
26. VPN Authentication Methods = Pre=shared Keys, Digital Certificates, Multi-factor Authentication (MFA), Username/Password
27. Best Practices for VPN Security = Strong Encryption, Secure Authentication, Regular Updates, Access Policies
28. Introduction to Direct Access = Seamless Connectivity, Transparent Operation, Domain Integration
29. Differences between DirectAccess and Traditional VPNs = Connection Initiation, Management Capabilities, Infrastructure Requirements

Day 5: Advanced PowerShell Automation
1. Security policy tools = Local Security Policy Editor, PowerShell Modules
2. Group Policy Fundamentals = Group Policy Objects (GPOs) and Organizational Units (OUs), GPO propagation, Security Filtering and Inheritance
3. PowerShell Group Policy Cmdlets = Get-GPO, New-GPO, Set-GPRegistryValue, New-GPLink
4. Advanced Automation Techniques = Error Handling, Logging and Backups, Remote Execution
5. PowerShell Security Policy Best Practices = Use Least Privilege with Constrained Endpoints, Test Policy Changes with GPResult, Document with Script Comments and Logs, Version Control with Git Repositories
6. Advanced GPO Filtering Techniques = Security Filtering, WMI Filtering
7. Backing up and Restoring GPOs = Backup all GPOs, Backup Specific GPO, Restore from backup
8. Remote GPO Management = Establish Secure Remote Session, Import Required Security Modules, Execute Security-Focused GPO Commands, Close and Audit Remote Session
9. Automating Security Baseline Deployment = Download Baseline, Import Templates, Customize Settings, Deploy and Verify
10. Auditing GPO Changes = Enable Advanced Audit Policy, Monitor Event Logs, Generate Change Reports
11. Troubleshooting GPO Application Issues 
= Event Logs, GPRsult, RSOP
= Policy Conflicts, WMI Filters, Security Filtering
= Check GPResult Output, Verify WMI Filters, Examine Security Filtering, Check GPO Status, Review Event Logs
12. Comparing Local vs. Domain Policies
13. Password Policy Automation
14. Account Lockout Policy Automation
15. Audit Policy Configuration
16. User Rights Assignment Automation
17. Security Template Deployment = Create Security Template, Import to GPO, Link and Apply
18. Automating Security Template Deployment
19. Registry-Based Policy Settings = Administrative templates, Custom Registry Settings, PowerShell Automation
20. Automating Registry Policy Setting
21. Software Restriction Policies = Path Rules, Hash Rules, Certificate Rules, Internet Zone Rules
22. AppLocker Policy Automation = Create Rules, Test in Audit Mode, Review Logs, Refine and Enforce
23. Windows Firewall Configuration via PowerShell = Create Firewall Rules, Configure Firewall Profiles, Deploy vis GPO
24. BitLocker Drive Encryption Automation = Check Hardware Compatibility, Configure BitLocker Settings, Enable BitLocker Encryption, Backup Recovery Keys
25. Automating Windows Defender Configuration
26. Credential Guard Configuration = Hardware Requirements, Enable via GPO, PowerShell Automation, Verification
27. Automating Credential Guard Deployment
28. Advanced Security Monitoring = Event Log Monitoring, PowerShell Log Analysis, Centralized Monitoring
29.


How to secure account? MFA, Password*
IPSec? Create VPN tunneling WAN
Encryption purpose? AH (Hashing), ESP (Encapsulation)
Baseline? Standardize,
least privilege? Restrict Access
Chain of Custody environment no need? Cloud
EFS? Encrypt file and folders
Bit Locker? Physical protected
Why NTFS format? Protect files, folders
Benefit of GPO? Central management, domain control
Vulnerability Scanner Tools? Nessus, 
Vulnerability Scanner? Old patch, what’s wrong
Window Service Update? Schedule Auto, patch, system update, what server locally
Bruce Force Attack? Password attack and random attack, black out
Deploy new server make secure?
Patch break Identified issue? Figure out first
Audit update software app? Update, patch
Administrator account How to break? Role-based
Why tool of log? Because of binary
Admin advantage of solution? Reduce number of admin, limited manage by powershell
Tool Managed GPO? Group Policy Management
Effect GPO? GPresult

