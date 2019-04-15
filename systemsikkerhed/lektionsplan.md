---
description: Valgfrie modul  VF1 Systemsikkerhed (10 ECTS) System Security
---

# Lektionsplan

## Fagets titel: VF1 Systemsikkerhed \(10 ECTS\)

English: Computer Systems Security

Teacher: Henrik Lund Kramshøj hlk@zencurity.com +45 2026 6000

This document is written on Gitbook, and then exported to PDF.
https://zencurity.gitbook.io/kea-it-sikkerhed/systemsikkerhed/lektionsplan

The PDF export seem to have problems with the big table, please check the Gitbook version if in doubt about reading list.

### Goals

The module is centered around the design and implementation of secure computer systems.
 Topics include operating system (OS) security, capabilities, information flow control, and more.

Teaching material will primarily be English, but the teaching will be in Danish.

See more about the course in the official curriculum.

### Exam:

Dates: tuesday 25/06 exam

### Teaching Methods:

* Lecture lessons
* Group exercises and cases, including practical exercises with laptop

Teaching dates: tuesdays and thursdays
23/04, 25/04, 30/04, 02/05, 07/05, 09/05, 14/05, 16/05, 21/05, 23/05, 28/05, 04/06, 06/06, 11/06, 13/06

### Course reading list

This course uses three books and a number of supporting resources.

Primary literature:

* Computer Security: Art and Science, Matt Bishop ISBN: 9780321712332

Supporting literature:

* Linux Basics for Hackers Getting Started with Networking, Scripting, and Security in Kali by OccupyTheWeb, December 2018, 248 pp. ISBN-13: 978-1-59327-855-7 - shortened LBfH

It is recommended to buy these books.

Also the course will use internet links and pages. Some inspired by other courses on the same subjects, like https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-858-computer-systems-security-fall-2014/related-resources/

Supporting Internet resources
* Kali Linux Revealed  Mastering the Penetration Testing Distribution [https://www.kali.org/download-kali-linux-revealed-book/](https://www.kali.org/download-kali-linux-revealed-book/) - shortened KLR

Control Hijacking Attacks
* [Smashing The Stack For Fun And Profit)](http://www.phrack.com/issues.html?issue=49&id=14#article), Aleph One
* [Bypassing non-executable-stack during exploitation using return-to-libc](http://css.csail.mit.edu/6.858/2014/readings/return-to-libc.pdf)
 by c0ntex.
* [Basic Integer Overflows](http://www.phrack.com/issues.html?issue=60&id=10#article) by blexim.
* [Return-Oriented Programming:Systems, Languages, and Applications](https://hovav.net/ucsd/dist/rop.pdf)
Ryan Roemer, Erik Buchanan, Hovav Shacam and Stefan Savage University of California, San Diego

OS Security
* [Secure Programming for Linux and Unix HOWTO](http://www.dwheeler.com/secure-programs/)), David Wheeler.
* [Setuid demystified](http://www.cs.berkeley.edu/~daw/papers/setuid-usenix02.pdf) by Hao Chen, David Wagner, and Drew Dean.
* [Some thoughts on security after ten years of qmail 1.0](http://cr.yp.to/qmail/qmailsec-20071101.pdf) Daniel J. Bernstein.
* [Wedge: Splitting Applications into Reduced-Privilege Compartments](http://css.csail.mit.edu/6.858/2014/readings/wedge.pdf) by Andrea Bittau, Petr Marchenko, Mark Handley, and Brad Karp.
* [Capsicum: practical capabilities for UNIX](https://www.usenix.org/legacy/event/sec10/tech/full_papers/Watson.pdf) Robert N. M. Watson University of Cambridge, Jonathan Anderson University of Cambridge, Ben Laurie Google UK Ltd., Kris Kennaway Google UK Ltd.
* [Removing ROP Gadgets from OpenBSD](https://www.openbsd.org/papers/asiabsdcon2019-rop-paper.pdf) Todd Mortimer mortimer@openbsd.org

Exploiting Hardware Bugs and Crypto Related
* [Bug Attacks on RSA](http://www.cs.technion.ac.il/~yanivca/BugAttacks.pdf), by Eli Biham, Yaniv Carmeli, and Adi Shamir.
* [Using Memory Errors to Attack a Virtual Machine](https://www.cs.princeton.edu/~appel/papers/memerr.pdf) by Sudhakar Govindavajhala and Andrew Appel
* _A Graduate Course in Applied Cryptography_ By Dan Boneh and Victor Shoup  [https://toc.cryptobook.us/](https://toc.cryptobook.us/) [https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup\_0\_4.pdf](https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup_0_4.pdf)

CPU Protections
* [Intel Memory Protection Extensions](http://software.intel.com/en-us/articles/using-intel-mpx-with-the-intel-software-development-emulator)
* [Intel 80386 Programmer's Reference Manual](http://css.csail.mit.edu/6.858/2014/readings/i386/toc.htm), 1987. Alternatively, in [PDF](http://css.csail.mit.edu/6.858/2014/readings/i386.pdf). Much shorter than the full current Intel architecture manuals below, but often sufficient.
[Intel Architecture Software Developer Manuals](http://www.intel.com/content/www/us/en/processors/architectures-software-developer-manuals.html).

Computer Forensics
* ENISA Presenting, correlating and filtering various feeds Handbook, Document for teachers [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/presenting-correlating-and-filtering-various-feeds-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/presenting-correlating-and-filtering-various-feeds-handbook)
* ENISA Forensic analysis, Network Incident Response [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/2016-resources/exe2\_forensic\_analysis\_ii-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/2016-resources/exe2_forensic_analysis_ii-handbook)
* ENISA Network Forensics, Handbook, Document for teachers [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/network-forensics-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/network-forensics-handbook)

Policies, governance and best Practice
* [Campus Network Security: High Level Overview](https://nsrc.org/workshops/2018/myren-nsrc-cndo/networking/cndo/en/presentations/Campus_Security_Overview.pdf) , Network Startup Resource Center  
* [Campus Operations Best Current Practice](https://nsrc.org/workshops/2018/tenet-nsrc-cndo/networking/cndo/en/presentations/Campus_Operations_BCP.pdf), Network Startup Resource Center  
* [Mutually Agreed Norms for Routing Security (MANRS)](https://www.manrs.org/wp-content/uploads/2018/09/MANRS_PDF_Sep2016.pdf)


## Planning

The detailed plan is below with a table summarizing lessons

UNFINISHED, papers listed above will be added soon


<table>
  <thead>
    <tr>
      <th style="text-align:left)Dato</th>
      <th style="text-align:left)Theme</th>
      <th style="text-align:left)Goal</th>
      <th style="text-align:left)Litterature / Preparation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left)23/4</td>
      <td style="text-align:left)
        <p>Welcome, goals and expectations</br>
        Prepare Kali Linux VM - bring laptop</p>
      </td>
      <td style="text-align:left)
        <p>Create a good starting point for learning </br>
         Introduce lecturer and students </br>
         Concrete Expectations </br>
         Prepare tools for the exercises </p>
      </td>
      <td style="text-align:left)
      <p> Reviewing the literature list will occur when we meet. </p>
         <p> Download Kali Linux Revealed </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left)25/4</td>
      <td style="text-align:left)<b>Overview of Computer Security</b>
      </td>
      <td style="text-align:left)         </td>
      <td style="text-align:left)
      <p>Bishop chapters 1 and 2 - ca 50 pages</br>

      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left)30/4</td>
      <td style="text-align:left)<b>Computer Security Models</b>
      </td>
      <td style="text-align:left)         </td>
      <td style="text-align:left)
      <p>Bishop chapters 3 - ca 55 pages</br>

      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left)2/5</td>
      <td style="text-align:left)<b>Security Policies / Confidentiality Policies</b>
      </td>
      <td style="text-align:left)         </td>
      <td style="text-align:left)
      <p>Bishop chapters 4 and 5 - ca 65 pages</br>
      Appendix G</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left)7/5</td>
      <td style="text-align:left)<b>integrity and Availability Policies</b>
      </td>
      <td style="text-align:left)         </td>
      <td style="text-align:left)
      <p>Bishop chapters 6 and 7 - ca 55 pages</br>

      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left)9/5</td>
      <td style="text-align:left)<b>Hybrid Policies</b>
      </td>
      <td style="text-align:left)         </td>
      <td style="text-align:left)
      <p>Bishop chapters 8 and 9 - ca 60 pages</br>

      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left)14/5</td>
      <td style="text-align:left)<b>Malware, Intrusion, Vulnerabilities</b>
      </td>
      <td style="text-align:left)</td>
      <td style="text-align:left)
      <p>Bishop chapters 23 and 24 - ca 105 pages</br>

      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left)16/5</td>
      <td style="text-align:left)<b>Basic Cryptography</b>
      </td>
      <td style="text-align:left)         </td>
      <td style="text-align:left)
      <p>Bishop chapters 10,12,13</br>
      Skim chapter 11 Key management. Total - ca 164 pages</p>
      </td>
    </tr>    <tr>
      <td style="text-align:left)21/5</td>
      <td style="text-align:left)<b>Secure Systems Design and Implementation</b>
      </td>
      <td style="text-align:left)         </td>
      <td style="text-align:left)
      <p>Bishop chapters 14,15,16 - ca 85 pages</br>

      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left)23/5</td>
      <td style="text-align:left)<b>Information Flow</b>
      </td>
      <td style="text-align:left)         </td>
      <td style="text-align:left)
      <p>Bishop chapters 17 and 18 - ca 85 pages</br>

      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left)28/5</td>
      <td style="text-align:left)<b>Forensics 1: Auditing and Intrusion Detection</b>
      </td>
      <td style="text-align:left)         </td>
      <td style="text-align:left)
      <p>Bishop chapters 25 and 26 - ca 80 pages</br>

      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left)4/6</td>
      <td style="text-align:left)<b>Forensics 2: Incident Response</b>
      </td>
      <td style="text-align:left)         </td>
      <td style="text-align:left)
      <p>Bishop chapter 27 - ca 40 pages</br>

      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left)6/6</td>
      <td style="text-align:left)<b>System Security in Practice</b>
      </td>
      <td style="text-align:left)         </td>
      <td style="text-align:left)
      <p>Bishop chapters 28,29,30 - ca 95 pages</br>

      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left)11/6</td>
      <td style="text-align:left)<b>Benchmarking and Auditing Recap</b>
      </td>
      <td style="text-align:left)         </td>
      <td style="text-align:left)
      <p>Paper <em>CIS Controls</em>
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left)13/6</td>
      <td style="text-align:left)<b>Summary and prepare for the exam</b></td>
      <td style="text-align:left)Summary of the course</td>
      <td style="text-align:left)</td>
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
