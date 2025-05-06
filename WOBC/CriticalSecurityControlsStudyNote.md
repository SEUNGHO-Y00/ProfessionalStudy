# Critical Security Controls Study Note

* Threat intel life cycle (Slide 67)
  - what are the 4 elements
  - Tasking, Collection, Processing, Exploitation, Dissemination

* What type of attack that sends multiple request to disable a system
  - DOS or DDOS (If multiple attacks)

* SIEM, what is and what does it do?
  - security information and event management
  - an approach to security management that combines SIM (security information management) and SEM (security event management)   functions into one security management system.

* Define a rootkit (118)
  - controls system at the lowest level
  - run invisibly

* Definition of pass-the-hash
  - A lateral movement technique in which an attacker uses cached account credentials to access other systems.
  - Used with SSO systems like Kerberos.​
  - Attacker doesn't need to crack hashes, just use them directly.​
  - Makes it easier to compromise other hosts in the domain.​
  - Cuts down on effort of moving from host to host.​
  - Windows Defender Credential Guard protects against pass the hash.

* Definition of APT
  - A stealth threat that continually exploits a target.

* Definition of supply chain attack
  - An attack that targets the end-to-end process of manufacturing, distributing, and handling goods and services.

* Elements and definition of physical security
  - Barrier, Locks, storage, Surveillance, Alarms, Guards, Logs

* Definition of a worm
  - Self-replicating
  - Does not attach to files

* Definition of DNS poisoning
  - An attack in which an attacker modifies a DNS server's cache to return a fraudulent IP address to users

* Definition of cross site scripting and how to remediate it
  - An attack that takes advantage of scripting and input validation vulnerabilities in web apps.

* Types of hackers
  - Hackavist
  - APT
  - Nation state

* Define qualitative analysis   
  - Uses words to measure the likelihood and impact of risk
  - Scenario base

* Definition of risk management process and the phases of it.
  - Phases are Identification, Assessment, Analysis, Response
  - Management of risk involves assigning weight for different contexts.

* What is the formula for risk
  - RISK= THREATS + VULN + CONSEQUENCE

* we have just exp an attack and the attacker it trying to use priv escalation. What cause the incident to happen?
  - Bad patch
  - Weak Security    
  - Properly

* Exp data exfiltration through DNS tunneling because of a compromise dns

* If we detected a malware attack the first step is to
  - Isolate

* What is the definition of reconnaissance attack?
  - Passive/active way of building information on a target
  - Followed by vuln assessing

* If you find an employee at and another employee computer, what is the first thing you do?
  - Monitor his activity

* what is remediation for a SQL injection attack
  - Input validation

* You have detected a breach and it is current exfil important data
  - Disconnect the system

* If a malware attack
  - Quarantine

* What is the def. of spear fishing
  - Specific Target

* You are exp a DDOS attack, what is the first thing you want to know?
  - The source
  - How attacker avoid DDOS
  - Maintaining botnets is a lucrative operation for attackers.​
  - Difficult to separate legitimate from malicious traffic.​
  - The server can't handle the traffic and is taken down.

