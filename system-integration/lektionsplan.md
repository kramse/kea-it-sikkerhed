---
description: Modul System integration (10 ECTS)
---

# Lecture planning

## Course title: System Integration \(10 ECTS\)

### General information

Teacher: Morten Voetmann Christiansen, morc@kea.dk

Secondary teacher: Henrik Kramselund Jereminsen hkj@zencurity.dk +45 2026 6000


This document is written on Gitbook, and then exported to PDF.
https://zencurity.gitbook.io/kea-it-sikkerhed/system-integration/lektionsplan

Teaching material will primarily be English, but the teaching will be in Danish.

### Goals

This subject element must help ensure that the student develops the competencies to be able to work with technical system integration. After completing this module, the student must be able to integrate existing systems in connection with the development of new systems, and develop new systems supporting future integration.


See more about the course in the official curriculum.

### Exam:

Online exam: xxxx 2021

Deliverables and Exam Procedure

* The course ends with a successful examination. The exam is individual, oral, censored, graded.
* The duration of the exam is up to 30 minutes.
* At the exam students can expect being asked any questions related to the learning objectives and presented material.

Pre-conditions

Students need to fulfill certain requirements  completed mandatory tasks - to qualify for participating in the exam.
Fulfilling the requirements automatically signs the student up for an exam. Alternatively, failing in delivering a mandatory
task on time prevents the student from taking part in the exam.

 Deliverables:
* 2 Mandatory assignments which can be team work up to 3 students
* Both mandatory assignments are required in order to be entitled to the exam


### Teaching Methods:

* Lecture lessons
* Group exercises and cases, including practical exercises with laptop

Teaching dates: mondays 08:15 - 11:45 and 12:30 - 15:00

Watch out for exceptions; March 29., April 5., May 24.

In total 14 days

### Course reading list
This course uses a few books and a number of supporting resources.

Primary literature:

* _Enterprise Integration Patterns_, Gregor Hohpe and Bobby Woolf, 2004
ISBN: 978-0-321-20068-6 EIP for short
* _Camel in action_, Claus Ibsen and Jonathan Anstey, 2018
ISBN: 978-1-61729-293-4
* _Service‑Oriented Architecture: Analysis and Design for Services and Microservices_, Thomas Erl, 2017
ISBN: 978-0-13-385858-7


It is recommended to buy these books. Note: we won't read all chapters and pages.

Also the course will use internet links and pages.

Supporting literature - optional to buy, but recommended:

* _Linux Basics for Hackers Getting Started with Networking, Scripting, and Security in Kali_ by OccupyTheWeb, December 2018, 248 pp. ISBN-13: 978-1-59327-855-7 - shortened LBfH
* _The Debian Administrator’s Handbook_, Raphaël Hertzog and Roland Mas can be downloaded from https://debian-handbook.info/
* _Microservices for Java Developers_ , Christian Posta, 2016 O’Reilly https://www.oreilly.com/programming/free/files/microservices-for-java-developers.pdf


## Exercises

This course will have exercises that you are expected to run. They will require you to access a Linux virtual machine with Debian Linux.

We will spend some time the first day to get you started with this.



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
  <td style="text-align:left">Day 0 Feb 8</td>
  <td style="text-align:left">
    <p>Welcome, goals and expectations</br>
    </p>
  </td>
  <td style="text-align:left">
  <p> Reviewing the literature list will occur when we meet. </p>
  </td>
</tr>
<tr>
  <td style="text-align:left">Day 1 Feb 15</td>
  <td style="text-align:left">
    <p>Integration intro</br>
    Java Apps, Tomcat, XML config, TCP/IP, DNS, HTTP intro<br>
    Git intro
    </p>
  </td>
  <td style="text-align:left">
  <p>EIP book chapter 1-2</p>
  </td>
</tr>
<tr>
  <td style="text-align:left">Day 2 Feb 22</td>
  <td style="text-align:left">
    <p>Starting out with Camel</br>
    </p>
  </td>
  <td style="text-align:left">
  <p>Camel book chapter 1-2</p>
  </td>
</tr>
<tr>
  <td style="text-align:left">Day 3 March 1</td>
  <td style="text-align:left">
    <p>Data overview, XML data, JSON<br>
Data Transformation<br>WebServices, SOAP, WSDL<br>Investigate examples
    </p>
  </td>
  <td style="text-align:left">
  <p>Camel chapter 3</p>
  </td>
</tr>
<tr>
  <td style="text-align:left">Day 4 March 8</td>
  <td style="text-align:left">
    <p>Messaging, MQ systems</br>
    Publish-Subscribe, Enterprise Integration Patterns
    </p>
  </td>
  <td style="text-align:left">
  <p>EIP chapter 3-4, Camel chapter 5</p>
  </td>
</tr>
<tr>
  <td style="text-align:left">Day 5 March 15</td>
  <td style="text-align:left">
    <p>Using components, JMS</br>
    databases
    </p>
  </td>
  <td style="text-align:left">
  <p>EIP chapter 5-6, Camel chapter 6</p>
  </td>
</tr>
<tr>
  <td style="text-align:left">Day 6 March 22</td>
  <td style="text-align:left">
    <p>SOA, EAI, ESB - connecting the dots</br>
    </p>
  </td>
  <td style="text-align:left">
  <p>SOA chapter 1-5</p>
  </td>
</tr>
<tr>
  <td style="text-align:left">Day 7 April 12</td>
  <td style="text-align:left">
    <p>Microservices</p>
  </td>
  <td style="text-align:left">
  <p>SOA chapter 6, Camel chapter 7, Microservices for Java chapter 1</p>
  </td>
</tr>
<tr>
  <td style="text-align:left">Day 8 April 19</td>
  <td style="text-align:left">
    <p>
    REST
    </p>
  </td>
  <td style="text-align:left">
  <p>SOA chapter 7, Camel chapter 10</p>
    </p>
  </td>
</tr>
<tr>
  <td style="text-align:left">Day 9 April 26 </br>4 lessons </td>
  <td style="text-align:left">
    <p> asynchronous and synchronous</br>
    APIs, versioning, contracts</br>
    GRPC, msgpack, protobuf, apache thrift etc.
    </p>
  </td>
  <td style="text-align:left">
  <p>SOA chapter 8,9,10 and Appendix B</p>
  </td>
</tr>
<tr>
  <td style="text-align:left">Day 10 May 3 </br>4 lessons </td>
  <td style="text-align:left">
    <p>Transactions and idempotency</br>
    </p>
  </td>
  <td style="text-align:left">
  <p>Camel chapter 12-13</p>
  </td>
</tr>
<tr>
  <td style="text-align:left">Day 11 May 10 </br>4 lessons </td>
  <td style="text-align:left">
    <p>Integration examples and standards</br>
    Running integration
    Management, Logs, Monitoring, Security - using systems we have used above as examples
    </p>
  </td>
  <td style="text-align:left">
  <p>EIP 13-14 Camel chapter 14-16, SOA Appendix A</p>
  </td>
</tr>
<tr>
  <td style="text-align:left">Day 12 May 17 </br>4 lessons </td>
  <td style="text-align:left">
    <p>Cloud and Cloud integration
    </p>
  </td>
  <td style="text-align:left">
  <p>Camel 18</p>
  </td>
</tr>

<tr>
  <td style="text-align:left">Day 13 May 31 </br>4 lessons </td>
  <td style="text-align:left">
    <p>Cloud and Cloud integration
    </p>
  </td>
  <td style="text-align:left">
  <p>Camel 18</p>
  </td>
</tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"><b>Prepare for the exam</b></td>
      <td style="text-align:left">Summary of the course, prepare for exam</td>
    </tr>
  </tbody>
</table>
