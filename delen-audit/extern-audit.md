# Extern Beveiligingsaudit Plan

## Doelstelling

Het externe deel van de audit richt zich op de beveiliging van externe verbindingen, zoals het internet, online diensten en communicatiekanalen. Dit deel is specifiek ontworpen voor kleine bedrijven en bevat eenvoudige controles om de risico’s van cyberaanvallen en datalekken te minimaliseren.

---

## Tijdsinvestering

De externe audit duurt ongeveer **1 tot 1,5 uur**. Dit omvat een korte controle van systemen en enkele gerichte vragen.

---

## Vraag achter de domein naam van het bedrijf en noteer deze

## 1. Beveiliging van internetverbinding (15-20 minuten)

### Controlepunten:

- Is het Wi-Fi-netwerk beveiligd met een sterk wachtwoord en WPA3 (of WPA2) encryptie?
- Heeft de router recente beveiligingsupdates (firmware)?
- Is remote toegang tot de router en andere systemen uitgeschakeld als dit niet nodig is?
- Wordt er een gastnetwerk gebruikt voor bezoekers en privé-apparaten?

### Te stellen vragen:

1. Wie beheert de router en voert updates uit?
2. Wordt het netwerk regelmatig gecontroleerd op vreemde apparaten?

### Acties:

- **Adviseer een sterk wachtwoord voor het Wi-Fi-netwerk en de router**.  
  _Verbindt met Lemma: ID.AM-1 (Asset Management: Inventarisatie van fysieke apparaten die aan het netwerk hangen)_
- **Controleer of het gastnetwerk is gescheiden van het bedrijfsnetwerk**.  
  _Verbindt met Lemma: ID.AM-3 (Asset Management: Bedrijfsmiddelen en communicatie worden in kaart gebracht)_
- **Controleer de routerinstellingen en stel updates in indien nodig**.  
  _Verbindt met Lemma: ID.GV-1 (Governance: Beleidsmaatregelen voor informatiebeveiliging)_

- **Configureer firewalls om inkomend en uitgaand verkeer te beperken tot alleen noodzakelijke verbindingen.**
  _Verbindt met Lemma: PR.AC-10: Firewalls shall be installed and activated on all the organization's networks_

- **Stel een risicoanalyse op die externe bedreigingen in kaart brengt en prioriteert.**
  _Verbindt met Lemma:ID.GV-6: Governance and risk management processes address cybersecurity risks_

---

## 2. E-mail- en online communicatie (15-20 minuten)

### Controlepunten:

- Worden zakelijke e-mailaccounts beschermd met sterke wachtwoorden en indien mogelijk twee-staps-verificatie (2FA)?
- Is het spamfilter ingeschakeld om phishing-aanvallen te verminderen?
- Wordt gevoelige informatie nooit gedeeld via onbeveiligde e-mails of berichten?

### Te stellen vragen:

1. Hoe vaak worden wachtwoorden van e-mailaccounts gewijzigd?
2. Hoe herkennen medewerkers (de ondernemer en eventuele partners) verdachte e-mails?
3. Wordt er gebruik gemaakt van een professioneel e-maildomein (bijv. naam@bedrijf.be)?

### Acties:

- **Adviseer het gebruik van twee-staps-verificatie (bijv. een code via sms of app)**.  
  _Verbindt met Lemma: PR.AC-4 (Identity Management: Beheer van toegangsrechten met multi-factor authenticatie)_
- **Controleer of e-mails via een professioneel domein lopen in plaats van gratis diensten zoals Gmail**.  
  _Verbindt met Lemma: ID.GV-2 (Governance: Begrip en naleving van juridische eisen, waaronder privacy)_

- **Geef uitleg over het herkennen van phishing e-mails**.  
  _Verbindt met Lemma: PR.AT-1 (Awareness and Training: Alle gebruikers zijn geïnformeerd en getraind)_

- **Maak een overzicht van externe bedreigingen, zoals phishing en malware.**
  _Verbindt met Lemma: ID.RA-3: Threats, vulnerabilities, likelihoods, and impacts are used to determine risk_

- **Implementeer e-mailfilters en webfilters om schadelijke inhoud te blokkeren.**
  _Verbindt met Lemma: PR.PT-3: Communications and control networks are protected_

---

## 3. Online diensten en cloudopslag (15-20 minuten)

### Controlepunten:

- Worden online diensten zoals boekhoudsoftware, agenda’s of cloudopslag beveiligd met sterke wachtwoorden en tweefactorauthenticatie?
- Is toegang tot gevoelige gegevens beperkt tot de juiste personen?
- Worden gevoelige gegevens opgeslagen in beveiligde cloudomgevingen (bijv. OneDrive, Google Drive met beveiligingsopties)?

### Te stellen vragen:

1. Welke online diensten gebruikt het bedrijf dagelijks?
2. Worden regelmatig back-ups gemaakt van belangrijke bestanden?
3. Wie heeft toegang tot gedeelde documenten of mappen in de cloud?

### Acties:

- **Controleer de toegang tot online diensten en stel indien nodig beveiligingsopties in**.  
  _Verbindt met Lemma: PR.DS-1 (Data Security: Bescherming van gegevens in rust)_

- **Adviseer om regelmatig back-ups te maken en deze op een veilige plek op te slaan**.  
  _Verbindt met Lemma: PR.IP-1 (Information Protection: Back-ups van informatie worden uitgevoerd, onderhouden en getest)_

- **Leg uit hoe je cloudopslag veilig instelt, inclusief toegangsrechten en 2FA**.  
  _Verbindt met Lemma: PR.AC-7 (Identity Management: Beheer van toegang tot kritieke informatie en technologie)_

---

## 4. Beveiliging van bedrijfswebsite (15-20 minuten)

### Controlepunten:

- Is de website beveiligd met een HTTPS-verbinding (SSL-certificaat)?
- Wordt de website regelmatig bijgewerkt, inclusief eventuele plugins en thema's?
- Heeft de website een contactformulier of andere functies die beveiligd moeten worden tegen spam of misbruik?

### Te stellen vragen:

1. Wie beheert de website en implementeert updates?
2. Wordt er regelmatig gecontroleerd op verdachte activiteiten of hacks?
3. Hoe wordt klantinformatie die via de website binnenkomt, beschermd?

### Acties:

- **Adviseer een gratis of betaald SSL-certificaat als dit nog ontbreekt**.  
  _Verbindt met Lemma: PR.DS-2 (Data Security: Bescherming van gegevens in transit)_

- **Controleer of het CMS (bijv. WordPress) en plugins up-to-date zijn**.  
  _Verbindt met Lemma: PR.MA-1 (Onderhoud: Ondersteunde software gebruiken en controleren op updates)_

- **Leg uit hoe regelmatig onderhoud aan de website risico's kan verminderen**.  
  _Verbindt met Lemma: PR.PT-1 (Protective Technology: Bescherming van communicatie en controle netwerken)_

---

## Documentatie en rapportage

### Tijdens de audit:

- Noteer zwakke plekken, zoals ontbrekende updates of zwakke wachtwoorden.
- Geef prioriteiten aan risico’s die eenvoudig op te lossen zijn (bijv. een sterker wachtwoord of inschakelen van 2FA).
- Zorg dat aanbevelingen duidelijk en uitvoerbaar zijn, bijvoorbeeld "Controleer maandelijks de routerinstellingen."

### Eindresultaat:

Een samenvatting van de belangrijkste externe beveiligingsrisico’s en praktische stappen die het bedrijf kan nemen om deze te verminderen. Dit helpt kleine bedrijven om hun externe beveiliging eenvoudig maar effectief te verbeteren, met duidelijke koppelingen naar de NIS2-vereisten en de bijbehorende lemmas.
