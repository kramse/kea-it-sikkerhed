---
description: Valgfrie modul  VF1 Systemsikkerhed (10 ECTS) System Security
---

# Lektionsplan

## Fagets titel: VF1 Systemsikkerhed \(10 ECTS\)

### General Information
English: Computer Systems Security

Teacher: Henrik Lund Kramshøj hlk@zencurity.com +45 2026 6000

This document is written on Gitbook, and then exported to PDF.
https://zencurity.gitbook.io/kea-it-sikkerhed/systemsikkerhed/lektionsplan

Teaching material will primarily be English, but the teaching will be in Danish.

### Goals

The module is centered around the design and implementation of secure computer systems.
 Topics include operating system (OS) security, capabilities, and more.



See more about the course in the official curriculum.

### Exam:

Date: 31/03 2020 exam

### Teaching Methods:

* Lecture lessons
* Group exercises and cases, including practical exercises with laptop

Teaching dates: tuesdays and thursdays
28/1 2020, 30/1 2020, 4/2 2020, 6/2 2020, 11/2 2020, 13/2 2020, 18/2 2020, 20/2 2020, 25/2 2020, 27/2 2020, 3/3 2020, 5/3 2020, 10/3 2020, 11/3 2020

### Course reading list
This course uses a few books and a number of supporting resources.

Primary literature:

* Computer Security: Art and Science, Matt Bishop ISBN: 9780321712332 1388 pages - referenced as Bishop below
* Defensive Security Handbook: Best Practices for Securing Infrastructure, Lee Brotherston, Amanda Berlin ISBN: 978-1-491-96038-7 284 pages - short DSH
* Forensics Discovery, Dan Farmer, Wietse Venema 2004, Addison-Wesley 240 pages. Can be found at http://www.porcupine.org/forensics/forensic-discovery/ but recommend buying it. Referenced below as FD

It is recommended to buy these books. Note: we won't read all chapters and pages.

Supporting literature - optional to buy, but recommended:

* Linux Basics for Hackers Getting Started with Networking, Scripting, and Security in Kali by OccupyTheWeb, December 2018, 248 pp. ISBN-13: 978-1-59327-855-7 - shortened LBfH

Also the course will use internet links and pages.

Supporting Internet resources
* Kali Linux Revealed  Mastering the Penetration Testing Distribution [https://www.kali.org/download-kali-linux-revealed-book/](https://www.kali.org/download-kali-linux-revealed-book/) - shortened KLR

Control Hijacking Attacks
* [Smashing The Stack For Fun And Profit](http://www.phrack.com/issues.html?issue=49&id=14#article), Aleph One
* [Bypassing non-executable-stack during exploitation using return-to-libc](http://css.csail.mit.edu/6.858/2014/readings/return-to-libc.pdf)
 by c0ntex.
* [Basic Integer Overflows](http://www.phrack.com/issues.html?issue=60&id=10#article) by blexim.
* [Return-Oriented Programming:Systems, Languages, and Applications](https://hovav.net/ucsd/dist/rop.pdf)
Ryan Roemer, Erik Buchanan, Hovav Shacam and Stefan Savage University of California, San Diego
* [MITRE ATT&CK](https://attack.mitre.org/) a globally-accessible knowledge base of adversary tactics and techniques based on real-world observations, read the [ATT&CK 101 Blog Post](https://medium.com/mitre-attack/att-ck-101-17074d3bc62)
* [Enterprise Survival Guide for Ransomware Attacks](https://www.sans.org/reading-room/whitepapers/incident/enterprise-survival-guide-ransomware-attacks-36962), Shafqat Mehmoon, SANS Information Securiy Reading Room

OS Security
* [Secure Programming for Linux and Unix HOWTO](http://www.dwheeler.com/secure-programs/)), David Wheeler.
* [Setuid demystified](http://www.cs.berkeley.edu/~daw/papers/setuid-usenix02.pdf) by Hao Chen, David Wagner, and Drew Dean.
* [Some thoughts on security after ten years of qmail 1.0](http://cr.yp.to/qmail/qmailsec-20071101.pdf) Daniel J. Bernstein.
* [Wedge: Splitting Applications into Reduced-Privilege Compartments](http://css.csail.mit.edu/6.858/2014/readings/wedge.pdf) by Andrea Bittau, Petr Marchenko, Mark Handley, and Brad Karp.
* [Capsicum: practical capabilities for UNIX](https://www.usenix.org/legacy/event/sec10/tech/full_papers/Watson.pdf) Robert N. M. Watson University of Cambridge, Jonathan Anderson University of Cambridge, Ben Laurie Google UK Ltd., Kris Kennaway Google UK Ltd.
* [Removing ROP Gadgets from OpenBSD](https://www.openbsd.org/papers/asiabsdcon2019-rop-paper.pdf) Todd Mortimer mortimer@openbsd.org
* [TCP Synfloods - an old yet current problem, and improving pf's response to it](http://quigon.bsws.de/papers/2017/bsdcan/)
Henning Brauer, BSDCan 2017

Exploiting Hardware Bugs and Crypto Related
* [Bug Attacks on RSA](http://www.cs.technion.ac.il/~yanivca/BugAttacks.pdf), by Eli Biham, Yaniv Carmeli, and Adi Shamir.
* [Using Memory Errors to Attack a Virtual Machine](https://www.cs.princeton.edu/~appel/papers/memerr.pdf) by Sudhakar Govindavajhala and Andrew Appel
* [Flipping Bits in Memory Without Accessing Them: An Experimental Study of DRAM Disturbance Errors](http://users.ece.cmu.edu/~yoonguk/papers/kim-isca14.pdf) Yoongu Kim, Ross Daly, Jeremie Kim, Chris Fallin, Ji Hye Lee, Donghyuk Lee, Chris Wilkerson, Konrad Lai, Onur Mutlu, see also [Exploiting the DRAM rowhammer bug to gain kernel privileges](https://googleprojectzero.blogspot.com/2015/03/exploiting-dram-rowhammer-bug-to-gain.html)
* _A Graduate Course in Applied Cryptography_ By Dan Boneh and Victor Shoup  [https://toc.cryptobook.us/](https://toc.cryptobook.us/) [https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup\_0\_4.pdf](https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup_0_4.pdf)

Computer Forensics, Incident Response, Intrusion Detection
* ENISA Presenting, correlating and filtering various feeds Handbook, Document for teachers [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/presenting-correlating-and-filtering-various-feeds-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/presenting-correlating-and-filtering-various-feeds-handbook)
* ENISA Forensic analysis, Network Incident Response [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/2016-resources/exe2\_forensic\_analysis\_ii-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/2016-resources/exe2_forensic_analysis_ii-handbook)
* ENISA Network Forensics, Handbook, Document for teachers [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/network-forensics-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/network-forensics-handbook)
* [Incident Handler's Handbook](https://www.sans.org/reading-room/whitepapers/incident/paper/33901)
by Patrick Kral, SANS Information Security Reading Room
* [An Intrusion-Detection Model](http://www.cs.colostate.edu/~cs656/reading/ieee-se-13-2.pdf), Dorothy E. Denning
IEEE Transactions on Software Engineering ( Volume: SE-13 , Issue: 2 , Feb. 1987 )
* [Forensic Discovery](http://fish2.com/security/wf-book.pdf) Dan Farmer, Wietse Venema,  Addison-Wesley Professional, 2005

Policies, governance and best Practice
* [Campus Network Security: High Level Overview](https://nsrc.org/workshops/2018/myren-nsrc-cndo/networking/cndo/en/presentations/Campus_Security_Overview.pdf) , Network Startup Resource Center  
* [Campus Operations Best Current Practice](https://nsrc.org/workshops/2018/tenet-nsrc-cndo/networking/cndo/en/presentations/Campus_Operations_BCP.pdf), Network Startup Resource Center  
* [Mutually Agreed Norms for Routing Security (MANRS)](https://www.manrs.org/wp-content/uploads/2018/09/MANRS_PDF_Sep2016.pdf)
* [CIS Controls](https://learn.cisecurity.org/cis-controls-download) Requires giving your email
* [PCI Best Practices for Maintaining PCI DSS Compliance v2.0 Jan 2019](https://www.pcisecuritystandards.org/documents/PCI_DSS_V2.0_Best_Practices_for_Maintaining_PCI_DSS_Compliance.pdf?agreement=true&time=1555354264656)
* [NIST Special Publication 800-63B Digital Identity Guidelines: Authentication and Lifecycle Management](https://pages.nist.gov/800-63-3/sp800-63b.html)
* [IT Security Guidelines for Transport Layer Security (TLS)](https://www.ncsc.nl/english/current-topics/factsheets/it-security-guidelines-for-transport-layer-security-tls.html)

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
        Prepare Kali Linux VM - bring laptop</p>
      </td>
      <td style="text-align:left">
      <p> Reviewing the literature list will occur when we meet. </p>
         <p> Download Kali Linux Revealed <br>Create VMs</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">30/1</td>
      <td style="text-align:left"><b>Overview of Computer Security</b>
      </td>
      <td style="text-align:left">
      <p>Bishop ch 1 and 2, DSH ch 1-2

      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">4/2</td>
      <td style="text-align:left"><b>Overview of Enterprise Attacks</b>
      </td>
      <td style="text-align:left">
      <p>Read <a href="https://medium.com/mitre-attack/att-ck-101-17074d3bc62">ATT&CK 101 Blog Post</a> and browse
      <a href="https://attack.mitre.org/">MITRE ATT&CK</a>
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">6/2</td>
      <td style="text-align:left"><b>Security Policies / Confidentiality Policies</b>
      </td>
      <td style="text-align:left">
      <p>Bishop ch 4 and 5</br>
      Perhaps skip/skim some policy language examples, skip 4.7<br>
      Appendix G,
      Browse: Campus Network Security: High Level Overview , Network Startup Resource Center  
Campus Operations Best Current Practice, Network Startup Resource Center  
Mutually Agreed Norms for Routing Security (MANRS) </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">11/2</td>
      <td style="text-align:left"><b>Integrity and Availability Policies</b>
      </td>
      <td style="text-align:left">
      <p>Read: Bishop ch 6 and 7, skim math parts</br>
      TCP Synfloods - an old yet current problem, BSDCan slides
      </p>
      <p>DBMS Security</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">13/2</td>
      <td style="text-align:left"><b>Hybrid Policies / Breaking out</b>
      </td>
      <td style="text-align:left">
      <p>Read DSH ch 3-5</p>
      <p>Bishop ch 8 -  skim math parts</br>
      Browse: Using Memory Errors to Attack a Virtual Machine paper, An Experimental Study of DRAM Disturbance Errors,  Exploiting the DRAM rowhammer bug to gain kernel privileges
      https://en.wikipedia.org/wiki/Row_hammer
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">18/2</td>
      <td style="text-align:left"><b>Basic Cryptography</b>
      </td>
      <td style="text-align:left">
      <p>Read Bishop ch 10, 11 until and including 11.3, 12 until 12.4, 13 until 13.5<br>
      Skim: NIST Special Publication 800-63B<br>
      Enterprise Survival Guide for Ransomware Attacks<br>
      IT Security Guidelines for Transport Layer Security</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">20/2</td>
      <td style="text-align:left"><b>Malware, Intrusion, Vulnerabilities</b>
      </td>
      <td style="text-align:left">
      <p>Read Bishop ch 23 and skim 24, FD ch 5-6</br>
      Smashing The Stack For Fun And Profit, Bypassing non-executable-stack during exploitation using return-to-libc, Basic Integer Overflows, Return-Oriented Programming
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">25/2</td>
      <td style="text-align:left"><b>Secure Systems Design and Implementation</b>
      </td>
      <td style="text-align:left">
      <p>Bishop ch 14-16</br>

      Skim, Setuid demystified,
Some thoughts on security after ten years of qmail 1.0,
Wedge: Splitting Applications into Reduced-Privilege Compartments
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">27/2</td>
      <td style="text-align:left"><b>Capabilities</b>
      </td>
      <td style="text-align:left">
      <p>Skim: Bishop ch 18 -  skim math parts</br>
      Skim:Capsicum: practical capabilities for UNIX
      Removing ROP Gadgets from OpenBSD
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">3/3</td>
      <td style="text-align:left"><b>Forensics 1: Auditing and Intrusion Detection</b>
      </td>
      <td style="text-align:left">
      <p>Bishop ch 25 and 26, FD ch 1-4 and appendix B</p>
      <p>Read DSH ch 19-20</p>
      Download and browse the ENISA papers listed under Computer Forensics in the reading list
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">5/3</td>
      <td style="text-align:left"><b>Forensics 2: Incident Response</b>
      </td>
      <td style="text-align:left">
      <p>Read DSH ch 6-7</p>
      <p>Bishop ch 27</br>
      Incident Handler's Handbook
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">10/3</td>
      <td style="text-align:left"><b>System Security in Practice</b>
      </td>
      <td style="text-align:left">
      <p>Skim: Bishop ch 28,29,30</br>
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">11/3</td>
      <td style="text-align:left"><b>Benchmarking and Auditing Recap</b>
      </td>
      <td style="text-align:left">
      <p>Read DSH ch 8, skim ch 10-12</p>
      <p>CIS controls and PCI Best Practices for Maintaining PCI DSS Compliance v2.0 Jan 2019</p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"><b>Prepare for the exam</b></td>
      <td style="text-align:left">Summary of the course, prepare for exam</td>
    </tr>
  </tbody>
</table>

## Detailed plan

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


**Confinement and isolation**

* Confinement and isolation
* Virtual Machines and Sandboxes
* Covert Channels
* Firewall Flow Controls

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
