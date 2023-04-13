---
description: Valgfrie modul  VF1 Systemsikkerhed (10 ECTS) System Security
---

# Lektionsplan

## Fagets titel: VF1 Systemsikkerhed \(10 ECTS\)

### General Information
English: Computer Systems Security

Teacher: Henrik Kramselund  xhek@kea.dk  hlk@zencurity.dk +45 2026 6000


This document is written using Github.

Teaching material will primarily be English, but the teaching will be in Danish.

### Goals

The module is centered around the design and implementation of secure computer systems.
 Topics include operating system (OS) security, capabilities, and more.



See more about the course in the official curriculum.

### Exam:

Date: date coming for 2023 exam

### Teaching Methods:

* Lecture lessons
* Group exercises and cases, including practical exercises with laptop

Teaching dates: tuesdays and thursdays 17:00 - 20:30

18/4, 20/4, 25/4, 27/2, 2/5, 4/5, 9/5, 11/5, 16/5, 30/5, 1/6, 6/6, 8/6, 13/6 2023

### Course reading list
This course uses a few books and a number of supporting resources.

Primary literature:

* _Mastering Linux Security and Hardening_ (MLSH), third edition, Donald A. Tevault, 2023 ISBN: 9781837630516
https://www.packtpub.com/product/mastering-linux-security-and-hardening-third-edition/9781837630516
* _Defensive Security Handbook: Best Practices for Securing Infrastructure_ (DSH), Lee Brotherston, Amanda Berlin ISBN: 978-1-491-96038-7 284 pages
* _Forensics Discovery_ (FD), Dan Farmer, Wietse Venema 2004, Addison-Wesley 240 pages. Can be found at http://www.porcupine.org/forensics/forensic-discovery/ but recommend buying it

It is recommended to buy these books. Note: we won't read all chapters and pages.

Supporting literature - optional to buy, but recommended:

* _The Linux Command Line: A Complete Introduction_, 2nd Edition by William Shotts Print: https://nostarch.com/tlcl2
Download -- internet edition https://sourceforge.net/projects/linuxcommand
* _Linux Basics for Hackers Getting Started with Networking, Scripting, and Security in Kali_ by OccupyTheWeb, December 2018, 248 pp. ISBN-13: 978-1-59327-855-7 - shortened LBfH

Also the course will use internet links and pages.

Supporting Internet resources
* The Debian Administrator’s Handbook, Raphaël Hertzog and Roland Mas https://debian-handbook.info/ - shortened DEB
* Kali Linux Revealed  Mastering the Penetration Testing Distribution - shortened KLR

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
      <td style="text-align:left">1/2</td>
      <td style="text-align:left">
        <p>Welcome, goals and expectations</br>
        Prepare Kali Linux VM - bring laptop</p>
      </td>
      <td style="text-align:left">
      <p> Reviewing the literature list will occur when we meet. </p>
         <p> Download PDF documents<br>Create VMs</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">3/2</td>
      <td style="text-align:left"><b>Overview of Computer Security</b>
      </td>
      <td style="text-align:left">
      <p>DSH chapters 1-2, MLSH ch 1 </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">8/2</td>
      <td style="text-align:left"><b>Overview of Enterprise Attacks</b>
      </td>
      <td style="text-align:left">
      <p>Read <a href="https://medium.com/mitre-attack/att-ck-101-17074d3bc62">ATT&CK 101 Blog Post</a> and browse
      <a href="https://attack.mitre.org/">MITRE ATT&CK</a>
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">10/2</td>
      <td style="text-align:left"><b>User Accounts</b>
      </td>
      <td style="text-align:left">
      <p> MLSH 1-2</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">15/2</td>
      <td style="text-align:left"><b>Security Policies</b>
      </td>
      <td style="text-align:left">
      <p>DSH ch 3-5, MLSH ch 3-4 - NOT firewalld part!<br>
      Browse: Campus Network Security: High Level Overview , Network Startup Resource Center
Campus Operations Best Current Practice, Network Startup Resource Center
Mutually Agreed Norms for Routing Security (MANRS) </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">17/2</td>
      <td style="text-align:left"><b>Basic Cryptography</b>
      </td>
      <td style="text-align:left">
      <p>MLSH ch 5, browse chapter 6<br>
       TLS1.2 RFC5246 table of contents - but only ToC, not the whole document!<br>
      Skim: NIST Special Publication 800-63B<br>
      Enterprise Survival Guide for Ransomware Attacks<br>
      IT Security Guidelines for Transport Layer Security</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">22/2</td>
      <td style="text-align:left"><b>Malware, Intrusion, Vulnerabilities</b>
      </td>
      <td style="text-align:left">
      <p></br>
      Browse: Smashing The Stack For Fun And Profit, Bypassing non-executable-stack during exploitation using return-to-libc, Basic Integer Overflows, Return-Oriented Programming
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">24/2</td>
      <td style="text-align:left"><b>Secure Systems Design and Implementation</b>
      </td>
      <td style="text-align:left">
      <p>MLSH ch 7-8</br>Skim, Setuid demystified, Some thoughts on security after ten years of qmail 1.0,
      Wedge: Splitting Applications into Reduced-Privilege Compartments </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">1/3</td>
      <td style="text-align:left"><b>Capabilities</b>
      </td>
      <td style="text-align:left">
      <p> MLSH ch 9-10</br>
      Skim: Removing ROP Gadgets from OpenBSD
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">3/3</td>
      <td style="text-align:left"><b>Breaking out</b>
      </td>
      <td style="text-align:left">
      <p>Read DSH ch </p>
      <p>
      Browse: Using Memory Errors to Attack a Virtual Machine paper, An Experimental Study of DRAM Disturbance Errors,  Exploiting the DRAM rowhammer bug to gain kernel privileges
      https://en.wikipedia.org/wiki/Row_hammer
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">8/3</td>
      <td style="text-align:left"><b>Forensics 1: Auditing and Intrusion Detection</b>
      </td>
      <td style="text-align:left">
      <p>Read DSH ch 19-20, MLSH 12</p>
      Download and browse the ENISA papers listed under Computer Forensics in the reading list
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">10/3</td>
      <td style="text-align:left"><b>Forensics 2: Incident Response</b>
      </td>
      <td style="text-align:left">
      <p>Read DSH ch 6-7</p>
      <p>Browse: Incident Handler's Handbook
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">15/3</td>
      <td style="text-align:left"><b>System Security in Practice</b>
      </td>
      <td style="text-align:left">
      <p>DSH ch 21</br>
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">17/3</td>
      <td style="text-align:left"><b>Benchmarking and Auditing Recap</b>
      </td>
      <td style="text-align:left">
      <p>Read MLSH 11, DSH ch 8, skim ch 10-12</p>
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
