# CISSP Study Note

## 1. Security and Risk Management

1. Security Fundamentals

* The five pillars of information security
  - Information security involves ongoing efforts like a continuous process.
  - Vulnerabilities and risks are evaluated based on their threats against one or more of the CIA Triad principles.
* Confidentiality - sensitive information, encryption, steganography
  - Violations of confidentiality are not limited to direct intentional attacks.
* Integrity - Hash, changes in hash values, digital signatures (Authenticity, Non-repudiation), digital certificates
* Availability - patching
  - A patch management process includes evaluating patches, testing patches, and auditing patches.
  - Accessibility of data, objects, and resources is the goal of availability.
* Authenticity and nonrepudiation - physical signature, digital signature, bio-security, video surveillance

2. Security Governance - Professional(standard form), Industry(laws regulation), External(regulatory agencies), Internal(senior management)
      % Security governance seeks to compare the security processes and infrastructure used within the organization with knowledge and insight obtained from external sources.
      % Security governance should include acquisitions, divestitures, and governance committees.
      % A divestiture occurs when something is being removed from the organization, whether a device, service, employee, or partnership.
      % The top-down approach is the aspect of security governance that is based on the idea that senior management is responsible for the success or failure of a security endeavor.
    1) Aligning security with the business - security leader, business leader, security professionals  
      * unbalanced decisions
      % The business or mission owner is responsible for defining the strategic direction of the organization and ensuring that all operations, processes, and initiatives align with the overall business objectives.
    2) Organizational processes
    3) Security roles and responsibilities - Due Care, Due Diligence
      % Due care is practicing the individual activities that maintain the security effort(Due diligence effort).
      % Due Care involves implementing necessary safeguards and policies to protect sensitive information and ensure safety.
      % Failing to perform periodic security audits can result in the perception that due care is not being maintained.
      % Due Diligence ensures that a company is aware of potential issues and takes appropriate measures to address them.
      % Due diligence often includes deployment of all necessary security controls as determined by risk management; crafting of policies, standards, guidelines, and procedures; and establishment of a board of directors.
        Due diligence is establishing a plan, policy, and process to protect the interests of an organization.
      % Security personnel perform a root cause analysis during the remediation stage during incident management.
    4) Control and risk frameworks 
      - COBIT (Control Objectives for IT, Audit), ISO Standards (IT control), NIST 800-53, NIST RMF (800-37), FedRAMP, SABSA
      % While COBIT focuses more on aligning IT management with business objectives and governance,
        ISO standards provide specific requirements for maintaining information security management quality and consistency across industries globally.
      % The COBIT key principles are: Provide Stakeholder Value, Holistic Approach, Dynamic Governance System, Governance Distinct From Management, Tailored to Enterprise Needs, and End-to-End Governance System.
      - SABSA (Sherwood Applied Business Security Architecture)
  C. Compliance and Ethics
    % A directive control is deployed to direct, confine, or control the actions of subjects to force or encourage compliance with security policies.
    1) Legal and compliance risks - GDPR, PCI DSS
      % The Fourth Amendment to the U.S. Constitution sets the “probable cause” standard that law enforcement officers must follow when conducting searches and/or seizures of private property.
      % The Fifth Amendment primarily protects individuals from self-incrimination, meaning that suspects cannot be compelled to provide evidence against themselves.
      % The 1991 U.S. Federal Sentencing Guidelines were established to provide a framework for sentencing organizations (including corporations) for criminal conduct, particularly white-collar crimes.
      % The Family Educational Rights and Privacy Act (FERPA) protects the rights of students and the parents of minor students.
      % The Gramm–Leach–Bliley Act (GLBA) provides, among other things, regulations regarding the way financial institutions can handle private information belonging to their customers.
      % Organizations subject to HIPAA may enter into relationships with service providers as long as the provider’s use of protected health information is regulated under a formal business associate agreement (BAA).
    2) Data privacy - PII (Identifiable), PHI (Health), GAPP(Accept Privacy, AICPA, CICA, ISACA, IIA)
      % The Children’s Online Privacy Protection Act (COPPA) provides severe penalties for companies that collect information from young children without parental consent (younger than the age of 13).
    3) GDPR - E.U regulations, anyone in E.U geolocation
    4) California privacy law - CPRA (SPI = Sensitive)
    5) National data privacy laws - PIPL(China), PPIA (South Africa)
      % Information Technology Infrastructure Library (ITIL) was initially crafted by the British government for domestic use but is now an international standard,
        which is a set of recommended best practices for core IT security and operational processes, and is often used as a starting point for the crafting of a customized IT security solution.
    6) Computer crimes - CFAA (Access), ECPA (network communication), ITADA (Identity)
      % The Computer Fraud and Abuse Act (CFAA) primarily focuses on unauthorized access to computer systems,
        especially those related to financial institutions, federal government systems, and the misuse of passwords for fraudulent purposes.
    7) Software Licensing - SLA, ELAs (Enterprise), EULAs(End User License Agreements)
      - Contractual agreements(high value)
    8) Intellectual Property - Copyrights, Trademarks, Patents(protect inventions)
      % The Digital Millennium Copyright Act contains provisions prohibiting the circumvention of copyright protection mechanisms.
      % Copyright protection generally lasts for 70 years after the death of the last surviving author of the work.
      % U.S. patent law provides for an exclusivity period of 20 years beginning at the time a utility patent application is submitted to the Patent and Trademark Office.
      % A trade secret is a type of intellectual property that includes formulas, practices, designs, instruments, or processes that are not generally known or reasonably ascertainable by others,
        and protects confidential information which provide a business with a competitive advantage.
      % Downstream liability refers to the legal responsibility that one party may have for the actions of another party downstream in a distribution chain,
        typically relating to intellectual property rights, defamation, or other legal issues.
    9) Import and export controls - ITAR (defense articles), EAR (dual use), OFAC (Sansation)
      % The Safe Harbor requirements were a framework established between the United States and the European Union.
      % Governance, risk, and compliance (GRC) solutions are generally not covered by import/export control regulations.
      & Data sovereignty laws, known as data localization laws, are imposed by a country to regulate how data is collected, stored, and flows out of its borders.
    10) Data breaches
      * Encryption is easy to protect data breach
    11) Ethics
      * ISC2 members are required to report breaches of the Code of Ethics to ISC2 for investigation
      % The first canon: Protect Society, the Common Good, Necessary Public Trust, and Confidence
      % The second canon: act honorably, honestly, justly, responsibly, and legally.
      % The third canon: Provide Diligent and Competent Service to Principals
      % The fourth canon: Advance and Protect the Profession
      % The Internet Architecture Board(IAB) developed an ethics-related statement concerning the use of the internet, particularly through their "Ethics and the Internet" document
  D. Security Policy
    1) Security policy framework - policies > standard(details) > guidelines(advice) / procedures    
      * Policy, standards, and procedures are mandatory. Guidelines are optional
      % The security policy is an overview or generalization of an organization’s security needs.
      & The common development process of creating a security policy includes initial and evaluation, development, approval, publication, implementation, and maintenance.
    2) Security Policies
      % An Acceptable Use Policy (AUP) defines the guidelines and restrictions for how users are allowed to employ company resources, such as hardware, software, internet access, and data.
      % An information policy defines how data is categorized based on its sensitivity and importance, which helps in determining the appropriate security measures and handling procedures.
      % A compensation control is deployed to provide various options to other existing controls to aid in enforcement and support of security policies.
  E. Business Continuity
    1) Business continuity planning(a corrective control) - BIA (Business Impact Assessment, identifies and prioritizes, criticality)
      * BCP is also known as continuity of operations planning (COOP) and is not operational control, BCP in the cloud is a partnership between providers and customers.
      % BCP includes strategies to prevent or minimize the impact of a disaster on the organization, ensuring that critical operations remain available or can be quickly restored.
      % People should always be your highest priority in business continuity planning.
      % In the provisions and processes phase, the BCP team designs the procedures and mechanisms to mitigate risks that were deemed unacceptable during the strategy development phase.
      % Risk mitigation controls to address acceptable risks would not be in the BCP.
      % An executive succession plan is designed to identify and prepare individuals to fill key leadership roles within an organization in the event that they become vacant, whether due to a disaster or other circumstances.
      % The qualitative analysis portion of the business impact analysis (BIA) allows you to introduce intangible concerns, such as loss of customer goodwill, into the BIA planning process.
      % The quantitative portion of the priority identification should assign asset values in monetary units.
      % Project Initiation: Establish the continuity planning policy statement, define objectives, scope, and obtain management support.
        Business Impact Analysis (BIA): Identify critical business functions, determine the impact of disruptions, and prioritize recovery efforts.
        Identify Preventative Controls: Implement measures to reduce the likelihood of disruptions.
        Develop Recovery Strategies: Create strategies for the recovery of critical operations.
        Plan Development: Document the plan, including roles, responsibilities, and procedures.
        Testing and Maintenance: Regularly test the plan, update it as needed, and ensure that personnel are trained.
      % In a Business Impact Analysis (BIA), systems are categorized based on how long the organization can tolerate them being down. Typically:
        Urgent: Systems with MTD of minutes to a few hours.
        Critical: Systems with MTD up to 24 hours.
        Normal: Systems with MTD between 24 and 72 hours.
        Nonessential: Systems with MTD of several days or more.
        Important: Can vary but generally falls between critical and normal.
    2) Business continuity controls - Single Point of Failure Analysis, Contingency Plan
      % Restoration team, damage assessment team, and salvage team execute the final plan.
    3) High availability (Multi-system, minimal interrupt) and fault tolerance (Single system) - load balancing (work evenly)
        Component redundancy - such as power supply or fan
        clustering - all active working
        RAID (Redundant Array of Inexpensive Disks) = Disk mirroring (RAID 1), Disk Striping (RAID 5)
        * RAID is a fault-tolerance technique, not a backup state
        % Disk mirroring (RAID 1) creates an exact copy of the data on a second drive. If one drive fails, the system can immediately switch to the mirrored drive,
          reducing downtime and making repairs more manageable and quicker without the need for data restoration.
  F. Personnel Security
    1) Personnel security - strong security policy, insider threat
      % The data loss prevention (DLP) alerts and log analysis are the only options that would potentially include useful information in regard to an insider exfiltrating the sensitive documents.
    2) Security in the hiring process - Employment Agreements, NDAs(Non-Disclosure Agreements)
    3) Employee termination process - Exit interview, Revoke Access Promptly
      % If the user’s account remains enabled, the user may log on later and cause damage. Disabling the account is to prevent sabotage.
    4) Employee privacy - minimization, limit access, encryption, masking (hiding)
    5) Social networking - multi-factoring
  G. Risk Management
    % Risk is an assessment of probability, possibility or chance, threat × vulnerability, and Every instance of exposure
    1) Risk analysis, assessment, and scope    
      * Threat vectors are the specific methods that threats use to exploit a vulnerability.
      % The DREAD questions are about Damage potential, Reproducibility, Exploitability, Affected users, and Discoverability.
    2) Quantitative risk assessment 
      - single risk and asset pair, Asset Value(AV), Exposure Factor(EF), Single-Loss Expectancy(SLE)
      - AV * EF = SLE
      - Annualized Rate of Occurrence(ARO), Annualized Loss Expectancy(ALE),
      - SLE * ARO = ALE
      * Be prepared to work through a quantitative risk assessment calculation on the exam
      % The annualized loss expectancy (ALE) is the best metric to compare relative risks because it incorporates both the likelihood and the impact of those risks.
      % A countermeasure primary affects ARO because the countermeasure is designed to prevent (or mitigate or reduce) the occurrence of the risk, thus reducing its frequency per year.
      - Mean Time to Failure(MTTF), Mean Time Between Failure(MTBF), Mean Time to Repair(MTTR)
      % maximum tolerable downtime (MTD) represents the maximum amount of time that a business function or resource can be unavailable before it causes significant harm to the organization.
    3) Risk treatment - Inherent Risk => controls applied => residual risk + control risk, Expansionary/Neutral/Conservative
      % Insurance is a form of risk assignment or transference.
      % Inherent risk is the level of natural, native, or default risk that exists in an environment, system, or product prior to any risk management efforts being performed.
      % Residual risk is the leftover risk after countermeasures and safeguards are implemented in response to original or total risk.
      & Risk appetite refers to how much risk the organization is willing to accept.
      & Risk tolerance is essentially the variation or deviation from the risk appetite that an organization is willing to take,
        depending on how much the organization feels that variation is worth for that particular business effort.
    4) Security control selection and implementation - Defense in Depth    
      * Technical controls are implemented by technology while operational controls are implemented by people!
      % Integral parts of information security administration are Physical controls, Technical controls, and Administrative controls
      % Operational controls are practices and procedures implemented to ensure the ongoing security and functionality of systems during regular operations such as backup.
      % Technical controls include system auditing, monitoring, access controls, encryption, and network security devices like firewalls and intrusion detection systems.
      % Managed detection and response (MDR) combines antimalware capabilities with a managed service that reduces the burden on the IT team.
    5) Continuous monitoring, measurement, and tuning
      % In reality, automated tools are often more thorough because they can continuously monitor and analyze large amounts of data in real-time, detecting patterns and anomalies that might be missed by manual monitoring.
      % Tailoring refers to modifying a list of security controls to align with the organization’s mission.
    6) Risk management frameworks - NIST 800-37 (categorize, select, implement, assess, authorize, monitor)
    7) Risk visibility and reporting
      % Risk mitigation procedures are usually developed by security or risk management teams within the organization.
        Senior management is responsible for setting the overall risk acceptance level, allocating resources, and approving monetary budgets for risk management.
      % The visibility considerations include types of neighbors and building markings and signs.
      % Alternative systems are that redundant communications circuits provide backup links that may be used when the primary circuits are unavailable.
  H. Threat Modeling
    1) Threat intelligence - Open-source intelligence, Email Address Harvesting
    2) Managing threat indicators - CybOX, STIX, TAXII, OpenIOC
    3) Intelligence sharing - ISACs, ISA(interconnection security agreement)
    4) Threat research
      % Process for Attack Simulation and Threat Analysis (PASTA) is a seven-stage threat modeling methodology.
    5) Identifying threats - structured approach
      % The three common threat modeling approaches from this list of options are focus on attackers, focus on assets, and focus on software.
      % a proactive approach to threat modeling, known as the defensive approach is threat hunting takes place after a product has been created and deployed
    6) Automating threat intelligence - Data Enrichment
    7) Threat hunting
  I. Supply Chain Risk Management
    1) Managing vendor relationships - VMS(vendor management system)
      % VMS is a software solution that assists with the management and procurement of staffing services, hardware, software, and other needed products and services.
    2) Vendor agreements - SLRs, SLA, MOU, MOA, BPA
      % A service-level requirement (SLR) is a statement of the expectations of service and performance from the product or service of a vendor. 
    3) Vendor information management
    4) Cloud audits - SOC1(assurance), SOC2(detailed), SOC3 (high-level), Type I report(control), Type II report(testing), SSAE 18, ISAE 3402
      % SOC 2 reports focus on a business's controls relevant to security, availability, processing integrity, confidentiality, and privacy of data.
      % SOC 3 engagements assess the organization’s controls that affect the security and privacy of information stored in a system.
      % The information regarding the backup and restoration of data in SOC 2 and SOC 3 reports applies to the availability tenet.
  J. Awareness and Training
    1) Security awareness training
      % Educating users is an important part of preventing virus infections and works with technical controls such as antimalware software.
        Awareness establishes a common baseline or foundation of security understanding across the entire organization and focuses on key or basic topics and issues related to security that all employees must understand.
    2) Compliance training
    3) User habits
    4) Measuring compliance and security

-----------------------------------------------------------------------------------------------------------------------------------------------------------

2. Asset Security
  A. Data Security
    1) Understanding data security
      - Data at Rest, Data in Transit, Data in Use
      % In asynchronous communication, data is transmitted one byte at a time, with start and stop bits used to signal the beginning and end of each byte.
      % Assets are classified based on the data that they hold or process.
      % a data in motion use case is specifically concerned about information that users are retrieving.
    2) Data security policies
      - Data classification, Data Lifecycle Policy (Retention, Disposal)
      % Record retention policies define the amount of time to keep data, and laws or regulations often drive these policies.
      % Data remanence is data remnants on media, and data destruction methods remove data remnants.
      % Slack space is the unused space in a cluster.
      % Data classifications provide strong protection against the loss of confidentiality and are the best choice of the available answers.
    3) Data security roles
      - Data Owner(business leaders) > Steward(handling day to day) > Custodian(IT staff members) > User
      % A data controller identifies what data to pass and process to the data processor and how that data should be processed.
      % The data custodian is responsible for day-to-day tasks(data protection tasks) maintaining and protecting data, such as backing up data,
        but the overall responsibility often lies with security professionals and other relevant departments.
      % Data owners have the ultimate responsibility for protecting data, and they identify the classification of data. Also, they have final corporate responsibility for the protection and storage of data.
      - Data Subject(collected data), Data processors(third parties)
      * GDPR(General Data Protection Regulation) uses the term data controller instead of data owner
      * System ownership and data ownership are two different concepts
      & The system owner is the manager accountable and responsible for a particular system that processes various types of data.
      % The asset owner is the person who has final corporate responsibility for the protection and storage of data.
    4) Limiting data collection
      - Minimize information collected, Monitor Third Parties
      % A data haven either has no laws or poorly enforced laws for information protection.
    5) The data lifecycle
      - Create, Store, Use, Share, Archive, Destroy
      - Clearing(Casual), Purging(advanced), Destroying
      % Purging writes a series of 1s and 0s over media multiple times, and it removes all data remnants.
      % Purging memory buffers removes all remnants of data after a program has used it.
      % Object reuse refers to the practice of reusing storage media, memory, or other data storage objects after ensuring that any residual data from previous use is securely removed or overwritten,
        preventing unauthorized access to potentially sensitive information.
      % Degaussing the disks often damages the electronics.
      % Defragmenting a disk optimizes it
      % Erasing data on a hard disk drive is likely to leave some data on a hard disk drive, also known as data remanence.
  B. Data Security Controls
    1) Developing security baselines
      - Baselines are generic, Monitoring is critical
      % Security baselines often require hundreds or thousands of individual security settings on a particular device.
      % Data Control Language (DCL) includes commands like GRANT and REVOKE that control access to data within the database by assigning and removing privileges to users.
        This enables granular control over who can access specific data or perform certain actions on the data.
      % The scoping process removes controls from a list of controls from a suggested baseline.
    2) Leveraging industry standards
    3) Customizing security standards
    4) Cloud storage security
      - Encryption, Access control
    5) Information classification
      - Data Classification Policy, Labeling Requirement
      & Statutory requirements set forth in laws and regulations and other statutes must be used as criteria for allowing access to data.
      % The term synonymous with security label is sensitivity label.
      % Information is compartmentalized in the information flow model are classification(Assigns a security level) and need to know(Ensures that only individuals).
      % The information flow model is concerned with the transfer of information between different security levels.
        It typically allows information to flow within the same security level and restricts the flow of information from lower to higher security levels to prevent unauthorized access or information leakage.
      % The noninterference model is designed to prevent actions at a higher security level from affecting or influencing those at a lower level, ensuring that information does not flow between different security levels in a way.
      % Declassification is the process of moving an object into a lower level of classification once it is determined that it no longer justifies being placed at a higher level.
    6) Digital rights management
      - IRM(information rights management), DRM(Digital Right)
      % Persistent online authentication, automatic expiration, and a continuous audit trail are all methods used with digital rights management (DRM) technologies.
    7) Data loss prevention
      - DLP(Data Loss Prevention), Host-based, Network-based, Pattern Matching, Watermarking, Cloud-based
      % A network-based data loss prevention (DLP) system monitors outgoing traffic (egress monitoring, outbound) and can thwart data exfiltration attempts.
      % Pseudonymization replaces data with a pseudonym or alias to protect the privacy of individuals identified in the original dataset.
      % Drive encryption (also known as full disk encryption) protects the entire contents of a storage device, ensuring that the data cannot be accessed by unauthorized users,
        even if the physical device is stolen or accessed without permission.
  C. Change and Configuration Management
    1) Change management
      - RFC(Request for change)
      % Request control provides users with a framework to request changes and developers with the opportunity to prioritize those requests. 
      % Concurrency uses a “lock” feature to allow an authorized user to make changes and then “unlock” the data elements only after the changes are complete.
      % Change management aims to ensure that any change does not result in unintended outages or reduce security.
      % Change management processes include requesting a change, creating a rollback plan for the change, release control, change control, and documenting the change.
      % Scalability only requires the ability to increase (but not decrease) available resources.
    2) Configuration and asset management
      - Baselines, Versioning
      % Configuration management includes supporting rollback of changes, maintaining detailed documentation, and running configuration audits.
      % The primary security concern of a distributed computing environment (DCE) is the interconnectedness of the components.
        This configuration could allow for error or malware propagation as well.
      % DCE IDL (Distributed Computing Environment Interface Definition Language) is a language used to define the interfaces between software components in a networked environment.
      % There are numerous examples DCE IDL or frameworks, such as remote procedure calls (RPC), the Common Object Request Broker Architecture (CORBA), and the Distributed Component Object Model (DCOM).
    3) Physical asset management
      - Media management(tracks highly sensitive data)
      % The capability aspect is crucial as it determines how much data the medium can hold, which is directly related to your organization's storage needs.
      % The three media management or control modes are simplex (one-direction), half-duplex (two-way, but only one direction can send data at a time),
        and full-duplex (two-way, in which data can be sent in both directions simultaneously) communications.
    4) Supply chain risks and mitigations
      - End of Sale(no longer be offered for purchase), End of Support(EOS, reduce or eliminate support), End of Life(no longer provide any support)
      % Systems with an EOS date that occurs in the following year should be a top priority for replacement.
      % The end-of-life (EOL) date is the date when the vendor will stop offering a product for sale.


-----------------------------------------------------------------------------------------------------------------------------------------------------------


3. Security Architecture and Engineering
  A. Secure Design
    1) Secure design principles
      - Fail open, Fail secure, Fail safe
      & The principle of secure defaults mean that out-of-the-box security controls should be secure rather than open.
      & A fail-secure state means that the control will fail to a more secure or closed state. This could conceivably interfere with an evacuation and indirectly harm personnel.
      & Fail open is the state a system fails over to which allows security controls to be turned off, in the vent of a crisis to save lives and prevent harm to persons.
      & During emergency situations doors and other systems that are designed for personnel evacuation and safety should default to a fail-safe condition.
      % Network segmentation involves dividing a network into smaller parts to improve security and manageability, but it doesn't directly prevent programs from accessing each other.
      % Process isolation is a security measure that ensures different programs run separately, preventing them from accessing or interfering with each other.
      % An execution domain provides a secure environment where processes with elevated privileges can operate, isolated from other processes to maintain security and prevent unauthorized access to critical resources.
    2) Security models
      - Bell-LaPadula Model(confidentiality, No read up, no write down, simple security rule, Star property rule), Biba Model(integrity, no read down, no write up, invocation rule)
      * The Bell-LaPadula model is rarely implemented outside of military applications
      * The Bell-LaPadula model and Biba models are important for the exam but rarely used in the real world
      % The tranquility principle ensures that the security labels of subjects and objects do not change dynamically, maintaining system stability and preventing the bypassing of security controls by altering security levels.
      % The Take-Grant model is an access control model that uses states and state transitions to define how rights can be transferred between subjects and objects.
      % The Clark-Wilson model is designed to enforce well-formed transactions and separation of duties, ensuring integrity through the implementation of integrity-monitoring rules and integrity-preserving rules.
        The Clark–Wilson model does define the constrained data item, transformation procedures, and integrity verification procedure.
      % The trusted computing base (TCB) has a component known as the reference monitor in theory, which becomes the security kernel in implementation.
        The TCB is the combination of hardware, software, and controls that work together to enforce a security policy.
      % In a dedicated security mode, every user who has access to the system must have the appropriate security clearance and formal approval to access all information processed by that system.
    3) Security evaluation models
      - TCSEC(Structured), Common Criteria(ISO 15408), Certification and Accreditation(ATO, IATO, IATT, DATO)
      % Trusted Computer System Evaluation Criteria (TCSEC), focuses on the security functionality and assurance of systems, ensuring they meet certain standards for protecting classified or sensitive information.
      % The Trusted Computer System Evaluation Criteria (TCSEC), defines the following security levels:
        D - Minimal Protection, C1 - Discretionary Security Protection, C2 - Controlled Access Protection
        B1 - Labeled Security Protection, B2 - Structured Protection(covert channel analysis), B3 - Security Domains, A1 - Verified Design
      % The Common Criteria (CC) framework includes components such as Protection Profile (PP), Security Target (ST), and Target of Evaluation (TOE).
      % Security targets (STs) specify the claims of security from the vendor that are built into a target of evaluation (TOE).
      % The Common Criteria Evaluation Assurance Level (EAL) is a scale that measures the depth and rigor of an evaluation for information technology products.
        EAL1: Functionally Tested. EAL2: Structurally Tested. EAL3: Methodically Tested and Checked. EAL4: Methodically Designed, Tested, and Reviewed (common benchmark for commercial products).
        EAL5: Semi-Formally Designed and Tested. EAL6: Semi-Formally Verified Design and Tested. EAL7: Formally Verified Design and Tested (highest level of assurance).
      * Certification and accreditation are different. Accreditation and authorization are the same.
      % Certification is the process of evaluating and verifying that security controls are correctly implemented and functioning as intended within an information system.
      % When the vendor is not meeting minimal security requirements which are necessary to the protection of the service and its customers, they should void the authorization to operate (ATO) of this vendor.
      % The four types of ATOs(Authorization to Operate) are authorization to operate, common control authorization, authorization to use, and denial of authorization.
    4) Segregation of duties
      % Segregation of duties is the principle that ensures no individual has access to multiple permissions
        that would allow them to perform a highly sensitive action alone, preventing fraud and errors.
      % Two-person control is a security measure that requires at least two authorized individuals to perform certain actions, ensuring that no single person can complete sensitive tasks alone.
    5) Privacy by design
      (1) Proactive preventive
      (2) Privacy as the Default Setting
      (3) Privacy Embedded into Design
      (4) Full Functionality
      (5) End to End security
      (6) Visibility and Transparency
      (7) Respect for User Privacy
    6) Secure defaults
      - Keep It Simple and Small
    7) Information system lifecycle
      % In the operate and maintain phase of the security management life cycle, ongoing security activities such as performing audits, monitoring systems,
        and ensuring that security settings meet established baselines are carried out.
      % The five key concepts of decomposition are trust boundaries, dataflow paths, input points, privileged operations, and details about security stance and approach.
  B. Virtualization and Cloud Computing
    1) What is the cloud?
    2) Cloud computing roles
      - Cloud Access Security Broker(CASB)
      & CASB can provide access control, auditing, and accountability services to a variety of cloud-based services, including third-party identity management offered by the cloud service provider.
    3) Drivers for cloud computing
      - On-demand self-service, Scalability, Elasticity, Broad Network Access, Measured Service
    4) Security service providers
      * MSSPs(Managed Security Service Providers) may also be referred to as security as a service (SECaaS)
      - Network-based CASB, API-Based CASB
      & Proxy-based CASB is specially designed for providing cloud-based security between end-user applications and data that resides in the cloud and is configured to intercept traffic.
    5) Multitenant computing
      - Oversubscription, Resource Pooling
    6) Virtualization
      - Type 1, Type 2(Operating system, personal device), VM Sprawl
      % Type 1 hypervisor is known as bare metal and runs on top of bare hardware.
      % Type 2 hypervisor is known as hosted and runs on top of an operating system.
      % RedPill and Scooby Doo attacks specifically target virtual machines.
      % VM escaping occurs when software within a guest OS is able to breach the isolation protection provided by the hypervisor in order to violate the container of other guest OSs or to infiltrate a host OS.
    7) Desktop and application virtualization
      - VDI(Virtual Desktop Infrastructure), Application Virtualization
      % Browsing the internet on a virtualization host can expose the host to unnecessary security risks, such as malware infections or unauthorized access, which could compromise the entire virtualization environment.
    8) Cloud compute resources
      % Serverless architecture is a cloud computing concept where code is managed by the customer and the platform (i.e., supporting hardware and software) or server is managed by the cloud service provider (CSP).
    9) Containerization
      - Applications are what containerized computing environments are created for.
      % Containerization is crafted to host a single application, including only the OS resources needed, and sharing a common binaries and libraries
      % A hypervisor is not part of containerization. A hypervisor is an application where you can create, manage, and run multiple VMs.
    10) Cloud activities and the cloud reference architecture
      - ISO/IEC 17789:2014
      * Reference architectures provide a useful framework, but they're just a starting point.
    11) Cloud deployment models
      * No cloud model is inherently superior to the other approaches. It all depends on the context.
      % Vertical scaling adds more resources to existing servers to meet demand.
      % Horizontal scaling adds more servers to the pool to meet increased demand.
    12) Cloud service categories
      - XaaS, SaaS(entire app / Data), PaaS(app platform / Data, Application), IaaS(Servers/storage / Data, Application, OS), FaaS(serverless computing)
      * Understanding the shared responsibility model is crucial for cybersecurity professionals.
    13) Edge and fog computing
      % In edge computing, the intelligence and processing are contained within each device. Thus, rather than having to send data off to a master processing entity, each device can process its own data locally.
      % Fog computing relies on sensors, IoT devices, or even edge computing devices to collect data and then transfer it back to a central location for processing.
      % A nonpersistent system or static system is a computer system that does not allow, support, or retain changes.
  C. Hardware Security
    1) Memory protection
      - Segmentation Fault, Memory Leak
      % Write blockers are hardware devices used to prevent the accidental writing of data to media that was collected as evidence.
      % indirect memory addressing is the address field points to a memory cell that contains the address of the operand.
      % Monitoring CPU load and memory usage helps identify performance-related problems, such as resource bottlenecks, application inefficiencies, and overall system health.
      % Direct Memory Access (DMA) allows devices to transfer data directly to or from memory without involving the CPU in each step of the transfer process.
    2) Hardware encryption
      - AES Crypt, FDE(Full-Disk Encryption), HSM(Hardware Security Module), TPM(Trusted Platform Modules), SED(Self-Encrypting Drive)
      % TPM provides secure generation, storage, and management of encryption keys, passwords, and other sensitive data to enhance the security of various cryptographic operations, such as drive encryption and digital rights management.
      & Sealing is the process of encrypting the data for a system's specific hardware and software configuration and storing it on the TPM.
      % High cohesion (united) refers to how closely related and focused the responsibilities of a single module are.
      % Low coupling specifically refers to the independence of modules.
      % High coupling is highly dependent on each other.
    3) Hardware and firmware security
      - BIOS, UEFI(Unified Extensible Firmware Interface), Measured Boot, Attestation, Hardware Root of Trust, EMI(Electromagnetic Interference, EMP)
  D. ServerSecurity Issues
    1) Server and database security
      - Aggregation(cluster), Inference
      % Open Database Connectivity(ODBC) is a standard API and a database feature that allows applications to communicate with different types of database management systems(DBMS)
        without having to be directly programmed for interaction with each type using SQL as the standard language.
      % In the relational model, data is organized into tables (relations), where each row is a tuple (a record or instance of the relation), and each column is an attribute (a property or characteristic of the relation)
      % Contamination is the mixing of data from a higher classification level and/or need-to-know requirement with data from a lower classification level and/or need-to-know requirement.
    2) NoSQL databases
      & NoSQL is used to aggregate databases and data source that are disparate in nature such as structured database combined with instructed (unformatted) data.
      % The cardinality of a table refers to the number of rows in the table, whereas the degree of a table is the number of columns.
    3) Distributed and high-performance computing
      - Large-Scale Parallel Data, Grid Computing, Peer-to-peer Computing(Tor)
      % Grid computing utilizes the unused processing power of multiple computers across different locations, combining them to form a virtual supercomputer that is managed by a centralized controller.
      % For an office performing highly sensitive tasks, especially for a governmental entity, maintaining a low profile choosing a location with low visibility helps minimize the attention drawn to the facility
      % High-performance computing (HPC) systems are used when real-time or near-real-time processing of massive data is necessary for a particular task or application. 
  E. Embedded Systems Security
    1) Industrial control systems and operational technology
      - SCADA(supervisory control and data acquisition, Remote Central), DCS(Controlling processes), PLC
      & Programmable logic controller, Human-machine interface, data historian
      % SCADA is used to gather information from remote sensors via telemetry and operate in a large utility company to manage and operate their equipment.
      % Distributed Control System (DCS) is used to control industrial processes. It is a network of industrial control system devices that are interconnected but may be part of a closed network.
      % Programmable Logic Controller (PLCs) is a device used to monitor and control industrial equipment.
    2) Internet of things
    3) Securing smart devices
      - Firmware Version Control, Security Wrapper
    4) Secure networking for smart devices
      * Network segmentation is the most important control for embedded devices
      * Embedded device security controls are effective for mainframes as well
    5) Embedded systems
      - RTOSs(a real-time operating system), CAN bus
      % The embedded system is typically designed around a limited set of specific functions in relation to the larger product of which it’s a component.
      % An embedded system is a computer implemented as part of a larger system.
    6) Communications for embedded devices
  F. Encryption
    1) Understanding encryption
      % A trapdoor function is a type of cryptographic function that is easy to compute in one direction but difficult to reverse without special information.
      % Another term for cryptographic strength is work factor which refers to the amount of effort, time, and computational resources required to break a cryptographic algorithm or system.
    2) Symmetric and asymmetric cryptography
      - Symmetric(same key), Asymmetric(different key, public, private)
      * Keys used to encrypt and decrypt using asymmetric cryptography must be from the same pair.
      % In symmetric encryption, the same key (the private key) is used for both encryption and decryption of data. This key must be securely shared between the sender and the receiver to enable secure communication.
    3) Goals and cryptography
      - Confidentiality, Integrity, Authentication, Obfuscation(hiding), Non-Repudiation
    4) Codes and ciphers
      * Codes and ciphers are related concepts, but you should know the difference when you take the exam
      - Stream Ciphers, Block Ciphers
      % The Feistel cipher structure is a symmetric encryption design model used in many block ciphers such as Blowfish, CAST-128, and Skipjack.
      % Concealment ciphers hide the message within the physical environment or use techniques such as steganography, where the presence of the message is obscured.
      % Galois/Counter Mode (GCM) and Counter with Cipher Block Chaining Message Authentication Code mode (CCM) are the only two modes that provide both confidentiality and data authenticity. 
    5) Cryptographic math
      - Exclusive Or(XOR), 
      - Confusion, Defusion, Obfuscation
      % Confusion occurs when the relationship between the plaintext and the key is so complicated that an attacker can’t merely continue altering the plaintext and analyzing the resulting ciphertext to determine the key.
        Diffusion occurs when a change in the plaintext results in multiple changes spread throughout the ciphertext.
    6) Choosing encryption algorithms
       * Don't try to build your own encryption algorithm unless you really know what you're doing.
    7) The perfect encryption algorithm
       - One-Time pad
       % Securely exchanging the pads is essential for the security of one-time pad operations, as interception by a third party could compromise the security of the encrypted messages.
       % Using AES (Advanced Encryption Standard) in conjunction with the one-time pad is not critical to the security of one-time pad operations, as the one-time pad's security is already absolute if implemented correctly.
       % The XOR operation is used to combine the plaintext with the one-time pad key to produce the ciphertext.
    8) The cryptographic lifecycle
       % A key revocation system is responsible for invalidating cryptographic keys that should no longer be used, either because they have been compromised, expired, or are no longer needed.
  G. Symmetric Cryptography
    1) Data encryption standard(DES) - 64bit blocks, 54bit length
      % DES uses 16 rounds of computation
    2) 3DES
      * Double DES is no more secure than standard DES, due to the meet-in-the-middle attack
      - 64-bit block, 112-bit length
      % The Data Encryption Standard (DES) and Triple DES (3DES) are outdated and no longer considered secure.
    3) AES, Blowfish, and Twofish
      - Rihndael algorithm, 128-bit blocks, 128, 192, 256 bits lengths
      - Blowfish = 64 bit blocks, 32~448 bits key lengths
      - Twofish = 128-bit blocks, 128,192,256 bits lengths
      % The Advanced Encryption Standard (AES) and Rivest Cipher 6 (RC6) are modern, secure algorithms.
    4) RC4 - WEP, WPA, SSL, TLS
    5) Cipher modes - ECB mode, CBC mode, Counter mode
      * Counter mode allows block ciphers to act more like stream ciphers and allows you to break an encryption or decryption operation into multiple independent steps.
      % Counter mode (CTR) encrypts successive values of a "counter" and uses this to encrypt the plaintext, meaning it does not depend on the previous encrypted block for the next block's encryption.
      % CBC(Cipher Block Chaining) mode feeds the ciphertext of the previous block into the encryption of the next block, 
        ensuring that identical plaintext blocks encrypt to different ciphertext blocks when the preceding ciphertext block is different.
    6) Steganography
  H. Asymmetric Cryptography
    1) Rivest-Shamir-Adelman(RSA)
      * Users create RSA key pairs using two large prime numbers.
      % A public key encryption algorithm
    2) PGP and GnuPG
      - Pretty Good Privacy, Open PGP, Combine Sym and Asym
      % A randomly generated symmetric key is used to encrypt the contents of a message when using PGP.
      - GPG = alternative to PGP
    3) Elliptic curve and quantum cryptography
      * You won't need to know the details of ECC. Remember that it doesn't use prime factorization.
      % Elliptic curve cryptography relies on the difficulty of the elliptic curve discrete logarithm problem, which quantum algorithms can solve more efficiently than classical algorithms.
      % Elliptic Curve Cryptography (ECC) is more efficient than RSA because it provides equivalent security with much smaller key sizes.
  I. Key management
    1) Key management practices
      % Key clustering refers to the phenomenon where two different cryptographic keys generate the same ciphertext from the same plaintext.
      % Key Generation, Key Initialization, Key Distribution, Key Activation, Key Usage, Key Rotation/Update, Key Deactivation, Key Termination, Key Archival
    2) Key exchange - Out-of-band key exchange, in-band key exchange(Diffie-Hellman)
    3) Diffie-hellman - Asymmetric, authentication
      % The difficulty of solving the discrete logarithm problem provides the security underlying the Diffie-Hellman algorithm.
      % The Diffie-Hellman algorithm is used to securely exchange cryptographic keys over a public, nonsecure medium.
    4) Key escrow - Recovery Agents
      % The clipper chip performed encryption, but it included a special law enforcement access field, or LEAF, value that allowed government agents to access the content of the communication.
    5) Key stretching - Salting, Hashing, PBKDF2 (Password-based key Derivation Function v2), bcryypt(blowfish)
    6) Hardware security modules(HSM)
  J. Public Key Infrastructure
    1) Trust models - Asymmetric Cryptography, Web of Trust(WOT)
    2) PKI and digital certificates
      % X.509 defines the format of public key certificates, which are used within PKI to authenticate and secure communications over networks, particularly the Internet.
      % In PKI, the revocation request grace period refers to the time it may take for a Certificate Authority (CA) to process and update the revocation status of a certificate.
      % A trust anchor refers to a public key that can be used to verify the certificate used in a digital signature.
      % Digital certificates typically have different assurance levels,
        Level 1 (Basic Assurance): Requires minimal identity verification, often just an email address.
        Level 2 (Medium Assurance): Involves verifying the user's name and email address, and sometimes additional identity details.
        Level 3 (High Assurance): Requires thorough identity verification, such as government-issued IDs.
        Level 4 (Very High Assurance): Involves in-person verification and is used for very sensitive transactions.
    3) Hash functions - MD5, SHA(Federal Computer), RIPEMD(government-sponsored)
      % The SHA-2 hash function produces hashes of 224, 256, or 512 bits.
      % Any change to the contents of a file changes the hash value generated for that file. This would include changing a single character, removing a line, or adding a line (even if that line is blank).
      % The output of a hash function must be a fixed length, not any length. Hash functions must also be one-way, collision resistant, and relatively easy to compute.
      % Message digests (or hashes) are used to prove the integrity of the original image.
      % The Message Authentication Code (MAC) ensures message integrity.
      % Message Security Protocol (MSP) is a U.S. military standard designed to protect email communications
    4) Digital signatures 
      - Authentication(signed message), Integrity(not alter), Non-reputation(prove third party)
      % Authentication verifies the identity of the sender
      % Digital signatures verify the authenticity and integrity of the driver files, ensuring they come from a trusted source and have not been tampered with since being published. 
      % The digital signature is authentic, the certificate has not expired, and the certificate has not been revoked.
      - Collision-resistant, Asymmetric                    
    5) Digital signature standard
      - RSA, ECDSA, EdDSA
      % DSA is no longer an acceptable implementation of digital signatures in the federal government under FIPS 186-5.
      % The hashing algorithm that was designed to be used with the Digital Signature Standard (DSS) is the Secure Hash Algorithm (SHA), specifically SHA-1 developed by the National Security Agency (NSA)
      % The Digital Signature Standard allows federal government use of the Digital Signature Algorithm, RSA, or the Elliptic Curve DSA in conjunction with the SHA-1 hashing function to produce secure digital signatures.
      % The Bureau of Industry and Security(BIS) within the Department of Commerce sets regulations on the export of encryption products outside of the United States.
      % The Elliptic Curve Digital Signature Algorithm (ECDSA) is the only one of the algorithms listed here that supports true digital signatures, providing integrity verification and nonrepudiation.
    6) Created a digital certificate
    7) Revoke a digital certificate - CRL(Certificate Revocation List), OCSP(Online Certificate Status Protocol)
      % The most effective method of revoking digital certificates is through the interactive OCSP responder.
      % Utilizing certificate revocation lists for revoking digital certificates is a manual process with inherent delays.
      % A Certificate Revocation List (CRL) is a list of digital certificates that have been revoked by the issuing Certificate Authority (CA) before their scheduled expiration date.
    8) Certificate stapling
      - Helping future visits for 24 hours
      % Certificate stapling involves a server sending a timestamped OCSP response to prove a certificate's validity but does not indicate that a certificate is unlikely to change over time.
    9) Certificate authorities
      - Self-Signed certificates, Offline CAs
      % The certificate owner can self-sign their own certificate. However, self-signed certificates may be used only internally and are not considered valid on the Internet.
      % The certificate authority(CA) digitally signs applicant certificates with the CA's digital signature.
      % The root CA is an offline CA that is used only to sign the certificates of intermediate CAs belonging to the same organization.
      % Internal CA refers to a certificate authority within an organization, which could be online or offline depending on its role, but is not specifically categorized as typically offline.
    10) Certificate subjects
      * You may find exam questions that discuss certificate object identifiers (OIDs).
      - Servers(SSH), Devices, Individuals, Developers(code signing)
      % SSH encrypts the connection between the client and server, ensuring that data, commands, and terminal sessions are protected from eavesdropping and tampering.
      - Certificate Pinning
      % Certificate pinning is used to tell clients that a certificate, or its public key, is unlikely to change over time.
        It helps in preventing man-in-the-middle attacks by ensuring that the client accepts only a specific certificate or public key.
    11) Certificate types
      - Root Certificates, Wildcard Certificates
      - Domain validation(DV), organizational validation(OV), extended validation(EV, highest)
    12) Certificate formats
      - DER(Distinguished Encoding Rules), PEM(Privacy Enhanced Mail)
      * CRT files may be either DER binary certificates or PEM text certificates.
      - PFX(Personal Information Exchange), P7B
      % The PFX format is most closely associated with Windows systems that store certificates in binary format, whereas the P7B format is used for Windows systems storing files in text format.
  K. Cryptanalytic Attacks
    % Cryptanalysis is primarily concerned with studying and analyzing cryptographic systems to find weaknesses and vulnerabilities.
    1) Brute-force attacks
    2) Knowledge-based attacks
      - Frequency Analysis
      * You won't need to perform cryptanalysis on the exam. You just need to know the different techniques.
      % Frequency analysis attack involves statistical analysis of ciphertext to detect patterns that might reveal the underlying plaintext,
        exploiting the fact that certain letters or combinations appear more frequently in a language.
      - Chosen Plaintext Attack
      % Chosen plaintext attack allows the attacker to encrypt plaintexts of their choosing, gaining information to decrypt other messages 
        or deduce the encryption key, rather than analyzing ciphertext for patterns.
      % Chosen ciphertext attacks require access to the algorithm and work by having the attacker perform encryption that results in an expected ciphertext.
        The attacker generally has access to the cryptographic system and can choose ciphertext to be decrypted into plaintext.
      - Known-plaintext attack
      & An attacker has not only ciphertext but also known plaintext that corresponds with it, enabling the attacker to compare the known plaintext with its ciphertext results to determine any relationships between the two.
    3) Eavesdropping attacks - Man-in-the-middle attack, Replay attack, SSL Stripping
      % RSH(Remote Shell) is an older protocol that transmits data, including passwords, in plaintext, making it vulnerable to interception by attackers like man-in-the-middle.
      % In a replay attack, the malicious individual intercepts an encrypted message between two parties (often a request for authentication) and then later replays the captured message to open a new session.
    4) Implementation attacks - Fault Injection Attack, Side-channel attack, Timing attack
      % Fault injection attacks compromise the integrity of a cryptographic device by causing some type of external fault, such as the application of high-voltage electricity.
      % Implementation attacks rely on flaws in the cryptographic algorithm.
      % Side-channel attacks use information gathered about a system’s use of resources, timing, or other characteristics to contribute to breaking the security of encryption.
    5) Limitations of encryption algorithms
    6) Ransomware - Mimikatz, Countermeasure(Backups, Antimalware)
      * Ransomware is specifically called out in the exam objectives
  L. Physical Security
    % Crime Prevention Through Environmental Design (CPTED) has four main strategies: natural access control, natural surveillance, and natural territorial reinforcement, maintenance.
    % The six common physical security control mechanisms is Deter, Deny, Detect, Delay, Determine, Decide.
    1) Site and facility design
      % Lighting is often claimed to be the most commonly deployed physical security mechanism.
      % Key locks are the most common and inexpensive form of physical access control device for both interior and exterior use.
      % An access control vestibule is a double set of doors that is often protected by a guard and used to contain a subject until their identity and authentication is verified.
      % Security guards have the ability to make real-time decisions and discriminating judgments based on context, assess situations dynamically, and respond accordingly.
      % Layering is the deployment of multiple security mechanisms in a series.
      % The primary elements of a cable plant management policy should include a mapping of the entrance facility (i.e., demarcation point), equipment room, backbone distribution system, telecommunications room, and horizontal distribution system.
      % Changing default passwords on PBX(Private Branch Exchange) systems provides the most effective increase in security. 
        PBX systems typically do not support encryption, although some VoIP PBX systems may support encryption in specific conditions.
    2) Data center environmental controls - Expanded Envelope(64.5~80.6), Dew Point Range(15.8~59)
      * Watch for exam questions that are indirectly covering the hot aisle/cold aisle strategy
      % A PIDAS (perimeter intrusion detection and assessment system) is a fence system that has two or three fences used in concert to optimize security.
    3) Data center environment protection
      - Class A(wood), Class B(oil), Class C(data center), Class D (industrial), Class K(Kitchen)
      * Be able to identify the classes of fire extinguishers on the exam.
      % A preaction system is the best type of water-based fire suppression system for a computer facility because it provides the opportunity to prevent the release of water in the event of a false alarm or false initial trigger.
    4) Power control - Blackouts, Sags(dim), Brownouts, Spikes, Surges(a prolonged high voltage)
      % Line conditioners are devices designed to regulate voltage and clean the power supply by filtering out noise, spikes, and other electrical disturbances,
        ensuring a steady and consistent voltage level to protect sensitive equipment.
      % A UPS (Uninterruptible Power Supply) is a device that provides backup power to electronic equipment during power outages or voltage drops.
    5) Physical access control - Locks
      % Shimming involves using a thin piece of metal or plastic, called a shim, to bypass the locking mechanism of a lock, especially padlocks or door locks.
      % Raking is a lockpicking technique used to manipulate the pins inside a lock to align them with the shear line, allowing the lock to open.
      % The main types of mechanical locks are warded locks and tumbler locks
      % A cipher lock is a programmable lock that allows entry based on a code entered into a keypad and can be programmed with more than one code for duress. 
    6) Visitor management
      % Cameras should always be disclosed to visitors when used as part of physical security controls to ensure compliance with privacy laws and regulations.
    7) Physical security personnel - Two-Person Integrity
  M. Software Security Architecture
    1) SOAP and REST 
      - API(Application Programming Interface, AWS, Twitter)
      - SOAP(Simple Object Access Protocol) = XML
      - REST(Representational State Transfer) = HTTPS
      % S-HTTP provides encryption specifically for individual documents or messages, making it suitable for your requirement to encrypt a single document.
      % HTTPS encrypts the entire communication session between the client and the server.
      % Software upgrade deployment is typically a responsibility of the network administrator, as it involves managing the overall infrastructure and ensuring that systems are up to date.
    2) SOA and microservices
      - Service-Oriented Architecture(SOA)
      - Microservices
      % Microservices are fine-grained services that provide small and discrete functions to other services.
      % Microservices are an emerging feature of web-based solutions and are derivative of service-oriented architecture (SOA). 
      % Arduino is an open source hardware and software organization that creates single-board 8-bit microcontrollers for building digital devices.


-----------------------------------------------------------------------------------------------------------------------------------------------------------


4. Communication and Network Security
  A. TCP/IP Networking
    1) Introducing TCP/IP - TCP / UDP, OSI Model
      * Know the seven layers of the OSI model and the four layers of the TCP model.
      % An active hub functions at the Physical layer (Layer 1) of the OSI model.
      % Data-link layer has flow control, error notification, and physical addressing.
      % Flow control in Data and transport layers manages the rate of data transmission between two devices to ensure that a fast sender does not overwhelm a slow receiver.
      % The Network layer (Layer 3) is responsible for ensuring that data is properly directed through the network to reach its intended endpoint such as path selection and logical addressing.
      % Transport layer has flow control, reliable communication, error detection and recovery
      % The Application layer provides the interface between the application software and the network, enabling various services such as file transfers, printing, messaging, and email.
      % Multicasting is the transmission of data to multiple specific recipients.
        Internet Group Management Protocol (IGMP) is used to register a host’s dynamic multicast group membership in order to receive a copy of the data stream.
        TFTP systems can be used to host or cache multicast datasets that are to be sent to the multiple recipients.
      % Fraggle is a denial of service (DoS) attack that uses UDP.
    2) IP addresses and DHCP - IPv4, IPv6
      % The "/22" indicates that 22 bits are used for the network portion of the address. Since IPv4 addresses are 32 bits in total, the remaining bits are used for the host portion. 32 - 22 = 10
    3) Network traffic
      % A dual backbone configuration typically involves having two separate network backbones, which ensures that if one backbone fails, the other can take over, maintaining network availability and minimizing downtime.
      % SPAN ports and network taps are the most reliable mechanisms for gathering network traffic.
      % Quality of service (QoS) controls allow administrators to prioritize different types of network traffic.
      % A TCP Wrapper is an application that can serve as a basic firewall by restricting access based on user IDs or system IDs.
    4) Domain name system (DNS) - UDP port 53, DNSSEC(digital signatures)
      % DNSSEC uses certificates to perform mutual authentication between DNS servers, and thus public key infrastructure (PKI) is needed to provide and support those certificates.
    5) Network ports
      * Memorize the list of common ports before taking the exam.
      - Port 21(FTP), Port 22(SSH), Port 3389(RDP), Port 137, 138, and 139(NetBIOS)
      - Port 25(SMTP), Port 110(POP), Port 143(IMAP)
      - Port 80(HTTP), Port 443(HTTPS)
      % Port 1433 is a database port and should never be exposed to an external network
    6) ICMP -Traceroute
    7) Multilayer protocols -  DNP3(Distributed Network Protocol)
  B. Secure Network Design
    1) Public and private addressing - IP Addresses Scarce, Network Address Translation(NAT), Port Address Translation(PAT)
      % Network Address Translation-Protocol Translation (NAT-PT) (RFC-2766) can be used to convert between IPv4 and IPv6 network segments similar to how NAT converts between internal and external addresses.
      % Static NAT is needed to allow an outside entity to initiate communications with an internal system behind a NAT proxy.
        Static NAT can be appropriately and securely used to grant external entities access to resources positioned in a screened subnet or an extranet, especially when those resource hosts are using private IP addresses.
      % RFC 1918 addresses are not internet routable or accessible because they are reserved for private or internal use only.
    2) Subnetting - Subnet Masks
    3) Security zones - Zero Trust, Extranet, Honeynet, Ad Hoc Network(Temporary, "for this specific purpose")
      & Physical security zones are created to separate untrusted or public areas from restricted areas, such as those that house sensitive equipment and information processing activities.
      % A network firewall is a security solution that can be used to separate a network into three distinct security zones.
      % A screened subnet is a type of security zone that can be positioned so that it operates as a buffer network between the secured private network and the internet and can host publicly accessible services.
    4) Isolating sensitive systems 
      - Network Segmentation
      * Physically isolated systems are called "air-gapped" systems.
      - Jump Server
      * Jump servers, jump boxes, and jump hosts are all the same thing.
    5) VLANs and logical segmentation - VRF(Virtual Routing and Forwarding), Virtual Domain, Network Overlays, Encapsulation
      % LiFi (Light Fidelity) uses light to transmit data wirelessly, employing LED lights to provide high-speed communication in a manner similar to WiFi, but with light waves instead of radio waves.
      % A VLAN (virtual LAN) is a hardware-imposed network segmentation created by switches that requires a routing function to support communication between different segments.
      % Virtual eXtensible LAN (VXLAN) is an encapsulation protocol that enables switch-created network segments (i.e., VLANs) to be stretched across subnets and geographic distances.
      % Encapsulation is both a benefit and a potentially harmful implication of multilayer protocols(IPv4 with IPv6).
      & Encapsulation, known as tunneling, is used to place traffic from one protocol into another protocol so that the traffic can be protected and transmitted.
    6) Security device placement
    7) Software defined networking(SDN)
      & Software-defined networking creates entire networks using only software
      & Software-defined wide area networking(SD-WAN) is a logical extension of software-defined networking(SDN) that creates software-defined WANs.
    8) Transmission media - VPC, SDV
      % Overt Storage Channel: A legitimate and intended method of communication where data is stored and accessed by authorized processes.
      % Covert Storage Channel: An unauthorized and unintended method of communication that exploits the storage medium to transfer information between processes in a way that bypasses normal security controls.
      % A PVC(permanent virtual circuit) reestablishes a link using the same basic parameters or virtual pathway each time it connects.
        PVC can be described as a logical circuit that always exists and is waiting for the customer to send data.
        A switched virtual circuit (SVC) has to be created each time it is needed using the best paths currently available before it can be used and then disassembled after the transmission is complete.
        SVCs use unique settings each time.
    9) Cloud networking
    10) Zero trust and SASE
  C. Network Security Design
    1) Routers, switches, and bridges
      % A switch operates primarily at layer 2 of the OSI model, handling data frames between devices on the same local area network (LAN).
      % A router operates mainly at layer 3, routing data packets between different networks based on IP addresses.
      % A router is the correct location to deploy Access Control Lists (ACLs) for confining sensitive internal data traffic to specific subnets
      % Cut-through switching is a method used in network switches where the switch starts forwarding a data frame to the destination as soon as it reads the destination address from the frame's header,
        without waiting for the entire frame to be received.
      % RIP(Routing Information Protocol) uses hop count as a simple metric to determine the best path to a destination network.
      % A hop(router) refers to the journey a data packet takes from one router or intermediate device to another.
    2) Network topologies
      % A Multistation Access Unit (MAU) is a central connecting device used in Token Ring networks
    3) Transport architecture
      % Configuring devices, monitoring performance, and troubleshooting problems are tasks associated with the management plane, which oversees and manages the network.
      % The control plane is responsible for making decisions about where data should flow through the network, using protocols to determine the best path for data packets.
    4) Firewalls - Stateful Inspection, Implicit Deny
      * You need to understand the default/implicit deny principle of firewalls.
      & An allow list enables a default-deny method of controlling access, since anything not in the list is denied by default.
      & A deny list enables a default-allow method of controlling access.
      % The implicit deny principle ensures that access to an object is denied unless access has been expressly allowed (or explicitly granted) to a subject.
      % Stateful inspection firewalls are able to grant a broader range of access for authorized users and activities and actively watch for and block unauthorized users and activities.
        It enables the real-time modification of the filtering rules based on traffic content and context. 
      & Circuit-level(End-to-end communication session), Application(Characteristics), Packet-filtering(traffic characteristic such as IP address), Stateful inspection(connection state of the inbound and outbound)
      % SOCKS is a circuit-level proxy firewall that provides a secure channel between two computers.
      % Application-level proxy firewalls inspect detrimentally the contents of packets at the application layer to introduce significant latency and overhead, leading to a more noticeable impact on network performance.
      % Firewalls use a rule-based access control model with rules expressed in an access control list.
      & A next-generation firewall typically is a multifunction device that incorporates firewall, proxy, and intrusion detection/prevention services.
    5) Proxy servers - Forward Proxies, Reverse Proxies, Transparent Proxies
    6) Load balancers - Autoscaling, Round-Robin Scheduling, Session Persistence
    7) VPNs and VPN concentrators - IPsec(Layer 3, L2TP), TCP Port 443, TLS VPN, L2TP/IPSec VPN, Client-to-site VPN, Site-to-site VPN
      % A VPN is a secure tunnel used to establish connections across a potentially insecure intermediary network. Intranet, subnet, extranet, and VLAN are examples of network segmentation.
      % L2TP (Layer 2 Tunneling Protocol) over IPSec (Internet Protocol Security) uses encryption to protect transmitted traffic and supports the transmission of multiple protocols.
      * Split-tunnel VPNs provide users with a false sense of security
      % The external firewall shields the VPN gateway from direct exposure to the internet, filtering out unauthorized traffic.
      % If traffic is decrypted at the VPN gateway, the firewall can inspect the plaintext before it enters the internal network, allowing for additional security checks.
      % In a VPN, trust is not as much of a primary concern because the communication is encrypted and secured over a public network like the internet.
      % Tunnel mode VPNs are used to connect networks to networks or hosts to networks.
    8) Network intrusion detection and prevention
      % An IDS is most likely to connect to a switch port configured as a mirrored port.
      * Anomaly detection, behavior-based detection, and heuristic detection are the same thing.
      % Anomaly detection identifies unusual patterns that may indicate a security incident, based on statistical analysis, without frequent specific threat updates.
      % Signature detection relies on a database of known threat signatures (misused) and requires frequent updates from the vendor to recognize new threats.
      % Snort is an open-source Intrusion Detection System (IDS) that monitors network traffic in real-time to detect suspicious activities and possible attacks.
      % The primary functional components of an IDS include information sources (such as logs or network traffic), event report analysis (to analyze data for potential intrusions), and response mechanisms (to act on detected threats).
        The other options listed (database component and event report analysis) are more closely related to typical IDS functions.
      % Heuristic detection identifies potentially malicious code by analyzing the behavior and characteristics of files, even if they do not match known virus signatures.
      % Proximity detectors create a magnetic field around an object or area, and when this field is disturbed by an intruder, the system triggers an alert.
      % An IPS not only detects potential security breaches (like an IDS) but also takes proactive steps to block or prevent the intrusion.
      % HIDS focuses on data specific to the host, such as logs and audit trails, rather than network traffic or OS alarms.
    9) Protocol analyzers - tcpdump, tcpreplay
      % A protocol analyzer (also known as a packet sniffer) captures and analyzes network traffic to inspect the data being transmitted over the network, including whether passwords are being sent in plain text or encrypted.
    10) Unified threat management
      % Breach and attack simulation (BAS) systems are designed to inject threat indicators onto systems and networks in an effort to trigger other security controls.
    11) Content distribution networks(CDNs)
  D. Network Security Techniques
    1) Restricting network access 
      - Perimeter security, Network Access Control
      - Rule based, role based, time based, location based
      % Rule-based access control (RBAC) uses a set of pre-defined rules that determine access permissions based on conditions such as time of day, IP address, or other criteria.
        A rule-based access control model uses global rules applied to all users and other subjects equally.
      % Role-Based Access Control (RBAC) offers several advantages: Low-Security Cost, By grouping permissions into roles, and Easier to Implement with well-defined roles and responsibilities.
      & Context-dependent access means that users must be in the correct environment and context in order to perform specific actions.
      & Content-dependent access means that users are restricted based on the type os information that an object holds, such as healthcare or financial information
    2) Network access control(NAC) - EAP(Supplicant), RADIUS (Authentication Server)
      % The network access server is the client within a RADIUS architecture.
      % NAC enforces security policies by evaluating devices before allowing them access to the network.
    3) Firewall rule management
      % A shadowed rule happens when an earlier rule in the firewall's rule set matches traffic that a later rule was intended to match, rendering the later rule ineffective.
      % An orphaned rule occurs when a service is decommissioned but the related firewall rules are not removed, leaving unused or unnecessary rules.
    4) Router configuration security
      * You won't need to know the syntax of router access control list commands.
    5) Switch configuration security - VLAN Pruning, VLAN Trunk Negotiation, Port Security, DHCP Snooping
    6) Maintaining network availability - Flooding Attack, Flood Guard Technology, Routing Loops, Spanning Tree Protocol(STP), BPDU Guard
    7) Network monitoring - Network Flow data
      % station statistics include metrics related to individual network stations, such as traffic patterns, errors, and packet loss
      % packet capture offers detailed packet-level analysis, while station statistics provide a broader view of network activity for specific devices
    8) Firewall and network logs - SIEM
    9) Network performance metrics - Latency(Concealment), Jitter
    10) SNMP
      * Use SNMPv3. Earlier versions have critical security flaws.
      % GetRequest messages are used by a network management system to request information from an SNMP agent.
      % SetRequest messages are used by a network management system to change a value on an SNMP agent.
      % Response messages are sent by an SNMP agent to a network management system in reply to GetRequests and SetRequests, not to report unusual events.
      % Trap can an SNMP agent send to a network management system to report an unusual event
    11) Deception technologies - Darknets, DNS Sinkhole
      % Using a DNS sinkhole, an admin can forward malicious DNS requests to another IP address to keep from harm.
    12) Network support - SLA (service level agreement)
  E. Specialized Networking
    1) Telephony - VoIP
      % Another term used for Plain Old Telephone Service (POTS) is PSTN (Public Switched Telephone Network).
      & Integrated Services Digital Network (ISDN) uses legacy PSTN with specialized equipment to send digital data over analog lines.
      % VLAN hopping is a switch security issue, not a VoIP security issue.
      % Implementing Secure Real-time Transport Protocol (SRTP) is the best option to secure VoIP and prevent the reoccurrence of the eavesdropping attack.
    2) Multimedia collaboration - XMPP
    3) Storage networks
      % Fibre Channel requires the use of dedicated connections and is known for its high speed and reliability in connecting computer data storage to servers.
      % NFS (Network File System), CIFS (Common Internet File System), and SMB (Server Message Block) are protocols used by NAS(Network-Attached Storage) devices for file sharing over a network.
  F. Transport Encryption
    1) TLS and SSL
      * TLS depends upon pairings of encryption and hash functions known as cipher suites.
      % TLS allows for use of TCP port 443; prevents tampering, spoofing, and eavesdropping; and can be used as a VPN solution.
      % TLS and SSL are not interoperable or backward compatible.
      * Session keys are also known as ephemeral keys.
    2) IPsec
      - ESP(Encapsulating Security Payload, Confidentiality), Authentication Header(AH, Integrity)
      % IPsec operates at the Network layer (layer 3).
      & ESP provides encryption services for data payloads in IPSec.
      % Tunnel mode encapsulates the original IP packet within a new packet
      % Transport mode is typically used for end-to-end communication between two hosts within the same network or securing communication between client-server applications
      - SA(Security Association)
      - Older Linux systems used telnet for remote access
      % Internet Security Association and Key Management Protocol (ISAKMP), an element of Internet Key Exchange (IKE), is used to organize and manage the encryption keys that have been generated and exchanged by OAKLEY and SKEME
        to support multiple simultaneous VPNs from each host.
    3) Remote network access
      % The primary examples of remote access techniques are remote node operation, remote control, screen scraping, and service specific.
      & Remote journaling is a real-time process that transmits only changes in files to the backup system or media.
  G. Wireless Networking
    1) Understanding wireless networking
      * Wi-Fi signals travel over open airwaves and are subject to undetectable interception!
      % Capturing electromagnetic signals (emanations) that can be intercepted from wireless networks.
    2) Wireless encryption
      & The IEEE 802.1X standard is a port-based network access control (NAC) standard that is widely used as an enterprise authentication method in wireless networks,
        but can also be used extensively in wired networks; allows for multiple authentication and encryption methods
      % WPA3 uses Simultaneous Authentication of Equals (SAE) for key exchange, providing enhanced protection against offline dictionary attacks compared to its predecessors.
      % WPA3, 802.11i, SAE, and WPS are all technologies that are specifically defined as part of wireless networking. 
      % TKIP (Temporal Key Integrity Protocol) was used in WPA for encryption but has been phased out in favor of more secure methods like CCMP and does not involve key exchange.
      % CCMP (Counter Mode Cipher Block Chaining Message Authentication Code Protocol) is an encryption protocol 
        used in Wi-Fi security for data confidentiality and is not specifically a key exchange mechanism.
      % SET (Secure Electronic Transaction) protocol is developed to secure online credit card transactions, using digital signatures to authenticate parties involved and digital certificates to verify identities.
    3) Wireless authentication - Captive portals, EAP (Extensible Authentication Protocol)
      % EAP (Extensible Authentication Protocol) is commonly used in secure environments where strong authentication methods, such as smart cards.
      - EAP-TLS (Transport Layer Security): Uses public key infrastructure (PKI) for mutual authentication via digital certificates. It’s highly secure but requires a complex setup.
      - EAP-TTLS (Tunneled TLS): Extends EAP-TLS by allowing the use of other authentication methods within a secure tunnel, reducing the need for client certificates.
      - PEAP (Protected EAP): Similar to EAP-TTLS, it uses a TLS tunnel to protect other authentication methods, often combined with MS-CHAPv2.
      - EAP-MD5: Provides simple password-based authentication, but it’s considered less secure due to lack of protection for the handshake.
      - LEAP (Lightweight EAP): Proprietary to Cisco, used mainly in wireless networks but considered weak against certain attacks.
      - EAP-SIM (Subscriber Identity Module): Used for authenticating with SIM cards in mobile networks.
      - EAP-AKA (Authentication and Key Agreement): Used for authentication in 3G mobile networks.
      * Make sure you understand the security status of the specific EAP variants in use on your network.
    4) Wireless signal propagation - Omnidirectional, Directional, Site survey
      % Beam forming uses multiple antennas to detect the location of a device connecting to the wireless access point and then steers the signal in the direction of that device.
      % Pulse modulation refers to a method of encoding information in a signal, rather than focusing wireless signals towards devices.
      % A site survey helps you detect any unauthorized access points (often referred to as "rogue" access points) that might have been set up in your building.
      % Orthogonal Frequency-Division Multiplexing (OFDM) offers high throughput with the least interference.
    5) Wireless networking equipment - Fat Access Points, Wi-Fi Analyzer
      % A wireless controller manages configurations, optimizes performance, and reduces interference among APs in wireless networks.
      % Fat AP refers to an access point with built-in intelligence for handling data processing but does not manage or optimize multiple APs.
  H. Mobile Device Security
    1) Mobile connection methods - Cellular Networks, Wi-Fi Networks, NFC, Bluetooth(30 feet)
      % LEO(Low Earth Orbit) offers high-speed communications with minimal latency when compared to other satellite offerings.
    2) Mobile device security
      % Bluejacking involves sending anonymous, unsolicited messages to Bluetooth-enabled devices within range, typically for harmless pranks or marketing purposes.
    3) Mobile device management(MDM)
      % The concept of corporate-owned, personally enabled (COPE) means the organization purchases devices and provides them to employees.
        Each user is then able to customize the device and use it for both work activities and personal activities.
      % A corporate-owned mobile strategy is when the company purchases mobile devices that can support compliance with the security policy.
      % To protect cell phones owned by an organization, you should employ Maintain physical control, Enable user authentication, and Disable unneeded features
    4) Mobile device tracking
    5) Mobile application security
      % Unified endpoint management(UEM) is type of software tool that provides a single management platform to control mobile, PC, IoT, wearables, ICSs, and other devices. 
    6) Mobile security enforcement
      % Sideloading refers to the process of installing apps on a device from sources other than the official app store.
      % Jailbreaking is the process of removing software restrictions imposed by iOS on devices by Apple, allowing the installation of unauthorized apps,
        but does not specifically refer to the act of installing apps outside of the App Store.
    7) Bring your own device (BYOD)
    8) Mobile deployment models
  I. Host Security
    1) Operating system security - System Hardening
      % Endpoint security is the security concept that encourages administrators to install firewalls, malware scanners, and an IDS on every host.
    2) Malware prevention
      - Viruses, Worms, Trojan Horses, Spyware
      - Protection = Sandboxing(isolates)
      - Spam Filtering
      % A companion virus, also known as a "spawning" virus, works by creating a new file with the same name as a legitimate file but with a different extension.
      % Retroviruses are designed specifically to target and disable security software, including antivirus programs, making it more difficult for the system to detect and remove the malicious code.
      % Fileless malware is malware that leaves no trace of its presence nor saves itself to a storage device, but is still able to stay resident and active on a computer.
    3) Application management
      * While the terms whitelisting and blacklisting are problematic, you should still know them for the exam.
      % BitLocker is a full disk encryption feature designed to protect data by providing encryption for entire volumes so that data cannot be stolen.
      % BitControl does not exist as an application control technology in Microsoft Windows.
      % App control is a general term for technologies that manage or restrict application usage, but it is not a specific built-in feature of Windows.
      % AppLocker is the application control technology built-in to Microsoft Windows
    4) Host-based network security controls
      * Granting network access requires configuring both network and host firewalls.
      % Host firewall is a built-in feature of Microsoft Windows designed to block unauthorized access to or from private networks.
    5) File integrity monitoring(FIM)
      % Tripwire is a file and data integrity monitoring tool that helps detect and report changes to files and configurations in a system.
      % Microsoft Endpoint Configuration Manager (MECM), formerly known as SCCM, is used for managing large groups of computers, focusing on configuration management rather than file integrity monitoring.
      % The two-phase commit protocol ensures that an entire transaction is executed in a coordinated manner across multiple databases.


-----------------------------------------------------------------------------------------------------------------------------------------------------------


5. Identity and Access Management (IAM)
  A. Identification
    1) Authentication, authorization, and accounting (AAA)
      * Remember that identification and authentication are separate and distinct steps!
      % Authorization limits user activity to actions they are permitted to perform, following the principle of least privilege.
      % Authentication verifies that a user is who they claim to be.
    2) Usernames and access cards
      % Memory cards are used for storing data but do not have the capability to process information or execute tasks.
    3) Biometrics - Low false, crossover error rate (CER)
      % FAR measures the frequency at which unauthorized users are inadvertently admitted.
      % FRR measures the frequency at which legitimate users are denied access to a system or facility.
      % By using multiple fingerprints, the system has more data to work with, which can reduce the chances of false rejections (Type 1 errors).
      % A lower CER indicates a higher-quality biometric device and a higher CER indicates a less accurate device.
      % Signature dynamics, also known as dynamic signature verification, analyzes both the physical motions involved in signing (such as speed, pressure, and rhythm)
        and the static features of the signature itself (such as the shape and style).
      % A capacitance motion detector senses changes in the electrical or magnetic field surrounding a monitored object.
      & A photoelectric sensor measures changes in light, such as those that may interrupt a beam of light or shadows in a lighted room.
      % Iris scanners are the most accurate, noninvasive biometric control from those listed.
    4) Registration and identity proofing
      - Request, Approval, Identity proofing, Issuance
  B. Authentication
    1) Authentication factors
      - Something you know, Something you are, Something you have
      - False Acceptance, False Rejection
    2) Multifactor authentication
      % Two-factor authentication is the strongest method.
    3) Something you have
      % An authentication token that requires a button to be pushed each time to receive a token is based on HOTP (HMAC-based One-Time Password).
    4) Password authentication protocols(PAP) - CHAP(Challenge-Handshake Authentication Protocol)
      % CHAP provides encrypted authentication by periodically verifying the identity of the client using a three-way handshake.
      % PAP (Password Authentication Protocol) sends credentials in plaintext.
    5) Single sign-on and federation
      % Federated Identity Management (FIM) is best to implement when you have accounts across multiple service providers with whom you would like to share identity information.
        With FIM, you can use one login to access resources you've been authorized throughout the federation.
      % To implement a single sign-on (SSO) system, the organization could use the following technologies: RADIUS, Kerberos, SESAME, Active Directory
      % SSO solutions and centralized administration and make it easier for administrators to manage user accounts.
      % A federation can include two or more networks and allow users in each network to share network resources.
    6) RADIUS (Remote Authentication Dial-In User Service)- Centralized approach
      * Remember that a RADIUS client is usually an application server!
      % RADIUS typically uses UDP, which is less reliable than TCP, and does not fully encrypt the authentication session, only the password.
      % Diameter supports more complex network access scenarios and is commonly used in modern telecommunications
      % TACACS is the original version of the protocol and is less sophisticated compared to TACACS+, lacking full encryption and the use of TCP for reliable communications.
      % TACACS+ is an open-standard remote connection protocol and an authentication protocol that fully encrypts the authentication session, uses the reliable TCP protocol and will work on Cisco devices.
      % The protocol that uses port 1812 to communicate with dial-up users is RADIUS.
      % The port TCP 49 is for TACACS+.
      % SESAME (Secure European System for Applications in a Multi-vendor Environment) is an authentication protocol that was designed to address some of the known vulnerabilities in Kerberos,
        such as the risk associated with the transmission of session keys. 
      % Callback ensures that only users from specific locations (those with authorized phone numbers) can access the network, adding an additional layer of security.
    7) Kerberos and LDAP 
      - Kerberos = core protocols for MS Active directory, Port 88, Golden tickets
      % The primary purpose of Kerberos is authentication since it allows users to prove their identity.
      % Active Directory (AD) is a directory service developed by Microsoft for Windows domain networks. 
      - LDAP = port 389, Port 636
      - NTLM (NT LAN Manager)
      % NTLM is known to be susceptible to pass-the-hash attacks, and this scenario describes a pass-the-hash attack.
      - TGS (Ticket Granting Server), AS (Authentication Server), TGT (Ticket Granting Ticket)
      % TGT includes information about the client and a copy of the client TGS session key.
      % When a client wishes to access a service, the client contacts the TGS.
      % The AS looks up the user in its database and retrieves the user's password. It performs authentication of the end user.
    8) SAML - Security Assertion Markup Langauge
      % Federated organizations use the Security Assertion Markup Language (SAML) to support single sign-on (SSO) capabilities on the internet.
    9) Identity as a service (IDaaS) - Directory Integration, Application Integration
      % IDaaS provides single sign-on, provisioning, password management, and access governance
    10) OAuth and OpenID Connect
      % OAuth is an authorization protocol, but not an authentication protocol.
      % OAuth 2.0, an authorization framework described in Request for Comments (RFC) 6749.
      % OpenID Connect(OIDC) provides SSO and uses a JavaScript Object Notation (JSON) Web Token (JWT).
      % OpenID provides authentication but doesn’t include profile information.
    11) Certificate-based authentication
      % Mutual authentication ensures that a server provides authentication before the client provides authentication.
    12) Passwordless authentication - Key-Based Authentication
  C. Accountability
    1) Accountability - Logs must be secure
      & Nonrepudiation ensures that someone cannot deny that they took an action, which means they can be held both accountable and responsible for that action.
      % Authentication is necessary to ensure a network supports accountability.
      % Accountability is possible by reviewing logs and tracking user activity.
      % Authentication of individuals is also needed to ensure the audit trails provide proof of identities listed in the logs.
      % Accountability is maintained by monitoring the activities of subjects and objects as well as monitoring core system functions that maintain the operating environment and the security mechanisms.
      % Accurate identification and authentication are required to support accountability.
    2) Session management - Timeouts, randomized session IDs, Encrypt cookies
  D. Account Management
    1) Understand account and privilege management - Least Privilege, Segregation of Duties, Job Rotation, Mandatory Vacation
      % When elevated privileges are required, the "Run as" command temporarily grants the necessary permissions without exposing the entire session to administrative rights, thereby adhering to the principle of least privilege.
    2) Account types - User Account, Privileged Account, Shared Account, Service Account
      * Avoid the use of shared/generic accounts and credentials.
      % Service accounts are regular accounts that are used to run applications and services(processes).
      % a service account assigns the specific privileges to the account needed by the application.
      % The LocalSystem account and the Administrator account both have full administrative privileges
    3) Account Policies - Group Policy Object(GPO)
      % Group policies provide centralized management and configuration of all entities to enforce security and compliance standards throughout the organization.
      % Using a domain group policy allows you to centrally manage and enforce the restriction across all computers in the domain.
      % Account access reviews can detect security issues for service accounts such as the sa (short for system administrator) account in Microsoft SQL Server systems
    4) Password policies
      * Current NIST guidance says that passwords should not expire.
      % A passphrase is a sequence of words or a sentence that is easier to remember than a random combination of characters
    5) Manage roles
      % A security group assigns users to roles within his Windows enterprise, as it allows for the grouping of user accounts, computer accounts,
        and other security groups into manageable units for assigning permissions and access rights.
      % A Distribution group is used primarily in email applications to send messages to groups of users and is not designed for assigning roles or managing permissions.
    6) Account monitoring - Inaccurate Permissions, Attestation, Unauthorized Use, Geotagging, Geofencing
    7) Provisioning and de-provisioning - Privilege Creep
      & Secure provisioning involves managing authorized access to the asset; assigning the correct authorizations for entities to be able to access the asset.
      & Privilege creep can happen over time when an employee moves from job to job within an organization or is simply promoted and retains privileges they no longer need.
      % Elasticity provides for automatic provisioning and deprovisioning of resources to meet demand.
      % Authorization creep occurs when a user is granted new permissions as they change roles or responsibilities within an organization, but their old permissions are not removed.
      % Capability creep refers to the gradual expansion of an individual's capabilities or roles within an organization.
      % Just-in-time (JIT) provisioning will create the accounts automatically the first time the employee accesses the benefits site.
  E. Authorization
    1) Understand authorization - Least Privilege, Account Review
      * Be able to identify least privilege and segregation of duties issues in a scenario
    2) Mandatory access controls (MAC)
      % In a Mandatory Access Control (MAC) system, objects are the resources or data entities that are being protected.
      % The MAC model assigns access based on a user’s need to know and organization policies.
      % Hybrid environments combine both hierarchical and compartmentalized environments so that security levels have subcompartments.
    3) Discretionary access controls (DAC)
      % In a discretionary access control system, individual users have the ability to alter access permissions.
      % In a Discretionary Access Control model, the owner of a resource (such as a file or folder) has the discretion to determine who can access it and what level of access they have. 
      % In the DAC model, the owner assigns access based on the owner’s desires.
    4) Access control lists
      % An ACL specifies which users or system processes (subjects) are allowed to access objects (like files, directories, or devices) and what operations (read, write, execute) they are permitted to perform on those objects. 
      % An access control matrix is a (capability) table used to specify the access rights of various subjects (e.g., users, processes) to different objects (e.g., files, resources) in a system.
        An access control matrix assembles ACLs from multiple objects into a single table. 
      % The subject is active and is always the entity that receives information about, or data from, the object.
    5) Database access control - SQL Server Authentication, Windows Authentication, Mixed Authentication
      % Polyinstantiation allows the insertion of multiple records that appear to have the same primary key values into a database at different classification levels. 
      % Detective controls are designed to identify and alert the organization to unauthorized activities, including when authorized users are involved in such actions.
      % A directive control is deployed to direct, confine, or control the actions of subjects to force or encourage compliance with security policies.
    6) Advanced authorization concepts - RBAC, ABAC, location-based control, Time-of-Day Restriction
      * Risk-based access controls apply stronger standards in situations posing greater risk.
      % A risk-based access control model can require users to authenticate with multifactor authentication.
      % The ABAC model is commonly used in SDNs.
      % An ABAC model can require user devices to meet specific requirements, such as being up-to-date with a current operating system.
      % Corrective access control is deployed to restore systems to normal after an unwanted or unauthorized activity has occurred.
      % Administrative overhead is high in a decentralized access control model.
  F. Access Control Attacks
    1) Social engineering - Authority and Trust, Intimidation(Sharing), Consensus/Social Proof, Scarcity, Urgency, Familiarity/Liking
      % A valid goal of a grudge attack is any action that can harm a person or organization, either directly or through embarrassment.
    2) Impersonation attacks - Spam, Phishing, Spear Phishing, Whaling, Pharming, Vishing, Smishing and SPIM, Spoofing, Brand Impersonation
    3) identity fraud and pretexting - Pretexting Attacks
      % In a pretexting attack, the attacker contacts a third-party company pretending to be the consumer and attempts to gain access to that consumer's account.
      % Backdoors are undocumented command sequences that allow individuals with knowledge of the backdoor to bypass normal access restrictions.
    4) Watering hole attacks
      % Watering hole attacks use sneaky techniques to lure unsuspecting users and infect their systems with malware. They use commonly visited sites without the website owner's knowledge.
    5) Physical social engineering - Shoulder surfing, Dumpster Diving, Tailgating


-----------------------------------------------------------------------------------------------------------------------------------------------------------


6. Security Assessment and Testing
  % A test is a defined procedure that records the properties, characteristics, and behaviors of the system being tested.
  A. Vulnerability Scanning
    1) What is vulnerability management?
      - Vulnerability Patching, Vulnerability management (detects, remediates, reports)
      - PCI DSS = quarterly, ASV
      - FISMA = regularly
      - Network vulnerability scan, application, web application scans
      % PCI DSS requires that Badin rescan the application at least annually and after any change in the application.
    2) Identify scan targets 
      - Asset Inventory
      - Impact, Likelihood, Criticality
      % Open Vulnerability and Assessment Language(OVAL)
      % A vulnerability scan will list or enumerate all security risks within a system.
    3) Scan configuration
      % Vulnerability scanning tools are specifically designed to identify security weaknesses, vulnerabilities, and potential exploits in networks, systems, or applications.
      % Vulnerability scanners can check systems to ensure they are up-to-date with current patches (along with other checks).
    4) Scan perspective
      - Agent-based scanning, Credential-based scanning
      % sqlmap is custom-designed to identify database vulnerabilities in web applications.
    5) Analyzing scan reports
      - vulnerability severity, system criticality, information sensitivity, remediation difficulty, system exposure
      % Systems with many or risky services installed should be prioritized higher for scanning.
      % The operating system is not necessarily a major factor in deciding whether a device should be scanned.
      - Vulnerability validation
      % Common Configuration Enumeration (CCE) provides a naming system for system configuration issues.
    6) Correlating scan results
      % If the vulnerability scanner is in the screened subnet, the scanner has unrestricted access to the web server because it doesn't need to pass through the firewall on the way to the web server.
  B. Penetration Testing
    1) Penetration testing
      % It is a proactive security assessment method used to identify and exploit vulnerabilities in a system, network, or application.
      % In a double-blind test, both the security team and the testers (often external penetration testers) are unaware of each other's identity or intentions.
        This type of assessment is more likely to demonstrate the success or failure of a possible attack because it simulates a real-world scenario.
      % A blind test involves a scenario where the security team is unaware that an assessment is being conducted, but the testers are informed. 
    2) Ethical disclosure - Responsible Disclosure
    3) Bug bounty
    4) Cybersecurity exercises
  C. Log Reviews
    1) Logging security information - Log and Data sources, Syslog(Linux), Tags, NXLog(Centralize)
    2) Security information and event management(SIEM) - SOAR (Security Orchestration, Automation, and Response)
      % Security Orchestration, Automation, and Response (SOAR) technologies provide automated responses to common attacks, reducing an administrator’s workload.
    3) Continuous security monitoring
      - Monitoring Process (Define, Establish, Implement, Analyze/Report, Respond, Review/Update)
      - Anomaly Analysis, Trend Analysis, Behavioral Analysis, Availability Analysis
    4) Endpoint monitoring - UEBA (User and Entity Behavior Analytics)
      % UEBA tools develop profiles of individual behavior and then monitor users for deviations from those profiles that may indicate malicious activity and/or compromised accounts.
  D. Code Testing
    1) Code review
      % Branch coverage evaluates whether every if statement has been executed under all if and else conditions.
      % Condition coverage tests whether every logical test in the code has been executed under all sets of input.
    2) Code tests 
      - Code Security Tests(SAST[Static] = SCA[Software Composition Analysis], DAST[Dynamic] = Synthetic transaction, IAST[Interactive])
      & Dynamic application security testing (DAST) is performed while the application is executing.
      & Static application security testing (SAST) involves testing application code without executing it. It requires access to the actual source code.
      * Different test types are complementary, rather than competitors!
      % Static code testing software analyzes code without executing it, checking for syntax errors, coding standards, and other issues.
      % A white box test is fully knowledgeable about the software code and its operations and functions.
      % Integration testing is performed when a new product is deployed or integrated into a real or simulated production environment to ensure that all previously function work tasks still work
        and all newly added or expected work tasks work as well.
      % Synthetic transactions are scripted transactions with known expected results.
    3) Fuzz testing - Avoid Looking Like a Hacker
      % zzuf is a tool that automates the process of mutation fuzzing.
      & Fuzzing is a part of dynamic testing and involves sending unexpected input to the application while it is executing.
    4) Interface testing - APIs(Application Programming Interface), User, Security, Physical
      % An interface is a point of interaction or communication between two systems, devices, or software components.
      % User interface testing includes assessments of both graphical user interfaces (GUIs) and command-line interfaces (CLIs) for a software program.
      & It examines the connections and entry/exit points between hardware and software from both a functional and security perspective.
    5) Misuse case testing
      % In misuse case testing the testers first enumerate known misuse/abuse cases (possible ways).
      & It involves assessing the different scenarios where software may be misused or abused.
    6) Test coverage analysis - Percentage software => Test Coverage = Cases Tested / Total Cases
      & It is the depth and level of detail an assessment must address, including which parts of a system, application, or process will be covered by the assessment, and how much is going to be tested.
    7) Code repositories - Integrity Measurement
      & Software library is a collection of software components, such as piece of code, functions, and so on, that can be used across many different software development projects.
    8) Third-party code - Libraries, SDKs(Software Development Kits)
    9) Software risk analysis and mitigation - Sandboxing
  E. Disaster Recovery Planning
    1) Disaster recovery - RTO (Recovery Time Objective), RPO (Recovery Point Objective), RSL (Recovery Service Level)
      * Disaster recovery efforts end only when the business is operating normally in its primary environment.
      % The recovery time objective (RTO) is the targeted amount of time to restore a service after a failure during a disaster recovery. It focuses on recovery speed.
      % The recovery service level (RSL) is the percentage of a service that must be available during a disaster.
      % The disaster recovery plan (DRP) includes procedures and measures to respond to emergencies, protect people and property, and ensure the safety of employees and assets during and after a disaster.
      % The recovery point objective (RPO) specifies the maximum amount of data that may be lost during a disaster and should be used to guide backup strategies.
    2) Backups - Full backups, Differential, Incremental
      % Any backup strategy must include full backups at some point in the process.
        Incremental backups are created faster than differential backups because of the number of files it is necessary to back up each time.
      % Incremental backs up all the new files that have changed since the last full or incremental backup and resets the archive bit.
      & Backup verification data, in the form of written logs or automated transaction logs from systems or applications, indicates whether data backups have been successful.
        It could contribute to determining if data loss has occurred with backups or normal processing.
    3) Restoring backups
      % Retention time refers to the duration for which backup media, such as tapes, are kept before their data is considered outdated and can be overwritten with new data.
    4) Disaster recovery sites - Hot Sites(Fully operational), Cold Sites(Empty), Warm Sites(not maintained), Mobile site(Physical relocation), Offsite Storage
      % Contracts typically focus on ensuring that the vendor provides a functional offsite facility that meets the agreed-upon criteria, such as availability, cost, testing access, and general site availability.
      % A redundant site is fully equipped and operational, allowing it to take over functions almost immediately in the event of a failure at the primary site.
      % A primary consideration for this mirrored site is the location. Some financial guidelines require a mirrored site to be a minimum distance away, such as at least 20 miles away.
    5) Testing BC/DR plans - Business Continuity (BC) and Disaster Recovery (DR) plans
    6) After action reports
  F. Assessing Security Processes
    1) Collect security process data
    2) Management review and approval
      % Security processes should be implemented at these times to reduce the risk of data loss and leakage, such as sanitizing assets, remove and destroy storage media, and debrief ex-employees.
    3) Security metrics
      % KRIs(Key Risk Indicators) are measures that seek to quantify the security risk facing an organization.
      % KPIs(Key Performance Indicators) are metrics that demonstrate the success of the security program in achieving its objectives.
        The ones from this list of options are: number of successful intrusions, number of successful disruptions, number of unsuccessful incidents, time to detect incidents, time to respond to incidents,
        level of organizational impact of incidents, and number of false positives (i.e., false detection alerts/alarms).
    4) Audits and assessments - User Access Reviews
      & Auditing is critical to being able to establish accountability, since it records the activities that users perform and the events that occur in the system.
      & An audit is a specific event consisting of a tailored, systematic assessment of a particular system or process to determine if it meets particular standard.
      & External auditors lack familiarity with the organization's people, internal processes, and infrastructure which is an advantage of using an external auditor; lack of familiarity facilitates a more objective audit.
      & Logs should be reviewed both before and after a security assessment to ensure the text executed as planned and to discover any anomalies that may have occurred during the test.
      % Account reviews should verify that every ACTIVE account is associated with a current employee.
      % The audit section ensures that all user activities are tracked, logged, and reviewed, providing a mechanism for tracing actions back to individual users, which is essential for maintaining accountability.
      % This type of review, conducted by an independent auditor at the request of the governing body, is best described as an audit.
      % An audit-reduction tool is designed to process and filter audit logs, removing extraneous information and reducing the volume of data, which makes it easier to analyze and focus on relevant security events.
      % Audit Privilege Use will log events whenever a user or process attempts to exercise a user right or privilege, such as accessing the system remotely.
      % An on-site assessment is a third-party assessment tool where auditors visit the site of the organization to interview personnel and observe their operating habits.
      % a security control assessment (SCA) is the formal evaluation of a security infrastructure’s individual mechanisms against a baseline or reliability expectation.
    5) Control management - Every Rule Has An Exception
      % Compensating controls are specifically designed to long-term mitigate the risk of exceptions to security policies by providing alternative security measures.
      & A preventive control prevents an individual from committing a malicious act or violating a policy.
      % Administrative controls involve policies, procedures, and guidelines to manage people's behavior and operations, not directly focused on exceptions.


-----------------------------------------------------------------------------------------------------------------------------------------------------------


7. Security Operations
  A. Investigations and Forensics
    1) Conducting investigations
      - Operational Investigation(technology issue), Criminal Investigation(possible crimes), Civil Investigation(Disputes), Regulatory Investigation(government regulators)
      * Cybersecurity investigators should leave interrogation to law enforcement!
      % Computer-assisted crimes generally involve using technology to commit or facilitate a crime, rather than directly harming computer systems themselves.
      % A bit-level copy (also known as a forensic image) creates an exact replica of the entire disk, including all files, free space, and hidden areas, ensuring that no data is overlooked.
      % Opportunity specifically refers to the time and place where a crime could be committed.
      % Motive refers to the reasons for committing the crime.
      % Means refer to the ability to commit it(how).
      % Civil investigations typically follow the “preponderance of the evidence” standard.
      % Criminal investigations typically follow the “beyond a reasonable doubt” standard of evidence.
      % A search warrant is a legal document authorized by a judge or magistrate that allows law enforcement to search a specific location for evidence related to a crime.
      % Internal investigations usually operate under the authority of senior managers, who grant access (i.e., voluntary surrender) to all information and resources necessary to conduct the investigation.
    2) Evidence types
      - Real(tangible objects), Documentary(written information), Testimonial(Witness)
      - Documentary = Authentication rule, Best evidence (Original documents are superior), Parol evidence(Written contract agreement)
      - Secondary evidence refers to copies or reproductions of original documents when the original is not available.
      % Testimonial direct evidence is provided based on a witness's own observations. Testimonial expert evidence is conclusions based upon other evidence.
      % Documentary evidence consists of written information, such as server logs.
      % Corroborative evidence helps to establish the validity of a point or an idea by providing additional information or testimony that is consistent with the primary evidence.
      % The parol evidence rule states that when an agreement between parties is put into written form, the written document is assumed to contain all the terms of the agreement, and no verbal agreements may modify the written agreement.
      % The best evidence rule states that when a document is used as evidence in a court proceeding, the original document must be introduced.
      % Real evidence must be either uniquely identified by a witness or authenticated through a documented chain of custody.
      & The four major phases of the evidence life cycle are initial response, collection, analysis, and presentation.
    3) Introduction to forensics
      - Digital Forensics, Volatility(Permanence)
    4) System and file forensics - Hashes Protect Evidence(Unique file signature)
      * Never try to perform forensics yourself unless you've received appropriate training.
      % In the preservation phase, the goal is to ensure that all evidence is captured and documented accurately without altering the original state of the data.
      & Wiping is an effective way to clear sensitive data from media that is intended to be reused.
    5) Network forensics - Wireshark Monitors Networks, NetFlow Summarizes Traffic
    6) Software forensics - Intellectual Property, Malware Origins
    7) Mobile device forensics
    8) Embedded device forensics
      % A write blocker prevents a forensic examiner from accidentally corrupting evidence while creating an image of a disk.
      % Each piece of evidence should be accompanied by an evidence log that records important events that happen in the lifecycle of the evidence.
      % Hashing is used to protect evidence by providing a unique file signature, demonstrating that a file hasn't been altered.
    9) Chain of custody - A paper trail of evidence
      % One copy is used for analysis, and the other is preserved as a "golden copy" to maintain the integrity of the evidence.
      % Police investigators, evidence technicians, attorneys, and anyone else involved in the collection, processing, analysis, and production of evidence must maintain the chain of custody.
    10) Reporting and documenting incidents - Formal Incident Report
      % Federal law does not require all U.S. businesses to report verified security incidents to US-CERT; reporting requirements vary by industry and specific regulations.
    11) Electronic discovery (eDiscovery)
      % For evidence to be admissible, it must meet certain criteria, including sufficiency, reliability, and relevance.
  B. Privilege Management
    1) Need to know and least privilege
      - need to know(information access), least privilege(system permissions)
      % Need to know is the requirement to have access to, knowledge about, or possession of data to perform specific work tasks, but no more.
      % The least privilege principle ensures that users (subjects) are granted only the most restrictive rights they need to perform their work tasks and job functions. 
      - Privilege Aggregation
      % Aggregation occurs when a user combines information from multiple sources or queries to deduce or infer data that they are not explicitly authorized to access.
      & M-of-n control is the same as multiperson control, except it doesn't require all designated individuals to be present to perform a task.
    2) Privileged account management(PAM) - Password Vaulting, Command Proxying, Monitoring, Credential Management
  C. Incident Management
    1) Build an incident response program - Incident Response Plan
      % The computer security incident response team(CSIRT) has IT department member, Legal department member, public relations department member, and management team member
      % Security personnel perform a root cause analysis during the remediation stage  in Incident Response Plan.
    2) Creating an incident response team - IR Service Provider
    3) Incident communications plan - Involving Law Enforcement, Secure Communication
      % While you may believe a law has been violated, you do not typically have an obligation to report this to law enforcement.
      $ Administrative laws do not require an act of the legislative branch to implement at the federal level. 
    4) Incident identification - Security incident and event management(SIEM), First Responders Must Act Quickly
      * The highest priority of a first responder must be containing damage through isolation
    5) Escalation and notification
    6) Mitigation - mitigation ends with stability
    7) Containment techniques
      % When we divide networks into logical segments, grouped by types of users or systems, we have performed segmentation.
      % When we move compromised systems to a network that is completely disconnected from the rest of the network, we have performed isolation. That is not the case in this scenario.
      % micro-segmentation can be implemented using internal segmentation firewalls (ISFWs), transactions between zones are filtered, and it can be implemented with virtual systems and virtual networks.
        It can be separated on sensitive hosts or even applications from other hosts, applications, or networks.
    8) Incident eradication and recovery - Eradication(Remove all traces), Recovery, Attackers Compromise Systems
    9) Validation
    10) Post-incident activities - Incident Summary Report
      % Independent facilitator is the most effective person to lead a lessons learned review
      % The IR personnel are too close to the situation and may not be able to remain impartial or assist others to share their thoughts and feelings.
  D. Personnel Safety
    1) Personnel safety
      * Watch for tricky questions that ask you to prioritize other actions over personal safety
    2) Emergency management
      % Exigent circumstances are used in situations where immediate action is necessary to prevent the imminent destruction of evidence, escape of a suspect, or harm to individuals or law enforcement officers.


-----------------------------------------------------------------------------------------------------------------------------------------------------------


8. Software Development Security
  A. Software Development Lifecycle
    1) Software platforms - Endpoint Applications, Client/Server Apps, Web Applications
      % Endpoint applications run on the host computer only without interacting with other systems.
    2) Development methodologies - Integrated product team(IPT)
      % The spiral model has four stages: requirements gathering/identification, design, build, and evaluation/risk analysis
      % The manifesto for agile development talks about valuing individuals and interactions, working software, customer collaboration, and responding to change.
      % The iterative waterfall model uses a seven-stage approach to software development and includes a feedback loop that allows development to return to the previous phase to correct defects discovered during the subsequent phase.
      % The Fagan inspection model uses the six formal steps of planning, overview, preparation, inspection, rework, and follow-up to conduct a formal code review process.
      % The daily stand-up meeting is a hallmark of the Scrum methodology.
      % Integrated Product Teams (IPTs) were introduced in 1995 by DoD to bring together stakeholders and foster parallel decision-making.
      % Continuous integration/continuous delivery approaches are designed to facilitate the release of code on an extremely frequent basis. 
    3) Scaled agile framework
      % The Large Solution SAFe configuration focuses on coordinating multiple Agile Release Trains (ARTs) and suppliers, which is necessary for building large, complex solutions but does not encompass the full breadth of SAFe.
      % The Full SAFe configuration incorporates all aspects of SAFe, including essential, large solution, and portfolio levels, to support enterprises with large and complex solutions.
      % The Essential SAFe configuration is the basic building block of SAFe, focusing on the team and program levels, but it does not include the large solution and portfolio levels.
    4) Maturity models - Capability Maturity Model Integration(CMMI), Software Assurance Maturity Model(SAMM), Risk Maturity Model(RMM)
      % Level 3 is defined and activities include: decision analysis & resolution, integrated project management, organizational process definition, organizational training,
        organizational process focus, product integration, requirements development, risk management, technical solution, validation, and verification.
      % Level 2 is managed and activities include: configuration management, measurement & analysis, project monitoring & control, project planning, process & product QA,
        requirements management, and supplier agreement management.
      % The level of RMM named Defined requires that a common or standardized risk framework be adopted organization-wide.
    5) Automation and DevOps - Infrastructure as Code
      * DevSecOps applies DevOps techniques to a cybersecurity program.
      % The DevSecOps approach integrates software development, cybersecurity, and operations into a single approach where the teams work closely together.
      % The three elements of the DevOps model are software development, quality assurance, and IT operations.
      % The DevOps model prioritizes operational tasks over development efforts.
      % DevOps combines Development and Operations to rapidly release code and meet customer demands.
      % Before releasing any code into production, the DevOps manager should verify the hashes of the files to be released. 
      % The JVM is the runtime virtual machine that allows the execution of Java code on a device.
    6) Programming Languages - Reverse Engineering
      % An assembler converts assembly language, a low-level programming language, into executable machine code, not the reverse.
      % A compiler translates source code written in a high-level programming language into machine code or bytecode, but it does not perform the reverse process of generating source code from executable code.
      % Interpreters translate source code into machine language when the software runs.
        An interpreter directly executes instructions written in a programming or scripting language without previously converting them into machine code, differing from decompilers which work with already compiled code.
      % Reverse engineering involves examining and analyzing the components, structure, and functionality of an application or system to understand how it works typically involving decompiling or disassembling object code (which is compiled code).
      & First generation (introduced machine language), Second (hardware-specific symbolic representation), Fourth (high-level languages and domain-specific), Fifth (knowledge-based programming)
    7) Acquired software - COTS(Commercial Off the Shelf), Software as a Service, Open-source
      % The phase of the software acquisition process in which the product is actually deployed is the Monitoring phase.
      % The use of Open-source libraries should be tracked and subject to regular security testing, as should any other closed-source library use.
      & Licensing is a distinguishing characteristic of maintaining COTS software, since licenses must be appropriately purchased and complied with to prevent piracy or illegal use of the software.
  B. Application Attacks
    1) OWASP top ten 
      - Broken Access Control, Cryptographic failures, Injection, Insecure Design, Security misconfiguration, Vulnerabile and outdated components, Identification and authentication failures, software and data integrity failures
        security logging and monitoring failures, server-side request forgery
    2) Application Security - Prompt Patching is critical
      % Validating user input is a critical security practice that helps prevent malicious data from causing harm or unauthorized actions within an application.
      % Encrypting sensitive information protects it from unauthorized access and ensures data confidentiality, a fundamental aspect of application hardening.
    3) Preventing SQL injection
      * You won't need to write SQL on the exam, but you should know how SQL injection works.
      % Single quotes are essential in input for a SQL injection attack because they allow the attacker to escape the built-in SQL query.
      % SQL injection attacks allow attackers to include their own SQL commands in the commands issued by a web application to a database.
    4) Understanding cross-site scripting - Use input validation
      & Input validation is a potential security issue with the source code of the applications that are connected via the API, but not in the API itself.
      % Conducting cross-site scripting is a type of attack rather than a hardening technique, making it not a standard method for improving application security.
      % Cross-site scripting (XSS) is a type of security vulnerability typically found in web applications.
      % A programmer can implement the most effective way to prevent XSS by validating input, coding defensively, escaping metacharacters, and rejecting all script-like input.
    5) Request forgery
      * Cross-site request forgery, CSRF, XSRF, and "sea surf" all refer to the same attack.
      - XSRF secretly sends requests, Server-side Request Forgery(SSRF)
      % Cross-site request forgery vulnerabilities trick users into executing actions on a web application in which they are authenticated, without their knowledge, but do not allow arbitrary command execution on the system.
      % Client-side XSRF attacks are on-path browser-based attacks on individual hosts with multiple browser tabs opened and logged into and with authentications crossing over browser tabs.
        Preventing the use of HTTP GET requests make it difficult for client-side XSRFs to take place.
      % network segmentation is not an effective defense against client-side XSRF attacks which are on-path browser-based attacks on individual hosts with multiple browser tabs opened and logged into and with authentications crossing over browser tabs.
    6) Defending against directory traversal
    7) Overflow attacks - Buffer Overflow Attacks
      % Buffer overflow attacks seek to write data to areas of memory reserved for other purposes.
      % Buffer overflow attacks allow an attacker to modify the contents of a system’s memory by writing beyond the space allocated for a variable.
    8) Explaining cookies and attachments
    9) Session hijacking - Guessable cookies
    10) Code execution attacks
      % Code execution attacks occur when an attacker exploits a vulnerability in a system that allows the attacker to run commands on that system.
      % Although an advanced persistent threat (APT) may leverage any of these attacks, they are most closely associated with zero-day attacks due to the cost and complexity of the research required to discover or purchase them.
    11) Privilege escalation
    12) Driver manipulation - Refactoring, Shimming
      % Driver refactoring involves modifying and improving the internal structure of existing driver code without changing its external behavior, not for malicious purposes.
      % Driver shimming is a technique that involves wrapping malicious code around a legitimate driver to bypass security measures or inject malicious code into a system.
    13) Memory vulnerabilities - Memory Overflow, Memory Leak, Memory Pointers, DLL Injection
      % Memory dumps capture the state of the system's memory at a specific point in time and can contain valuable information such as running processes, active network connections, and data in memory,
        including potentially sensitive information like encryption keys or cached data.
    14) Race condition vulnerabilities - Time of Check/Time of Use
  C. Secure Coding Practices
    % Secure coding practices include using stored procedures, code signing, and server-side validation.
    1) Input validation - whitelisting, blacklisting
      * Input validation should always be performed on the server.
    2) Parameterized queries - Stored Procedures
      % A stored procedure is an example of a parameterized query.
      % Developers of web applications should leverage parameterized queries to limit the application’s ability to execute arbitrary code.
    3) Authentication/session management issues - Hashing, Salting, Transport layer security
    4) Output encoding - HTML encoding, URL encoding
    5) Error and exception handling
    6) Code signing
    7) Database Security - 1NF
      * You don't need to know the details of the normal forms on the exam.
      - Database Activity Monitoring, Stored Procedures
      % There is an active and healthy debate in the database community about how closely database designers should follow the normal forms.
      % The atomicity of database transactions requires transaction execution in an all-or-nothing fashion.
    8) Data de-identification - Anonymization
      % You can often combine seemingly innocuous fields to uniquely identify an individual.
      % Anonymization techniques remove all data so that it is difficult to identify the original identities.
    9) Data obfuscation - Rainbow Table attack, Tokenization, Masking






