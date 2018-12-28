---
description: Obligatoriske modul Ob 1 Netværks- og kommunikationssikkerhed (10 ECTS)
---

# Lektionsplan UDKAST

## Fagets titel: Ob 1 Netværks- og kommunikationssikkerhed \(10 ECTS\)

Underviser: Henrik Lund Kramshøj hlk@zencurity.com +45 2026 6000

### Formål

Elementet går ud på at forstå og håndtere netværkssikkerhedstrusler samt implementere og konfigurere udstyr til samme.

Elementet omhandler forskellig sikkerhedsudstyr \(IDS\) til monitorering. Derudover vurdering af sikkerheden i et netværk, udarbejdelse af plan til at lukke eventuelle sårbarheder i netværket samt gennemgang af forskellige VPN teknologier.

Undervisningsmateriale vil primært være engelsk, men undervisningen foregår på dansk.

### Litteraturliste

Dette kursus benytter tre bøger og et antal internetresourcer.
Primær litteratur: Applied Network Security Monitoring Collection, Detection, and Analysis, 2017 Chris Sanders ISBN: 9780124172081 forkortes ANSM

Practical Packet Analysis - Using Wireshark to Solve Real-World Network Problems, 3rd edition 2017, Chris Sanders ISBN: 9781593278021 forkortes PPA

Linux Basics for Hackers
Getting Started with Networking, Scripting, and Security in Kali
by OccupyTheWeb, December 2018, 248 pp. ISBN-13: 978-1-59327-855-7 forkortes LBfH

Sekundær litteratur:

* Kali Linux Revealed  Mastering the Penetration Testing Distribution https://www.kali.org/download-kali-linux-revealed-book/
* _Security problems in the TCP/IP protocol suite_, S. M. Bellovin
* _An Evening with Berferd: In Which a Cracker is Lured, Endured, and Studied,_ Bill Cheswick, AT&T Bell Laboratories
* _A Graduate Course in Applied Cryptography_ By Dan Boneh and Victor Shoup  [https://toc.cryptobook.us/](https://toc.cryptobook.us/) [https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup\_0\_4.pdf](https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup_0_4.pdf)
* Strange Attractors and TCP/IP Sequence Number Analysis, Michal Zalewski [http://lcamtuf.coredump.cx/newtcp/](http://lcamtuf.coredump.cx/newtcp/)

Underviseren samler papers så de nemt kan downloades.


### Specificerede læringsmål:

#### Viden

Den studerende har viden om og forståelse for:

* Netværkstrusler
* Trådløs sikkerhed
* Sikkerhed i TCP/IP
* Adressering i de forskellige lag
* Dybdegående kendskab til flere af de mest anvendte internet protokoller \(ssl\)
* Hvilke enheder, der anvender hvilke protokoller
* Forskellige sniffing strategier og teknikker
* Netværk management \(overvågning/logning, snmp\)
* Forskellige VPN setups
* Gængse netværksenheder der bruges ifm. sikkerhed \(firewall, IDS/IPS, honeypot, DPI\).

#### Færdigheder

Den studerende kan:

* Overvåge netværk samt netværkskomponenter, \(f.eks. IDS eller IPS, honeypot\)
* Teste netværk for angreb rettet mod de mest anvendte protokoller
* Identificere sårbarheder som et netværk kan have.

#### Kompetencer

Den studerende kan:

* Håndtere udviklingsorienterede situationer herunder: designe, konstruere og implementere samt teste et sikkert netværk monitorere og administrere et netværks komponenter mht. it-sikkerhed
* Udfærdige en rapport om de sårbarheder et netværk eventuelt skulle have \(red team report\)
* Opsætte og konfigurere et IDS eller IPS.
* kan håndtere relevante krypteringstiltag til sikring af netværkskommunikation

### Eksamensform:

Dato 9. april 2019

### Lektioner

Undervisningsformer:

* Tavleundervisning
* Gruppeøvelser og cases, herunder praktiske øvelser med laptop

Undervisningsdatoer:
05/02 2019, 07/02 2019, 12/02 2019, 14/02 2019, 19/02 2019, 21/02 2019, 26/02 2019, 28/02 2019, 05/03 2019, 07/03 2019, 12/03 2019, 14/03 2019, 19/03 2019, 21/03 2019, 26/03 2019


## Plan

Den detaljerede plan er nedenfor med en tabel der opsummerer undervisningsgange

<table>
  <thead>
    <tr>
      <th style="text-align:left">Dato</th>
      <th style="text-align:left">Tema</th>
      <th style="text-align:left">Mål</th>
      <th style="text-align:left">Litteratur</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
      <p>5/2</p>
      </td>
      <td style="text-align:left">
        <p>Velkommen og formål</p>
        <p>Forventninger til uddannelsen/modulet</p>
        <p>Lave Kali Linux VM</p>
      </td>
      <td style="text-align:left">
        <p>Skabe et godt udgangspunkt for læring</p>
        <p>Introducere underviser og studerende</p>
        <p>Konkretisere forventninger</p>
        <p>Forberede værktøjer til øvelserne</p>
      </td>
      <td style="text-align:left">
      <p>Gennemgang af litteraturlisten.</p>
      <p>Download af Kali Linux Revealed</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">7/2</td>
      <td style="text-align:left">TCP/IP and Security in TCP/IP protocol suite</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">PPA til og med Kapitel 2<b><br /></b>Paper <em>Security problems in the TCP/IP protocol suite</em>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">12/2</td>
      <td style="text-align:left">Network Security Threats</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">14/2</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">
      <p>19/2</p>        
      </td>
      <td style="text-align:left">
      <p></p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
      <p>21/2</p>        
      </td>
      <td style="text-align:left">
      <p></p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
      <p>26/2</p>        
      </td>
      <td style="text-align:left">
      <p></p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
      <p>28/2</p>        
      </td>
      <td style="text-align:left">
      <p></p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
      <p>5/3</p>        
      </td>
      <td style="text-align:left">
      <p></p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
      <p>7/3</p>        
      </td>
      <td style="text-align:left">
      <p></p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
      <p>12/3</p>        
      </td>
      <td style="text-align:left">
      <p></p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
      <p>14/3</p>        
      </td>
      <td style="text-align:left">
      <p></p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
      <p><em>19/3</em> flyttes</p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
      <p><em>21/3</em> flyttes</p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
    </tr>
    <tr>
      <td style="text-align:left">
      <p>26/3</p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
      <td style="text-align:left">
      <p> </p>        
      </td>
    </tr>
</tbody>
</table>

**Introduction and welcome**
* Expectations for this course
* Literature list walkthrough
* Kali Linux introduction

Kali Linux is a toolbox we will use and participants will use a virtual machine

**TCP/IP and Security in TCP/IP protocol suite**

* Addressing and layering OSI model vs internet model
* Network devices Ethernet, bridges, switches, routers
* Common protocols, layer 2 and layer 3
* Secure network design  Background paper _Security problems in the TCP/IP protocol suite_, S. M. Bellovin

Exercise run tcpdump, wireshark, traceroute, whois

**Network Security Threats**  
* ARP spoofing, ICMP redirects, the classics
* Person in the middle attacks
* Network Scanning
* intro to routing protocols attacks
* BGP intro and hijacking

Exercise ARP spoofing and ettercap

**Traffic inspection and firewalls**  
* Network sniffing strategies and techniques
* Generic IP Firewalls stateless filtering vs stateful inspection
* Next Generation firewalls, Deep Packet Inspection
* IEEE 802.1q
* Common countermeasures in firewalls

Exercise Nping, and pcap-diff https://github.com/isginf/pcap-diff

**Transport Layer Security TLS**
* Encryption
* Diffie Helman exchange
[https://da.wikipedia.org/wiki/Transport\_Layer\_Security](https://da.wikipedia.org/wiki/Transport_Layer_Security)

Exercise/examples
* mitmproxy https://mitmproxy.org/
* sslsplit https://www.roe.ch/SSLsplit
* sslstrip https://moxie.org/software/sslstrip/

**Virtual Private Networks**  
* IPsec VPN
* TLS VPN
* OpenVPN
* Linux VPN
* Microsoft Remote Access VPN

**Wifi Security**
* Wifi standarder IEEE 802.11
* Authentication Protocols RADIUS, PAP, CHAP, EAP
* IEEE 802.1x
* Security problems in wireless protocols
* Security problems in wireless encryption
* Hacking wireless networks

**DNS and Email Security**  
* DNSSEC
* DMARC
* DKIM
* SMTP TLS
* DNS over TLS vs DNS over HTTPS

**Network Management**  
* Monitoring
* Centralized management SSH, Jump hosts
* SNMP version 2 vs version 3
* Bruteforcing network devices SSH vs SNMP
* Centralized syslog

**Network Intrusion Detection**  
* Intrusion Detection Systems
* NIDS vs HIDS
* Suricata Zeek
* Network Security Data Visualization
* Kibana Dashboards

ENISA Presenting, correlating and filtering various feeds
Handbook, Document for teachers
https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/presenting-correlating-and-filtering-various-feeds-handbook

**Network Forensics**
* Netflow data
* Collect Network Evidence
* Analyze Network data
* Create Incident Reports
Input from

ENISA Forensic analysis, Network Incident Response
https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/2016-resources/exe2_forensic_analysis_ii-handbook

ENISA Network Forensics, Handbook, Document for teachers
https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/network-forensics-handbook

http://www.honeynet.org/sites/default/files/files/KYT-Picviz_v1_0.pdf

**Honeypots**  
* History of honeypots
* Why use them research, production
* Types of honeypots low vs high interaction
* Honey nets

Background paper _An Evening with Berferd: In Which a Cracker is Lured, Endured, and Studied_ Bill Cheswick, AT&T Bell Laboratories

also http://www.honeynet.org/ specielt http://www.honeynet.org/papers

**Building Robust Networks**
* Design a robust network
* Isolation and segmentation
* Routing Security
* Switch and access security
* Wireless security
* Using reputation lists
