---
description: Obligatoriske modul Ob 1 Netværks- og kommunikationssikkerhed (10 ECTS)
---

# Lektionsplan UDKAST

## Fagets titel: Ob 1 Netværks- og kommunikationssikkerhed \(10 ECTS\)

Underviser: Henrik Lund Kramshøj hlk@zencurity.com +45 2026 6000

### Formål

Elementet går ud på at forstå og håndtere netværkssikkerhedstrusler samt implementere og konfigurere udstyr til samme.

Elementet omhandler forskellig sikkerhedsudstyr \(IDS\) til monitorering. Derudover vurdering af sikkerheden i et netværk, udarbejdelse af plan til at lukke eventuelle sårbarheder i netværket samt gennemgang af forskellige VPN teknologier.

### Litteraturliste

Hvad skal de studerende læse: bog titel, forfatter, side tal.  
Husk også at skrive ind hvis de skal forberede andet til denne undervisningsgang

Primær litteratur: Applied Network Security Monitoring Collection, Detection, and Analysis, 2017 Chris Sanders ISBN: 9780124172081

Practical Packet Analysis - Using Wireshark to Solve Real-World Network Problems, 3rd edition 2017, Chris Sanders ISBN: 9781593278021

Sekundær litteratur:

* M. Bellovin, S. \(2002\). Security problems in the TCP/IP protocol suite. 19. 10.1145/378444.378449.
* An Evening with Berferd: In Which a Cracker is Lured, Endured, and Studied Bill Cheswick, AT&T Bell Laboratories
* A Graduate Course in Applied Cryptography By Dan Boneh and Victor Shoup  [https://toc.cryptobook.us/](https://toc.cryptobook.us/) [https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup\_0\_4.pdf](https://crypto.stanford.edu/~dabo/cryptobook/BonehShoup_0_4.pdf)

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

#### Dato

Mål

Den studerende opnår viden om \(samlet overblik for to moduler: 1/2\):

```text
Sikkerhed i TCP/IP protokollerne
```

Den studerende kan i produktudviklingsprocessen:

```text
Beregne areal, tyngdepunkt, inertimoment og modstandsmoment for simple tværsnit (dvs. tværsnit som kan konstrueres ud fra rette liner og cirkelbuer).
Forstår hvordan et 3D-moduleringsprogram kan anvendes til at beregne både simple og mere komplicerede tværsnit.
```

Den studerende kan efterfølgende:

```text
Overføre tilegnet viden og færdigheder til design af netværk og imødegå truslerne
```

Tema Sikkerhed i TCP/IP

Litteratur

Paper M. Bellovin, S. \(2002\). Security problems in the TCP/IP protocol suite. 19. 10.1145/378444.378449.

## Plan

**Security in TCP/IP protocol suite**  
Addressing and layering Network devices and secure network design   
Background paper M. Bellovin, S. \(2002\). _Security problems in the TCP/IP protocol suite_. 19. 10.1145/378444.378449.

**Network Threats**  
ARP spoofing, Person in the middle attacks Network sniffing strategies and techniques

**Traffic inspection and firewalls**  
Generic IP Firewalls Next Generation firewalls, Deep Packet Inspection

**Network Intrusion Detection**  
Suricata Zeek

**Transport Layer Security TLS**  
[https://da.wikipedia.org/wiki/Transport\_Layer\_Security](https://da.wikipedia.org/wiki/Transport_Layer_Security)

**DNS and Email Security**  
DNSSEC, DMARC, DKIM SMTP TLS, DNS over TLS, DNS over HTTPS

**Wifi Security**

**Virtual Private Networks**  
TLS VPN, OpenVPN, IPsec VPN, Linux VPN Microsoft Connect VPN

**Honeypots**  
Background paper _An Evening with Berferd: In Which a Cracker is Lured, Endured, and Studied_ Bill Cheswick, AT&T Bell Laboratories

**Network Management**  
 Monitoring Centralized syslog and SNMP

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
      <td style="text-align:left"></td>
      <td style="text-align:left">
        <p>Velkommen og formål</p>
        <p>Forventninger til uddannelsen/modulet</p>
      </td>
      <td style="text-align:left">
        <p>Skabe et godt udgangspunkt for læring</p>
        <p>Introducere underviser og studerende</p>
        <p>Konkretisere forventninger</p>
      </td>
      <td style="text-align:left">Gennemgang af boglisten</td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left">TCP/IP Security</td>
      <td style="text-align:left"></td>
      <td style="text-align:left">Paper M. Bellovin, S. (2002). Security problems in the TCP/IP protocol
        suite. 19. 10.1145/378444.378449.</td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left">Firewalls and low level attacks</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>