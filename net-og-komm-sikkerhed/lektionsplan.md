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

* _An Evening with Berferd: In Which a Cracker is Lured, Endured, and Studied_ , Bill Cheswick, AT&T Bell Laboratories
* _Firewalls and Internet Security: Repelling the Wily Hacker_ , Second Edition, William R. Cheswick, Steven M. Bellovin, and Aviel D. Rubin
http://www.wilyhacker.com/ forkortes Cheswick
* _A Graduate Course in Applied Cryptography_ By Dan Boneh and Victor Shoup  [https://toc.cryptobook.us/](https://toc.cryptobook.us/) [https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup\_0\_4.pdf](https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup_0_4.pdf)
* _Strange Attractors and TCP/IP Sequence Number Analysis_ , Michal Zalewski [http://lcamtuf.coredump.cx/newtcp/](http://lcamtuf.coredump.cx/newtcp/)
* _WireGuard: Next Generation Kernel Network Tunnel_, https://www.wireguard.com/papers/wireguard.pdf

* ENISA Presenting, correlating and filtering various feeds Handbook, Document for teachers [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/presenting-correlating-and-filtering-various-feeds-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/presenting-correlating-and-filtering-various-feeds-handbook)
* ENISA Forensic analysis, Network Incident Response [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/2016-resources/exe2\_forensic\_analysis\_ii-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/2016-resources/exe2_forensic_analysis_ii-handbook)
* ENISA Network Forensics, Handbook, Document for teachers [https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/network-forensics-handbook](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/documents/network-forensics-handbook)
* [http://www.honeynet.org/sites/default/files/files/KYT-Picviz\_v1\_0.pdf](http://www.honeynet.org/sites/default/files/files/KYT-Picviz_v1_0.pdf)
* _Campus Network Security: High Level
Overview_ , Network Startup Resource Center  https://nsrc.org/workshops/2018/myren-nsrc-cndo/networking/cndo/en/presentations/Campus_Security_Overview.pdf
* _Campus Operations Best Current Practice_, Network Startup Resource Center  https://nsrc.org/workshops/2018/tenet-nsrc-cndo/networking/cndo/en/presentations/Campus_Operations_BCP.pdf
* Mutually Agreed Norms for Routing
Security (MANRS) https://www.manrs.org/wp-content/uploads/2018/09/MANRS_PDF_Sep2016.pdf
* RFC2827: Network Ingress Filtering: Defeating Denial of Service Attacks

Underviseren samler papers så de nemt kan downloades.

Websider benyttes også i undervisningen.

### Hardware

Da vi skal lave øvelser med opsamling af data vil det være en fordel at have et wireless netkort med USB.

Det anbefales således at købe et USB wireless netkort, eksempelvis et af disse:
* Billigste TP-link TL-WN722N hardware version 2.0 men kun 2.4GHz
* Alfa AWUS036ACH 2.4GHz + 5GHz Dual-Band

Begge de to virker glimrende med Kali Linux og til vores formål.


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
      <th style="text-align:left">Litteratur / Forberedelse</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">5/2</td>
      <td style="text-align:left">
        <p>Velkommen og formål</br>
        Forventninger til uddannelsen/modulet</br>
        Lave Kali Linux VM</p>
      </td>
      <td style="text-align:left">
        <p>Skabe et godt udgangspunkt for læring</br>
        Introducere underviser og studerende</br>
        Konkretisere forventninger</br>
        Forberede værktøjer til øvelserne</p>
      </td>
      <td style="text-align:left">
        <p>Gennemgang af litteraturlisten vil ske når vi mødes.</p>
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
      <p>PPA til og med Kapitel 4 - ca 66 sider</br>
      ANSM kapitel 13 - ca. 44 sider
      Paper <em>Security problems in the TCP/IP protocol suite</em>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">12/2</td>
      <td style="text-align:left"><b>Network Security Threats</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>PPA kapitel 5,6,10 - ca. 72 sider</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">14/2</td>
      <td style="text-align:left"><b>Traffic inspection and firewalls</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>ANSM kapitel 1,2,3 - ca. 73 sider</br>
      https://en.wikipedia.org/wiki/Firewall_(computing)</br>
      http://www.wilyhacker.com/ Cheswick kapitel 2 og 3 PDF, ca 55 sider</p>
      <p>Skimmes kapitlerne fra 1st edition:</br>
      http://www.wilyhacker.com/1e/chap03.pdf
      http://www.wilyhacker.com/1e/chap04.pdf
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">19/2</td>
      <td style="text-align:left"><b>Encrypting the network layer</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>Skimmes:</br>
      https://tools.ietf.org/html/rfc5246 The Transport Layer Security (TLS) Protocol Version 1.2</br>
      https://en.wikipedia.org/wiki/Transport_Layer_Security</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">21/2</td>
      <td style="text-align:left"><b>Virtual Private Networks</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>https://en.wikipedia.org/wiki/Virtual_private_network</br>
      https://kb.juniper.net/InfoCenter/index?page=content&id=KB11104  IPSec VPN between JUNOS and Cisco IOS</p>
      <p>Skimmes:</br>
      https://en.wikipedia.org/wiki/Multiprotocol_Label_Switching</br>
      https://en.wikipedia.org/wiki/OpenVPN</br>
      https://en.wikipedia.org/wiki/IPsec</br>
      https://en.wikipedia.org/wiki/DirectAccess</br>
      https://www.wireguard.com/papers/wireguard.pdf
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">26/2</td>
      <td style="text-align:left"><b>Wifi Security</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>PPA kapitel 11 - ca. 20 sider</p>
      <p>Skimmes:</br>
      http://aircrack-ng.org/doku.php?id=cracking_wpa
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">28/2</td>
      <td style="text-align:left"><b>Network Management</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>PPA kapitel 7,8,9 - ca. 76 sider </p>
      <p>Skimmes:</br>
      https://nsrc.org/workshops/2015/sanog25-nmm-tutorial/materials/snmp.pdf</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">5/3</td>
      <td style="text-align:left"><b>Network Intrusion Detection</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>ANSM kapitel 7,8,9,10 - ca. 140 sider</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">7/3</td>
      <td style="text-align:left"><b>Network Forensics</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>ANSM kapitel 4,5,6 - ca. 75 sider</br>
      Bro documentation Intel framework, Suricata reputation support</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">12/3</td>
      <td style="text-align:left"><b>Honeypots</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>ANSM kapitel 11,12 - ca. 54 sider</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">14/3</td>
      <td style="text-align:left"><b>DNS and Email Security</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>Genlæs evt. PPA DNS s 120-129</p>
      <p>https://en.wikipedia.org/wiki/Sender_Policy_Framework</br>
      https://en.wikipedia.org/wiki/DMARC</br>
      https://en.wikipedia.org/wiki/DomainKeys_Identified_Mail</p>
      <p>ANSM kapitel 14,15 - ca. 66 sider</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><em>19/3</em> flyttes</td>
      <td style="text-align:left"><b>Building Robust Networks</b>
      </td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>https://nsrc.org/workshops/2018/myren-nsrc-cndo/networking/cndo/en/presentations/Campus_Security_Overview.pdf</br>
      https://nsrc.org/workshops/2018/tenet-nsrc-cndo/networking/cndo/en/presentations/Campus_Operations_BCP.pdf
      <p>Download, men læs ikke https://nsrc.org/workshops/2015/apricot2015/raw-attachment/wiki/Track1Agenda/01-ISP-Network-Design.pdf</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left"><em>21/3</em> flyttes</td>
      <td style="text-align:left"><b>Running a Modern Network</b></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">
      <p>https://www.manrs.org/ bladre og læs specifikt https://www.manrs.org/wp-content/uploads/2018/09/MANRS_PDF_Sep2016.pdf
      https://tools.ietf.org/pdf/bcp38.pdf</br>
      RFC2827: Network Ingress Filtering: Defeating Denial of Service Attacks
      </p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">26/3</td>
      <td style="text-align:left"><b>Opsamling forberedelse til eksamen</b></td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Alt læst i de tre primære bøger</td>
    </tr>
  </tbody>
</table>

**Introduction and welcome**

* Expectations for this course
* Literature list walkthrough
* Kali Linux introduction
* Kali Linux installation

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
* Intro to routing protocols attacks
* BGP intro and hijacking
* DDoS and flooding

Exercise ARP spoofing and ettercap, EtherApe

**Traffic inspection and firewalls**

* Network sniffing strategies and techniques
* Generic IP Firewalls stateless filtering vs stateful inspection
* Next Generation firewalls, Deep Packet Inspection
* IEEE 802.1q VLAN
* Common countermeasures in firewalls

Exercise Nping, and pcap-diff [https://github.com/isginf/pcap-diff](https://github.com/isginf/pcap-diff)

** Encrypting the network layer**

* Basic cryptography
* Encryption Decryption
* Hashing
* Short introduction to algorithms RSA, AES
* Diffie Helman exchange
* Transport Layer Security (TLS)

Exercise/examples

* mitmproxy [https://mitmproxy.org/](https://mitmproxy.org/)
* sslsplit [https://www.roe.ch/SSLsplit](https://www.roe.ch/SSLsplit)
* sslstrip [https://moxie.org/software/sslstrip/](https://moxie.org/software/sslstrip/)
* https://www.ssllabs.com/ and sslscan checking servers


**Virtual Private Networks**

* IPsec and L2TP/IPsec
* TLS VPN with example OpenVPN
* Linux Wireguard VPN
* Microsoft DirectAccess and VPN (RAS)

Exercise go through the ones used by participants, how are they secured why/why not. Sniff data without VPN and after VPN turned on

**Wifi Security**

* Wifi standarder IEEE 802.11
* Authentication Protocols RADIUS, PAP, CHAP, EAP
* IEEE 802.1x
* Security problems in wireless protocols
* Security problems in wireless encryption
* Hacking wireless networks

Exercises WPA hacking with a short password

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



Exercise
*run Bro and Suricata on small pcaps

**Network Forensics**

* Netflow data
* Collect Network Evidence
* Analyze Network data
* Create Incident Reports

Exercises
* run forensics similar to ENISA examples
* create a Kibana dashboard for looking at logs

**Honeypots**

* History of honeypots
* Why use them research, production
* Types of honeypots low vs high interaction
* Honey nets



Exercise run SSH honeypot and try brute-force it

**DNS and Email Security**
* DNS introduction
* SMTP introduction
* SMTP TLS
* SPF, DKIM, DMARC
* DNSSEC - DNS integrity
* DNS over TLS vs DNS over HTTPS - DNS encryption

Exercises check some examples like how danish banks are using DMARC, and how your own companies can start using it. SSLscan with SMTP TLS

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
* Hardened network device configurations
* Jump hosts and management networks
* DDoS protection
* Check you network from outside RIPEstat, BGPmon

Exercises look at your own networks, from the outside
