# User Journey Map (docs/ux.md)

| Persona              | Ziel (هدف)                                   | Touchpoints (نقاط تماس)                                                                 | Outcome (نتیجه / ارزش)                          |
|----------------------|-----------------------------------------------|------------------------------------------------------------------------------------------|------------------------------------------------|
| **Local Shopper**    | Produkte von lokalen Shops entdecken & kaufen | Home → Suche/Karte → Shop-Detail → Warenkorb → Checkout → Lieferung/Smart Locker          | Einfache Entdeckung, günstige Deals, bequeme Lieferung |
| **Event Visitor**    | Teilnahme an lokalen Festivals & Events        | Festival/Events → Event auswählen → Angebote/Tickets → Checkout → QR-Code                 | Direkter Zugang zu Events, Verbindung digital ↔ physisch |
| **Job Seeker**       | Lokale Jobs finden (flexibel, Teilzeit, Gig)   | Jobboard → Filter/ Suche → Job-Detail → Bewerbung mit 1 Klick → Bestätigung              | Zugang zu Jobs in der Nähe, schnelle Bewerbung |
| **Local Merchant**   | Sichtbarkeit steigern, Produkte & Jobs posten  | Geschäftskonto Login → Dashboard → Produkte/Jobs/Events hinzufügen → Analytics Dashboard | Mehr Reichweite, besseres Inventarmanagement   |
| **Courier/Driver**   | Geld verdienen durch lokale Lieferungen        | Courier Mode → Aufträge anzeigen → Auftrag annehmen → Lieferung ausführen → Gutschrift   | Flexible Einkünfte, Teil des lokalen Ökosystems |
| **Community User**   | Teilhabe an Community, Belohnungen sammeln     | Home → Challenges / Loyalty → Aufgaben erledigen → Punkte sammeln → Rewards einlösen     | Bindung an Plattform, Spaß & Belohnung         |

---

## User Flow Diagram

```mermaid
flowchart TD
    A[Start: App öffnen] --> B[Login / Registrierung]

    B --> H[Home Dashboard]

    %% Shopper
    H --> S1[Suche/Karte]
    S1 --> S2[Shop-Detail]
    S2 --> S3[Produkt wählen]
    S3 --> S4[Warenkorb / Checkout]
    S4 --> S5[Lieferoptionen: Smart Locker / Kurier]
    S5 --> S6[Zahlung]
    S6 --> S7[Kaufbestätigung + Loyalty]

    %% Event Visitor
    H --> E1[Festival/Events]
    E1 --> E2[Event auswählen]
    E2 --> E3[Ticket/Bundle kaufen]
    E3 --> E4[QR-Code erhalten]

    %% Job Seeker
    H --> J1[Jobboard]
    J1 --> J2[Filter / Suche]
    J2 --> J3[Job-Detail]
    J3 --> J4[1-Klick Bewerbung]
    J4 --> J5[Bestätigung]

    %% Merchant
    H --> M1[Geschäftskonto Login]
    M1 --> M2[Dashboard]
    M2 --> M3[Produkte/Jobs/Events posten]
    M2 --> M4[Analytics Dashboard]

    %% Courier
    H --> C1[Courier Mode]
    C1 --> C2[Aufträge anzeigen]
    C2 --> C3[Auftrag annehmen]
    C3 --> C4[Lieferung ausführen]
    C4 --> C5[Gutschrift erhalten]

    %% Community User
    H --> CU1[Loyalty / Challenges]
    CU1 --> CU2[Aufgaben erledigen]
    CU2 --> CU3[Punkte sammeln]
    CU3 --> CU4[Rewards einlösen]
```

