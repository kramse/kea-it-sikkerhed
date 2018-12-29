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

Dette kursus benytter tre bøger og et antal internetresourcer. Primær litteratur: Applied Network Security Monitoring Collection, Detection, and Analysis, 2017 Chris Sanders ISBN: 9780124172081 forkortes ANSM

Practical Packet Analysis - Using Wireshark to Solve Real-World Network Problems, 3rd edition 2017, Chris Sanders ISBN: 9781593278021 forkortes PPA

Linux Basics for Hackers Getting Started with Networking, Scripting, and Security in Kali by OccupyTheWeb, December 2018, 248 pp. ISBN-13: 978-1-59327-855-7 forkortes LBfH

Sekundær litteratur:

* Kali Linux Revealed  Mastering the Penetration Testing Distribution [https://www.kali.org/download-kali-linux-revealed-book/](https://www.kali.org/download-kali-linux-revealed-book/) forkortes KLR
* _Security problems in the TCP/IP protocol suite_, S. M. Bellovin samt
_A Look Back at “Security Problems in the TCP/IP Protocol Suite”_ https://www.cs.columbia.edu/~smb/papers/acsac-ipext.pdf

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

Undervisningsdatoer: 05/02 2019, 07/02 2019, 12/02 2019, 14/02 2019, 19/02 2019, 21/02 2019, 26/02 2019, 28/02 2019, 05/03 2019, 07/03 2019, 12/03 2019, 14/03 2019, 19/03 2019, 21/03 2019, 26/03 2019

## Plan (udkast)

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
      <td style="text-align:left">5/2</td>
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
        <p>Identifikation af kapitler og afsnit fra KLR og LBfH til læsning som hjemmeopgave</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">7/2</td>
      <td style="text-align:left"><b>TCP/IP and Security in TCP/IP protocol suite</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>PPA til og med Kapitel 2<b></p>
      <p>ANSM kapitel 13 - ca. 44 sider</p>
      <p>Paper <em>Security problems in the TCP/IP protocol suite</em>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">12/2</td>
      <td style="text-align:left"><b>Network Security Threats</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">14/2</td>
      <td style="text-align:left"><b>Traffic inspection and firewalls</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>ANSM kapitel 1,2,3 - ca. 73 sider</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">19/2</td>
      <td style="text-align:left"><b>Transport Layer Security TLS</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">21/2</td>
      <td style="text-align:left"><b>Virtual Private Networks</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">26/2</td>
      <td style="text-align:left"><b>Wifi Security</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">28/2</td>
      <td style="text-align:left"><b>DNS and Email Security</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">5/3</td>
      <td style="text-align:left"><b>Network Management</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">7/3</td>
      <td style="text-align:left"><b>Network Intrusion Detection</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>ANSM kapitel 7,8,9,10 - ca. 140 sider</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">12/3</td>
      <td style="text-align:left"><b>Network Forensics</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>ANSM kapitel 4,5,6,14,15 - ca. 140 sider</p>
      <p>Bro documentation Intel framework, Suricata reputation support</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">14/3</td>
      <td style="text-align:left"><b>Honeypots</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>ANSM kapitel 11,12 - ca. 54 sider</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><em>19/3</em> flyttes</td>
      <td style="text-align:left"><b>Building Robust Networks</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><em>21/3</em> flyttes</td>
      <td style="text-align:left"><b>Running a Modern Network</b></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p></p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">26/3</td>
      <td style="text-align:left"><b>Opsamling forberedelse til eksamen</b></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Alt læst i de tre primære bøger</td>
    </tr>
  </tbody>
</table>**Introduction and welcome**

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
* DDoS and flooding

Exercise ARP spoofing and ettercap, EtherApe

**Traffic inspection and firewalls**

* Network sniffing strategies and techniques
* Generic IP Firewalls stateless filtering vs stateful inspection
* Next Generation firewalls, Deep Packet Inspection
* IEEE 802.1q
* Common countermeasures in firewalls

Exercise Nping, and pcap-diff [https://github.com/isginf/pcap-diff](https://github.com/isginf/pcap-diff)

** Encrypting the network layer**

* Basic cryptography
* Encryption Decryption
* Hashing
* Short introduction to algorithms RSA, AES
* Diffie Helman exchange
* Transport Layer Security (TLS)

  [https://da.wikipedia.org/wiki/Transport\_Layer\_Security](https://da.wikipedia.org/wiki/Transport_Layer_Security)

Exercise/examples

* mitmproxy [https://mitmproxy.org/](https://mitmproxy.org/)
* sslsplit [https://www.roe.ch/SSLsplit](https://www.roe.ch/SSLsplit)
* sslstrip [https://moxie.org/software/sslstrip/](https://moxie.org/software/sslstrip/)

**Virtual Private Networks**

* IPsec VPN
* TLS VPN
* OpenVPN
* Linux VPN
* Microsoft Remote Access VPN

Exercise go through the ones used by participants, how are they secured why/why not

**Wifi Security**

* Wifi standarder IEEE 802.11
* Authentication Protocols RADIUS, PAP, CHAP, EAP
* IEEE 802.1x
* Security problems in wireless protocols
* Security problems in wireless encryption
* Hacking wireless networks

Exercises WPA hacking with a short password

**DNS and Email Security**

* DNSSEC
* DMARC
* DKIM
* SMTP TLS
* DNS over TLS vs DNS over HTTPS

Exercises check some examples like Danske Bank using it, and how your own companies can start using it.

**Network Management**

* Monitoring
* Centralized management SSH, Jump hosts
* SNMP version 2 vs version 3
* Bruteforcing network devices SSH vs SNMP
* Centralized syslog

Exercise use SNMP and brute-force SNMP

**Network Intrusion Detection**

* Intrusion Detection Systems
* NIDS vs HIDS
* Suricata Zeek
* Network Security Data Visualization
* Kibana Dashboards

ENISA Presenting, correlating and filtering various feeds Handbook, Document for teachers [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/presenting-correlating-and-filtering-various-feeds-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/presenting-correlating-and-filtering-various-feeds-handbook)

Exercise run Bro and Suricata on small pcaps

**Network Forensics**

* Netflow data
* Collect Network Evidence
* Analyze Network data
* Create Incident Reports

  Input from

ENISA Forensic analysis, Network Incident Response [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/2016-resources/exe2\_forensic\_analysis\_ii-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/2016-resources/exe2_forensic_analysis_ii-handbook)

ENISA Network Forensics, Handbook, Document for teachers [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/network-forensics-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/network-forensics-handbook)

[http://www.honeynet.org/sites/default/files/files/KYT-Picviz\_v1\_0.pdf](http://www.honeynet.org/sites/default/files/files/KYT-Picviz_v1_0.pdf)

Exercise create a Kibana dashboard for looking at logs, run forensics similar to ENISA examples

**Honeypots**

* History of honeypots
* Why use them research, production
* Types of honeypots low vs high interaction
* Honey nets

Background paper _An Evening with Berferd: In Which a Cracker is Lured, Endured, and Studied_ Bill Cheswick, AT&T Bell Laboratories

also [http://www.honeynet.org/](http://www.honeynet.org/) specielt [http://www.honeynet.org/papers](http://www.honeynet.org/papers)

Exercise run SSH honeypot and try brute-force it

**Building Robust Networks**

* Design a robust network
* Isolation and segmentation
* Routing Security
* Switch and access security, port security
* Wireless security
* Using reputation lists

Exercise We will design and build a sample network together

**Running a Modern Network**

* BCP38 RFC2827: Network Ingress Filtering: Defeating Denial of Service Attacks which employ IP Source Address Spoofing
* MANRS https://www.manrs.org/isps/
* Testing security, evaluating and reporting
* DDoS protection
* Jump hosts and management networks
* Check you network from outside RIPEstat, BGPmon

Exercises look at your own networks, from the outside
