---
description: Valgfrie modul VF 3 Netværkspenetrationstest (5 ECTS) Penetration testing
---

# Lektionsplan

## Fagets titel: VF 3 Netværkspenetrationstest \(5 ECTS\)

English: Penetration testing

Teacher: Henrik Lund Kramshøj hlk@zencurity.dk +45 2026 6000

This document is written in markdown, uploadet to GitHub and then processed by Gitbook.

The link for this is:
https://zencurity.gitbook.io/kea-it-sikkerhed/penetrationstest/lektionsplan

### Goals

The module is centered around penetration testing and executing penetration testing. You will be expected to be able to perform basic penetration testing, and gather information about new vulnerabilities. You will be presented for and expected to execute relevant tools for this purpose.

Teaching material will primarily be English, but the teaching will be in Danish.

See more about the course in the official curriculum which can be downloaded from the main page [https://kompetence.kea.dk/uddannelser/it-digitalt/diplom-i-it-sikkerhed](https://kompetence.kea.dk/uddannelser/it-digitalt/diplom-i-it-sikkerhed)
- near the top "Download studieordningen".

### Exam:

Date 17/12 2019

### Teaching Methods:

* Lecture lessons
* Group exercises and cases, including practical exercises with laptop

Teaching dates: 24/10 2019, 05/11 2019, 07/11 2019, 14/11 2019, 21/11 2019, 28/11 2019, 05/12 2019

### Course reading list

This course uses a few books and a number of supporting resources.

Primary literature:

* Gray Hat Hacking: The Ethical Hacker's Handbook, fifth edition
Allen Harper ISBN: 9781260108415
* Linux Basics for Hackers Getting Started with Networking, Scripting, and Security in Kali by OccupyTheWeb, December 2018, 248 pp. ISBN-13: 978-1-59327-855-7 - shortened LBfH

It is recommended to buy these books.

The book LBfH introduces the Linux operating system commands, using Kali Linux as example. The tools presented include a lot of generic Unix tools. If you have no experience with Linux or Unix it is recommended to buy this book.


Supporting literature:

* Kali Linux Revealed  Mastering the Penetration Testing Distribution [https://www.kali.org/download-kali-linux-revealed-book/](https://www.kali.org/download-kali-linux-revealed-book/) - shortened KLR
* More to come


We will also use the OWASP Juice Shop Tool Project as a running example. This is an application which is modern AND designed to have security flaws.

Read more about this project at [https://www.owasp.org/index.php/OWASP_Juice_Shop_Project](https://www.owasp.org/index.php/OWASP_Juice_Shop_Project) and
[https://github.com/bkimminich/juice-shop](https://github.com/bkimminich/juice-shop)


It is recommended to buy the _Pwning OWASP Juice Shop_
Official companion guide to the OWASP Juice Shop.

From [https://leanpub.com/juice-shop](https://leanpub.com/juice-shop) - suggested price USD 5.99


Most of these can be downloaded from the internet.

Also the course will use internet links and pages.



Supporting Internet resources

System Design and Architecture
* [Security by Design Principles, OWASP](https://www.owasp.org/index.php/Security_by_Design_Principles)

Control Hijacking Attacks
* [Smashing The Stack For Fun And Profit](http://www.phrack.com/issues.html?issue=49&id=14#article), Aleph One
* [Bypassing non-executable-stack during exploitation using return-to-libc](http://css.csail.mit.edu/6.858/2014/readings/return-to-libc.pdf)
 by c0ntex.
* [Basic Integer Overflows](http://www.phrack.com/issues.html?issue=60&id=10#article) by blexim.
* [Return-Oriented Programming:Systems, Languages, and Applications](https://hovav.net/ucsd/dist/rop.pdf)
Ryan Roemer, Erik Buchanan, Hovav Shacam and Stefan Savage University of California, San Diego
* [MITRE ATT&CK](https://attack.mitre.org/) a globally-accessible knowledge base of adversary tactics and techniques based on real-world observations, read the [ATT&CK 101 Blog Post](https://medium.com/mitre-attack/att-ck-101-17074d3bc62)

* [Removing ROP Gadgets from OpenBSD](https://www.openbsd.org/papers/asiabsdcon2019-rop-paper.pdf) Todd Mortimer mortimer@openbsd.org



Policies, governance and best Practice
* [Campus Network Security: High Level Overview](https://nsrc.org/workshops/2018/myren-nsrc-cndo/networking/cndo/en/presentations/Campus_Security_Overview.pdf) , Network Startup Resource Center  
* [Campus Operations Best Current Practice](https://nsrc.org/workshops/2018/tenet-nsrc-cndo/networking/cndo/en/presentations/Campus_Operations_BCP.pdf), Network Startup Resource Center  
* [CIS Controls](https://learn.cisecurity.org/cis-controls-download) Requires giving your email
* [PCI Best Practices for Maintaining PCI DSS Compliance v2.0 Jan 2019](https://www.pcisecuritystandards.org/documents/PCI_DSS_V2.0_Best_Practices_for_Maintaining_PCI_DSS_Compliance.pdf?agreement=true&time=1555354264656)
* [NIST Special Publication 800-63B Digital Identity Guidelines: Authentication and Lifecycle Management](https://pages.nist.gov/800-63-3/sp800-63b.html)
* [IT Security Guidelines for Transport Layer Security (TLS)](https://english.ncsc.nl/publications/publications/2019/juni/01/it-security-guidelines-for-transport-layer-security-tls)



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
      <td style="text-align:left">24/10</td>
      <td style="text-align:left">
        <p>Welcome, goals and expectations</br>
        Prepare Virtual Machines - bring laptop</p>
        <p>Create a good starting point for learning </br>
         Introduce lecturer and students </br>
         Concrete Expectations </br>
         Prepare tools for the exercises.<b>Lab setup</b> </p>
      </td>
      <td style="text-align:left">
      <p> Reviewing the literature list will occur when we meet. </p>
         <p> Download Kali Linux Revealed </p>
         <p> Identification of chapters and sections from KLR and LBfH<br>
        for reading as home assignment </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">5/11</td>
      <td style="text-align:left"><p><b>Ethics and executing pentest</b></p></td>
      <td style="text-align:left">
      <p></p>
      <p>Curriculum Grayhat chapters 1,6-9</p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">7/11</td>
      <td style="text-align:left"><p><b>Programming and basic buffer overflows</b></p></td>
      <td style="text-align:left">
      <p>Curriculum: Grayhat chapters 2-3,11</p>
      <p>Supporting litterature: </p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">14/11</td>
      <td style="text-align:left"><p><b>Network spoofing and Cracking Passwords</b></p></td>
      <td style="text-align:left">
      <p>Curriculum: Grayhat chapters 10,15</p>
      <p>Supporting litterature: </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">21/11</td>
      <td style="text-align:left"><p><b>Network Attacks and Advanced Vulnerabilities</b></p></td>
      <td style="text-align:left">
      <p>Curriculum: Grayhat chapters 12-14</p>
      <p>Supporting litterature: </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">28/11</td>
      <td style="text-align:left"><p><b>Web Application Hacking</b> - and some IoT</p></td>
      <td style="text-align:left">
      <p>Grayhat chapters Skim 22-25</p>
      <p>Supporting litterature: </p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">5/12</td>
      <td style="text-align:left"><p><b>Managing Pentests and Vulnerabilities</b></p></td>
      <td style="text-align:left">
      <p>Supporting litterature: Familiarize yourself with sources listed above at _Policies, governance and best Practice_. Will also run some Metasploit to to everything together</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">17/12</td>
      <td style="text-align:left"><b>Exam date</b></td>
     <td style="text-align:left">
     <p></p>
      </td>
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
