[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Shopify & Etsy btw-calculator: multi-land belastingcompliance-sjabloon en werkboek

![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform: Browser + Excel](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-green.svg)
![Tool Type: VAT Compliance & Decision Support](https://img.shields.io/badge/Tool-VAT%20Decision%20Support-orange.svg)

**Automatiseer je grensoverschrijdende e-commerce belastingcompliance met deze gratis Shopify en Etsy btw-calculator (omzetbelasting). Deze herbruikbare Excel-sjabloon en browsergebaseerde boekhoudtool reconcileert maandelijkse multi-land btw-aangiften, OSS-aangiften (One Stop Shop) en omzetbelastingverplichtingen direct — zonder handmatige spreadsheetfouten en zonder softwareabonnement.**

**Geen registratie. Geen installatie. Gratis in je browser.**

Test je transactiegegevens in de gratis browserversie. Voor terugkerende maandelijkse boekhouding upgrade je naar het downloadbare Excel-formaat (met 30 dagen geld-terug-garantie, zonder vragen).
>
> 🌐 **Voer directe belastingreconciliatie uit** → [*Probeer de gratis btw-calculator-app in de browser*](https://hyvoid.github.io/shopify-etsy-vat-calculator/)
>
> 📥 **Automatiseer maandelijkse aangiften** → [*Download het herbruikbare Excel-sjabloon voor btw-boekhouding*](https://www.theseusworkshop.com/l/ytjhap?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=shopify-etsy-vat-dashboard)
>
> Verkrijgbaar in zowel **browsergebaseerde HTML-software** als **macrovrij Excel-werkboek**.

---

## Btw-pijnpunten in e-commerce en geautomatiseerde oplossingen (Wat het je helpt bijhouden)

In plaats van basisstatistieken op te sommen, laat deze belastingreconciliatiesjabloon zien hoe je e-commerce boekhoudpijnpunten worden gemapt op uitvoerbare aangifteoplossingen:

* **Pijnpunt:** gefragmenteerde multikanaals CSV-exports.
  * **Oplossing:** consolideert maandelijks verschuldigde btw per land uit Shopify en Etsy in één *enkel rapportagegrootboek*.
* **Pijnpunt:** ondoorzichtige netto-omzetcijfers.
  * **Oplossing:** berekent bruto-omzet, netto-omzet, verschuldigde btw, restitutie-btw en definitieve belastingverplichtingen tegelijk voor auditklare rapportage.
* **Pijnpunt:** stille fouten in belastingjurisdictietoewijzingen.
  * **Oplossing:** markeert transacties met ontbrekende landkoppelingen, onjuiste belastingaannames of rapportage-inconsistenties vóór de aangifte.
* **Pijnpunt:** te veel betaalde grensoverschrijdende belasting door marketplace-berekeningslogica.
  * **Oplossing:** controleert door het platform geïnde belastingbedragen tegen je intern berekende btw-verplichtingen.
* **Pijnpunt:** geld verliezen bij klantretouren.
  * **Oplossing:** automatiseert restitutiegebonden btw-terugvorderingen die anders in je OSS-aangiften zouden ontbreken.
* **Pijnpunt:** aangiftestress op het laatste moment.
  * **Oplossing:** geeft een definitieve aangiftegereedheidsstatus voordat je btw- of OSS-aangiften indient bij de belastingdienst.

---

# Waarom ik deze belastingreconcilietool heb gebouwd

De meeste kleine en middelgrote grensoverschrijdende e-commercebedrijven struikelen niet omdat IOSS- (Import One-Stop Shop) of EU-btw-regels onmogelijk te begrijpen zijn.

Ze struikelen omdat btw-berekeningen versplinteren over winkelplatforms, ruwe CSV-exports, externe accountants, marketplaces en lokale belastingjurisdicties.

Een typische handmatige boekhoudworkflow ziet er vaak zo uit:
1. Exporteer de financiële rapporten van Shopify.
2. Exporteer de transactieoverzichten van Etsy.
3. Plak ruwe gegevens in aparte, snel kapotte spreadsheets.
4. Bereken jurisdictiespecifieke btw handmatig.
5. Vergelijk door de marketplace geïnde belasting met de boekhoudkundige aannames.
6. Ontdek belastingverschillen tijdens de late avonden van aangiftevoorbereiding.

De echte analytische fout is niet "onjuiste Excel-belastingformules". De fout is **belastingbeslissingen nemen zonder één eenduidig model op transactieniveau van je omzetbelastingverplichting**.

Bijvoorbeeld:

| Belastingbeoordelingsscenario | Traditionele handmatige boekhouding |
| ----------------------- | ----------------------------- |
| Bruto-omzet Duitsland (DE)| €42,800                       |
| Verondersteld lokaal btw-tarief  | 19%                           |
| Door Shopify geïnde belasting   | €6,750                        |
| Werkelijk berekende btw   | €6,832                        |
| **Reconciliatieverschil**| **€82**                    |

Een verschil van €82 lijkt misschien verwaarloosbaar. Maar vermenigvuldigd over vier EU-landen, twee marketplace-platforms, honderden restituties en kwartaal-OSS-aangifteperioden wordt het probleem een systemisch reconcilieprobleem in plaats van een simpele rekenfout.

Dit werkboek maakt van een herhaalbaar e-commerce analytisch kader een product:

> **Importeer ruwe exports eenmaal → normaliseer gegevens automatisch eenmaal → valideer afwijkingen eenmaal → genereer herhaaldelijk nauwkeurige belastingaangifte-resultaten.**

Het doel is geen automatisering om de automatisering. Het doel is weten:
> **"Kan de multi-land btw-aangifte van deze maand met 100% vertrouwen worden ingediend bij de belastingdienst?"**

---

## Btw-compliancevergelijking: traditioneel vs. geautomatiseerd

| Veelvoorkomend complianceprobleem        | Traditionele handmatige boekhoudworkflow | Geautomatiseerde btw-werkboekoplossing            |
| ---------------------------------------- | -------------------------------------- | ------------------------------------------- |
| **Gefragmenteerde verkopen over platforms**   | Shopify- en Etsy-gegevens handmatig consolideren via VLOOKUPs | Gegevens opnemen in een voorgebouwd, uniform transactiegrootboek |
| **Ontbrekende grensoverschrijdende belastingkoppelingen**    | Rapportagefouten pas laat ontdekken bij upload naar het aangifteportaal | Ontbrekende jurisdicties automatisch markeren in het validatiedashboard |
| **Verschillen tussen marketplace en werkelijke belasting** | Platformlogica handmatig regel voor regel reconciliëren | Automatische afwijkingsdetectie activeren voor verschillen > €1.00 |
| **Verrekening van restitutie-btw**          | Restitutiebelasting-terugvordering weglaten, met te veel betaling als gevolg | Restitutie-btw-verrekeningen automatisch berekenen voor nauwkeurige aftrek |
| **Maandelijkse aangiftevoorbereiding**           | De belastingtracking-spreadsheet elke rapportagecyclus opnieuw opbouwen | Gestructureerde aangifte-output automatisch genereren via dynamische arrays |
| **Validatie van compliancegereedheid**      | Volledig vertrouwen op handmatige controle door een externe boekhouder | Vertrouwen op systematische uitzonderingscontrole vóór de definitieve belastingaangifte |

---

## Praktijkscenario's voor btw-compliance voor grensoverschrijdende teams

Dit sjabloon dekt workflowbehoeften met hoge intentie in verschillende operationele scenario's:

* **Kwartaalgewijze OSS-/IOSS-aangiften:** B2C-grensoverschrijdende omzet in de hele EU aggregeren voor nauwkeurige rapportage aan het belastingportaal.
* **Multikanaals marketplace-reconciliatie:** de kloof overbruggen tussen de marketplace-facilitator-belastinglogica van Etsy en de zelfstandige belastinginning door Shopify-handelaren.
* **Auditvoorbereiding en grootboekback-up:** een back-up op transactieniveau van alle belastingberekeningen bijhouden ter verdediging bij jurisdictiebelastingcontroles.
* **Winstgevendheids- en nettomargeanalyse:** de btw-component uit de bruto marketplace-uitkeringen halen om de werkelijke netto productomzet te begrijpen.

---

## Voor wie is dit? (Doelrollen en use cases)

Deze tool is expliciet ontworpen om specifieke rollen te koppelen aan hun operationele knelpunten:

* **Shopify International-handelaren** die een *geautomatiseerde EU-btw-berekeningssjabloon* nodig hebben om foutgevoelige handmatige spreadsheets te vervangen.
* **Etsy-verkopers** die op zoek zijn naar *maandelijkse belastingcompliance-trackersoftware* die restitutieverrekeningen automatisch verwerkt.
* **E-commerce financiële managers** die een *multikanaals belastingreconciliespreadsheet* zoeken om uiteenlopende gegevensstromen te verenigen.
* **Fractional CFO's en boekhouders** die meerdere klantportefeuilles beheren met een gestandaardiseerd *grensoverschrijdend boekhoud-dashboard*.
* **Btw-consultants** die een robuust *belastingdiagnose- en validatiewerkboek* nodig hebben voor klantonboarding.

Deze tool is **niet** bedoeld voor:
* ERP-vervangingsprojecten (bijv. NetSuite of SAP).
* Enterprise wereldwijde belastingengines (bijv. Avalara of Vertex).
* API-gateways voor geautomatiseerde belastingaangiften.
* Plugins voor realtime transactiebelastingberekening bij de checkout.

Geavanceerde spreadsheetkennis is niet vereist.

---

## Snelle start-workflow: reconcileer je eerste btw-aangifte

Volg dit gestroomlijnde operationele protocol om vandaag nog je belastingverplichtingen te controleren:

1. **Platformgegevens exporteren:** download je standaard CSV-transactierapporten uit de Shopify- en Etsy-verkopersdashboards voor de doelrapportagemaand.
2. **Voer de diagnose uit:** plak je ruwe gegevens in de [*Gratis btw-calculator in de browser*](https://hyvoid.github.io/shopify-etsy-vat-calculator/) om direct een belastinggezondheidscheck uit te voeren.
3. **Los uitzonderingen op:** gebruik het Validatiecentrum om niet-gekoppelde landcodes, afwijkingswaarschuwingen en niet-teruggevorderde restitutiebelasting te identificeren.
4. **Automatiseer toekomstige aangiften:** zodra je gegevens schoon zijn, genereer je definitieve btw-aangifterapport. Voor doorlopende maandelijkse bedrijfsvoering **[download je het herbruikbare Excel-btw-werkboek](https://www.theseusworkshop.com/l/ytjhap?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=shopify-etsy-vat-dashboard)** om je aangepaste jurisdictiekoppelingen vast te leggen, herhaalde instellingen te elimineren en je grensoverschrijdende compliance permanent te standaardiseren.

---

## Technische details

<details>
<summary>Voor technische reviewers, Excel-boekhoudpractici en financieel analisten</summary>

---

### Werkboekarchitectuur

Het werkboek volgt een vierlaagse analytische architectuur, ontworpen voor financiële gegevensintegriteit:

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

| Bladnaam | Architectuurlaag | Kernboekhoudkundig doel |
| --- | --- | --- |
| Control Panel | Presentatie | Parameters en KPI-monitoring |
| Shopify Import | Data-opname | Shopify ruwe CSV-opname |
| Etsy Import | Data-opname | Etsy ruwe CSV-opname |
| Normalization Engine | Data-engineering | Uniform transactiegrootboek |
| VAT Calculation Engine | Berekening | Belastingberekening en -toewijzing |
| Validation Center | Kwaliteitsborging | Uitzonderingsdetectie |
| Monthly VAT Report | Output | Aangifteklaar rapport |

**Vuistregel:** validatie vindt altijd plaats voordat rapportage-output operationeel betrouwbaar is.

---

### Drie valkuilen die zelfs ervaren e-commerce financiële teams vangen

#### Valkuil 1 — Ervan uitgaan dat platformbelasting gelijk is aan de werkelijke belastingverplichting

1. Er is een aangiftebeslissing genomen.
2. De beslissing was uitsluitend gebaseerd op door de marketplace geïnde belastingbedragen.
3. De belastinglogica van het platform week af van de regels van de lokale aangiftejurisdictie.
4. Het uiteindelijk ingediende bedrag bleek onjuist.

| Metriek | Marketplace-platform | Werkelijke verplichting |
| --- | --- | --- |
| Bruto-omzet | €50,000 | €50,000 |
| Platformbelasting | €7,600 | — |
| Berekende btw | — | €8,042 |

**Onjuiste conclusie:**

```text
VAT payable = Platform tax collected

```

**Juiste aanpak:**

```text
VAT payable = Gross Sales - Net Sales - Refund VAT adjustments

```

```excel
Net Sales = Gross/(1+VAT Rate)
Output VAT = Gross-Net Sales
Net VAT Payable = Output VAT-Refund VAT

```

---

#### Valkuil 2 — Restitutiebelastingterugvordering negeren

1. Er vonden klantrestituties plaats.
2. Btw-terugvorderingsberekeningen werden weggelaten.
3. De totale belastingverplichting bleef overdreven, wat nettomarge kostte.

| Grootboekpost | Zonder belastingterugvordering | Met belastingterugvordering |
| --- | --- | --- |
| Verkoop-btw | €12,300 | €12,300 |
| Restitutie-btw | €0 | €1,120 |
| Definitieve btw | €12,300 | €11,180 |

De kritische analytische fout is restituties te behandelen als bruto-omzetcorrecties in plaats van als specifieke correcties van de belastingverplichting.

```excel
Refund VAT = Refund Amount × VAT Rate ÷ (1+VAT Rate)

```

---

#### Valkuil 3 — Ervan uitgaan dat landcodes van klanten altijd accuraat zijn

1. De aangifteberekeningen werden uitgevoerd.
2. Standaardlandtoewijzingen bevatten lege of foutieve gegevens.
3. De btw-jurisdictietoewijzing werd fundamenteel gebrekkig.

Voorbeeld van stille mislukking:

| Transactie-ID | Factuurland |
| --- | --- |
| TX-10025 | DE |
| TX-10026 | BLANK |
| TX-10027 | XX |

Zonder programmatische validatie glippen deze niet-gekoppelde transacties stil in je definitieve belastingaangiften.

**Gecorrigeerde validatieaanpak:**

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

### Formelereferentie en afhankelijkheden

```excel
FILTER()
VSTACK()
CHOOSECOLS()
MAP()
LET()
HSTACK()

```

*Doel:* lege rijen verwijderen, platformschema normaliseren, landcodes standaardiseren, transactiegrootboek opbouwen.

```excel
XLOOKUP()
SUMIFS()
MAP()

```

*Doel:* dynamische btw-lookup, jurisdictiebelastingtoewijzing, extractie van restitutie-terugvorderingen, berekening van netto verschuldigd bedrag.

```excel
FILTER()
TEXTJOIN()
ABS()
IF()
LET()

```

*Doel:* uitzonderingsdetectie, generatie van diagnostische payloads, belastingaangifte-controlepoort.

</details>

---

## De bedrijfslogica en methodologie

Deze tool is niet zomaar een berekeningsspreadsheet; het is een operationele methodologie die je nettomarge beschermt en auditgereedheid waarborgt. Het lost het kernbedrijfsprobleem van **multikanaals financiële fragmentatie** op door enterprise-grade reconcilieprincipes toe te passen op grensoverschrijdende e-commerce van het MKB.

Dit is de methodologie die het systeem aandrijft:

### 1. Gegevensnormalisatie (single source of truth)
*   **Het bedrijfsprobleem:** Shopify en Etsy exporteren transactiegegevens in totaal verschillende rapportageschema's. Handmatig vergelijken leidt tot versiechaos en kapotte VLOOKUPs.
*   **De methodologie:** de tool fungeert als een lichtgewicht ETL-pipeline (Extract, Transform, Load). Het neemt automatisch uiteenlopende ruwe CSV-exports op en normaliseert ze tot een gestandaardiseerd, uniform transactiegrootboek — een single source of truth voor je compliancegegevens.

### 2. Zero-trust belastingherberekening
*   **Het bedrijfsprobleem:** blind vertrouwen op "belasting geïnd"-cijfers van marketplaces leidt vaak tot jurisdictiefouten in rapportage, omdat platformalgoritmen mogelijk niet aansluiten bij jouw specifieke nexusverplichtingen of productbelastingklassen.
*   **De methodologie:** de engine gebruikt een "zero-trust" berekeningsmodel. Het herberekent je werkelijke belastingverplichting *bottom-up* op basis van bruto-omzet en jouw geconfigureerde jurisdictietarieven en controleert deze basislijn tegen de door het platform geïnde belasting om verborgen rekenafwijkingen bloot te leggen.

### 3. Management by exception
*   **Het bedrijfsprobleem:** elke maand handmatig duizenden microtransacties beoordelen voor een OSS-aangifte is een onhoudbare aanslag op financiële middelen.
*   **De methodologie:** de architectuur verschuift je boekhoudworkflow naar "uitzonderingsgebaseerd management". In plaats van elke rij te controleren isoleert het Validatiecentrum alleen de anomalieën — ontbrekende landcodes, lege belastingtarieven of inningsverschillen groter dan €1.00 — zodat je je volledig richt op het oplossen van hoogrendabele problemen.

### 4. Nettomargeherstel via restitutieverrekeningen
*   **Het bedrijfsprobleem:** veel grensoverschrijdende handelaren behandelen klantretouren puur als omzetcorrecties en vorderen de bijbehorende verschuldigde btw niet systematisch terug, waardoor nettowinst lekt naar belastingdiensten.
*   **De methodologie:** de berekeningsengine isoleert programmatisch restitutietransacties en koppelt ze terug aan hun jurisdicties van herkomst. Het past automatisch belastingcreditverrekeningen toe op je bruto verschuldigde btw, zodat je de belastingkosten van terugbetaalde verkopen nooit zelf draagt.

---


## Andere operationele tools in deze serie

* **Inventory Planning & Replenishment Console** — sjabloon voor besteloptimalisatie en voorraadrisicobeheer.
* **Marketing Attribution Audit System** — kanaalattributievalidering en ROAS-efficiëntieanalyse.
* **Project Cost Allocation Workbench** — spreadsheet voor personeelsallocatie en projectwinstgevendheid.
* **Multi-Entity Logistics Control Tower** — dashboard voor grensoverschrijdende zendingen en douanemonitoring.

Ontdek meer beslissingsondersteunende kaders en sjablonen via het GitHub-profiel en onze [website](https://www.theseusworkshop.com/).

---

## Licentie

Dit project is gelicentieerd onder de **Apache License 2.0**.

Zie het LICENSE-bestand voor details.
