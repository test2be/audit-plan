# Security Audit Plan – Extern Deel

## Doelstelling
Het externe deel van de audit heeft als doel om te beoordelen hoe goed een bedrijf beschermd is tegen externe bedreigingen, zoals cyberaanvallen of onbevoegde toegang tot externe systemen. Dit omvat de beoordeling van openbare en toegankelijke systemen, externe verbindingen en compliance met beveiligingsstandaarden.

---

## 1. Web- en applicatiebeveiliging
### Controlepunten:
- Is de bedrijfswebsite beveiligd met een geldig SSL/TLS-certificaat (HTTPS)?
- Zijn webapplicaties beschermd tegen veelvoorkomende aanvallen zoals SQL-injecties, cross-site scripting (XSS), en andere OWASP Top 10-kwetsbaarheden?
- Worden alle plugins, thema's en CMS-systemen (bijv. WordPress) regelmatig bijgewerkt?
- Is er een Web Application Firewall (WAF) actief?
- Wordt er gebruikgemaakt van beveiligingstests (bijv. pentesting of vulnerability scanning) op applicaties?

### Te stellen vragen:
1. Hoe vaak wordt de bedrijfswebsite gecontroleerd op kwetsbaarheden?
2. Wie beheert de webapplicaties, en hoe worden updates geïmplementeerd?
3. Is er een plan voor DDoS-aanvallen of andere verstoringen?

---

## 2. Beveiliging van externe verbindingen
### Controlepunten:
- Wordt er gebruikgemaakt van een Virtual Private Network (VPN) voor externe toegang tot bedrijfsnetwerken?
- Zijn remote desktop en andere toegangsmethoden (bijv. RDP, SSH) goed beveiligd met sterke wachtwoorden en/of multi-factor authentication (MFA)?
- Worden externe verbindingen regelmatig gecontroleerd op ongeautoriseerde toegangspogingen?
- Is er een beleid voor het gebruik van openbare Wi-Fi-netwerken door medewerkers die extern werken?

### Te stellen vragen:
1. Hoe wordt de veiligheid van externe toegang gewaarborgd?
2. Worden logboeken van externe verbindingen gemonitord en geanalyseerd?
3. Hoe worden tijdelijke of externe medewerkers toegang verleend?

---

## 3. E-mail- en communicatiebeveiliging
### Controlepunten:
- Is e-mail beveiligd tegen phishing-aanvallen (bijv. met SPF, DKIM, en DMARC)?
- Wordt er gebruikgemaakt van versleutelde communicatiekanalen voor gevoelige informatie (bijv. end-to-end encryptie)?
- Zijn medewerkers bewust van de risico’s van phishing en andere sociale-engineering-aanvallen?
- Wordt verdachte e-mailverkeer actief gemonitord en gemeld?

### Te stellen vragen:
1. Hoe wordt phishing herkend en behandeld binnen de organisatie?
2. Welke maatregelen zijn genomen om gevoelige informatie in e-mail te beschermen?
3. Zijn er beveiligingsprotocollen voor externe communicatie met klanten of partners?

---

## 4. Cloud- en externe opslagbeveiliging
### Controlepunten:
- Worden cloudservices (zoals Google Workspace, Microsoft 365, of Dropbox) beveiligd met MFA en toegangscontrole?
- Worden gevoelige gegevens in de cloud versleuteld opgeslagen?
- Is er een back-upbeleid voor gegevens in de cloud?
- Zijn rechten en toegangsregels goed ingericht en periodiek gecontroleerd?

### Te stellen vragen:
1. Welke cloudoplossingen worden gebruikt en hoe worden deze beheerd?
2. Hoe wordt de toegang tot cloudsystemen gemonitord?
3. Wat gebeurt er bij een datalek in de cloud?

---

## 5. Beoordeling van leveranciers en externe partners
### Controlepunten:
- Zijn leveranciers en externe partners beoordeeld op hun eigen beveiligingspraktijken?
- Worden externe partijen die toegang hebben tot bedrijfsgegevens of systemen gescreend en gecontroleerd?
- Zijn er duidelijke afspraken en contracten over beveiliging (bijv. Service Level Agreements, verwerkersovereenkomsten)?
- Hoe worden externe verbindingen tussen systemen beveiligd?

### Te stellen vragen:
1. Hoe worden leveranciers en externe partners beoordeeld op hun beveiligingsmaatregelen?
2. Welke gegevens of systemen zijn toegankelijk voor externe partijen?
3. Hoe worden incidenten aangepakt als deze door een leverancier worden veroorzaakt?

---

## 6. Openbare informatie en social engineering
### Controlepunten:
- Welke bedrijfsinformatie is openbaar toegankelijk (bijv. via sociale media, website, of andere bronnen)?
- Worden medewerkers gewaarschuwd voor de risico’s van informatie delen op openbare platforms?
- Wordt er gebruik gemaakt van monitoring om te zien welke informatie over het bedrijf beschikbaar is op het dark web of via andere kanalen?

### Te stellen vragen:
1. Hoe wordt gecontroleerd welke informatie openbaar beschikbaar is?
2. Zijn er richtlijnen voor medewerkers over het delen van bedrijfsinformatie online?
3. Wat wordt er gedaan om informatielekken via openbare bronnen te minimaliseren?

---

## 7. Incidentrespons en monitoring
### Controlepunten:
- Wordt er gebruikgemaakt van monitoringtools om verdachte externe activiteiten te detecteren?
- Is er een incidentresponsplan in geval van een externe aanval?
- Worden logs van externe systemen regelmatig gecontroleerd en bewaard?
- Wordt er gebruikgemaakt van intrusion detection/prevention systems (IDS/IPS)?

### Te stellen vragen:
1. Hoe worden externe bedreigingen gedetecteerd en aangepakt?
2. Wat is het protocol voor een beveiligingsincident zoals een datalek?
3. Hoe vaak wordt het incidentresponsplan getest of bijgewerkt?

---

## Documentatie en rapportage
### Tijdens de audit:
- Noteer bevindingen per sectie, inclusief duidelijke voorbeelden van externe risico's en beveiligingslekken.
- Geef prioriteiten aan acties, zoals het implementeren van MFA, het verbeteren van e-mailbeveiliging of het inschakelen van een WAF.
- Adviseer over lange-termijnmaatregelen om externe dreigingen te blijven beheersen.

### Eindresultaat:
Een overzichtelijk rapport waarin externe beveiligingskwetsbaarheden worden geïdentificeerd, met concrete aanbevelingen om de weerbaarheid tegen aanvallen te verbeteren.
