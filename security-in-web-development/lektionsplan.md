---
description: elective Security in Web Development (10 ECTS)
---

# Lecture plan

## Elective Security in Web Development \(10 ECTS\)


Teacher: Henrik Kramselund Jereminsen xhek@kea.dk +45 2026 6000


This document is written on Gitbook, and then exported to PDF.

https://zencurity.gitbook.io/kea-it-sikkerhed/security-in-web-development/lektionsplan


### Goals

The module is centered around security in web development including software quality, software flaws, vulnerabilities, software APIs, error handling and software architecture.


### Course description

Security in web development is designed to give the students an idea of some of the challenges that web
developers face when implementing web applications. It also gives some suggestions on how to handle these
challenges, and what to be especially aware of.


### Learning Goals

* Understand basic web application security concepts
* Understand how hackers exploit web applications
* Understand the principle of layered security
* Spot potential security flaws in web applications
* Use best practice on some web security challenges

### Content

* Hacking in general
* History, cases, vulnerability info etc
* Basic Applied Cryptography
  * Symmetric and asymmetric encryption
  * TLS (create certificate and install it on server)
  * Hashing and salting
* Security principles, least privilege etc.
* Security touchpoints

* Attack patterns
 * SQL injection, XSS, XXE, XSRF, Client side manipulation, Session hijacking, DoS, DDoS
 * Linux security
   * Basic CLI (folders, privileges), basic firewall (iptables/ufw), basic servers (SSH, Apache, MySQL, Nginx)
   * Server security settings (Apache, Nginx)

Teaching material will primarily be English.

### Exam:

Date to be entered here 2022

### Teaching Methods:

* Lecture lessons
* Group exercises and cases, including practical exercises with laptop

### Teaching dates - F2022:

1/2, 8/2, 15/2, 22/2, 1/3, 8/3, 15/3, 22/3, 29/3, 5/4, 19/4, 26/4, 3/5, 10/5, 17/5

Make sure to mark dates in your calendar.

### Hardware

Since we are going to be doing exercises, each team will need two virtual machines.

The following are two recommended models:
* One based on Debian, running software servers and web applications
* One based on Kali Linux, running attacks against software

Read more about these at [https://github.com/kramse/kramse-labs](https://github.com/kramse/kramse-labs)


### Course reading list

This course uses one books and a number of supporting resources.

Primary literature:

* Web Application Security, Andrew Hoffman, 2020, ISBN: 9781492053118 called WAS below

This book is currently available for "free" if you give your email address:
https://www.nginx.com/resources/library/web-application-security/


It is recommended to buy the _Pwning OWASP Juice Shop_ Official companion guide to the OWASP Juice Shop, but it is also available online for free.

From [https://leanpub.com/juice-shop](https://leanpub.com/juice-shop) - suggested price USD 5.99


Supporting literature:


* Linux Basics for Hackers Getting Started with Networking, Scripting, and Security in Kali by OccupyTheWeb, December 2018, 248 pp. ISBN-13: 978-1-59327-855-7 - shortened LBfH

This book introduces the Linux operating system commands, using Kali Linux as example. The tools presented include a lot of generic Unix tools. If you have no experience with Linux or Unix it is recommended to buy this book.

Books about the virtual machines we will run

* The Debian Administrator’s Handbook, Raphaël Hertzog and Roland Mas
[https://debian-handbook.info/](https://debian-handbook.info/) - shortened DEB

* Kali Linux Revealed  Mastering the Penetration Testing Distribution [https://www.kali.org/download-kali-linux-revealed-book/](https://www.kali.org/download-kali-linux-revealed-book/) - shortened KLR

We will also use the OWASP Juice Shop Tool Project as a running example. This is an application which is modern AND designed to have security flaws.

Read more about this project at [https://www.owasp.org/index.php/OWASP_Juice_Shop_Project](https://www.owasp.org/index.php/OWASP_Juice_Shop_Project) and
[https://github.com/bkimminich/juice-shop](https://github.com/bkimminich/juice-shop)

Multiple older resources are also interesting for programmers.

* The Web Application Hacker's Handbook: Finding and Exploiting Security Flaws 2nd Edition, Dafydd Stuttard  (Author), Marcus Pinto (Author) ISBN: 978-1118026472

* Hacking Web Apps, Mike Shema ISBN: 978-1-59749-951-4, 2012, Syngress

* 24 Deadly Sins of Software Security: Programming Flaws and How to Fix Them, Michael Howard, David LeBlanc, John Viega, ISBN: 9780071626750, 2010 The McGraw-Hill Companies Additional software security problems, listed language agnostically and with small examples. Highly recommended for programmers.


Supporting Internet resources

Also the course will use internet links and pages. These can be downloaded from the internet often for free and may be gathered by the instructor for easy download.

These are not part of the curriculum for this course, but are considered important references. It is recommended to skim, browse them and familiarize yourself with the content.

System Design and Architecture

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
* _The Debian Administrator’s Handbook_, Raphaël Hertzog and Roland Mas can be downloaded from https://debian-handbook.info/
* _Kali Linux Revealed  Mastering the Penetration Testing Distribution_ available from [https://www.kali.org/](https://www.kali.org) - shortened KLR


Exploiting Hardware Bugs and Crypto Related
* _RFC5246 The Transport Layer Security (TLS)_ https://tools.ietf.org/html/rfc5246
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
      <td style="text-align:left">1/2</td>
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
         <p> Identification of chapters and sections from DEB, KLR and LBfH<br>
        for reading as home assignment </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">8/2</td>
      <td style="text-align:left"><b>Hacking in General</b><p>Initial Overview of Software Security </p>
      <p>Do some initial hacking</p></td>
      <td style="text-align:left">
      <p>Curriculum: WAS Preface and chapter 1</p>
      <p>Supporting litterature: </p>      </td>
    </tr>
    <tr>
      <td style="text-align:left">15/2</td>
      <td style="text-align:left"><b></b>
      <p>Get an overview of the subject</p></td>
      <td style="text-align:left">
      <p>Curriculum: WAS chapter </p>
      <p>Supporting litterature: </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">22/2</td>
      <td style="text-align:left"><b></b>
      <p>Get an overview of the subject</p></td>
      <td style="text-align:left">
      <p>Curriculum: </p>
      <p>Supporting litterature: </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">1/3</td>
      <td style="text-align:left"><b>Web Application Security: Recon</b></td>
      <td style="text-align:left">
      <p></p>
      <p>Look at: Getting started with Burp Suite [https://portswigger.net/support/getting-started-with-burp-suite](https://portswigger.net/support/getting-started-with-burp-suite)</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">8/3</td>
      <td style="text-align:left"><b>Web Application Security: Recon and Offensive</b></td>
      <td style="text-align:left">
      <p>WAS chapters 1-8, very short chapters </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">15/3</td>
      <td style="text-align:left"><b>Hacking Web Applications: Offensive</b></td>
      <td style="text-align:left">
      <p>WAS chapters 9-16, very short chapters</p>
      <p>Browse: _Secure Coding Best Practices Handbook Veracode_</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">22/3</td>
      <td style="text-align:left"><b>Software Programming & Memory Corruption</b></td>
      <td style="text-align:left">
      <p></p>
      <p>Browse: Smashing The Stack For Fun And Profit, Aleph One,
Bypassing non-executable-stack during exploitation using return-to-libc
by c0ntex, Basic Integer Overflows by blexim.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">29/3</td>
      <td style="text-align:left"><b>Program Building blocks and exploitation</b></td>
     <td style="text-align:left">
     <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">5/4</td>
      <td style="text-align:left"><b>Strings and Pointers</b></td>
      <td style="text-align:left">
      <p></p>
      <p>Browse: _Return-Oriented Programming:Systems, Languages, and Applications_ and _Removing ROP Gadgets from OpenBSD_</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">5/10</td>
      <td style="text-align:left"><b>Network Attacks Intro</b></td>
      <td style="text-align:left">
      <p>Hacking chapter 4 browse!</p>
      <p>_TCP Synfloods - an old yet current problem_
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">19/4</td>
      <td style="text-align:left"><b>Fuzzing intro</b></td>
      <td style="text-align:left">
      <p></p>
      <p>Browse: _Bug Attacks on RSA_, _Flipping Bits in Memory Without Accessing Them: An Experimental Study of DRAM Disturbance Errors_ and _Using Memory Errors to Attack a Virtual Machine_ </p></td>
    </tr>
    <tr>
      <td style="text-align:left">26/4</td>
      <td style="text-align:left"><b>Security Design and Defense</b>
      </td>
      <td style="text-align:left">
      <p> Security by Design Principles, OWASP https://www.owasp.org/index.php/Security_by_Design_Principles
      Wikipedia Privacy by Design https://en.wikipedia.org/wiki/Privacy_by_design . WAS chapters chapters 17-21, very short chapters </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">3/5</td>
      <td style="text-align:left"><b>   </b></td>
      <td style="text-align:left">
      <p>.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">10/5</td>
      <td style="text-align:left"><b></b></td>
      <td style="text-align:left">
      <p>.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">17/5</td>
      <td style="text-align:left"><b>General questions and summary</b></td>
      <td style="text-align:left">
      <p>We will do a practice exam and talk about exam subjects.</p>
      </td>
    </tr>
  </tbody>
</table>

Only chapters listed will be part of the exam. The rest is left as an optional reading.
