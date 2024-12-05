# Beveiligingsauditplan

## Doelstelling

Het doel van deze audit is om de beveiliging van een klein bedrijf te beoordelen, met de focus op interne, externe en online beveiliging. De audit is verdeeld in drie secties: intern, extern en online, die allemaal een overzicht geven van de belangrijkste controles en vragen die moeten worden gesteld.

---

# 1. Intern Deel

## Doelstelling

Het interne deel van de audit richt zich op de fysieke beveiliging, netwerken, apparaten en het bewustzijn van medewerkers binnen het bedrijf.

**Tijdsduur:** 1,5 tot 2 uur

## 1.1 Fysieke Beveiliging

**Tijdsduur:** 15-20 minuten

**Controlepunten:**

- Is het kantoor goed afgesloten?
- Zijn servers, ethernet poorten en switches (indien aanwezig) goed afgesloten?
- Worden apparaten zoals laptops veilig opgeborgen als ze niet worden gebruikt?
- Zijn belangrijke documenten goed bewaard? (zeker de papieren met persoons gegevens.)
- Is er een badge systeem?
- Zijn de printers beveiligd? (indien aanwezig)

**Te stellen vragen:**

- Hoe voorkom je dat iemand zonder toestemming het kantoor in komt?
- Is er een badge systeem aanwezig?
- Zijn er servers, ethernetpoorten, switchen waar mensen zomaar aankunnen?
- Waar leg je je laptop of waardevolle spullen neer als je ze niet gebruikt?
- Waar bewaar je documenten die belangrijk zijn? Geld dit ook voor de papieren met persoonsgegevens?
- Kan iedereen zomaar aan de printer?

**Acties:**

- Zorg ervoor dat laptops altijd veilig opgeborgen worden.
  _Verbindt met Lemma: PR.PT-4 (Protective Technology: Toepassing van fysieke beveiliging op apparatuur en netwerken)_
- Bewaar belangrijke documenten op een veilige plek.
  _Verbindt met Lemma: PR.DS-3 (Data Security: Fysieke en virtuele middelen worden beheerd bij verwijdering, overdracht en afstoting)_
- Zorg ervoor dat alleen de juiste mensen toegang hebben tot het kantoor.
  _Verbindt met Lemma: PR.AC-1 (Identity Management and Access Control: Beheer van fysieke toegang tot gevoelige gebieden)_
- Stel voor om printers aan te schaffen met "follow me" software

---

## 1.2 Interne Netwerkbeveiliging

**Tijdsduur:** 20-25 minuten

**Controlepunten:**

- Is je Wi-Fi-netwerk veilig met een sterk wachtwoord?
- Hebben gasten een apart Wi-Fi-netwerk?
- wat is de beveiling van het netwerk?

**Te stellen vragen:**

- Hoe sterk is je Wi-Fi-wachtwoord?
- Heb je een apart netwerk voor gasten, of gebruiken ze jouw netwerk?
- welke beveiliging heeft de wifi? (kijk dit desnoods zelf na als de klant hier niet genoeg van weet)

**Acties:**

- Zet een sterk wachtwoord in voor je Wi-Fi en wijzig het regelmatig.
  _Verbindt met Lemma: PR.AC-3 (Identity Management and Access Control: Beheer van netwerkinstellingen, inclusief toegangspunten)_
- Zet een apart netwerk op voor gasten en andere apparaten die geen toegang hoeven te hebben tot bedrijfsgegevens.
  _Verbindt met Lemma: PR.AC-3 (Identity Management and Access Control: Isoleren van netwerken om toegang te beperken)_
  - Zorg ervoor dat alle apparaten op het netwerk een virusscanner hebben en dat deze up-to-date is.
  - Zorg dat de wifi zeker beveiligd is met WPA3 en het gasten netwerk liefst enterprise is.

---

## 1.3 Beheer van Apparaten

**Tijdsduur:** 20-25 minuten

**Controlepunten:**

- Worden apparaten zoals computers en telefoons regelmatig geüpdatet?
- Hebben laptops een versleuteling zodat je gegevens veilig zijn als je je laptop verliest?
- Worden apparaten beheerd met Intune?

**Te stellen vragen:**

- Heb je automatische updates ingesteld voor je apparaten?
- Wat gebeurt er als je laptop verloren gaat of gestolen wordt?
- Worden de apparaten centraal beheert met bv: Intune? (geld alleen als er meerdere apparaten aanwezig zijn.)

**Acties:**

- Zorg ervoor dat automatische updates zijn ingeschakeld.
  _Verbindt met Lemma: PR.IP-3 (Information Protection: Beheer van beveiligingspatches en updates)_
- Zet versleuteling aan voor je laptops en apparaten, zoadt gegevens niet toegankelijk zijn voor andere.
  _Verbindt met Lemma: PR.DS-5 (Data Security: Versleuteling van gevoelige gegevens op apparaten)_
- Stel duidelijke regels op voor het gebruik van persoonlijke apparaten voor werk.  
  _Verbindt met Lemma: PR.AC-4 (Identity Management and Access Control: Toegangscontrole voor persoonlijke apparaten)_
- Segmenteer het interne netwerk zodat kritieke systemen gescheiden zijn van andere systemen.
  _Verbindt met Lemma: PR.AC-11 (Where appropriate, network integrity of the organization's critical systems shall be protected by incorporating network segmentation and segregation)_
- Stel monitoring in op interne netwerken en activeer logboeken voor verdachte activiteiten.
  _Verbindt met Lemma: DE.CM-4 (The network is monitored to detect potential cybersecurity events)_
- Zorg voor centraal beheer bv. Intune.
  _Verbindt met Lemma: PR.AC-1 (Identities and credentials are issued, managed, verified, revoked, and audited
  for authorized devices, users, and processes)._

---

## 1.4 Gegevensbeveiliging

**Tijdsduur:** 20-25 minuten

**Controlepunten:**

- Maak je regelmatig back-ups van belangrijke bestanden?
- Hebben alleen de juiste mensen toegang tot gevoelige gegevens?

**Te stellen vragen:**

- Hoe vaak maak je een back-up van belangrijke documenten? (Bereken RTO,RPO, retentie)
- Wie kan er bij jouw belangrijke gegevens?

**Acties:**

- Maak regelmatig back-ups van belangrijke bestanden.
  _Verbindt met Lemma: PR.DS-1 (Data Security: Beveiliging van gegevens door back-ups en veilige opslag)_
- Zorg ervoor dat alleen de juiste mensen toegang hebben tot vertrouwelijke gegevens.
  _Verbindt met Lemma: PR.AC-5 (Identity Management and Access Control: Minimum access rights en autorisatiebeheer)_
- Versleutel vertrouwelijke informatie bij verzending (bijvoorbeeld via e-mail) en bij opslag.  
   _Verbindt met Lemma: PR.DS-5 (Data Security: Versleuteling van gegevens voor veilige overdracht)_
- Stel een lijst op waarin systemen worden gerangschikt op basis van impact bij uitval.
  _Verbindt met Lemma: ID.AM-5: Resources are prioritized based on their classification, criticality, and business value_. Kijk zeker ook na of er classificatie is van de data (publiek, persoonsgegevens, etc.)

---

## 1.5 Personeel en Bewustzijn

**Tijdsduur:** 15-20 minuten

**Controlepunten:**

- Weten medewerkers wat ze moeten doen bij verdachte e-mails (phising) of beveiligingsincidenten?
- Hebben medewerkers geleerd hoe ze sterke wachtwoorden kunnen maken?

Te stellen vragen:

- Wat doe je als je een verdachte e-mail ontvangt?
- Weet je hoe je een sterk wachtwoord kiest? (Is er een password policy aanwezig?)
- Worden wachtwoorden herbruikt?

**Acties:**

- Zorg ervoor dat medewerkers weten wat te doen bij verdachte e-mails.
  _Verbindt met Lemma: PR.AT-1 (Awareness and Training: Trainingen en bewustwording voor medewerkers over beveiligingsrisico's)_
- Geef medewerkers training over sterke wachtwoorden. (Leg uit wat een sterk wachtwoord is)
  _Verbindt met Lemma: PR.AT-1 (Awareness and Training: Trainingen en bewustwording voor medewerkers over beveiligingsrisico's)_
- Zorg ervoor dat medewerkers weten waar ze beveiligingsproblemen kunnen melden.  
   _Verbindt met Lemma: DE.AE-2 (Anomalies and Events: Melding van beveiligingsincidenten door medewerkers)_
- Schrijf een informatiebeveiligingsbeleid en update jaarlijks op basis van feedback.
  _Verbindt met Lemma: ID.GV-4 (Policies and procedures for information security and cybersecurity shall be created, documented, reviewed, approved, and updated when changes occur)_

---

# 2. Extern Deel

## Doelstelling

Het externe deel van de audit richt zich op de beveiliging van externe verbindingen, zoals internet, online diensten en communicatiekanalen.

**Tijdsduur:** 1 tot 1,5 uur

## Vraag achter de domein naam van het bedrijf en noteer deze

## 2.1 Beveiliging van Internetverbinding

**Tijdsduur:** 15-20 minuten

**Controlepunten:**

- Is de router goed beveiligd en geüpdatet?

**Te stellen vragen:**

- Hoe zorg je ervoor dat je Wi-Fi goed beveiligd is?
- Wie zorgt ervoor dat de router altijd up-to-date is?

**Acties:**

- Zet een sterk wachtwoord voor je Wi-Fi-netwerk.
  _Verbindt met Lemma: ID.AM-1 (Asset Management: Inventarisatie van fysieke apparaten die aan het netwerk hangen)_
- Zorg ervoor dat de router altijd up-to-date is.
  _Verbindt met Lemma: ID.GV-1 (Governance: Beleidsmaatregelen voor informatiebeveiliging)_
- Stel een risicoanalyse op die externe bedreigingen in kaart brengt en prioriteert.
  _Verbindt met Lemma:ID.GV-6: Governance and risk management processes address cybersecurity risks_
- Configureer firewalls om inkomend en uitgaand verkeer te beperken tot alleen noodzakelijke verbindingen.
  _Verbindt met Lemma: PR.AC-10: Firewalls shall be installed and activated on all the organization's networks_

---

## 2.2 E-mail- en Online Communicatie

**Tijdsduur:** 15-20 minuten

**Controlepunten:**

- Wordt e-mailbeveiliging geregeld met sterke wachtwoorden en, indien mogelijk, tweefactorauthenticatie (2FA)?
- Heb je een spamfilter aan staan om phishing-aanvallen te blokkeren?

**Te stellen vragen:**

- Hoe zorg je ervoor dat je e-mailaccounts goed beveiligd zijn?
- Hoe voorkom je dat je per ongeluk op een nep-link in een e-mail klikt?

**Acties:**

- Zet 2FA in voor e-mailaccounts als dat mogelijk is.
  _Verbindt met Lemma: PR.AC-4 (Identity Management: Beheer van toegangsrechten met multi-factor authenticatie)_
- Gebruik een spamfilter om verdachte e-mails te blokkeren.
  _Verbindt met Lemma: ID.GV-2 (Governance: Begrip en naleving van juridische eisen, waaronder privacy)_
- Maak een overzicht van externe bedreigingen, zoals phishing en malware.
  _Verbindt met Lemma: ID.RA-3: Threats, vulnerabilities, likelihoods, and impacts are used to determine risk_

- Implementeer e-mailfilters en webfilters om schadelijke inhoud te blokkeren.
  _Verbindt met Lemma: PR.PT-3: Communications and control networks are protected_

---

## 2.3 Online Diensten en Cloudopslag

**Tijdsduur:** 15-20 minuten

**Controlepunten:**

- Worden online diensten zoals cloudopslag beveiligd met een sterk wachtwoord?
- Zijn de gegevens goed beschermd als ze in de cloud staan?

**Te stellen vragen:**

- Hoe zorg je ervoor dat je bestanden veilig zijn in de cloud?
- Wie heeft toegang tot je gedeelde documenten online?

**Acties:**

- Zet een sterk wachtwoord in voor cloudopslag.
  _Verbindt met Lemma: PR.AC-7 (Identity Management: Beheer van toegang tot kritieke informatie en technologie)_
- Controleer regelmatig wie toegang heeft tot je gedeelde documenten.
  _Verbindt met Lemma: PR.DS-1 (Data Security: Bescherming van gegevens in rust)_

---

## 2.4 Beveiliging van Bedrijfswebsite

**Tijdsduur:** 15-20 minuten

**Controlepunten:**

- Heeft je website een beveiligde verbinding (HTTPS)?
- Wordt je website regelmatig geüpdatet?

**Te stellen vragen:**

- Is je website beveiligd met een slotje (HTTPS)?
- Wordt je website regelmatig gecontroleerd en bijgewerkt?

**Acties:**

- Zorg voor HTTPS-beveiliging op je website.
  _Verbindt met Lemma: PR.DS-2 (Data Security: Bescherming van gegevens in transit)_
- Werk je website regelmatig bij.
  _Verbindt met Lemma: PR.PT-1 (Protective Technology: Bescherming van communicatie en controle netwerken)_

---

# 3. Online Deel

## Doelstelling

Het online deel van de audit richt zich op het beoordelen van de beveiliging van digitale aanwezigheid en accounts. Dit omvat de bescherming van online diensten, sociale media, en accounts die door het bedrijf worden gebruikt, evenals de monitoring van online bedreigingen en naleving van regelgeving.

**Tijdsduur:** 2,5 tot 4 uur

## 3.1 Beveiliging van Online Accounts

**Tijdsduur:** 30-45 minuten

**Controlepunten:**

- Worden alle bedrijfsaccounts beveiligd met sterke wachtwoorden en eventueel tweefactorauthenticatie (MFA)?
- Zijn de toegangsmogelijkheden tot online accounts goed ingesteld?
- Zijn gebruikersrollen en toegangsrechten goed ingesteld op online platforms zoals Office 365, Google en andere cloudservices?

**Te stellen vragen:**

- Gebruik je een sterk wachtwoord voor je online accounts?
- Zet je tweefactorauthenticatie in voor belangrijke accounts?
- Hoe wordt toegang tot gevoelige online diensten (bijv. boekhoudsoftware, CRM-systemen, Office 365, Google) beheerd?
  **Acties:**

- Zet tweefactorauthenticatie in voor belangrijke accounts.
  _Verbindt met Lemma: PR.AC-4 (Identity Management and Access Control: Beheer van toegang via multi-factor authenticatie)_
- Gebruik sterke wachtwoorden voor al je online accounts.
  _Verbindt met Lemma: PR.AC-4 (Identity Management and Access Control: Beheer van toegang via multi-factor authenticatie)_

---

## 3.2 Sociale Media en Reputatiebeheer

**Tijdsduur:** 30 minuten

**Controlepunten:**

- Zijn sociale media-accounts beveiligd met sterke wachtwoorden en 2FA?
- Worden sociale media regelmatig gecontroleerd op verdachte activiteit?

**Te stellen vragen:**

- Wie heeft toegang tot de sociale media-accounts van je bedrijf?
- Hoe zorg je ervoor dat je sociale media veilig blijven?

**Acties:**

- Zet 2FA in voor sociale media-accounts.
  _Verbindt met Lemma: PR.AC-4 (Identity Management and Access Control: Beheer van toegang via multi-factor authenticatie)_
- Controleer of er regelmatig een audit wordt uitgevoerd op de social media accounts van het bedrijf.
  _Verbindt met Lemma: PR.AT-1 (Awareness and Training: Alle gebruikers zijn geïnformeerd en getraind over veilig gebruik van online platforms)_

---

## 3.3 Monitoring van Online Bedreigingen (optioneel)

**Tijdsduur:** 30-45 minuten

**Controlepunten:**

- Worden online bedreigingen zoals phishing-aanvallen en hacks gemonitord?

**Te stellen vragen:**

- Hoe houd je online bedreigingen in de gaten, zoals phishing of hacks?
- Wat doe je als je iets verdachts ziet online?

**Acties:**

- Zet tools in om online bedreigingen te monitoren.
  _Verbindt met Lemma: DE.AE-1 (Anomalies and Events: Gegevens worden verzameld en gecorreleerd van meerdere bronnen en sensoren)_
- Wees alert op verdachte e-mails en activiteiten online.
  _Verbindt met Lemma: PR.AT-1 (Awareness and Training: Alle gebruikers zijn geïnformeerd en getraind)_

---

## 3.4 Online Compliance en Regelgeving

**Tijdsduur:** 15-30 minuten

**Controlepunten:**

- Voldoet het bedrijf aan de privacywetgeving, zoals de AVG (GDPR)?
- Wordt het privacybeleid duidelijk gecommuniceerd aan klanten en medewerkers?
  **Te stellen vragen:**

- Hoe zorg je ervoor dat klantgegevens veilig worden bewaard?
- Volg je de regels voor privacy zoals de AVG?
- Is er een privacybeleid opgesteld en hoe wordt dit onderhouden en geüpdatet?
- Hoe worden klanten en medewerkers geïnformeerd over hun recehten met betrekking tot privacy (bijv. recht op inzage, correctie, of verwijdering van gegevens)?

**Acties:**

- Zorg ervoor dat je voldoet aan de privacywetgeving (zoals de AVG). Als men ook niet weet wat bijvoorbeeld AVG is, leg je dit ook uit.
  _Verbindt met Lemma: ID.GV-2 (Governance: Juridische en regelgevende vereisten omtrent cybersecurity worden begrepen en nageleefd)_
- Stel duidelijke regels in voor het omgaan met klantgegevens.
  _Verbindt met Lemma: ID.GV-2 (Governance: Juridische en regelgevende vereisten omtrent cybersecurity worden begrepen en nageleefd)_
- Controleer de cookie-instellingen op de website en zorg ervoor dat ze voldoen aan de AGV.
  _Verbindt met Lemma: PR.DS-1 (Data Security: Gegevens in rust worden beschermd)_
- Zorg dat alle medewerkers bekend zijn met de regelgeving en documenteer naleving.
  _Verbindt met Lemma:ID.GV-5: Legal and regulatory requirements regarding cybersecurity, including privacy and civil liberties obligations, are understood and managed_
- Zorg dat alle medewerkers op de hoogte zijn van het privacybeleid en hoe ze moeten handelen bij vragen of verzoeken van klanten.
  _Verbindt met Lemma: PR.AT-1 (Awareness and Training: Training over relevante beveiligings- en privacynormen)_
- Implementeer een proces voor periodieke beoordeling en bijwerking van het privacybeleid.
  _Verbindt met Lemma: ID.RA-2 (Risk Assessment: Security en privacyprogramma's worden regelmatig beoordeeld en aangepast)_

---

---

## 3.5 Back-ups en hetstelplannen

**controlerpunten:**

- Worden gegevens van online diensten regelmatig geback-upt?
- Zijn back-ups versleuteld en opgeslagen op een veilige locatie?
- Is er een herstelplan in geval van dataverlies of een aanval op online systemen?
- Worden back-ups getest om zeker te zijn dat ze werken?
- Zijn back-ups opgeslagen in de cloud, lokaal, of op beide locaties voor redundantie?
  **Te stellen vragen:**

- Waar worden back-ups van online gegevens opgeslagen?
- Hoe vaak worden back-ups gemaakt en gecontroleerd?
- Wat is het proces om gegevens te herstellen na een incident?
- Worden back-ups versleuteld om ongeautoriseerde toegang te voorkomen?
- Is er een plan om te bepalen welke back-upopslag (lokaal, cloud) het beste past bij de behoeften van het bedrijf?

**Acties:**

- Zorg ervoor dat back-ups veilig worden opgeslagen en regelmatig worden gecontroleerd.
  _Verbindt met Lemma: PR.DS-3 (Data Security: Fysieke en virtuele middelen worden beheerd bij verwijdering, overdracht en afstoting)_

- Controleer of er een herstelplan is voor dataverlies of cyberaanvallen.
  _Verbindt met Lemma: RC.RP-1 (Recovery Planning: Herstelplan wordt uitgevoerd na een incident)_

- Maak een incidentresponsplan en organiseer simulaties voor crisissituaties.
  _Verbindt met Lemma: RS.RP-2: Response plan is executed during or after an incident_

- Test herstelprocedures regelmatig en zorg voor redundante back-ups op externe locaties.
  _Verbindt met Lemma: RC.RP-2: Recovery plan is executed during or after a cybersecurity incident_
- Evalueer de voordelen en risico's van lokale en cloudopslag en maak een weloverwogen keuze die aansluit bij de beveiligings- en bedrijfscontinuïteitsdoelen.
  _Verbindt met Lemma: ID.RA-3 (Risk Assessment: Periodieke evaluatie van operationele processen)_

---

## 3.6. Beveiliging van websites en online diensten

**Controlepunten:**

- Wordt de website regelmatig gecontroleerd op kwetsbaarheden (bijv. scans voor malware of kwetsbaarheden in CMS)?
- Is er een beleid voor het beheren van toegangsrechten tot de website en hostingplatforms?
- Wordt er gebruik gemaakt van CDN’s (Content Delivery Networks) en DDoS-bescherming?
- Zijn API’s en andere online diensten goed beveiligd tegen ongeautoriseerde toegang?
- Is de DNS-configuratie correct en wordt deze regelmatig gecontroleerd?
- Staat het eigendom van de dommeinnaam op naam van het bedrijf en is het abonnement betaald en up-to-date?

**Te stellen vragen:**

- Wie is verantwoordelijk voor het onderhoud van de website en andere online diensten?
- Hoe worden beveiligingsupdates en patches geïmplementeerd?
- Worden er regelmatig scans uitgevoerd om kwetsbaarheden te identificeren?
- Wie beheert de DNS-instellingen en hoe wordt toegang tot de DNS beperkt?
- Op wie staat het eigendom van de domeinnaam en is het abonnement up-to-date?
- Welke partij betaalt voor de domeinnaam en hosting?

**Acties:**

- Zorg ervoor dat er een beleid bestaat voor de beveiliging van de website en online diensten, inclusief het gebruik van beveiligingspatches.
  _Verbindt met Lemma: PR.MA-1 (Maintenance: Onderhoud en reparatie van organisatieassets wordt uitgevoerd en gedocumenteerd)_

- Controleer of er gebruik wordt gemaakt van een CDN en DDoS-bescherming.
  _Verbindt met Lemma: PR.PT-1 (Protective Technology: Bescherming van communicatie- en controle-netwerken)_
- Bevestig dat de domeinnaam eigendom is van het bedrijf, dat de registratie up-to-date is, en dat verlengingen tijdig worden uitgevoerd.
  _Verbindt met Lemma: ID.AM-1 (Asset Management: Beheer van organisatieassets)_

- Implementeer een proces voor het periodiek controleren van DNS-records, eigenaarschap en verlengingen.
  _Verbindt met Lemma: ID.RA-3 (Risk Assessment: Periodieke evaluatie van operationele processen)_

- Voer regelmatig audits uit van hosting-, domein- en DNS-diensten om risico's te identificeren en te minimaliseren.
  _Verbindt met Lemma: DE.CM-8 (Detection Processes: Beveiligingsbewakingsoplossingen worden gebruikt voor alle kritieke middelen)_

---

# Conclusie en Rapportage

- **Tijdens de audit:** Noteer bevindingen en risico's, markeer prioriteiten en geef duidelijke aanbevelingen.
- **Eindrapport:** Lever een eenvoudig rapport met concrete stappen voor het verbeteren van de beveiliging, zowel intern, extern als online.
- **Openemen (optioneel):** Neem het gesprek op en maak een transcriptie voor toekomstige referentie.

---

# Resultaat:

Een overzicht van de beveiligingsstatus van het bedrijf, met duidelijke aanbevelingen voor verbetering van de beveiliging in interne, externe en online systemen.
