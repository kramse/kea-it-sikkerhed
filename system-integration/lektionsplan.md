---
description: Modul System integration (10 ECTS) System Security
---

# Lektionsplan

## Fagets titel: System Integration \(10 ECTS\)

English: Systems Security

Teacher: Henrik Lund Kramshøj hlk@zencurity.com +45 2026 6000

This document is written on Gitbook, and then exported to PDF.
https://zencurity.gitbook.io/kea-it-sikkerhed/system-integration/lektionsplan

### Goals

This subject element must help ensure that the student develops the competencies to be able to work with technical system integration. After completing this module, the student must be able to integrate existing systems in connection with the development of new systems, and develop new systems supporting future integration.

Teaching material will primarily be English, but the teaching will be in Danish.

See more about the course in the official curriculum.

### Exam:

Date:  2020 exam

### Teaching Methods:

* Lecture lessons
* Group exercises and cases, including practical exercises with laptop

Teaching dates: mondays

### Course reading list
This course uses a few books and a number of supporting resources.

Primary literature:

* TBA

It is recommended to buy these books. Note: we won't read all chapters and pages.

Supporting literature - optional to buy, but recommended:

* TBA

Also the course will use internet links and pages.

Supporting Internet resources

## Planning

The detailed plan is below with a table summarizing lessons

<table>
<thead>
<tr>
  <th style="text-align:left">Dato</th>
  <th style="text-align:left">Theme</th>
  <th style="text-align:left">Litterature / Preparation</th>
</tr>
</thead>
<tbody>
    <tr>
      <td style="text-align:left">28/1</td>
      <td style="text-align:left">
        <p>Welcome, goals and expectations</br>
        Bring laptop</p>
      </td>
      <td style="text-align:left">
      <p> Reviewing the literature list will occur when we meet. </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"><b>Prepare for the exam</b></td>
      <td style="text-align:left">Summary of the course, prepare for exam</td>
    </tr>
  </tbody>
</table>

**Introduction and welcome**

* Create a good starting point for learning
* Introduce lecturer and students
* Expectations for this course
* Literature list walkthrough
* Prepare tools for the exercises
* Kali and Debian Linux introduction

Linux is a toolbox we will use and participants will use virtual machines

Exercises
* Kali Linux installation
* Debian Linux installation

**Overview of Computer Security**

* Confidentiality, Integrity and Availability
* Cost-Benefit Analysis
* Risk Analysis
* Human Issues
* Access Control Matrix

Exercises
* Risk Analysis

**Overview of Enterprise Attacks**

* Get an idea of the MITRE ATT&CK framework

Exercises
* Run Armitage Hail-Mary against Metasploitable, describe attacks that succeeded in relation to MITRE ATT&CK framework

**Security Policies / Confidentiality Policies**

* Security policy
* Discretionary Access Control (DAC)
* Mandatory Access Control (MAC)
* Example Acceptable Use Policies
* Example Academic Computer Security Policy from the book
* Confidentiality Policies Bell-LaPadula Model
* More examples from the real world

Exercises
* Find your AUP for the ISPs we use, you use, your company uses
* A look at SELinux an example Mandatory Access Control system

**Integrity and Availability Policies**

* Accuracy vs disclosure
* The Biba Model
* Clark-Wilson Integrity Model
* Trust models
* Deadlocks
* Availability and flooding attacks
* Protection against TCP Synfloods

Exercises
* Databases - discussion about Relational Database Management System RDBMS Model and NoSQL
* SYN flooding exercise

**Hybrid Policies**

* Chinese Wall model - Confidentiality and Integrity
* Clinical Information Systems security model
* Originator Controlled Access Control
* Role-based Access Control (RBAC)
* Break-the-glass Policies
* Side Channels and Deducibility
* Memory Errors and Row hammer

Exercises
* RBAC Access permissions on GitHub

**Basic Cryptography**

* Basic Cryptography
* Symmetric Cryptosystems
* Data Encryption Standard (DES) / Advanced Encryption Standard (AES)
* Public Key Cryptography
* Stream and Block Ciphers
* Example cryptosystems OpenPGP, IPsec, Transport Layer Security (TLS)
* Authentication and Password security, NIST guidelines

Exercises
* sslscan scan various sites for TLS settings, Qualys SSLLabs
* Try Nmap and Ikescan
* Try ssh scanners, similar to sslscan
* Crack your own passwords

**Malware, Intrusion, Vulnerabilities**

* Trojan horses, Rootkits, computer viruses
* Computer worms, from Morris Worm to today
* Bots and botnets
* Ransomware
* Phishing and spear phishing
* Sandboxing, Java and browsers
* Penetration testing
* Common Vulnerabilities and Exposure CVE
* Common Weakness Enumeration CWE

Exercises
* Make a non-privileged user, make a system directory writable, create root cronjob without path
* Discuss when to use Anti-virus and "endpoint security"



**Secure Systems Design and Implementation**

* Principle of least privilege, fail-safe defaults, separation of privilege etc.
* Files, objects, users, groups and roles
* Naming and Certificates
* Access Control Lists
* DNSSEC

Exercises
* DNSSEC, SPF, DMARC - DNS based updates to your email domain security


**Information Flow**

* Firewall Flow Controls
* Confinement and isolation
* Virtual Machines and Sandboxes
* Covert Channels

Exercises
* Research VM escapes

**Forensics 1: Auditing and Intrusion Detection**

* Auditing and logging
* Volatility and file systems
* Intrusion Detection
* Host and Networks Based Intrusion Detection (HIDS/NIDS)
* Network Security Monitoring

Exercises
* Centralized syslogging and example system
* Create Kibana Dashboard
* Open a file system dump

**Forensics 2: Incident Response**

* Attack and Response
* Attack graphs
* Attack surfaces, and reducing them
* Intrusion Handling, phases
* Incident Response
* Digital forensics / Computer Forensics
* Honeypots

Exercises
* Clean or rebuild a server, use example Debian with your cron job vuln as example
* Cloud environments influence on incident response

**System Security in Practice**

* Network security
* Infrastructure security
* Implement a small scale enterprise network

Exercises
Work on our model network, each team has a server and an attacker - reduce attack surface on the server by configuration
* Configure VLAN on switch for the uplink
* Enable central logging
* Configure SSH keys for more secure access
* Enable firewall



**Benchmarking and Auditing Recap**

* Benchmarking standards
* CIS controls Center for Internet Security
* PCI Best Practices for Maintaining PCI DSS Compliance v2.0 Jan 2019\\
Payment Card Industry Data Security Standard


Exercises
* Evaluate our network, write a scope before doing PCI compliance
