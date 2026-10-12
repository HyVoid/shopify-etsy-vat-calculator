[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Calculateur de TVA Shopify & Etsy : Modèle et classeur de conformité fiscale multi-pays

![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform: Browser + Excel](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-green.svg)
![Tool Type: VAT Compliance & Decision Support](https://img.shields.io/badge/Tool-VAT%20Decision%20Support-orange.svg)

**Automatisez la conformité fiscale de votre e-commerce transfrontalier avec ce calculateur de TVA (taxe sur la valeur ajoutée) gratuit pour Shopify et Etsy. Ce modèle Excel réutilisable et cet outil comptable basé navigateur rapprochent instantanément les déclarations mensuelles de TVA multi-pays, les déclarations OSS (guichet unique) et les dettes fiscales sur les ventes — en éliminant les erreurs manuelles de tableur, sans abonnement logiciel.**

**Aucune inscription. Aucune installation. Gratuit dans votre navigateur.**

Testez les données de vos transactions dans la version navigateur gratuite. Pour une comptabilité mensuelle récurrente, passez au format Excel téléchargeable (avec garantie de remboursement de 30 jours, sans condition).
>
> 🌐 **Lancer le rapprochement fiscal instantané** → [*Essayer l'application gratuite de calcul de TVA dans le navigateur*](https://hyvoid.github.io/shopify-etsy-vat-calculator/)
>
> 📥 **Automatiser les déclarations mensuelles** → [*Télécharger le modèle Excel réutilisable de comptabilité TVA*](https://www.theseusworkshop.com/l/ytjhap?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=shopify-etsy-vat-dashboard)
>
> Disponible à la fois en **logiciel HTML basé navigateur** et en **classeur Excel sans macros**.

---

## Points de friction de la TVA e-commerce et solutions automatisées (Ce que l'outil vous aide à suivre)

Plutôt que de lister des indicateurs basiques, voici comment ce modèle de rapprochement fiscal relie vos points de friction comptables e-commerce à des solutions de déclaration concrètes :

* **Point de friction :** Exports CSV fragmentés sur plusieurs canaux.
  * **Solution :** Consolide la TVA mensuelle à payer par pays, Shopify et Etsy confondus, dans un *registre de reporting unique*.
* **Point de friction :** Chiffres de chiffre d'affaires net opaques.
  * **Solution :** Calcule simultanément ventes brutes, ventes nettes, TVA collectée, TVA sur remboursements et dettes fiscales finales pour un reporting prêt pour l'audit.
* **Point de friction :** Erreurs silencieuses d'affectation des juridictions fiscales.
  * **Solution :** Signale les transactions comportant des correspondances de pays manquantes, des hypothèses fiscales incorrectes ou des incohérences de reporting avant la déclaration.
* **Point de friction :** Surpaiement de taxes transfrontalières dû à la logique de calcul des places de marché.
  * **Solution :** Audite les montants de taxe collectés par la plateforme par rapport à vos obligations de TVA calculées en interne.
* **Point de friction :** Argent perdu lors des retours clients.
  * **Solution :** Automatise les récupérations de TVA liées aux remboursements, autrement omises de vos déclarations OSS.
* **Point de friction :** Stress de déclaration de dernière minute.
  * **Solution :** Fournit un statut de préparation définitif avant de soumettre les déclarations de TVA ou OSS à l'administration fiscale.

---

# Pourquoi j'ai construit cet outil de rapprochement fiscal

La plupart des petites et moyennes entreprises d'e-commerce transfrontalier ne peinent pas parce que les règles IOSS (Import One-Stop Shop) ou de TVA UE seraient incompréhensibles.

Elles peinent parce que les calculs de TVA se fragmentent entre les plateformes de boutique, les exports CSV bruts, les comptables externes, les places de marché et les juridictions fiscales locales.

Un flux comptable manuel type ressemble souvent à ceci :
1. Exporter les rapports financiers Shopify.
2. Exporter les relevés de transactions Etsy.
3. Coller les données brutes dans des tableurs séparés, facilement cassables.
4. Calculer manuellement la TVA propre à chaque juridiction.
5. Comparer les taxes collectées par la place de marché aux hypothèses comptables.
6. Découvrir les écarts fiscaux en pleine préparation de déclaration tard le soir.

L'échec analytique réel n'est pas « des formules Excel fiscales incorrectes ». L'échec, c'est de **prendre des décisions fiscales sans modèle unifié, au niveau des transactions, de votre dette fiscale sur les ventes**.

Par exemple :

| Scénario d'évaluation fiscale | Comptabilité manuelle traditionnelle |
| ----------------------- | ----------------------------- |
| Ventes brutes Allemagne (DE)| €42,800                       |
| Taux de TVA local supposé  | 19%                           |
| Taxe collectée par Shopify   | €6,750                        |
| TVA réellement calculée   | €6,832                        |
| **Écart de rapprochement**| **€82**                    |

Un écart de €82 peut paraître négligeable. Multiplié pourtant sur quatre pays de l'UE, deux places de marché, des centaines de remboursements et des périodes trimestrielles de déclaration OSS, le problème devient un défaut systémique de rapprochement plutôt qu'une simple erreur de calcul.

Ce classeur transforme en produit un cadre analytique e-commerce répétable :

> **Importer les exports bruts une fois → normaliser les données automatiquement une fois → valider les anomalies une fois → générer des résultats de déclaration fiscale précis de façon répétée.**

L'objectif n'est pas l'automatisation pour elle-même. L'objectif, c'est de savoir :
> **« La déclaration de TVA multi-pays de ce mois peut-elle être soumise à l'administration fiscale avec une confiance de 100 % ? »**

---

## Comparaison de conformité TVA : manuel vs automatisé

| Problème de conformité fiscale courant    | Flux comptable manuel traditionnel | Solution automatisée du classeur TVA             |
| ---------------------------------------- | -------------------------------------- | ------------------------------------------- |
| **Fragmentation des ventes multiplateformes**   | Consolider manuellement les données Shopify et Etsy via des VLOOKUP | Ingérer les données dans un registre de transactions unifié préconstruit |
| **Correspondances fiscales transfrontalières manquantes**    | Découvrir les erreurs de reporting tard, lors du téléversement sur le portail de déclaration | Signaler automatiquement les juridictions manquantes dans le tableau de bord de validation |
| **Écarts entre taxe marketplace et taxe réelle** | Effectuer un rapprochement manuel ligne à ligne de la logique de la plateforme | Déclencher une détection automatique des écarts pour toute différence > €1.00 |
| **Traitement de la compensation de TVA sur remboursements**          | Omettre la récupération de taxe sur les remboursements, d'où un trop-payé | Calculer automatiquement les compensations de TVA sur remboursements pour des déductions exactes |
| **Préparation mensuelle de la déclaration**           | Reconstruire le tableur de suivi fiscal à chaque cycle de reporting | Générer automatiquement un résultat de déclaration structuré via des tableaux dynamiques |
| **Validation de la préparation à la conformité**      | Dépendre entièrement de la revue manuelle d'un comptable externe | S'appuyer sur un contrôle systématique des exceptions avant la soumission fiscale finale |

---

## Scénarios réels de conformité TVA pour les équipes transfrontalières

Ce modèle couvre les besoins de flux de travail à forte intention dans divers scénarios opérationnels :

* **Déclarations trimestrielles OSS / IOSS :** agréger les ventes B2C transfrontalières de toute l'UE pour un reporting précis au portail fiscal.
* **Rapprochement multiplaces de marché :** combler l'écart entre la logique de taxe du marketplace facilitator d'Etsy et la collecte de taxe indépendante des marchands Shopify.
* **Préparation d'audit et sauvegarde du registre :** conserver une sauvegarde au niveau transaction de tous les calculs fiscaux pour faire face aux contrôles fiscaux juridictionnels.
* **Analyse de rentabilité et de marge nette :** retirer la composante TVA des versements bruts des places de marché pour connaître le vrai revenu net produit.

---

## À qui cela s'adresse (rôles cibles et cas d'usage)

Cet outil est explicitement conçu pour relier des rôles précis à leurs goulots d'étranglement opérationnels :

* **Marchands internationaux Shopify** ayant besoin d'un *modèle automatisé de calcul de TVA UE* pour remplacer des tableurs manuels sources d'erreurs.
* **Vendeurs Etsy** cherchant un *logiciel mensuel de suivi de conformité fiscale* gérant automatiquement les compensations de remboursements.
* **Responsables financiers e-commerce** cherchant un *tableur de rapprochement fiscal multicanal* pour unifier des flux de données distincts.
* **CFO externalisés et comptables** gérant plusieurs portefeuilles clients avec un *tableau de bord comptable transfrontalier* standardisé.
* **Consultants TVA** nécessitant un *classeur robuste de diagnostic et de validation fiscale* pour l'intégration des clients.

Cet outil n'est **pas** conçu pour :
* Les projets de remplacement d'ERP (p. ex. NetSuite ou SAP).
* Les moteurs fiscaux mondiaux d'entreprise (p. ex. Avalara ou Vertex).
* Les passerelles API de déclaration fiscale automatisée.
* Les plugins de calcul fiscal transactionnel en temps réel au checkout.

Aucune expertise avancée du tableur n'est requise.

---

## Flux de démarrage rapide : rapprochez votre première déclaration de TVA

Suivez ce protocole opérationnel simplifié pour auditer vos dettes fiscales dès aujourd'hui :

1. **Exporter les données de la plateforme :** téléchargez vos rapports CSV de transactions standards depuis les tableaux de bord marchands Shopify et Etsy pour le mois de reporting cible.
2. **Lancer le diagnostic :** collez vos données brutes dans le [*Calculateur de TVA gratuit dans le navigateur*](https://hyvoid.github.io/shopify-etsy-vat-calculator/) pour effectuer un contrôle sanitaire fiscal instantané.
3. **Résoudre les exceptions :** utilisez le Centre de Validation pour identifier les codes pays non mappés, les alertes d'écart et les taxes de remboursement non récupérées.
4. **Automatiser les déclarations futures :** une fois vos données propres, générez votre rapport final de déclaration de TVA. Pour un fonctionnement mensuel continu, **[téléchargez le classeur Excel TVA réutilisable](https://www.theseusworkshop.com/l/ytjhap?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=shopify-etsy-vat-dashboard)** pour figer vos correspondances de juridictions personnalisées, éliminer la configuration répétitive et standardiser durablement votre conformité transfrontalière.

---

## Détails techniques

<details>
<summary>Pour les relecteurs techniques, praticiens de la comptabilité Excel et analystes financiers</summary>

---

### Architecture du classeur

Le classeur suit une architecture analytique en quatre couches conçue pour l'intégrité des données financières :

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

| Nom de la feuille | Couche d'architecture | Objectif comptable principal |
| --- | --- | --- |
| Control Panel | Présentation | Paramètres et suivi des KPI |
| Shopify Import | Ingestion de données | Ingestion du CSV brut Shopify |
| Etsy Import | Ingestion de données | Ingestion du CSV brut Etsy |
| Normalization Engine | Ingénierie des données | Registre de transactions unifié |
| VAT Calculation Engine | Calcul | Calcul et affectation de la taxe |
| Validation Center | Assurance qualité | Détection des exceptions |
| Monthly VAT Report | Sortie | Reporting prêt pour la déclaration |

**Règle empirique :** la validation a toujours lieu avant que les résultats de reporting ne deviennent opérationnellement fiables.

---

### Trois pièges qui prennent au dépourvu même les équipes financières e-commerce expérimentées

#### Piège 1 — Considérer que la taxe de la plateforme égale la dette fiscale réelle

1. Une décision de déclaration fiscale a été prise.
2. La décision reposait uniquement sur les montants de taxe collectés par la place de marché.
3. La logique fiscale de la plateforme différait des règles de la juridiction de déclaration locale.
4. Le montant final déclaré s'est avéré inexact.

| Indicateur | Place de marché | Dette réelle |
| --- | --- | --- |
| Ventes brutes | €50,000 | €50,000 |
| Taxe plateforme | €7,600 | — |
| TVA calculée | — | €8,042 |

**Conclusion incorrecte :**

```text
VAT payable = Platform tax collected

```

**Approche correcte :**

```text
VAT payable = Gross Sales - Net Sales - Refund VAT adjustments

```

```excel
Net Sales = Gross/(1+VAT Rate)
Output VAT = Gross-Net Sales
Net VAT Payable = Output VAT-Refund VAT

```

---

#### Piège 2 — Ignorer la récupération de taxe sur les remboursements

1. Des remboursements clients sont survenus.
2. Les calculs de récupération de TVA ont été omis.
3. La dette fiscale globale est restée surestimée, érodant la marge nette.

| Poste du registre | Sans récupération de taxe | Avec récupération de taxe |
| --- | --- | --- |
| TVA sur ventes | €12,300 | €12,300 |
| TVA sur remboursements | €0 | €1,120 |
| TVA finale | €12,300 | €11,180 |

L'erreur analytique critique consiste à traiter les remboursements comme des ajustements de chiffre d'affaires brut au lieu d'ajustements spécifiques de la dette fiscale.

```excel
Refund VAT = Refund Amount × VAT Rate ÷ (1+VAT Rate)

```

---

#### Piège 3 — Supposer que les codes pays clients sont toujours exacts

1. Les calculs de déclaration ont été exécutés.
2. Les affectations de pays par défaut contenaient des données vides ou erronées.
3. L'affectation des juridictions de TVA est devenue fondamentalement défaillante.

Exemple de défaillance silencieuse :

| ID de transaction | Pays de facturation |
| --- | --- |
| TX-10025 | DE |
| TX-10026 | BLANK |
| TX-10027 | XX |

Sans validation programmatique, ces transactions non mappées entrent silencieusement dans vos déclarations fiscales finales.

**Approche de validation corrigée :**

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

### Référence des formules et dépendances

```excel
FILTER()
VSTACK()
CHOOSECOLS()
MAP()
LET()
HSTACK()

```

*Objectif :* supprimer les lignes vides, normaliser le schéma de la plateforme, standardiser les codes pays, construire le registre de transactions.

```excel
XLOOKUP()
SUMIFS()
MAP()

```

*Objectif :* recherche dynamique de TVA, affectation fiscale par juridiction, extraction des récupérations sur remboursements, calcul du net à payer.

```excel
FILTER()
TEXTJOIN()
ABS()
IF()
LET()

```

*Objectif :* détection des exceptions, génération des charges utiles de diagnostic, porte de contrôle de la déclaration fiscale.

</details>

---

## Logique métier et méthodologie

Cet outil n'est pas un simple tableur de calcul ; c'est une méthodologie opérationnelle conçue pour protéger votre marge nette et garantir la préparation à l'audit. Il résout le problème métier central de la **fragmentation financière multicanal** en appliquant des principes de rapprochement de niveau entreprise à l'e-commerce transfrontalier des PME.

Voici la méthodologie qui alimente le système :

### 1. Normalisation des données (source unique de vérité)
*   **Le problème métier :** Shopify et Etsy exportent les données de transactions selon des schémas de reporting entièrement différents. Les comparer manuellement mène au chaos de gestion de versions et à des VLOOKUP cassés.
*   **La méthodologie :** l'outil agit comme un pipeline ETL (extraction, transformation, chargement) léger. Il ingère automatiquement des exports CSV bruts hétérogènes et les normalise en un registre de transactions unifié et standardisé — créant une source unique de vérité pour vos données de conformité.

### 2. Recalcul fiscal Zero-Trust
*   **Le problème métier :** se fier aveuglément aux chiffres de « taxe collectée » des places de marché conduit souvent à des erreurs de déclaration par juridiction, car les algorithmes des plateformes peuvent ne pas correspondre à vos obligations de nexus spécifiques ni à vos classes de taxe produit.
*   **La méthodologie :** le moteur utilise un modèle de calcul « Zero-Trust ». Il recalcule votre vraie dette fiscale *de bas en haut* à partir des ventes brutes et de vos taux juridictionnels configurés, puis audite cette référence par rapport à la taxe collectée par la plateforme pour révéler les écarts de calcul cachés.

### 3. Gestion par exception
*   **Le problème métier :** examiner manuellement des milliers de microtransactions chaque mois pour préparer une déclaration OSS épuise durablement les ressources financières.
*   **La méthodologie :** l'architecture fait basculer votre flux comptable vers une « gestion par exception ». Au lieu d'auditer chaque ligne, le Centre de Validation isole uniquement les anomalies — codes pays manquants, taux de taxe vides ou écarts de collecte supérieurs à €1.00 — vous permettant de vous concentrer uniquement sur la résolution de problèmes à fort levier.

### 4. Récupération de marge nette via les compensations de remboursements
*   **Le problème métier :** beaucoup de marchands transfrontaliers traitent les retours clients uniquement comme des déductions de chiffre d'affaires, sans récupérer systématiquement la TVA collectée associée — laissant ainsi du bénéfice net aux administrations fiscales.
*   **La méthodologie :** le moteur de calcul isole programmatiquement les transactions de remboursement et les rattache à leurs juridictions d'origine. Il applique automatiquement des compensations de crédit de taxe sur votre TVA brute à payer, garantissant que vous n'absorbez jamais le coût fiscal des ventes remboursées.

---


## Autres outils opérationnels de cette série

* **Inventory Planning & Replenishment Console** — modèle d'optimisation des réapprovisionnements et de gestion du risque de stock.
* **Marketing Attribution Audit System** — validation d'attribution de canaux et analyse d'efficacité ROAS.
* **Project Cost Allocation Workbench** — tableur d'allocation de main-d'œuvre et de suivi de rentabilité des projets.
* **Multi-Entity Logistics Control Tower** — tableau de bord de suivi des expéditions transfrontalières et douanes.

Explorez d'autres cadres d'aide à la décision et modèles via le profil GitHub et notre [site web](https://www.theseusworkshop.com/).

---

## Licence

Ce projet est sous licence **Apache License 2.0**.

Consultez le fichier LICENSE pour plus de détails.
