---
description: Elective Course Introduction to Incident Response (5 ECTS)
---

# Lektionsplan

## Course: Introduction to Incident Response \(5 ECTS\)

### General Information


Teacher: Henrik Kramselund xhek@kea.dk hlk@zencurity.dk +45 2026 6000


This document is written using Github.

Teaching material will primarily be English, but the teaching will be in Danish.

### Goals

The module is an introduction to Incident Response that will describe the basics of incident response. This will include the terms, tools and processes used by professionals.

See more about the course in the official curriculum.

### Exam:

Date: TBD 2023 exam

### Teaching Methods:

* Lecture lessons
* Group exercises and cases, including practical exercises with laptop

### Teaching dates - Spring 2023:

Teaching dates: thursdays 08:30 - 12:30 in GBG.E436

9/2, 16/2, 23/2, 2/3, 9/3, 23/3, 30/3, 13/4, 27/4
Note: we need to move one date! 9/3

### Hardware

Since we are going to be doing exercises, each team will need two virtual machines.

The following are two recommended models:
* One based on Debian, running software servers and web applications
* One based on Linux, running tools

Read more about these at [https://github.com/kramse/kramse-labs](https://github.com/kramse/kramse-labs)


### Course reading list
This course uses a few books and a number of supporting resources.

Primary literature:

* Forensics Discovery, Dan Farmer, Wietse Venema 2004, Addison-Wesley 240 pages. Can be found at http://www.porcupine.org/forensics/forensic-discovery/ but recommend buying it. Referenced below as FD
* Computer Security Incident Handling Guide, NIST SP 800-61 Rev. 2, August 2012
https://doi.org/10.6028/NIST.SP.800-61r2

It is recommended to get these books. Note: we won't read all chapters and pages.

Supporting literature - optional to buy, but recommended:

* Linux Basics for Hackers Getting Started with Networking, Scripting, and Security in Kali by OccupyTheWeb, December 2018, 248 pp. ISBN-13: 978-1-59327-855-7 - shortened LBfH

Also the course will use internet links and pages.

Supporting Internet resources
* The Debian Administrator’s Handbook, Raphaël Hertzog and Roland Mas
[https://debian-handbook.info/](https://debian-handbook.info/) - shortened DEB

* Kali Linux Revealed  Mastering the Penetration Testing Distribution [https://www.kali.org/download-kali-linux-revealed-book/](https://www.kali.org/download-kali-linux-revealed-book/) - shortened KLR

Attacks on infrastructure:
* [Smashing The Stack For Fun And Profit](http://www.phrack.com/issues.html?issue=49&id=14#article), Aleph One
* [Return-Oriented Programming:Systems, Languages, and Applications](https://hovav.net/ucsd/dist/rop.pdf)
Ryan Roemer, Erik Buchanan, Hovav Shacam and Stefan Savage University of California, San Diego
* [MITRE ATT&CK](https://attack.mitre.org/) a globally-accessible knowledge base of adversary tactics and techniques based on real-world observations, read the [ATT&CK 101 Blog Post](https://medium.com/mitre-attack/att-ck-101-17074d3bc62)
* [Enterprise Survival Guide for Ransomware Attacks](https://www.sans.org/reading-room/whitepapers/incident/enterprise-survival-guide-ransomware-attacks-36962), Shafqat Mehmoon, SANS Information Securiy Reading Room
* [TCP Synfloods - an old yet current problem, and improving pf's response to it](http://quigon.bsws.de/papers/2017/bsdcan/)
Henning Brauer, BSDCan 2017
* _A Graduate Course in Applied Cryptography_ By Dan Boneh and Victor Shoup  [https://toc.cryptobook.us/](https://toc.cryptobook.us/) [https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup\_0\_4.pdf](https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup_0_4.pdf)

Computer Forensics, Incident Response, Intrusion Detection
* [Incident Handler's Handbook](https://www.sans.org/reading-room/whitepapers/incident/paper/33901)
by Patrick Kral, SANS Information Security Reading Room
* [An Intrusion-Detection Model](http://www.cs.colostate.edu/~cs656/reading/ieee-se-13-2.pdf), Dorothy E. Denning
IEEE Transactions on Software Engineering ( Volume: SE-13 , Issue: 2 , Feb. 1987 )
* ENISA Presenting, correlating and filtering various feeds Handbook, Document for teachers [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/presenting-correlating-and-filtering-various-feeds-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/presenting-correlating-and-filtering-various-feeds-handbook)
* ENISA Forensic analysis, Network Incident Response [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/2016-resources/exe2\_forensic\_analysis\_ii-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/2016-resources/exe2_forensic_analysis_ii-handbook)
* ENISA Network Forensics, Handbook, Document for teachers [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/network-forensics-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/network-forensics-handbook)

Policies, governance and best Practice
* [Campus Network Security: High Level Overview](https://nsrc.org/workshops/2018/myren-nsrc-cndo/networking/cndo/en/presentations/Campus_Security_Overview.pdf) , Network Startup Resource Center  
* [Campus Operations Best Current Practice](https://nsrc.org/workshops/2018/tenet-nsrc-cndo/networking/cndo/en/presentations/Campus_Operations_BCP.pdf), Network Startup Resource Center  
* [CIS Controls](https://learn.cisecurity.org/cis-controls-download) Requires giving your email
* [PCI Best Practices for Maintaining PCI DSS Compliance v2.0 Jan 2019](https://www.pcisecuritystandards.org/documents/PCI_DSS_V2.0_Best_Practices_for_Maintaining_PCI_DSS_Compliance.pdf?agreement=true&time=1555354264656)
* [NIST Special Publication 800-63B Digital Identity Guidelines: Authentication and Lifecycle Management](https://pages.nist.gov/800-63-3/sp800-63b.html)
* [IT Security Guidelines for Transport Layer Security (TLS)](https://english.ncsc.nl/publications/publications/2022/january/19/it-security-guidelines-for-transport-layer-security-2.1)

## Planning

The detailed plan is below with a table summarizing lessons

<table>
<thead>
<tr>
  <th style="text-align:left">Date</th>
  <th style="text-align:left">Theme</th>
  <th style="text-align:left">Litterature / Preparation</th>
</tr>
</thead>
<tbody>
    <tr>
      <td style="text-align:left">9/2</td>
      <td style="text-align:left"><b> Subject</b></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">16/2</td>
      <td style="text-align:left"><b> Subject</b></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">23/2</td>
      <td style="text-align:left"><b> Subject</b></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">2/3</td>
      <td style="text-align:left"><b> Subject</b></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">9/3</td>
      <td style="text-align:left"><b> Subject</b></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">12/3</td>
      <td style="text-align:left"><b> Subject</b></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">30/3</td>
      <td style="text-align:left"><b> Subject</b></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">13/4</td>
      <td style="text-align:left"><b> Subject</b></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">27/4</td>
      <td style="text-align:left"><b> Subject</b></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"><b>Prepare for the exam</b></td>
      <td style="text-align:left">Summary of the course, prepare for exam</td>
    </tr>
  </tbody>
</table>
