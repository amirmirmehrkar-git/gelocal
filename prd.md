# Product Requirements Document (PRD)

## 1. Vision
Ein synergetisches, digitales Ökosystem zur Stärkung der lokalen Wirtschaft in Hamburg – mit Skalierungspotential für andere Städte wie Izeh. Das Produkt ist eine multifunktionale Mobile-First-App, die Handel, Logistik, Community, Arbeitsmarkt und Events in einer konsistenten Plattform vereint. Die Vision: **eine nachhaltige, gemeinschaftsorientierte, digitale Infrastruktur, die lokale Wertschöpfungsketten stärkt.**

## 2. Goals
- **Empower Local SMEs:** Mehr Sichtbarkeit, Umsatzsteigerung und einfacherer Zugang zu neuen Kunden.
- **Reduce Waste:** Verringerung von Lebensmittel- und Warenverschwendung durch innovative Überbestands-Lösungen.
- **Enable Local Jobs:** Flexible, lokale Arbeitsmöglichkeiten für verschiedene Qualifikationsniveaus.
- **Promote Community:** Stärkung von Nachbarschaft, Vertrauen und gemeinschaftlicher Identität.
- **Hybrid Synergy:** Verbindung digitaler Tools mit physischen Erlebnissen (Events, Festivals, Märkte).
- **Sustainable Logistics:** Niedrigschwellige, CO₂-arme Lösungen für Last-Mile Delivery.

## 3. Key Features
### 3.1 Shopper / Local Consumer
- Intelligente Suche (Suchleiste + Map-Ansicht)
- Shop-Profile mit Produktkatalog, Öffnungszeiten, Bewertungen & Medien
- Warenkorb, Checkout, verschiedene Bezahlmethoden (inkl. Wallet)
- Lieferoptionen: Smart Lockers, Kuriernetzwerk, Community Delivery
- Loyalty-Programm, Gamification (Challenges, Abzeichen)
- Push Notifications für Angebote & Events

### 3.2 Event Visitor
- Event-/Festival-Liste mit Filtern (Datum, Location, Kategorie)
- Detailseiten mit Angeboten, Ticketkauf und Ausstellerlisten
- In-App-Ticketing (QR-/Barcode, Wallet-Integration)
- Event-spezifische Deals & Rabatte

### 3.3 Job Seeker
- Lokales Jobboard (Mini-Jobs, Gig Work, Teilzeit, Vollzeit)
- 1-Klick-Bewerbung & CV-Upload
- Integration flexibler Schichtarbeit (On-Demand Jobs)
- Bewertungssystem für Arbeitgeber & Arbeitnehmer

### 3.4 Merchant / Business Owner
- Business Dashboard (Web + App)
- Produkte, Jobs, Events einstellen & verwalten
- B2B- und C2B-Marktplatz mit Anonymitätsfunktionen für Bulk Sales
- Analytics Dashboard mit Echtzeit-Daten & Trend-Reports
- Marketing-Coop: gemeinsame Kampagnen, Cross-Promotion

### 3.5 Courier
- Courier Mode: Aufträge annehmen, Live-Tracking
- Optimierte Routenplanung
- Status-Updates (Abholung, Lieferung, abgeschlossen)
- Automatisierte Abrechnung & Wallet-Auszahlung

### 3.6 Community User
- Challenges (z. B. „Entdecke 10 lokale Shops“)
- Loyalty-Punkte sammeln & Rewards einlösen
- Interaktive Nachbarschafts-Features (Bewertungen, Empfehlungen)
- Community-basierte Lieferoptionen

## 4. Constraints
- **Tech:** Mobile-First; native iOS & Android; Integration mit 3rd-Party Services (3PL, Payment, Smart Lockers, Ticketing).
- **Legal:** DSGVO-Compliance, Identitätsprüfung (KYC) für Businesses & Couriers, sichere Zahlungsabwicklung.
- **Business:** Stufenweise Einführung (Hamburg als Pilotmarkt, Skalierung in 2. Phase), MVP-Fokus auf Kernfeatures.
- **UX:** Mehrsprachigkeit (Deutsch, Englisch; später Farsi), Accessibility (WCAG-konform), einfache Onboarding-Flows.
- **Operational:** Kooperation mit lokalen Partnern (Logistik, Events, Arbeitsvermittler).

## 5. Success Metrics
- **Adoption:** Anzahl aktive Businesses & User nach 3/6/12 Monaten.
- **Engagement:** Durchschnittliche Sitzungsdauer, DAU/MAU, Retention-Rate.
- **Economic Impact:** Umsatzsteigerung lokaler Shops (% Wachstum), Menge reduzierter Lebensmittelabfälle (kg/Monat).
- **Community:** Anzahl gebuchter Jobs, Anzahl Festival-/Event-Teilnahmen, Community-Challenges abgeschlossen.
- **Sustainability:** # Lieferungen über Shared Logistics, CO₂-Einsparungen durch Smart Lockers & Kurier-Sharing.

## 6. Non-Functional Requirements (NFRs)
- **Performance:** Antwortzeiten < 2 Sekunden für Hauptinteraktionen.
- **Scalability:** Skalierbarkeit auf >10.000 gleichzeitige Nutzer in Hamburg.
- **Availability:** 99,9% Uptime SLA.
- **Security:** End-to-End Encryption, Role-based Access, sichere Speicherung von Zahlungsdaten.
- **Maintainability:** API-first, Modular Codebase, CI/CD-Pipeline.
- **Localization:** DE/EN/Farsi Support, inkl. RTL.

## 7. User Stories (Auswahl)
- Als *Shopper* möchte ich eine Karte der nahegelegenen Shops sehen, damit ich neue lokale Geschäfte entdecken kann.
- Als *Business Owner* möchte ich meine überschüssigen Produkte als „Surprise Bags“ listen, um Verluste zu vermeiden.
- Als *Job Seeker* möchte ich kurzfristige Schichten sehen, um flexibel Geld zu verdienen.
- Als *Courier* möchte ich Aufträge in meiner Nähe annehmen, um meine Arbeitszeit effizient zu nutzen.
- Als *Event Visitor* möchte ich Tickets im App kaufen, um Wartezeiten zu vermeiden.

## 8. Dependencies
- **Payments:** PayPal, Klarna, Apple Pay, Google Pay, SEPA.
- **Logistics:** 3PL-Partner, lokale Kuriere, Smart Locker Anbieter (z. B. MyFlexBox, DHL).
- **Events:** Guestoo, Locaboo APIs.
- **Analytics:** Metabase, Google Looker Studio.

## 9. MVP Definition
- **Phase 1 (MVP):** Shop Discovery, Surprise Bags (C2B), Jobboard (Mini-Jobs), Smart Lockers, Simple Analytics.
- **Phase 2:** Festival-Integration, B2B Bulk Sales, Gamification, Advanced Analytics, Community Challenges.
- **Phase 3:** Vollständige Integration von Marketing-Coops, White-Label Logistics, Loyalty-Program in mehreren Stufen.

## 10. Stakeholders & Governance
- **Internal:** PM, System Architect, UX/UI, Engineering, QA, Marketing.
- **External:** Local Chambers, Event Organizer, Logistics Partner, Financial Services.
- **Governance:** Agile Scrum Setup, zweiwöchentliche Sprints, Steering Committee (PM + Key Stakeholders).

## 11. Assumptions & Risks
- **Assumptions:** Hohe Smartphone-Penetration in Hamburg; Bereitschaft lokaler Businesses zur digitalen Zusammenarbeit.
- **Risks:** Geringe Akzeptanzrate ohne starke Marketing-Kampagnen; rechtliche Barrieren (Arbeitsrecht, Logistik-Lizenzen).

## 12. Open Questions
- Welche Payment-Methoden sollen im MVP enthalten sein (PayPal, Klarna, Apple/Google Pay)?
- Wie stark soll das Community-Element im MVP ausgeprägt sein (Gamification sofort oder Phase 2)?
- Welche Eventpartner eignen sich als erste Pilotkunden für die Festival-Integration?

---
👉 Dieses PRD (v0.3) enthält alle strukturellen Ergänzungen (NFRs, User Stories, Dependencies, MVP, Governance). Nächster Schritt: *agent architect → Technische Architektur & Systemdesign.

