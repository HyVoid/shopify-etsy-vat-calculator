[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Shopify- & Etsy-USt-Rechner: Vorlage & Arbeitsmappe für Steuercompliance in mehreren Ländern

![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform: Browser + Excel](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-green.svg)
![Tool Type: VAT Compliance & Decision Support](https://img.shields.io/badge/Tool-VAT%20Decision%20Support-orange.svg)

**Automatisieren Sie Ihre grenzüberschreitende E-Commerce-Steuercompliance mit diesem kostenlosen Shopify- und Etsy-USt-Rechner (Umsatzsteuer). Diese wiederverwendbare Excel-Vorlage und dieses browserbasierte Buchhaltungstool gleichen monatliche USt-Anmeldungen in mehreren Ländern, OSS-Erklärungen (One-Stop-Shop) und Umsatzsteuerverbindlichkeiten sofort ab – ohne manuelle Tabellenkalkulationsfehler und ohne Software-Abo.**

**Keine Registrierung. Keine Installation. Kostenlos im Browser.**

Testen Sie Ihre Transaktionsdaten in der kostenlosen Browserversion. Für die laufende monatliche Buchhaltung wechseln Sie zum herunterladbaren Excel-Format (mit 30-tägiger bedingungsloser Geld-zurück-Garantie).
>
> 🌐 **Sofortige Steuerabstimmung durchführen** → [*Die kostenlose USt-Rechner-App im Browser ausprobieren*](https://hyvoid.github.io/shopify-etsy-vat-calculator/)
>
> 📥 **Monatliche Anmeldungen automatisieren** → [*Die wiederverwendbare Excel-Vorlage für USt-Buchhaltung herunterladen*](https://www.theseusworkshop.com/l/ytjhap?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=shopify-etsy-vat-dashboard)
>
> Verfügbar als **browserbasierte HTML-Software** und als **makrofreie Excel-Arbeitsmappe**.

---

## USt-Schwachstellen im E-Commerce & automatisierte Lösungen (Was die Vorlage für Sie überwacht)

Statt grundlegende Kennzahlen aufzulisten, zeigt diese Vorlage zur Steuerabstimmung, wie sie typische Buchhaltungsprobleme im E-Commerce auf konkrete Anmeldelösungen abbildet:

* **Schwachstelle:** Zersplitterte CSV-Exporte über mehrere Kanäle.
  * **Lösung:** Konsolidiert die monatlich zahlbare Umsatzsteuer nach Ländern aus Shopify und Etsy in einem *einzigen Berichtsledger*.
* **Schwachstelle:** Intransparente Nettoumsatzzahlen.
  * **Lösung:** Berechnet Bruttoumsätze, Nettoumsätze, geschuldete USt, Erstattungs-USt und endgültige Steuerbelastungen gleichzeitig für prüfungsfähige Berichte.
* **Schwachstelle:** Stille Fehler bei der Zuordnung von Steuerjurisdiktionen.
  * **Lösung:** Markiert Transaktionen mit fehlenden Länderzuordnungen, falschen Steuerannahmen oder Berichtsinkonsistenzen, bevor die Anmeldung erfolgt.
* **Schwachstelle:** Überzahlte grenzüberschreitende Steuern durch Marketplace-Berechnungslogik.
  * **Lösung:** Prüft die von der Plattform einbehobenen Steuerbeträge gegen Ihre intern berechneten USt-Verbindlichkeiten.
* **Schwachstelle:** Verlorenes Geld bei Kundenretouren.
  * **Lösung:** Automatisiert erstattungsbedingte USt-Rückforderungen, die sonst in Ihren OSS-Erklärungen fehlen würden.
* **Schwachstelle:** Anmeldungsstress in letzter Minute.
  * **Lösung:** Liefert einen verbindlichen Anmeldungsstatus, bevor Sie USt-Anmeldungen oder OSS-Erklärungen an das Finanzamt übermitteln.

---

# Warum ich dieses Tool zur Steuerabstimmung gebaut habe

Die meisten kleinen und mittleren grenzüberschreitenden E-Commerce-Unternehmen scheitern nicht, weil IOSS- oder EU-USt-Regeln unverständlich wären.

Sie scheitern, weil die USt-Berechnungen zwischen Shop-Plattformen, rohen CSV-Exporten, externen Steuerberatern, Marketplaces und lokalen Steuerjurisdiktionen zersplittern.

Ein typischer manueller Buchhaltungs-Workflow sieht oft so aus:
1. Shopify-Finanzberichte exportieren.
2. Etsy-Transaktionsabrechnungen exportieren.
3. Rohdaten in separate, leicht fehleranfällige Tabellen einfügen.
4. Länderspezifische USt manuell berechnen.
5. Vom Marketplace einbehobene Steuerbeträge mit den Buchhaltungsannahmen abgleichen.
6. Steuerdiskrepanzen erst bei der nächtlichen Anmeldungsvorbereitung entdecken.

Der eigentliche analytische Fehler sind nicht „falsche Excel-Steuerformeln“. Der Fehler besteht darin, **Steuerentscheidungen ohne ein einheitliches, transaktionsbasiertes Modell Ihrer Umsatzsteuerverbindlichkeit** zu treffen.

Zum Beispiel:

| Szenario der Steuerbewertung | Traditionelle manuelle Buchhaltung |
| ----------------------- | ----------------------------- |
| Bruttoumsätze Deutschland (DE)| €42,800                       |
| Angenommener lokaler USt-Satz  | 19%                           |
| Von Shopify einbehobene Steuer   | €6,750                        |
| Tatsächlich berechnete USt   | €6,832                        |
| **Abstimmungsdifferenz**| **€82**                    |

Eine Differenz von €82 wirkt unerheblich. Multipliziert man sie jedoch über vier EU-Länder, zwei Marketplace-Plattformen, hunderte Erstattungen und quartalsweise OSS-Anmeldezeiträume, wird daraus ein systemisches Abstimmungsproblem statt eines einfachen Rechenfehlers.

Diese Arbeitsmappe macht einen wiederholbaren E-Commerce-Analyserahmen zum Produkt:

> **Rohe Exporte einmal importieren → Daten einmal automatisch normalisieren → Anomalien einmal validieren → präzise Steueranmeldeergebnisse wiederholt erzeugen.**

Das Ziel ist keine Automatisierung um ihrer selbst willen. Das Ziel ist Gewissheit:
> **„Kann die USt-Anmeldung dieses Monats für mehrere Länder mit 100 % Sicherheit beim Finanzamt eingereicht werden?“**

---

## USt-Compliance im Vergleich: manuell vs. automatisiert

| Häufiges Compliance-Problem             | Traditioneller manueller Buchhaltungs-Workflow | Automatisierte USt-Arbeitsmappe             |
| ---------------------------------------- | -------------------------------------- | ------------------------------------------- |
| **Fragmentierte Verkäufe über Plattformen**   | Shopify- und Etsy-Daten manuell per VLOOKUP konsolidieren | Daten in einen vorgefertigten, einheitlichen Transaktionsledger einlesen |
| **Fehlende grenzüberschreitende Steuerzuordnungen**    | Berichtsfehler erst spät beim Upload ins Anmeldeportal entdecken | Fehlende Jurisdiktionen automatisch im Validierungs-Dashboard markieren |
| **Differenzen zwischen Marketplace und tatsächlicher Steuer** | Plattformlogik manuell Zeile für Zeile abstimmen | Automatische Differenzenerkennung für Abweichungen > €1.00 auslösen |
| **Verrechnung der Erstattungs-USt**          | Erstattungssteuer-Rückforderung vergessen und zu viel zahlen | Erstattungs-USt-Verrechnung automatisch für korrekte Abzüge berechnen |
| **Monatliche Anmeldungsvorbereitung**           | Die Steuer-Tracking-Tabelle in jedem Berichtszyklus neu aufbauen | Strukturierte Anmeldeergebnisse automatisch über dynamische Arrays erzeugen |
| **Validierung der Compliance-Bereitschaft**      | Vollständig auf manuelle Prüfung durch externes Buchhaltungspersonal angewiesen | Systematische Ausnahmenkontrolle vor der endgültigen Steueranmeldung |

---

## Praxisnahe USt-Compliance-Szenarien für grenzüberschreitende Teams

Diese Vorlage deckt erfolgskritische Workflow-Bedürfnisse in verschiedenen Betriebsszenarien ab:

* **Quartalsweise OSS-/IOSS-Erklärungen:** Aggregation grenzüberschreitender B2C-Verkäufe in der gesamten EU für eine korrekte Meldung an das Steuerportal.
* **Multikanal-Marketplace-Abstimmung:** Überbrückung der Lücke zwischen der Marketplace-Facilitator-Steuerlogik von Etsy und der eigenständigen Steuererhebung durch Shopify-Händler.
* **Auditvorbereitung & Ledger-Backup:** Transaktionsgenaues Backup aller Steuerberechnungen zur Verteidigung gegen steuerliche Betriebsprüfungen.
* **Rentabilitäts- & Nettomargenanalyse:** Herausrechnen der USt-Komponente aus den Brutto-Marketplace-Auszahlungen, um den echten Nettoproduktumsatz zu verstehen.

---

## Für wen ist das? (Zielrollen & Anwendungsfälle)

Dieses Tool verknüpft bestimmte Rollen ausdrücklich mit ihren operativen Engpässen:

* **Shopify-International-Händler**, die eine *automatisierte EU-USt-Berechnungsvorlage* brauchen, um fehleranfällige manuelle Tabellen zu ersetzen.
* **Etsy-Verkäufer**, die eine *monatliche Software zur Verfolgung der Steuercompliance* suchen, die Erstattungsverrechnungen automatisch übernimmt.
* **E-Commerce-Finanzmanager**, die eine *multikanale Steuerabstimmungstabelle* suchen, um unterschiedliche Datenströme zu vereinen.
* **Fractional CFOs und Buchhalter**, die mehrere Kundenportfolios mit einem standardisierten *grenzüberschreitenden Buchhaltungs-Dashboard* verwalten.
* **USt-Berater**, die eine robuste *Steuerdiagnose- und Validierungsarbeitsmappe* für das Kunden-Onboarding benötigen.

Dieses Tool ist **nicht** geeignet für:
* ERP-Ersatzprojekte (z. B. NetSuite oder SAP).
* Globale Unternehmens-Steuer-Engines (z. B. Avalara oder Vertex).
* API-Gateways für automatisierte Steueranmeldungen.
* Plugins für Echtzeit-Transaktionssteuerberechnung im Checkout.

Fortgeschrittene Tabellenkalkulationskenntnisse sind nicht erforderlich.

---

## Schnellstart-Workflow: Stimmen Sie Ihre erste USt-Anmeldung ab

Folgen Sie diesem schlanken Ablaufprotokoll, um noch heute Ihre Steuerbelastungen zu prüfen:

1. **Plattformdaten exportieren:** Laden Sie Ihre Standard-CSV-Transaktionsberichte aus den Shopify- und Etsy-Händlerdashboards für den Zielberichtsmonat herunter.
2. **Diagnose ausführen:** Fügen Sie Ihre Rohdaten in den [*Kostenlosen USt-Rechner im Browser*](https://hyvoid.github.io/shopify-etsy-vat-calculator/) ein, um einen sofortigen Steuer-Gesundheitscheck durchzuführen.
3. **Ausnahmen beheben:** Nutzen Sie das Validierungszentrum, um nicht zugeordnete Ländercodes, Differenzwarnungen und nicht zurückgeforderte Erstattungssteuern zu identifizieren.
4. **Künftige Anmeldungen automatisieren:** Sobald Ihre Daten sauber sind, erzeugen Sie Ihren finalen USt-Anmeldebericht. Für den laufenden Monatsbetrieb **[laden Sie die wiederverwendbare Excel-USt-Arbeitsmappe herunter](https://www.theseusworkshop.com/l/ytjhap?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=shopify-etsy-vat-dashboard)**, um Ihre benutzerdefinierten Jurisdiktionszuordnungen zu fixieren, wiederkehrende Einrichtung zu eliminieren und Ihre grenzüberschreitende Compliance dauerhaft zu standardisieren.

---

## Technische Details

<details>
<summary>Für technische Prüfer, Excel-Buchhaltungspraktiker und Finanzanalysten</summary>

---

### Arbeitsmappen-Architektur

Die Arbeitsmappe folgt einer vierstufigen Analysearchitektur, die auf die Integrität finanzieller Daten ausgelegt ist:

```text
DATA INPUT
    ↓
NORMALIZATION ENGINE
    ↓
VAT CALCULATION ENGINE
    ↓
VALIDATION CENTER
    ↓
MONTHLY VAT REPORT (AUDIT-READY)

```

| Blattname | Architekturschicht | Hauptbuchhaltungszweck |
| --- | --- | --- |
| Control Panel | Präsentation | Parameter- und KPI-Überwachung |
| Shopify Import | Datenaufnahme | Shopify-Roh-CSV-Einlesen |
| Etsy Import | Datenaufnahme | Etsy-Roh-CSV-Einlesen |
| Normalization Engine | Datenengineering | Einheitlicher Transaktionsledger |
| VAT Calculation Engine | Berechnung | Steuerberechnung und -verteilung |
| Validation Center | Qualitätssicherung | Ausnahmeerkennung |
| Monthly VAT Report | Ausgabe | Anmeldefähiger Bericht |

**Faustregel:** Die Validierung erfolgt immer, bevor Berichtsergebnisse operationell vertrauenswürdig sind.

---

### Drei Fallen, die selbst erfahrene E-Commerce-Finanzteams erwischen

#### Falle 1 — Plattformsteuer mit tatsächlicher Steuerbelastung gleichsetzen

1. Es wurde eine Anmeldungsentscheidung getroffen.
2. Die Entscheidung stützte sich ausschließlich auf die vom Marketplace einbehobenen Steuerbeträge.
3. Die Steuerlogik der Plattform wich von den Regeln der lokalen Anmeldejurisdiktion ab.
4. Der endgültig angemeldete Betrag wurde ungenau.

| Kennzahl | Marketplace-Plattform | Tatsächliche Belastung |
| --- | --- | --- |
| Bruttoumsätze | €50,000 | €50,000 |
| Plattformsteuer | €7,600 | — |
| Berechnete USt | — | €8,042 |

**Falsche Schlussfolgerung:**

```text
VAT payable = Platform tax collected

```

**Richtiger Ansatz:**

```text
VAT payable = Gross Sales - Net Sales - Refund VAT adjustments

```

```excel
Net Sales = Gross/(1+VAT Rate)
Output VAT = Gross-Net Sales
Net VAT Payable = Output VAT-Refund VAT

```

---

#### Falle 2 — Erstattungssteuer-Rückforderung ignorieren

1. Es kam zu Kundenerstattungen.
2. Die Berechnung der USt-Rückforderung wurde ausgelassen.
3. Die Gesamtsteuerbelastung blieb überhöht und verzehrte die Nettomarge.

| Ledger-Posten | Ohne Steuerückforderung | Mit Steuerückforderung |
| --- | --- | --- |
| Verkaufs-USt | €12,300 | €12,300 |
| Erstattungs-USt | €0 | €1,120 |
| Endgültige USt | €12,300 | €11,180 |

Der entscheidende analytische Fehler besteht darin, Erstattungen als Bruttoumsatzkorrekturen statt als spezifische Korrekturen der Steuerbelastung zu behandeln.

```excel
Refund VAT = Refund Amount × VAT Rate ÷ (1+VAT Rate)

```

---

#### Falle 3 — Voraussetzen, dass Kundenländercodes immer korrekt sind

1. Die Anmeldeberechnungen wurden ausgeführt.
2. Standard-Länderzuordnungen enthielten leere oder fehlerhafte Daten.
3. Die Verteilung der USt-Jurisdiktionen wurde grundlegend fehlerhaft.

Beispiel eines stillen Fehlers:

| Transaktions-ID | Rechnungsland |
| --- | --- |
| TX-10025 | DE |
| TX-10026 | BLANK |
| TX-10027 | XX |

Ohne programmatische Validierung gelangen diese nicht zugeordneten Transaktionen still in Ihre endgültigen Steueranmeldungen.

**Korrigierter Validierungsansatz:**

```text
IF Country is missing
OR VAT rate is unmapped
OR Tax variance > threshold
THEN Generate Exception Flag

```

```excel
err_country = country=""
err_unmapped = vat_rate=0
err_tax = ABS(platform-calculated)>1

```

---

### Formelreferenz & Abhängigkeiten

```excel
FILTER()
VSTACK()
CHOOSECOLS()
MAP()
LET()
HSTACK()

```

*Zweck:* Leere Zeilen entfernen, Plattformschema normalisieren, Ländercodes standardisieren, Transaktionsledger aufbauen.

```excel
XLOOKUP()
SUMIFS()
MAP()

```

*Zweck:* Dynamische USt-Suche, steuerliche Jurisdiktionsverteilung, Extraktion der Erstattungsrückforderungen, Berechnung des Nettobetrags.

```excel
FILTER()
TEXTJOIN()
ABS()
IF()
LET()

```

*Zweck:* Ausnahmeerkennung, Erzeugung von Diagnose-Datenpaketen, Steueranmelde-Kontrollgate.

</details>

---

## Die Geschäftslogik & Methodik

Dieses Tool ist nicht nur eine Berechnungstabelle; es ist eine operationale Methodik zum Schutz Ihrer Nettomarge und zur Sicherstellung der Prüfungsbereitschaft. Es löst das Kerngeschäftsproblem der **multikanalen Finanzfragmentierung**, indem es Abstimmungsprinzipien auf Enterprise-Niveau auf den grenzüberschreitenden E-Commerce von KMU anwendet.

Hier ist die Methodik, die das System antreibt:

### 1. Datennormalisierung (Single Source of Truth)
*   **Das Geschäftsproblem:** Shopify und Etsy exportieren Transaktionsdaten in völlig unterschiedlichen Berichtsschemata. Manueller Vergleich führt zu Versionschaos und defekten VLOOKUPs.
*   **Die Methodik:** Das Tool fungiert als schlanke ETL-Pipeline (Extract, Transform, Load). Es liest automatisch unterschiedliche Roh-CSV-Exporte ein und normalisiert sie zu einem standardisierten, einheitlichen Transaktionsledger – eine Single Source of Truth für Ihre Compliance-Daten.

### 2. Zero-Trust-Steuerneuberechnung
*   **Das Geschäftsproblem:** Blindes Vertrauen auf „Tax Collected“-Werte des Marketplace führt oft zu Fehlmeldungen nach Jurisdiktion, da Plattformalgorithmen nicht mit Ihren konkreten Nexus-Verpflichtungen oder Produktsteuerklassen übereinstimmen.
*   **Die Methodik:** Die Engine nutzt ein „Zero-Trust“-Berechnungsmodell. Sie berechnet Ihre tatsächliche Steuerbelastung *Bottom-up* aus Bruttoumsätzen und Ihren konfigurierten Jurisdiktionsraten neu und prüft diese Basislinie gegen die von der Plattform einbehobene Steuer, um versteckte Rechenabweichungen aufzudecken.

### 3. Management by Exception
*   **Das Geschäftsproblem:** Tausende Mikrotransaktionen monatlich manuell für eine OSS-Erklärung zu prüfen, ist eine nicht tragfähige Belastung der Finanzressourcen.
*   **Die Methodik:** Die Architektur verlagert Ihren Buchhaltungs-Workflow auf „ausnahmebasiertes Management“. Statt jede Zeile zu prüfen, isoliert das Validierungszentrum nur die Anomalien – fehlende Ländercodes, leere Steuersätze oder Erhebungsabweichungen über €1.00 –, sodass Sie sich voll auf die Lösung wirkungsvoller Probleme konzentrieren können.

### 4. Nettomargenrückgewinnung durch Erstattungsverrechnung
*   **Das Geschäftsproblem:** Viele grenzüberschreitende Händler behandeln Kundenretouren nur als Umsatzkorrekturen und holen die zugehörige geschuldete USt nicht systematisch zurück – der Nettogewinn geht so an die Steuerbehörden verloren.
*   **Die Methodik:** Die Berechnungs-Engine isoliert programmatisch Erstattungstransaktionen und ordnet sie ihren Ursprungsjurisdiktionen zu. Sie wendet automatisch Steuerguthaben-Verrechnungen gegen Ihre Brutto-USt-Zahlung an, damit Sie die Steuerlast erstatteter Verkäufe nie selbst tragen.

---


## Weitere operative Tools dieser Serie

* **Inventory Planning & Replenishment Console** — Vorlage zur Bestelloptimierung und Bestandsrisikosteuerung.
* **Marketing Attribution Audit System** — Kanalattributionsvalidierung und ROAS-Effizienzanalyse.
* **Project Cost Allocation Workbench** — Tabelle für Personalkostenverteilung und Projektrentabilität.
* **Multi-Entity Logistics Control Tower** — Dashboard zur Überwachung grenzüberschreitender Sendungen und Zollabwicklung.

Entdecken Sie weitere Entscheidungsunterstützungs-Frameworks und Vorlagen über das GitHub-Profil und unsere [Website](https://www.theseusworkshop.com/).

---

## Lizenz

Dieses Projekt ist unter der **Apache License 2.0** lizenziert.

Details finden Sie in der LICENSE-Datei.
