📘 Available in: [English version](https://github.com/Florisoft-issues/AppRoadmap/blob/main/Florisoft_README_EN.md)

❇️ Bekijk de [officiële publieke app-roadmap van Florisoft](https://github.com/orgs/Florisoft-issues/projects/67)

Welkom bij de publieke **Florisoft Roadmap**. Deze omgeving biedt een actueel en gestructureerd overzicht van de app-functionaliteiten waar we aan werken, inclusief hun status en verwachte oplevermomenten.

**In deze repository worden onderstaande punten nader toegelicht:**
1. [Opbouw & handleiding van de roadmap](#1-opbouw--handleiding-van-de-roadmap)  
2. [Ontwikkelfases](#2-ontwikkelfases)  
3. [App structuur: functioneel domein, applicaties en use cases](#3-app-structuur-functioneel-domein-applicaties-en-use-cases)

De huidige roadmap is bedoeld om onze gebruikers inzicht te geven in onze productontwikkeling. In een later stadium willen we de interactie verbreden, het format verfijnen en u de mogelijkheid bieden om actief mee te denken. 

Via het discussiekanaal blijft u op de hoogte van aankondigingen, zoals de oplevering van een applicatie of de introductie van nieuwe functionaliteiten. U vindt dit kanaal via de volgende link: [GitHub Discussions – AppRoadmap](https://github.com/Florisoft-issues/AppRoadmap/discussions).

Alle wijzigingen en updates kunt u bovendien terugvinden in het changelog via: [Changelog Florisoft](https://app.florisoft.nl/apps/latest/changelog.html).

## 1. Opbouw & handleiding van de roadmap

Bij het openen van de publieke roadmap ziet u een **totaaloverzicht** van alle app-ontwikkelingen met per ontwikkeling de tijdlijn waarin de ontwikkeling plaatsvindt, gaat vinden of heeft gevonden. U kunt het overzicht filteren door gebruik te maken van de gespecificeerde tabbladen of de zoekfunctie bovenaan de pagina.

Voor iedere ontwikkeling is een GitHub issue aangemaakt. Ieder issue bevat de volgende informatie: 

- Korte omschrijving van de **functionaliteit(en)**
- De **ontwikkelfase** waarin het roadmap-item zich bevindt*
- Om welke **applicatie** het gaat
- Het **functioneel domein** van de applicatie (bijv. Logistics, Sales, Inventory)*
- De use case** of specifieke **feature** * 
- Eenmaal opgeleverd, krijgt het item het label **geleverd** en wordt het gesloten met een link naar de changelog

\* Meer informatie over de structuur van de ontwikkelfases, functionele domeinen, applicaties en use cases leest u in onderstaande alinea's.

❇️ Bekijk de [officiële publieke app-roadmap van Florisoft](https://github.com/orgs/Florisoft-issues/projects/67)

## 2. Ontwikkelfases

Onze roadmap is opgebouwd rondom vaste ontwikkelfases, zoals besproken tijdens de kick-off van ieder project. Iedere app, use case of functie doorloopt minimaal een MVP-fase, gevolgd door iteratieve uitbreidingen en verbeterslagen. Onderstaand een korte omschrijving van iedere specifieke fase:

### 🌱 Initiële ontwikkelfases (Kick-off-gebaseerd)

- **Dev phase 1 (MVP):**  
    Eerste werkende versie met essentiële functionaliteit.
    
- **Livegang:**  
    MVP wordt opgeleverd en eventueel in productie gebracht.
    
- **Dev phase 2 – 5 (child use cases):**  
    Verfijning en uitbreiding van de MVP met specifieke extra functionaliteiten.
    
- **Livegang na elke fase:**  
    Tussentijdse opleveringen na afronding van elke ontwikkelfase.
    

### 🔄 Verbeterfases (Improve Phases)

Zodra er voldoende feedback, ideeën of bugs zijn verzameld, starten we een nieuwe verbeterronde:

- **Improve phase 1:**  
    Optimalisatie en gebruiksverbeteringen op basis van praktijkervaring.
    
- **Improve phase 2, 3, …**  
    Vervolgfases waarin batches van nieuwe verbeterpunten worden opgepakt.
    

Deze aanpak zorgt ervoor dat we snel waarde kunnen leveren én blijven verbeteren.

## 3. App structuur: functioneel domein, applicaties en use cases

Om de roadmap overzichtelijk te houden, structureren we de items op drie niveaus: **functioneel domein, applicaties en use cases.**

### 🔹 Functionele domeinen

De functionele domeinen zijn de hoofdgebieden binnen onze applicaties: Logistics, Purchasing, Sales, CRM, Assortment, Financial, Inventory, Management en Assets.

### 🔸 Applicaties en use cases.

Binnen ieder functioneel domein onderscheiden we verschillende applicaties en de bijbehorende use cases. In sommige gevallen is de scope van een applicatie zo specifiek dat deze (nog) niet in aparte use cases is gedefinieerd. 

<details>
<summary><strong>Logistics</strong></summary>

- **Applicatie:** Packing

  **Use cases:** Kubus, Packing, Trolley Loading
  
- **Applicatie:** Picking 

  **Use cases:** Palet Picking, Generic Picking
  
- **Applicatie:** Quality Control

  **Use cases:** Final Outbound Check, Exception Handling, Exception Registration

- **Applicatie:** Labeling

  **Use cases:** Price label, Stock label
  
- **Applicatie:** Track & Tracing

  **Use cases:**  N.v.t.
  
- **Applicatie:** Receiving

  **Use cases:** Entry Control
  
- **Applicatie:** Shipping

  **Use cases:** Adress Label

-  **Applicatie:** Automating Agent

   **Use cases:** Sorting, Weighing

</details>

<details>
<summary><strong>Purchasing</strong></summary>

- **Applicatie:** Proposals

  **Use cases:** Offer Request Floriday

</details>

<details>
<summary><strong>Sales</strong></summary>

- **Applicatie:** POS

  **Use cases:** Cash & Carry, Order Registration, Floriline
  
- **Applicatie:** Purchasing Proposals

  **Use cases:** N.v.t.
  
- **Applicatie:** Licensing

  **Use cases:** N.v.t.

</details>

<details>
<summary><strong>CRM</strong></summary> 

- **Applicatie:** Tickets

  **Use cases:** N.v.t.

</details>

<details>
<summary><strong>Assortment</strong></summary> 

- **Applicatie:** Product Sourching

  **Use cases:** Floriday Grower Catalog

</details>

<details>
<summary><strong>Financial</strong></summary>

- **Applicatie:** Invoice Receipt Verification

  **Use cases:** N.v.t.
  
- **Applicatie:** Receiving Claims

  **Use cases:** N.v.t.
  
- **Applicatie:** Payments

  **Use cases:** N.v.t.
  
- **Applicatie:** Invoicing

  **Use cases:** N.v.t.

</details>

<details>
<summary><strong>Inventory</strong></summary> 

- **Applicatie:** Inventory

  **Use cases:** Slotting, Stock Counting
  
</details>

<details>
<summary><strong>Assets</strong></summary>

- **Applicatie:** Asset Tracking

  **Use cases:** Outbound, Inbound

</details>

<details>
<summary><strong>Core services</strong></summary>

- **Applicatie:** Hub

  **Use cases:** N.v.t.
  
- **Applicatie:** Job Agent

  **Use cases:** Job Agent Server, Job Agent Client

  </details>

## Disclaimer

De informatie in deze repository, waaronder de roadmap, is gebaseerd op onze huidige kennis en inzichten. De roadmap is bedoeld als een indicatie van de verwachte ontwikkelingen, maar bevat geen garanties of toezeggingen over specifieke opleverdata. Het is ten aller tijden mogelijk dat de roadmap tussentijds wordt aangepast. We raden u daarom aan deze niet als basis voor aankoopbeslissingen te gebruiken.

❇️ Bekijk de [officiële publieke app-roadmap van Florisoft](https://github.com/orgs/Florisoft-issues/projects/67)
