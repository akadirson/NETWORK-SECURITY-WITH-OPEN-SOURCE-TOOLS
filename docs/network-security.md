

ESKISEHIR OSMANGAZI UNIVERSITY

COMPUTER ENGINEERING

2023 Autumn Term

MTH 151015308

NETWORK SECURITY WITH OPEN SOURCE TOOLS

MkDocs GitHub:

**TITLE:**

NETWORK SECURITY STRATEGIES,

NETWORK SECURITY TESTING and TECHNIQUES

RESARCH PROJECT

152120201086 Abdulkadir Sönmezışık

[akadirson27@gmail.com](about:blank)

**Instructor**

Cem İbrahim Arı

December 2023

CONTENTS

1.        INTRODUCTION

2.        NETWORK SECURITY STRATEGIES

2.1.     CONCEPT OF COMPUTER NETWORK SECURITY

2.2.     MAJOR THREATS OF COMPUTER NETWORK

2.3.      PROTECTIVE MEASURES OF COMPUTER NETWORK SECURITY

2.3.1.  Technical Level Countermeasures

2.3.2.  Management Level Countermeasures

2.3.3.  Physical Security Level Countermeasures

4\.        NETWORK SECURITY TESTING and TECHNIQUES

4.1.     Network Scanning

4.2.     Vulnerability Scanning

4.3.     Password Cracking

4.4.     Log Reviews

4.5.     Virus Detectors

5\.        CONCLUSION

6.        REFERENCES

**1\.        INTRODUCTION**

Network security is a critical aspect of modern digital environments, safeguarding our online interactions and data. It involves a set of policies and practices designed to protect network infrastructure and data from unauthorized access, misuse, or harm. This field addresses various threats, ranging from malware to cyber attacks, ensuring safe and reliable network usage. Key practices include effective management of user access, data encryption, and the use of firewalls and antivirus software. As digital threats evolve, network security remains a dynamic and essential field.

**2.         NETWORK SECURITY STRATEGIES**

**2.1.     CONCEPT OF COMPUTER NETWORK SECURITY**

  

Computer network security involves using network management and technical measures to protect data privacy, integrity, and availability in a network environment. It has two main aspects: physical security and logical security. Physical security safeguards equipment and facilities from damage or loss, while logical security focuses on information integrity, secrecy, and availability.

  

The meaning of computer network security varies among users. General users seek protection for individual privacy and confidential information during network transmission, aiming to avoid eavesdropping, tampering, and forgery. Network providers, on the other hand, are concerned not only with network information safety but also with addressing sudden natural disasters, like a military strike causing hardware damage. They also focus on restoring network communication and maintaining continuity in abnormal situations.

  

In essence, network security includes hardware that forms the network system, software, and secure information transfer over the network. This protection guards against accidental or malicious attacks. Network security addresses both technical problems and management issues, with these aspects complementing each other.

**2.2.    MAJOR THREATS OF COMPUTER NETWORK**

·       **Internal Threats:** Confidentiality Breach: Insiders may intentionally or unintentionally leak or alter confidential information. Unauthorized Personnel Actions: Internal personnel may steal confidential data, manipulate network configurations, or cause damage. Misuse of Privileges: Insiders may misuse their authorized access to exploit sensitive information or compromise network integrity.

·       **Unauthorized Access:** Unauthorized use of network resources, including illegal hacking or improper operation by legitimate users.

·       **Information Integrity Damage:** Attackers may compromise information integrity by altering the order, timing, content, or form of information, including deleting or inserting news to mislead recipients.

·       **Interception:** Attackers may intercept confidential information through wiretapping or electromagnetic wave radiation during installation without damaging the transferred data.

·       **Pretending:** Attackers may impersonate leaders, hosts, or network control programs to issue false orders, deceive legitimate users, or manipulate access to key information.

·       **Destroy System Availability:** Attackers may disrupt network availability by preventing legitimate user access to resources, delaying responses to time-sensitive services, or causing system destruction.

·       **Repeat Itself:** Attackers may repeatedly send intercepted and recorded information as needed.

·       **Denial:** Possible denials include the sender denying the transmission of specific content or the receiver denying the receipt of a message.

·       **Other Threats:** Network threats also encompass computer viruses, electromagnetic leakage, various disasters, and operational errors.

  

**2.3.     PROTECTIVE MEASURES OF COMPUTER NETWORK SECURITY**

**A. Technical Level Countermeasures**

**Safety Management System**

Establish a safety management system to enhance the expertise of staff, inspect viruses in critical departments, and regularly back up data.

**Network Access Control**

Implement access control measures to protect network resources from illegal use, covering network access, directory level, and attribute controls.

**Database Backup and Recovery**

Perform regular database backup and recovery operations to ensure data security and integrity, utilizing strategies like full database backup, backup with affairs log, and incremental backup.

**Application Code Technology**

Implement robust information security measures, including secure passwords, digital signatures, and identity authentication, to ensure information integrity.

**Transmission Way Control**

Thoroughly examine affected hard disks and computers, avoid unexplained USB disks and suspicious programs, and prevent the download of questionable information.

**Enhanced Anti-virus Technology**

Install virus firewalls, conduct real-time filtering, regularly scan and monitor file servers, use anti-virus software, and strengthen network directory and file access settings.

**Research and Development**

Invest in research and development to enhance the operation of high-quality security systems and develop high-security operating systems.

  

  

**B. Management Level Countermeasures:**

**User Education and Security Management**

Educate users on computer safety, establish security management institutions, and continually improve and strengthen management functions.

**Legislation and Law Enforcement**

Strengthen legislation and law enforcement related to computer and network security, enhancing awareness of laws, regulations, and ethical concepts among computer users.

**Legal Education**

Provide ongoing legal education to computer users, clarifying rights and obligations, promoting adherence to legal principles, and resisting illegal activities to maintain system safety.

**C. Physical Security Level Countermeasures:**

**Computer System Environment Conditions**

Maintain specific environmental conditions, including temperature, humidity, air cleanliness, and protection against corrosion, vibration, and electrical disturbance.

**Computer Room Environment Selection**

Choose suitable installation places for computer systems, considering external environment safety, avoiding strong vibrations, noise sources, high buildings, and water exposure.

**Computer Room Safety Protection**

Design security measures to prevent unauthorized damage or theft, implement access control, define visitor activities, establish multilayer security protection, and provide equipment to safeguard against natural disasters.

  

**3.         NETWORK SECURITY TESTING and TECHNIQUES**

Security testing encompasses various techniques, each with its own strengths and weaknesses. While some testing methods are primarily manual, requiring human initiation and execution, others are highly automated, reducing the need for extensive human involvement. Regardless of the testing type, individuals responsible for setting up and conducting security tests should possess substantial knowledge in network security, firewalls, intrusion detection systems, operating systems, programming, and networking protocols like TCP/IP.

Often, a combination of these testing techniques is employed to obtain a more comprehensive assessment of overall network security. For instance, penetration testing typically involves network and vulnerability scanning to identify potential targets for later penetration. Some vulnerability scanners also include password cracking capabilities. It's important to note that none of these tests, when conducted in isolation, provide a complete picture of the network or its security status.

  

  

**A.    Network Scanning**

Network scanning is a way to find devices on a company's network. It uses a tool called a port scanner to discover active hosts, like computers or servers, and the services they use, such as FTP or HTTP. The scan creates a list of all active devices, like printers and routers, in that network area.

  

Port scanners, like nmap, find active hosts using TCP/IP and ICMP ECHO packets. Once found, the tool checks for open ports, revealing the services on each device. Different scanners have strengths for various tasks, like scanning through firewalls or internally.

  

All basic scanners find active hosts and open ports, but some give extra details. During an open port scan, information can identify the target operating system, known as operating system fingerprinting. However, this has limitations due to firewalls.

**B.    Vulnerability Scanning**

Vulnerability scanning, an advanced form of port scanning, not only identifies hosts and open ports but also provides crucial information on associated vulnerabilities. Unlike port scanners, vulnerability scanners offer insights into potential threats and suggest mitigation strategies, making them invaluable for proactive network security. These tools help system administrators assess an organization's exposure to vulnerabilities, detect outdated software, and ensure compliance with security policies. Despite their advantages, vulnerability scanners have limitations, such as a possible high false positive rate and increased network traffic during scans. Additionally, their effectiveness relies on regular updates to the vulnerability database. Organizations must carefully consider these factors when selecting and utilizing vulnerability scanning tools to enhance their overall cybersecurity posture.

**C.    Password Cracking**

Password cracking is a way to find weak passwords. Passwords are stored as encrypted hashes. During a penetration test or attack, captured password hashes are used. They can be intercepted during network transmission or obtained with administrative access. Automated password crackers quickly generate hashes until a match is found. The fastest method is a dictionary attack, using words from dictionaries or text files. Hybrid attacks add numeric and symbolic characters to dictionary words. Brute force is the most powerful method, generating random passwords and hashes. While it takes time, it's faster than many password policies allow. Penetration testers and attackers may use multiple machines to speed up the process.

**D.    Log Reviews**

Log reviews involve checking system logs like firewall, IDS, and server logs for any deviations from the organization's security policy. While not a traditional testing activity, log analysis ensures that systems operate according to policies. For instance, examining IDS logs behind a firewall can reveal unauthorized activities, signaling a potential security issue. Snort, a free IDS sensor, aids in real-time traffic analysis, packet logging, and detecting various attacks. It uses a flexible rules language and offers real-time alerting capabilities, serving as a packet sniffer, packet logger, or complete intrusion detection system.

**E.     Virus Detectors**

Viruses, Trojans, and worms pose risks for organizations using the internet or removable media. Antivirus programs come in two types: network-based (on servers or firewalls) and end-user-based. Both are needed for full protection. Network-based detectors catch viruses before entering the network, and end-user software detects them locally. Updates are crucial for virus databases to recognize threats. Antivirus programs compare file contents with known signatures, quarantining or repairing infected files. However, relying on user-initiated updates may lead to some issues. Overall, a combination of both types of antivirus programs is essential for effective protection against potential threats.

**4.          CONCLUSION**

This report has provided a comprehensive overview of network security, highlighting its significance in safeguarding digital information and infrastructure. From understanding the basic concepts to addressing various threats and implementing countermeasures, we have delved into both the technical and managerial aspects of network security. The importance of continuous vigilance and adaptation in response to evolving cyber threats is evident. As technology advances, so must our strategies to protect networks. The future of digital security depends on our ongoing commitment to developing robust, innovative solutions that can withstand the challenges of an ever-changing cyber landscape.

References:

Fuguo Li, "Study on security and prevention strategies of computer network," 2012 International Conference on Computer Science and Information Processing (CSIP), Xi'an, China, 2012, pp. 645-647, doi: 10.1109/CSIP.2012.6308936. ([https://ieeexplore.ieee.org/abstract/document/6308936](https://ieeexplore.ieee.org/abstract/document/6308936))

  

Wack, John, Miles Tracy, and Murugiah Souppaya. "Guideline on network security testing." _Nist special publication_ 800.42 (2003): 13-14.rkdown Converter