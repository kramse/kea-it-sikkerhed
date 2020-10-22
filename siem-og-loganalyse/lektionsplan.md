---
description: Valgfrit modul  VF4 SIEM og log-analyse (5 ECTS)
---

# Lektionsplan

## Fagets titel: VF4 SIEM og log-analyse \(5 ECTS\)

English: SIEM and Log Analysis

Teacher: Henrik Lund Kramshøj hlk@zencurity.com +45 2026 6000

This document is written in markdown, uploadet to GitHub and then processed by Gitbook.

The link for this is:
https://zencurity.gitbook.io/kea-it-sikkerhed/siem-og-loganalyse/lektionsplan

### Goals

The module is centered around Security information and event management (SIEM) and log analysis including common SIEM systems, logging, gathering, processing and working with logs.

Teaching material will primarily be English, but the teaching will be in Danish.

See more about the course in the official curriculum which can be downloaded from the main page [https://kompetence.kea.dk/uddannelser/it-digitalt/diplom-i-it-sikkerhed](https://kompetence.kea.dk/uddannelser/it-digitalt/diplom-i-it-sikkerhed)
- near the top "Download studieordningen".

### Exam:

Date
7/1 2021

### Teaching Methods:

* Lecture lessons
* Group exercises and cases, including practical exercises with laptop

Teaching dates: 26/11 2020, 1/12 2020, 3/12 2020, 8/12 2020, 10/12 2020, 15/12 2020, 17/12 2020

Make sure to mark dates in your calendar - some weeks will have lessons tuesday/thursdays, some weeks will have three days in a row - tuesday, wednesday, thursday.

### Hardware

Since we are going to be doing exercises, each team will need two virtual machines.

The following are two recommended models:
* One based on Debian 9 or 10, running software servers and web applications
* One based on Kali Linux, running attacks against software

Read more about these at [https://github.com/kramse/kramse-labs](https://github.com/kramse/kramse-labs)


### Course reading list

This course uses three books and a number of supporting resources.

Primary literature:

* Data-Driven Security: Analysis, Visualization and Dashboards
Jay Jacobs, Bob Rudis
ISBN: 978-1-118-79372-5 February 2014
https://datadrivensecurity.info/

* Crafting the InfoSec Playbook: Security Monitoring and Incident Response Master Plan
by Jeff Bollinger, Brandon Enright, and Matthew Valites

* Intelligence-Driven Incident Response ISBN: 9781491934944
Scott Roberts		

* Security Operations Center Building, Operating, and Maintaining your SOC
ISBN: 9780134052014 Joseph Muniz

It is recommended to buy these books.

Also the course will use internet links and pages. These can be downloaded from the internet often for free and may be gathered by the instructor for easy download.

Supporting literature:

* Linux Basics for Hackers Getting Started with Networking, Scripting, and Security in Kali by OccupyTheWeb, December 2018, 248 pp. ISBN-13: 978-1-59327-855-7 - shortened LBfH

This book introduces the Linux operating system commands, using Kali Linux as example. The tools presented include a lot of generic Unix tools. If you have no experience with Linux or Unix it is recommended to buy this book.

Installing and running the specific Linux distributions used is described in these books

* The Debian Administrator’s Handbook, Raphaël Hertzog and Roland Mas
[https://debian-handbook.info/](https://debian-handbook.info/) - shortened DEB

* Kali Linux Revealed  Mastering the Penetration Testing Distribution [https://www.kali.org/download-kali-linux-revealed-book/](https://www.kali.org/download-kali-linux-revealed-book/) - shortened KLR


### Supporting Internet resources


Most of these can be downloaded from the internet.

TBD

## Planning

The detailed plan is below with a table summarizing lessons.

**Unfinished - do not trust yet, copied from software security**


**Note: contains lot of pages, learn to skim and skip chapters and parts that don't interest you. In real life we don't have time to read every word!**

<table>
  <thead>
    <tr>
      <th style="text-align:left;width:10%">Week</th>
      <th style="width:45%">Theme / Goals</th>
      <th style="width:45%">Litterature / Preparation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">27/8</td>
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
      <td style="text-align:left">29/8</td>
      <td style="text-align:left"><b>Lab setup and programming knowledge</b><p>Do some initial programming</p></td>
      <td style="text-align:left">
      <p>Linux introduction and familiarisation </p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">3/9</td>
      <td style="text-align:left"><b>Initial Overview of Software Security</b>
<p>Get an overview of the subject</p></td>
      <td style="text-align:left">
      <p>AoST chapters 1,2 - ca 50 pages</p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">10/9</td>
      <td style="text-align:left"><b>SDLC and risk ranking</b>
      </td>
      <td style="text-align:left">
      <p>AoST chapters 3,4,5 - ca 50 pages</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">11/9</td>
      <td style="text-align:left"><b>Web Application Hacking Intro</b></td>
      <td style="text-align:left">
      <p>AoST chapters 6,7,8,9 - ca 72 pages.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">12/9</td>
      <td style="text-align:left"><b>Fuzzing intro</b></td>
      <td style="text-align:left">
      <p>AoST chapters 10,11,12 - ca 65 pages.</p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">17/9</td>
      <td style="text-align:left"><b>Software Programming & Memory Corruption</b></td>
      <td style="text-align:left">
      <p>This week AoSSA chapters 6,5 - ca 129 pages.</p>

      </td>
    </tr>
    <tr>
      <td style="text-align:left">19/9</td>
      <td style="text-align:left"><b>Program Building blocks</b></td>
     <td style="text-align:left">
     <p>AoSSA chapter 7 - ca 90 pages.</p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">24/9</td>
      <td style="text-align:left"><b>Strings and Metacharacters</b></td>
      <td style="text-align:left">
      <p>AoSSA chapter 8 - ca 70 pages.</p>
      </td>
    </tr>


    <tr>
      <td style="text-align:left">1/10</td>
      <td style="text-align:left"><b>Network Attacks Intro</b></td>
      <td style="text-align:left">
      <p>AoSSA chapters 14,15 - ca 90 pages!</p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">3/10</td>
      <td style="text-align:left"><b>Network Attacks</b></td>
      <td style="text-align:left">
      <p>AoSSA chapter 16 - ca 80 pages!</p><p>Will also use examples from chapters 17,18 so browse Table of Contents for those.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">8/10</td>
      <td style="text-align:left"><b>Software Assessment</b></td>
      <td style="text-align:left">
      <p>AoSSA chapters 1,2,3,4 - many pages, skim if you need to.</b></p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">9/10</td>
      <td style="text-align:left"><b>Security Design</b>
      </td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">10/10</td>
      <td style="text-align:left"><b>General questions and summary</b></td>
      <td style="text-align:left">
      <p>We will do a practice exam and talk about exam subjects.</p>
      </td>
    </tr>

  </tbody>
</table>

This plan will make us read all of the green book AoST and parts of the red one AoSSA - the rest is left as an optional reading.

**Introduction and welcome**

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

**Lab setup and programming knowledge**

* Linux introduction and familiarisation
* Learn difference between compiled program C, and scripted Python
* Introduce Python programming
* Run programs, servers and applications, how to
* Find the level of programming in the group

Exercises
* Run small programs: Python, Shell script
* Run parts of a Django tutorial
* Setup JuiceShop environment, app and proxy

**Initial Overview of Software Security**

* Introduction to Methods
* Strategies for Security Testing
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

**SDLC and Risk Ranking**

* Software Development Lifecycle
* Secure Software Development Lifecycle
* Phases of SSDL
* Roles and Responsibilities

Exercises
* Choose a few real vulnerabilities, prioritize them


**Web Application Hacking Intro**

* Generic Fault Injection
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
* Try running brute force and fuzzing
* Try American fuzzy lop [http://lcamtuf.coredump.cx/afl/](http://lcamtuf.coredump.cx/afl/)


**Software Programming & Memory Corruption**

* Memory Corruption Errors
* Buffer overflows, stack errors
* C language issues
* Shell code

Exercises
* Writing and expoloiting a small buffer overflow
* Run debugger


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
