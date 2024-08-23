---
description: Obligatorisk modul OB2 Softwaresikkerhed (10 ECTS) Software Security
---

# Lektionsplan

## Fagets titel: VF1 Softwaresikkerhed \(10 ECTS\)

English: Software Security

Teacher: Henrik Kramselund xhek@kea.dk hlk@zencurity.dk +45 2026 6000


This document is written using Github.


### Goals

The module is centered around software security including software quality, software flaws, vulnerabilities, software APIs, error handling and software architecture.

Teaching material will primarily be English, but the teaching will be in Danish.

See more about the course in the official curriculum which can be downloaded from the main page [https://kompetence.kea.dk/uddannelser/it-digitalt/diplom-i-it-sikkerhed](https://kompetence.kea.dk/uddannelser/it-digitalt/diplom-i-it-sikkerhed)
- near the top "Download studieordningen".

### Teaching Methods:

* Lecture lessons
* Group exercises and cases, including practical exercises with laptop

### Important dates:

Teaching dates - fall 2024 tuesdays and thursdays 17:00 - 20:30

29/8, 3/9, 10/9, 12/9, 17/9, 19/8, 24/9, 26/9, {\sout1/10}, 3/10, 8/10, 10/10, 22/10, 24/10

Exam: 5/11 2024

Changed dates: 1/10 moving due to external meeting for Henrik, propose 15/10

### Hardware

Since we are going to be doing exercises, each team will need two virtual machines.

The following are two recommended models:
* One based on Debian, running software servers and web applications
* One based on Kali Linux, running attacks against software

Read more about these at [https://github.com/kramse/kramse-labs](https://github.com/kramse/kramse-labs)


### Course reading list

This course uses three books and a number of supporting resources.

Primary literature:

* The Art of Software Security Testing Identifying Software Security Flaws,
Chris Wysopal, 2006, ISBN: 9780321304865, named AoST or the Green Book
* Web Application Security, Andrew Hoffman, 2020, ISBN: 9781492053118 called WAS below. Can be downloaded for free from https://www.nginx.com/resources/library/web-application-security/
* Pwning OWASP Juice Shop Official companion guide to the OWASP Juice Shop
Can be found online for free, but recommend buying the PDF from https://leanpub.com/juice-shop - suggested price USD 5.99

Supporting literature:

* Linux Basics for Hackers Getting Started with Networking, Scripting, and Security in Kali by OccupyTheWeb, December 2018, ISBN-13: 978-1-59327-855-7 - shortened LBfH
* Gray Hat Hacking: The Ethical Hacker's Handbook, sixth edition Allen Harper ISBN: 9781264268955

**It is highly recommended to get these books listed above.**


### Supporting Internet resources

Also the course will use internet links and pages. These can often be downloaded from the internet for free and may be gathered by the instructor for easy download.

These are not part of the curriculum for this course, but are considered important references. It is recommended to skim, browse them and familiarize yourself with the content.

Books about the virtual machines we will run:

* The Debian Administrator’s Handbook, Raphaël Hertzog and Roland Mas
[https://debian-handbook.info/](https://debian-handbook.info/) - shortened DEB

* Kali Linux Revealed  Mastering the Penetration Testing Distribution [https://www.kali.org/download-kali-linux-revealed-book/](https://www.kali.org/download-kali-linux-revealed-book/) - shortened KLR

We will also use the OWASP Juice Shop Tool Project as a running example. This is an application which is modern AND designed to have security flaws.

Read more about this project at [https://www.owasp.org/index.php/OWASP_Juice_Shop_Project](https://www.owasp.org/index.php/OWASP_Juice_Shop_Project) and
[https://github.com/bkimminich/juice-shop](https://github.com/bkimminich/juice-shop)


System Design and Architecture
* [Security by Design Principles, OWASP](https://www.owasp.org/index.php/Security_by_Design_Principles)
* Wikipedia article about Privacy by Design
[Privacy by Design](https://en.wikipedia.org/wiki/Privacy_by_design)
* This in danish summarizing the implications of General Data Protection Regulation (GDPR)
[https://www.dubex.dk/aktuelt/nyheder/det-skal-du-vide-om-privacy-by-design-ny-vejledning](https://www.dubex.dk/aktuelt/nyheder/det-skal-du-vide-om-privacy-by-design-ny-vejledning)
* Article recommends doing Privacy Impact Assessment (PIA) [https://itb.dk/persondataforordningen/privacy-by-design-default/](https://itb.dk/persondataforordningen/privacy-by-design-default/)
* ENISA, EU security office, reports about Privacy by Design [Privacy and Data Protection by Design](https://www.enisa.europa.eu/publications/privacy-and-data-protection-by-design) and
[Privacy by design in big data](https://www.enisa.europa.eu/publications/big-data-protection)

Control Hijacking Attacks
* [Smashing The Stack For Fun And Profit](http://www.phrack.com/issues.html?issue=49&id=14#article), Aleph One
* [Bypassing non-executable-stack during exploitation using return-to-libc](http://css.csail.mit.edu/6.858/2014/readings/return-to-libc.pdf)
 by c0ntex.
* [Basic Integer Overflows](http://www.phrack.com/issues.html?issue=60&id=10#article) by blexim.
* [Return-Oriented Programming:Systems, Languages, and Applications](https://hovav.net/ucsd/dist/rop.pdf)
Ryan Roemer, Erik Buchanan, Hovav Shacam and Stefan Savage University of California, San Diego
* [MITRE ATT&CK](https://attack.mitre.org/) a globally-accessible knowledge base of adversary tactics and techniques based on real-world observations, read the [ATT&CK 101 Blog Post](https://medium.com/mitre-attack/att-ck-101-17074d3bc62)



OS Security and secure coding
* [Secure Coding Best Practices Handbook](https://info.veracode.com/secure-coding-best-practices-hand-book-guide-resource.html) Veracode
* [Secure Programming for Linux and Unix HOWTO](http://www.dwheeler.com/secure-programs/)), David Wheeler.
* [Setuid demystified](http://www.cs.berkeley.edu/~daw/papers/setuid-usenix02.pdf) by Hao Chen, David Wagner, and Drew Dean.
* [Removing ROP Gadgets from OpenBSD](https://www.openbsd.org/papers/asiabsdcon2019-rop-paper.pdf) Todd Mortimer mortimer@openbsd.org
* [TCP Synfloods - an old yet current problem, and improving pf's response to it](http://quigon.bsws.de/papers/2017/bsdcan/)
Henning Brauer, BSDCan 2017
* 24 Deadly Sins of Software Security: Programming Flaws and How to Fix Them, Michael Howard, David LeBlanc, John Viega, ISBN: 9780071626750, 2010 The McGraw-Hill Companies, named 24-deadly below



Exploiting Hardware Bugs and Crypto Related
* [Bug Attacks on RSA](https://css.csail.mit.edu/6.858/2011/readings/rsa-bug-attacks.pdf), by Eli Biham, Yaniv Carmeli, and Adi Shamir.
* [Using Memory Errors to Attack a Virtual Machine](https://www.cs.princeton.edu/~appel/papers/memerr.pdf) by Sudhakar Govindavajhala and Andrew
Appel
* [Flipping Bits in Memory Without Accessing Them: An Experimental Study of DRAM Disturbance Errors](http://users.ece.cmu.edu/~yoonguk/papers/kim-isca14.pdf) Yoongu Kim, Ross Daly, Jeremie Kim, Chris Fallin, Ji Hye Lee, Donghyuk Lee, Chris Wilkerson, Konrad Lai, Onur Mutlu, see also [Explo
iting the DRAM rowhammer bug to gain kernel privileges](https://googleprojectzero.blogspot.com/2015/03/exploiting-dram-rowhammer-bug-to-gain.html)
* _A Graduate Course in Applied Cryptography_ By Dan Boneh and Victor Shoup  [https://toc.cryptobook.us/](https://toc.cryptobook.us/)



## Planning

The detailed plan is below with a table summarizing lessons.

**Note: contains lot of pages, learn to skim and skip chapters and parts that don't interest you. In real life we don't have time to read every word!**

<table>
  <thead>
    <tr>
      <th style="text-align:left;width:10%">Date</th>
      <th style="width:45%">Theme / Goals</th>
      <th style="width:45%">Litterature / Preparation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">15/8</td>
      <td style="text-align:left">
        <p>Welcome, goals and expectations</br>
        Prepare Virtual Machines - bring laptop</p>
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
      <td style="text-align:left">17/8</td>
      <td style="text-align:left"><b>Lab setup and Programming Knowledge</b><p>Do some initial programming</p></td>
      <td style="text-align:left">
      <p>Linux introduction and familiarisation </p>
      <p>AoST chapters 1</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">22/8</td>
      <td style="text-align:left"><b>Initial Overview of Software Security</b>
<p>Get an overview of the subject</p></td>
      <td style="text-align:left">
      <p>Curriculum: AoST chapters 2</p>
      <p>Supporting litterature: 24-deadly introduction before page 1, browse Table of Contents for _Secure Programming for Linux and Unix HOWTO_ </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">24/8</td>
      <td style="text-align:left"><b>SDLC and risk ranking</b>
      </td>
      <td style="text-align:left">
      <p>AoST chapters 3,4,5 - ca 50 pages</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">29/8</td>
      <td style="text-align:left"><b>Web Application Security: Recon</b></td>
      <td style="text-align:left">
      <p>AoST chapters 6,7,8,9 - ca 72 pages.</p>
      <p>Look at: Getting started with Burp Suite [https://portswigger.net/support/getting-started-with-burp-suite](https://portswigger.net/support/getting-started-with-burp-suite)</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">31/8</td>
      <td style="text-align:left"><b>Web Application Security: Recon and Offensive</b></td>
      <td style="text-align:left">
      <p>WAS chapters 1-8, very short chapters </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">5/9</td>
      <td style="text-align:left"><b>Hacking Web Applications: Offensive</b></td>
      <td style="text-align:left">
      <p>WAS chapters 9-16, very short chapters</p>
      <p>Browse: _Secure Coding Best Practices Handbook Veracode_</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">7/9</td>
      <td style="text-align:left"><b>Software Programming & Memory Corruption</b></td>
      <td style="text-align:left">
      <p>Next three evenings programming and buffer overflow.
      Grayhat chapters 1-2, 11-13 - browse if you need to, many pages.</p>
      <p>Browse: Smashing The Stack For Fun And Profit, Aleph One,
Bypassing non-executable-stack during exploitation using return-to-libc
by c0ntex, Basic Integer Overflows by blexim.</p>
<p>Supporting litterature: 24-deadly chapters 5-8 - if you have it</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">12/9</td>
      <td style="text-align:left"><b>Program Building blocks and exploitation</b></td>
     <td style="text-align:left">
     <p>Grayhat chapters 1-2, 11-13</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">14/9</td>
      <td style="text-align:left"><b>Strings and Pointers</b></td>
      <td style="text-align:left">
      <p>Grayhat chapters 1-2, 11-13</p>
      <p>Browse: _Return-Oriented Programming:Systems, Languages, and Applications_ and _Removing ROP Gadgets from OpenBSD_</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">19/9</td>
      <td style="text-align:left"><b>Network Attacks Intro</b></td>
      <td style="text-align:left">
      <p>_TCP Synfloods - an old yet current problem_
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">21/9</td>
      <td style="text-align:left"><b>Fuzzing intro</b></td>
      <td style="text-align:left">
      <p>AoST chapters 10,11,12 - ca 65 pages</b></p>
      <p>Browse: _Bug Attacks on RSA_, _Flipping Bits in Memory Without Accessing Them: An Experimental Study of DRAM Disturbance Errors_ and _Using Memory Errors to Attack a Virtual Machine_ </p></td>
    </tr>
    <tr>
      <td style="text-align:left">26/9</td>
      <td style="text-align:left"><b>Security Design and Defense</b>
      </td>
      <td style="text-align:left">
      <p> Security by Design Principles, OWASP https://www.owasp.org/index.php/Security_by_Design_Principles
      Wikipedia Privacy by Design https://en.wikipedia.org/wiki/Privacy_by_design . WAS chapters chapters 17-21, very short chapters </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">28/9</td>
      <td style="text-align:left"><b>General questions and summary</b></td>
      <td style="text-align:left">
      <p>We will do a practice exam and talk about exam subjects.</p>
      </td>
    </tr>
  </tbody>
</table>

This plan will make us read parts of the books.  Only chapters listed will be part of the exam. The rest is left as an optional reading.

**Introduction and Welcome**

* Create a good starting point for learning
* Introduce lecturer and students
* Expectations for this course
* Literature list walkthrough
* Prepare tools for the exercises
* Kali and Debian Linux introduction

Debian and Kali Linux are toolboxes we will use and participants will use virtual machines

Exercises
* Debian Linux installation
* Kali Linux installation

**Overview, Programming Knowledge and Lab Setup**


Initial Overview of Software Security
* Introduction to Methods
* Strategies for Security Testing

Get lab environment ready
* Linux introduction and familiarisation
* Introduce Python programming
* Run programs, servers and applications, how to
* Find the level of programming in the group

Exercises
* Run small programs: Python, Shell script
* Run parts of a Django tutorial
* Setup JuiceShop environment, app and proxy

**Initial Overview of Software Security**

* Design vs Implementation
* Common  Secure Design Issues
* Poor Use of Cryptography
* Input Validation
* Basic Cryptography introduction
* Symmetric Cryptosystems
* Data Encryption Standard (DES) / Advanced Encryption Standard (AES)
* Public Key Cryptography
* Stream and Block Ciphers

Exercises

* sslscan scan various sites for TLS settings, Qualys SSLLabs
* Buffer Overflow 101

**SDLC and Risk Ranking**

* Software Development Lifecycle
* Secure Software Development Lifecycle
* Phases of SSDL
* Roles and Responsibilities

Exercises
* Choose a few real vulnerabilities, prioritize them


**Web Application Hacking Intro**

* Generic Network Fault Injection
* Attacking Authentication
* Session IDs
* Common web application issues

Exercises
* Try a few attacks in the JuiceShop with web proxy


**Fuzzing Intro**

* What is Fuzzing
* Example fuzzers
* Web fuzzing
* Exploitability

Exercises
* Try Wireshark for decoding protocols
* Try American fuzzy lop [http://lcamtuf.coredump.cx/afl/](http://lcamtuf.coredump.cx/afl/)


**Software Programming & Memory Corruption**

* Memory Corruption Errors
* Buffer overflows, stack errors
* C language issues

Exercises
* Pointers and Structure padding


**Program Building blocks**

* Common constructs
* Recurring code patterns
* Example programs with flaws: OpenSSH, OpenSSL, Windows MS-RPC DCOM, Linux teardrop

Exercises
* Work through some of the examples from the book on the white board, what really happened


**Strings and Metacharacters**

* Processing strings
* C String handling
* Metacharacters
* Character sets and unicode

Exercises
* Recommendations for handling strings, how does Python help, how does Django handle strings, and input validation


**Network Attacks Intro**

* Internet Protocol
* TCP and UDP
* Firewalls and related issues
* Intrusion Detection
* Host and Networks Based Intrusion Detection (HIDS/NIDS)
* Network Security Monitoring

Exercises
* SYN flooding exercise


**Network Attacks**

* Auditing Application Protocols
* Example protocols and vulnerabilities
* ASN.1 problems
* Examples from AoSSA chapters 17 and 18

Exercises
* Examples from AoSSA chapters 17 and 18


**Software Assessment**

* Review using the red book, similarities to green book
* Repetition, common problems, how to improve software security
* How to do Review and audit of software
* Attack and Response
* Attack graphs
* Attack surfaces, and reducing them
* Common Vulnerabilities and Exposure CVE
* Common Weakness Enumeration CWE
* MITRE ATT&CK framework


Exercises
* Layout a plan for securing the Juice Shop

**Security Design**

* How to reach the goal of secure design
* Security Principles for software
* Principle of least privilege, fail-safe defaults, separation of privilege etc.
* Files, objects, users, groups and roles
* Security by Design
* Privacy by Design
* Benchmarking standards
* CIS controls Center for Internet Security

Exercises
* How should software be designed today


**General questions and summary**

* Summary of the course

Exercises

* Practice Exam
