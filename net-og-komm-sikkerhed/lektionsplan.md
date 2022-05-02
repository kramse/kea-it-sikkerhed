---
description: Obligatoriske modul Ob 1 Netværks- og kommunikationssikkerhed (10 ECTS) Communication and Network Security
---

# Lektionsplan

## Fagets titel: Ob 1 Netværks- og kommunikationssikkerhed \(10 ECTS\)

English: Communication and Network Security

Teacher: Henrik Kramselund  hlk@zencurity.dk +45 2026 6000

This document is written using Github.

### Goals

The module is centered around network threats and implementing and configuring equipment in this area.

Module includes different security equipment like IDS for monitoring.

The evaluation of security in a network, developing plans for closing security vulnerabilities in the network and a review of various VPN technologies.

Teaching material will primarily be English, but the teaching will be in Danish.

See more about the course in the official curriculum.

### Exam:

Date: 15/6 2022

### Teaching Methods:

* Lecture lessons
* Group exercises and cases, including practical exercises with laptop
* 17:00 - 20:30 Online meetup and exercises - planned!

Teaching dates: Teaching dates: tuesdays and thursdays 17:00 - 20:30\\
19/4 2022, 21/4 2022, 26/4 2022, 28/4 2022, 3/5 2022, \sout{5/5 2022}, 10/5 2022, 12/5 2022, 17/5 2022, 19/5 2022, 24/5 2022, 31/5 2022, 2/6 2022, 7/6 2022

### Course reading list

This course uses three books and a number of supporting resources.

Primary literature:

* Applied Network Security Monitoring Collection, Detection, and Analysis, 2014 Chris Sanders ISBN: 9780124172081 - shortened ANSM

* Practical Packet Analysis - Using Wireshark to Solve Real-World Network Problems, 3rd edition 2017, Chris Sanders ISBN: 9781593278021 - shortened PPA

* Linux Basics for Hackers Getting Started with Networking, Scripting, and Security in Kali by OccupyTheWeb, December 2018, 248 pp. ISBN-13: 978-1-59327-855-7 - shortened LBfH

It is recommended to buy these books. The cost for all three will be about 1.000-1.100DKK

Curriculum will be chapters from the books, listed below!

Supporting literature is mostly background information, with a few exceptions. I do not expect you to read these in detail.

Supporting literature:
* _Linux Basics for Hackers Getting Started with Networking, Scripting, and Security in Kali_ by OccupyTheWeb, December 2018, 248 pp. ISBN-13: 978-1-59327-855-7 - especially if you dont know any Linux/Unix
* _Kali Linux Revealed  Mastering the Penetration Testing Distribution_ [https://www.kali.org/download-kali-linux-revealed-book/](https://www.kali.org/download-kali-linux-revealed-book/) - shortened KLR
* _The Debian Administrator’s Handbook_, Raphaël Hertzog and Roland Mas can be downloaded from https://debian-handbook.info/
* _Security problems in the TCP/IP protocol suite_, S. M. Bellovin https://www.cs.columbia.edu/~smb/papers/ipext.pdf samt
_A Look Back at “Security Problems in the TCP/IP Protocol Suite”_ https://www.cs.columbia.edu/~smb/papers/acsac-ipext.pdf
* _An Evening with Berferd: In Which a Cracker is Lured, Endured, and Studied_ , Bill Cheswick, AT&T Bell Laboratories http://www.cheswick.com/ches/papers/berferd.pdf
* _Firewalls and Internet Security: Repelling the Wily Hacker_ , Second Edition, William R. Cheswick, Steven M. Bellovin, and Aviel D. Rubin
http://www.wilyhacker.com/ - shortened Cheswick
* _A Graduate Course in Applied Cryptography_ By Dan Boneh and Victor Shoup  [https://toc.cryptobook.us/](https://toc.cryptobook.us/) Download latest version - currently version 0.5 [https://toc.cryptobook.us/book.pdff](https://toc.cryptobook.us/book.pdf)
* _RFC5246 The Transport Layer Security (TLS)_ https://tools.ietf.org/html/rfc5246
* _Strange Attractors and TCP/IP Sequence Number Analysis_ , Michal Zalewski [http://lcamtuf.coredump.cx/newtcp/](http://lcamtuf.coredump.cx/newtcp/)
* _WireGuard: Next Generation Kernel Network Tunnel_, https://www.wireguard.com/papers/wireguard.pdf
* _ENISA Presenting, correlating and filtering various feeds Handbook, Document for teachers_ [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/presenting-correlating-and-filtering-various-feeds-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/presenting-correlating-and-filtering-various-feeds-handbook)
* _ENISA Forensic analysis, Network Incident Response_ [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/2016-resources/exe2\_forensic\_analysis\_ii-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/2016-resources/exe2_forensic_analysis_ii-handbook)
* _ENISA Network Forensics, Handbook, Document for teachers_ [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/network-forensics-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/network-forensics-handbook)
* [http://www.honeynet.org/sites/default/files/files/KYT-Picviz\_v1\_0.pdf](http://www.honeynet.org/sites/default/files/files/KYT-Picviz_v1_0.pdf)
* _Campus Network Security: High Level Overview_ , Network Startup Resource Center  https://nsrc.org/workshops/2018/myren-nsrc-cndo/networking/cndo/en/presentations/Campus_Security_Overview.pdf
* _Campus Operations Best Current Practice_, Network Startup Resource Center  https://nsrc.org/workshops/2018/tenet-nsrc-cndo/networking/cndo/en/presentations/Campus_Operations_BCP.pdf
* _Mutually Agreed Norms for Routing Security (MANRS)_ https://www.manrs.org/wp-content/uploads/2018/09/MANRS_PDF_Sep2016.pdf
* _RFC2827: Network Ingress Filtering: Defeating Denial of Service Attacks_ https://tools.ietf.org/html/rfc2827


These can be downloaded from the internet for free and may be gathered by the instructor for easy download.

Also the course will use internet links and pages.

### Hardware

Since we are going to be doing exercises, sniffing data it will be an advantage to have a wireless USB network card.

The following are two recommended models:
* TP-link TL-WN722N hardware version 2.0 cheap but only support 2.4GHz
* Alfa AWUS036ACH 2.4GHz + 5GHz Dual-Band and high performing

Both work great in Kali Linux for our purposes.

Unfortunately the vendors change models often enough that the above are hard to find. I recommend using your favourite search engine and research which cards work with Kali Linux and airodump-ng.

## Planning

The detailed plan is below with a table summarizing lessons

<table>
  <thead>
    <tr>
      <th style="text-align:left">Date</th>
      <th style="text-align:left">Theme</th>
      <th style="text-align:left">Goals</th>
      <th style="text-align:left">Litterature / Preparation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">19/4</td>
      <td style="text-align:left">
        <p>Welcome, goals and expectations</br>
        Prepare Kali Linux VM - bring laptop</p>
      </td>
      <td style="text-align:left">
        <p>Create a good starting point for learning </br>
         Introduce lecturer and students </br>
         Concrete Expectations </br>
         Prepare tools for the exercises </p>
      </td>
      <td style="text-align:left">
      <p> Reviewing the literature list will occur when we meet. </p>
         <p> Download Kali Linux Revealed </p>
         <p> Identification of chapters and sections from KLR and LBfH<br>
        for reading as home assignment </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">21/4</td>
      <td style="text-align:left"><b>TCP/IP and Security in TCP/IP protocol suite</b>
      </td>
      <td style="text-align:left">Understand basic IP protocols and inherent security problems</td>
      <td style="text-align:left">
      <p>Read: PPA chapters 1,2,3 - 52 pages,</br>
      ANSM chapter 13 - 44 pages</p>
      <p>Skim: papers <em>Security problems in the TCP/IP protocol suite</em>
      and <em>A Look Back at "Security Problems ..."</em></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">26/4</td>
      <td style="text-align:left"><b>Network Security Threats</b>
      </td>
      <td style="text-align:left">Know common threats in networks, and solutions</td>
      <td style="text-align:left">
      <p>Read: PPA chapters 4,5,6 - 66 pages</p>
      <p>Skim: papers <em>Strange Attractors and TCP/IP Sequence Number Analysis</em></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">28/4</td>
      <td style="text-align:left"><b>Traffic inspection and firewalls</b>
      </td>
      <td style="text-align:left">Understand basic firewall technologies</td>
      <td style="text-align:left">
      <p>Read: ANSM chapter 1,2,3 - 73 pages</br>
      https://en.wikipedia.org/wiki/Firewall_(computing)</br>
      http://www.wilyhacker.com/ Cheswick chapter 2 og 3 PDF, ca 55 pages</p>
      <p>Skim: chapters from 1st edition:</br>
      http://www.wilyhacker.com/1e/chap03.pdf
      http://www.wilyhacker.com/1e/chap04.pdf
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">3/5</td>
      <td style="text-align:left"><b>Encrypting the network</b>
      </td>
      <td style="text-align:left">Know how math, algorithms and protocols are used to ensure confidentiality and integrity</td>
      <td style="text-align:left">
      <p>Read: PPA chapters 7,8,9 - 80 pages </p>
      <p>Skim: table of contents of
      RFC5246 The TLS Protocol Version 1.2</br> and the wikipedia page
      https://en.wikipedia.org/wiki/Transport_Layer_Security</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">5/5</td>
      <td style="text-align:left"><b>Virtual Private Networks</b>
      </td>
      <td style="text-align:left">Know methods of connecting securely across insecure networks</td>
      <td style="text-align:left">
      <p>Read: ANSM chapter 7,8 - 54 pages,</p>
      <p>https://en.wikipedia.org/wiki/Virtual_private_network</br>
      https://kb.juniper.net/InfoCenter/index?page=content&id=KB11104  IPSec VPN between JUNOS and Cisco IOS</p>
      <p>Skim:
      https://en.wikipedia.org/wiki/Multiprotocol_Label_Switching</br>
      https://en.wikipedia.org/wiki/OpenVPN</br>
      https://en.wikipedia.org/wiki/IPsec</br>
      https://en.wikipedia.org/wiki/DirectAccess</br>
      https://www.wireguard.com/papers/wireguard.pdf
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">10/5</td>
      <td style="text-align:left"><b>Wifi Security</b>
      </td>
      <td style="text-align:left">Knowledge of Wireless 802.11 and security methods used</td>
      <td style="text-align:left">
      <p>Read: PPA chapters 12, 13 - 60 pages</p>
      <p>Skim:</br>
      http://aircrack-ng.org/doku.php?id=cracking_wpa
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">12/5</td>
      <td style="text-align:left"><b>Network Management</b>
      </td>
      <td style="text-align:left">Understand why managed networks are more secure</td>
      <td style="text-align:left">
      <p>Read: PPA chapter 10,11 - 58 pages </p>
      <p>Skim:</br>
      https://nsrc.org/workshops/2015/sanog25-nmm-tutorial/materials/snmp.pdf</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">17/5</td>
      <td style="text-align:left"><b>Network Intrusion Detection</b>
      </td>
      <td style="text-align:left">Learn how to sniff and detect network problems using IDS</td>
      <td style="text-align:left">
      <p>Browse -- note a few headlines: ANSM chapter 9,10 - 86 pages - very usefull if you want to implement IDS. Not curriculum, but introduce IDS and are a good reference</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">19/5</td>
      <td style="text-align:left"><b>Network Forensics</b>
      </td>
      <td style="text-align:left">Introduction to network investigations</td>
      <td style="text-align:left">
      <p>Read: ANSM chapter 4 - 24 pages</br>
      Zeek documentation Intel framework https://docs.zeek.org/en/stable/frameworks/intel.html<br>
      Suricata reputation support https://suricata.readthedocs.io/en/suricata-4.0.5/reputation/index.html</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">24/5</td>
      <td style="text-align:left"><b>Honeypots</b>
      </td>
      <td style="text-align:left">See how systems can attract attackers and monitor attacks</td>
      <td style="text-align:left">
      <p>Read: ANSM chapter 12 Browse: ANSM chapter 11 - uses an older tool package SiLK but the process described is great</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">31/5</td>
      <td style="text-align:left"><b>DNS and Email Security</b>
      </td>
      <td style="text-align:left">Learn the role of DNS in securing networks and systems</td>
      <td style="text-align:left">
      <p>Read: ANSM chapter 14,15 - 66 pages</p>
      <p>Re-Read: PPA DNS pages 173-183</p>
      <p>Browse https://en.wikipedia.org/wiki/Sender_Policy_Framework</br>
      https://en.wikipedia.org/wiki/DMARC</br>
      https://en.wikipedia.org/wiki/DomainKeys_Identified_Mail</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">2/6</td>
      <td style="text-align:left"><b>Building Robust Networks</b>
      </td>
      <td style="text-align:left">Learn the process of securing a network using security components</td>
      <td style="text-align:left">
      <p>Read: ANSM chapter 5,6 - 50 pages,</br>
      _Campus Network Security: High Level Overview_ NSRC,</br>
      _Campus Operations Best Current Practice_ NSRC</p>
      <p>Download, but dont Read:it all https://nsrc.org/workshops/2015/apricot2015/raw-attachment/wiki/Track1Agenda/01-ISP-Network-Design.pdf</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">7/6</td>
      <td style="text-align:left"><b>Running a Modern Network</b></td>
      <td style="text-align:left">Learn that your network is part of the bigger Internet, your security affects others</td>
      <td style="text-align:left">
      <p>Browse https://www.manrs.org/  and Read:these https://www.manrs.org/wp-content/uploads/2018/09/MANRS_PDF_Sep2016.pdf
      https://tools.ietf.org/pdf/bcp38.pdf</p>
      <p>Skim:
      RFC2827: Network Ingress Filtering: Defeating Denial of Service Attacks
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"><b>Summary and prepare for the exam</b></td>
      <td style="text-align:left">Summary of the course</td>
      <td style="text-align:left">Everything read in the primary books, listed above</td>
    </tr>
  </tbody>
</table>

**Introduction and welcome**

* Expectations for this course
* Literature list walkthrough
* Kali Linux introduction

Kali Linux is a toolbox we will use and participants will use a virtual machine

Exercises
* Kali Linux installation

**TCP/IP and Security in TCP/IP protocol suite**

* Addressing and layering OSI model vs internet model
* Network devices Ethernet, bridges, switches, routers
* Common protocols, layer 2 and layer 3
* Secure network design  Background paper _Security problems in the TCP/IP protocol suite_, S. M. Bellovin

Exercises
* run tcpdump, wireshark, traceroute, whois

**Network Security Threats**

* ARP spoofing, ICMP redirects, the classics
* Person in the middle attacks
* Network Scanning
* Intro to routing protocols attacks
* BGP intro and hijacking
* DDoS and flooding

Exercises
* ARP spoofing and ettercap
* EtherApe
* Nmap and Nping
* Pcap-diff [https://github.com/isginf/pcap-diff](https://github.com/isginf/pcap-diff)

**Traffic inspection and firewalls**

* Network sniffing strategies and techniques
* Generic IP Firewalls stateless filtering vs stateful inspection
* Next Generation firewalls, Deep Packet Inspection
* IEEE 802.1q VLAN
* Common countermeasures in firewalls

Exercises
* Nmap scanning basics

**Encrypting the network**

* Basic cryptography
* Encryption Decryption
* Hashing
* Short introduction to algorithms RSA, AES
* Diffie Helman exchange
* Transport Layer Security (TLS)

Exercise/examples

* mitmproxy [https://mitmproxy.org/](https://mitmproxy.org/)
* sslsplit [https://www.roe.ch/SSLsplit](https://www.roe.ch/SSLsplit)
* sslstrip [https://moxie.org/software/sslstrip/](https://moxie.org/software/sslstrip/)
* https://www.ssllabs.com/ and sslscan checking servers


**Virtual Private Networks**

* IPsec and L2TP/IPsec
* TLS VPN with example OpenVPN
* Linux Wireguard VPN
* Microsoft DirectAccess and VPN (RAS)

Exercises
* go through the ones used by participants, how are they secured why/why not.
* Sniff data without VPN and after VPN turned on

**Wifi Security**

* Wifi standarder IEEE 802.11
* Authentication Protocols RADIUS, PAP, CHAP, EAP
* Port Based Network Access Control IEEE 802.1x
* Security problems in wireless protocols
* Security problems in wireless encryption
* Hacking wireless networks

Exercise
* Wifi scanning, aka wardriving
* WPA hacking with a short password

**Network Management**

* SNMP version 2 vs version 3
* Bruteforcing network devices SSH vs SNMP
* Centralized management SSH, Jump hosts
* Monitoring


Exercise
* Run SNMP walk
* Try brute-force SNMP

**Network Intrusion Detection**

* Intrusion Detection Systems
* NIDS vs HIDS
* Suricata Zeek
* Network Security Data Visualization
* Kibana Dashboards

Exercise
* Run Zeek and Suricata on small pcaps

**Network Forensics**

* Centralized syslog
* Netflow data
* Collect Network Evidence
* Analyze Network data
* Network Forensics
* Create Incident Reports

Exercises
* Run forensics similar to ENISA examples
* Create a Kibana dashboard for looking at logs

**Honeypots**

* History of honeypots
* Why use them research, production
* Types of honeypots low vs high interaction
* Honey nets

Exercise
* Run SSH honeypot and try brute-force it

**DNS and Email Security**
* DNS introduction
* SMTP introduction
* SMTP TLS
* SPF, DKIM, DMARC
* DNSSEC - DNS integrity
* DNS over TLS vs DNS over HTTPS - DNS encryption

Exercises
* Check some examples like how danish banks are using DMARC, and how your own companies can start using it
* SSLscan with SMTP TLS

**Building Robust Networks**

* Design a robust network
* Isolation and segmentation
* (Routing Security) removed, see Running a Modern Network slide set
* Switch and access security, port security
* (Wireless security) removed - see Wireless Security slide set
* (Using reputation lists) removed - see Network Intrusion Detection slide set

Parts removed, to make room for practical exercises.

Exercise
We will design and build a sample network together
* VLANs, Routing and RPF
* Wifi, WPA and guest network
* Monitoring - setup LibreNMS
* IDS with Zeek and Suricata  - if we have time
* Configure port security  - if we have time

**Running a Modern Network**

* BCP38 RFC2827: Network Ingress Filtering: Defeating Denial of Service Attacks which employ IP Source Address Spoofing
* Mutually Agreed Norms for Routing
Security (MANRS) https://www.manrs.org/isps/
* Testing security, evaluating and reporting
* Hardened network device configurations
* Jump hosts and management networks
* DDoS protection
* Check you network from outside RIPEstat, BGPmon

Exercises
* look at your own networks, from the outside
