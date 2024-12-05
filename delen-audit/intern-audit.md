| **Auteur** |
| ---------- |
| Gerben     |

### **Intern Security Audit Stappenplan voor KMO's**

---

#### **Doelstelling**

Het interne deel van de audit is gericht op het controleren van de fysieke beveiliging, netwerken, apparaten en het bewustzijn van medewerkers binnen het bedrijf. Het doel is om te zorgen voor een basisbeveiliging die eenvoudig te begrijpen en te implementeren is voor kleine bedrijven met weinig technische kennis.

**Tijdsduur:** ongeveer 1,5 tot 2 uur

---

## 1. Fysieke beveiliging (15-20 minuten)

### Controlepunten:

- Is het kantoor goed afgesloten?
- Zijn servers, ethernet poorten en switches (indien aanwezig) goed afgesloten?
- Worden apparaten zoals laptops veilig opgeborgen als ze niet worden gebruikt?
- Zijn belangrijke documenten goed bewaard? (zeker de papieren met persoons gegevens.)
- Is er een badge systeem?
- Zijn de printers beveiligd? (indien aanwezig)

### Te stellen vragen:

- Hoe voorkom je dat iemand zonder toestemming het kantoor in komt? 
- Is er een badge systeem aanwezig?
- Zijn er servers, ethernetpoorten, switchen waar mensen zomaar aankunnen?
- Waar leg je je laptop of waardevolle spullen neer als je ze niet gebruikt?
- Waar bewaar je documenten die belangrijk zijn? Geld dit ook voor de papieren met persoonsgegevens?
- Kan iedereen zomaar aan de printer?

### Acties:

- Zorg ervoor dat laptops altijd veilig opgeborgen worden.
  _Verbindt met Lemma: PR.PT-4 (Protective Technology: Toepassing van fysieke beveiliging op apparatuur en netwerken)_
- Bewaar belangrijke documenten op een veilige plek.
  _Verbindt met Lemma: PR.DS-3 (Data Security: Fysieke en virtuele middelen worden beheerd bij verwijdering, overdracht en afstoting)_
- Zorg ervoor dat alleen de juiste mensen toegang hebben tot het kantoor.
  _Verbindt met Lemma: PR.AC-1 (Identity Management and Access Control: Beheer van fysieke toegang tot gevoelige gebieden)_
- Stel voor om printers aan te schaffen met "follow me" software

---

## 2. Interne netwerkbeveiliging (20-25 minuten)

### Controlepunten:

   - Is het Wi-Fi-netwerk beveiligd met een sterk wachtwoord?
   - Is er een aparte Wi-Fi voor gasten en medewerkers?
   - Zijn de apparaten in het netwerk goed beschermd tegen virussen en andere bedreigingen?
    - wat is de beveiling van het netwerk?

### Te stellen vragen:

   - Is het Wi-Fi-wachtwoord moeilijk te raden?
   - Hebben gasten een eigen Wi-Fi-netwerk of delen zij de Wi-Fi van het bedrijf?
   - Hoe controleer je of apparaten op het netwerk veilig zijn?
   - welke beveiliging heeft de wifi? (kijk dit desnoods zelf na als de klant hier niet genoeg van weet) 

### Acties:

   - **Stel een sterk wachtwoord in voor het Wi-Fi-netwerk en wijzig het regelmatig.**
     *Verbindt met Lemma: PR.AC-3 (Identity Management and Access Control: Beheer van netwerkinstellingen, inclusief toegangspunten)*

   - **Zet een apart netwerk op voor gasten en andere apparaten die geen toegang hoeven tot bedrijfsgegevens.** 
     *Verbindt met Lemma: PR.AC-3 (Identity Management and Access Control: Isoleren van netwerken om toegang te beperken)*

   - **Zorg ervoor dat alle apparaten op het netwerk een virusscanner hebben en dat deze up-to-date is.**
     *Verbindt met Lemma: PR.PT-1 (Protective Technology: Beveiliging van technologie via antivirussoftware en netwerkbeveiliging)*
   
   - **Segmenteer het interne netwerk zodat kritieke systemen gescheiden zijn van andere systemen.**
     *Verbindt met Lemma: PR.AC-11: Where appropriate, network integrity of the organization's critical systems shall be protected by incorporating network segmentation and segregation*
   
   - **Stel monitoring in op interne netwerken en activeer logboeken voor verdachte activiteiten.**
     *Verbindt met Lemma: DE.CM-4: The network is monitored to detect potential cybersecurity events*
  - **Zorg dat de wifi zeker beveiligd is met WPA3 en het gasten netwerk liefst enterprise is.**

---

## 3. Beheer van apparaten (20-25 minuten)

### Controlepunten:

   - Worden apparaten zoals computers en telefoons regelmatig geüpdatet met de nieuwste software?
   - Zijn er regels voor het gebruik van persoonlijke apparaten (bijv. telefoon) voor werk?
   - Worden laptops versleuteld zodat ze niet kunnen worden gelezen als ze verloren gaan?
   - Worden apparaten beheerd met Intune? 

### Te stellen vragen:

   - Worden je apparaten automatisch bijgewerkt of moet je dit handmatig doen?
   - Gebruik je je eigen telefoon voor werk? Zo ja, hoe zorg je ervoor dat die veilig is?
   - Wat gebeurt er als je laptop verloren gaat of gestolen wordt?
   - Worden de apparaten centraal beheert met bv: Intune? (geld alleen als er meerdere apparaten aanwezig zijn.) 

### Acties:

   - **Zorg ervoor dat automatische updates ingeschakeld zijn voor alle apparaten (computers, telefoons).** 
     *Verbindt met Lemma: PR.IP-3 (Information Protection: Beheer van beveiligingspatches en updates)*

   - **Gebruik versleuteling voor apparaten zoals laptops, zodat gegevens niet toegankelijk zijn voor anderen.** 
     *Verbindt met Lemma: PR.DS-5 (Data Security: Versleuteling van gevoelige gegevens op apparaten)*

   - **Stel duidelijke regels op voor het gebruik van persoonlijke apparaten voor werk.**
     *Verbindt met Lemma: PR.AC-4 (Identity Management and Access Control: Toegangscontrole voor persoonlijke apparaten)*
   
   - **Beperk het gebruik van admin-accounts tot systeembeheer en stel aparte accounts in voor dagelijks gebruik.**
     *Verbindt met Lemma:PR.AC-9: Nobody shall have administrator privileges for daily tasks*

  - **Zorg voor centraal beheer bv. Intune.**
  _Verbindt met Lemma: PR.AC-1 (Identities and credentials are issued, managed, verified, revoked, and audited 
for authorized devices, users, and processes)._
---

## 4. Gegevensbeveiliging (20-25 minuten)

### Controlepunten:

   - Worden belangrijke bestanden regelmatig geback-upt (bv. elke week)?
   - Hebben alleen de juiste mensen toegang tot belangrijke gegevens?
   - Worden gegevens versleuteld als ze opgeslagen of verzonden worden?

### Te stellen vragen:

   - Hoe vaak maak je een back-up van belangrijke bestanden? ((Bereken RTO,RPO, retentie))
   - Wie kan er bij de belangrijke gegevens binnen het bedrijf?
   - Hoe verstuur je vertrouwelijke informatie? Is deze versleuteld?

### Acties:

   - **Maak regelmatig back-ups van belangrijke bestanden (bijvoorbeeld wekelijks) en bewaar ze op een veilige plaats (bv. een externe harde schijf of in de cloud).**  
     *Verbindt met Lemma: PR.DS-1 (Data Security: Beveiliging van gegevens door back-ups en veilige opslag)*

   - **Zorg ervoor dat alleen medewerkers die toegang nodig hebben, bij gevoelige informatie kunnen.**  
     *Verbindt met Lemma: PR.AC-5 (Identity Management and Access Control: Minimum access rights en autorisatiebeheer)*

   - **Versleutel vertrouwelijke informatie bij verzending (bijvoorbeeld via e-mail) en bij opslag.**  
     *Verbindt met Lemma: PR.DS-5 (Data Security: Versleuteling van gegevens voor veilige overdracht)*

   - **Stel een lijst op waarin systemen worden gerangschikt op basis van impact bij uitval.**
     *Verbindt met Lemma: ID.AM-5: Resources are prioritized based on their classification, criticality, and business value*

---

## 5. Personeel en bewustzijn (15-20 minuten)

### Controlepunten:

   - Weten medewerkers wat ze moeten doen als ze een verdachte e-mail of beveiligingsincident zien?
   - Worden medewerkers getraind in hoe ze sterke wachtwoorden moeten kiezen en phishing-e-mails moeten herkennen?
   - Is er een manier voor medewerkers om beveiligingsproblemen te melden?

### Te stellen vragen:

   - Wat moet je doen als je een verdachte e-mail ontvangt?
   - Heb je ooit geleerd hoe je een sterk wachtwoord maakt?
   - Hoe meld je een probleem als je iets verdachts ziet op je computer of in je werk?
   - Worden wachtwoorden herbruikt? 

### Acties:

   - **Organiseer een eenvoudige training voor medewerkers over hoe ze phishing-e-mails kunnen herkennen en sterke wachtwoorden kunnen maken.**  
     *Verbindt met Lemma: PR.AT-1 (Awareness and Training: Trainingen en bewustwording voor medewerkers over beveiligingsrisico's)*

   - **Zorg ervoor dat medewerkers weten waar ze beveiligingsproblemen kunnen melden.**  
     *Verbindt met Lemma: DE.AE-2 (Anomalies and Events: Melding van beveiligingsincidenten door medewerkers)*
   
   - **Schrijf een informatiebeveiligingsbeleid en update jaarlijks op basis van feedback.**
     *Verbindt met Lemma: ID.GV-4: Policies and procedures for information security and cybersecurity shall be created, documented, reviewed, approved, and updated when changes occur*

---

## 6. Documentatie en rapportage (15-20 minuten)

### Tijdens de audit:

   - Noteer bevindingen per sectie en maak onderscheid tussen belangrijke risico's en minder urgente problemen.
   - Schrijf alles duidelijk op, zodat medewerkers de bevindingen makkelijk kunnen begrijpen en actie kunnen ondernemen.

### Eindrapport:
   - Maak een eenvoudig rapport met duidelijke verbeterpunten.
   - Geef korte adviezen over wat het bedrijf direct kan doen om de beveiliging te verbeteren.

---
