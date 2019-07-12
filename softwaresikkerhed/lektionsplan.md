---
description: Obligatoriske modul  OB2 Softwaresikkerhed (10 ECTS) Software Security
---

# Lektionsplan

## Fagets titel: OB2 Softwaresikkerhed \(10 ECTS\)

English: Software Security

Teacher: Henrik Lund Kramshøj hlk@zencurity.com +45 2026 6000

This document is written on Gitbook, and then exported to PDF.
https://zencurity.gitbook.io/kea-it-sikkerhed/softwaresikkerhed/lektionsplan

The PDF export seem to have problems with the big table, please check the Gitbook version if in doubt about reading list.

### Goals

The module is centered around software security including software quality, software flaws, vulnerabilities, software APIs, error handling and software architecture.

Teaching material will primarily be English, but the teaching will be in Danish.

See more about the course in the official curriculum.

### Exam:

Date 22/10 2019

### Teaching Methods:

* Lecture lessons
* Group exercises and cases, including practical exercises with laptop

Teaching dates:
27/8 2019, 29/8 2019, 3/9 2019, 10/9 2019, 11/9 2019, 12/9 2019, 17/9 2019, 19/9 2019, 24/9 2019, 1/10 2019, 3/10 2019, 8/10 2019, 9/10 2019, 10/10 2019

Make sure to mark dates in your calendar - some weeks will have lessons tuesday/thursdays, some weeks will have three days in a row - tuesday, wednesday, thursday.

### Hardware

Since we are going to be doing exercises, each team will need two virtual machines.

The following are two recommended models:
* One based on Debian 9, running software servers and web applications
* One based on Kali Linux, running attacks against software

Read more about these at [https://github.com/kramse/kramse-labs](https://github.com/kramse/kramse-labs)


### Course reading list

This course uses three books and a number of supporting resources.

Primary literature:

* The Art of Software Security Assessment Identifying and Preventing
Software Vulnerabilities
Mark Dowd, John McDonald, Justin Schuh ISBN: 9780321444424, AoSSA
* The Art of Software Security Testing Identifying Software Security Flaws
Chris Wysopal ISBN: 9780321304865, AoST

It is recommended to buy these books.

Supporting literature:

* Linux Basics for Hackers Getting Started with Networking, Scripting, and Security in Kali by OccupyTheWeb, December 2018, 248 pp. ISBN-13: 978-1-59327-855-7 - shortened LBfH
* Kali Linux Revealed  Mastering the Penetration Testing Distribution [https://www.kali.org/download-kali-linux-revealed-book/](https://www.kali.org/download-kali-linux-revealed-book/) - shortened KLR
* More to come

These can be downloaded from the internet for free and may be gathered by the instructor for easy download.

Also the course will use internet links and pages.


## Planning

The detailed plan is below with a table summarizing lessons.

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
      <p>Linux introduction and familiarisation </p><p>AoST chapters 1,2,3,4,5 - ca 100 pages - start reading the book. Dont need to read all before the day.</p><p> Also start reading first chapters of the AoSSA</p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">3/9</td>
      <td style="text-align:left"><b>Initial overview, SDLC and risk ranking</b>
<p>Get an overview of the subject</p></td>
      <td style="text-align:left">
      <p>This week AoSSA chapters 1,2,3,4 approx 150 pages.</p><p>Also begin reading 6,5,7,8</p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">10/9</td>
      <td style="text-align:left"><b>Software Programming</b>
      </td>
      <td style="text-align:left">
      <p>This week AoSSA chapters 6,5 approx 129 pages.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">11/9</td>
      <td style="text-align:left"><b>Building blocks</b></td>
      <td style="text-align:left">
      <p>This week AoSSA chapter 7 approx 90 pages.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">12/9</td>
      <td style="text-align:left"><b>Strings and Metacharacters</b></td>
      <td style="text-align:left">
      <p>This week AoSSA chapter 8 approx 70 pages.</p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">17/9</td>
      <td style="text-align:left"><b>Unix architecture and examples</b>
      </td>
      <td style="text-align:left">
      <p>AoSSA chapters 9,10 approx 166 pages. Skim reading!</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">19/9</td>
      <td style="text-align:left"><b>Windows architecture and examples</b></td>
      <td style="text-align:left">
      <p>AoSSA chapters 11,12 approx 129 pages. Skim reading!</p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">24/9</td>
      <td style="text-align:left"><b>Fuzzing</b>
      </td>
      <td style="text-align:left">
      <p>AoST chapters 10,11,12 approx 65 pages.</p><p>Start reading AoSSA chapters 14,15,16 after tuesday.</p>
      </td>
    </tr>


    <tr>
      <td style="text-align:left">1/10</td>
      <td style="text-align:left"><b>Network Attacks</b></td>
      <td style="text-align:left">
      <p>AoSSA chapters 14,15,16 <b>approx 170 pages!</b></p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">3/10</td>
      <td style="text-align:left"><b>Web application hacking</b>
      </td>
      <td style="text-align:left">
      <p>AoST chapters 6,7,8,9 approx 72 pages.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">8/10</td>
      <td style="text-align:left"><b>Web Applications</b></td>
      <td style="text-align:left">
      <p>This week AoSSA chapters 17,18 approx 120 pages.</p>
      </td>
    </tr>

    <tr>
      <td style="text-align:left">9/10</td>
      <td style="text-align:left"><b>Web Applications</b>
      </td>
      <td style="text-align:left">
      <p>This week AoSSA chapters 17,18 approx 120 pages.</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">10/10</td>
      <td style="text-align:left"><b>Web applications and summary</b></td>
      <td style="text-align:left">
      <p>We will do a practice exam and talk about exam subjects.</p>
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
