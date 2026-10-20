# SOLAR-MOVE Use Case Repository

> **SOLAR-MOVE — WP1 / Task T1.3: Regulation, Services, Use Cases**<br>
> Business Use Cases (BUCs) and their System Use Cases (SUCs) for the SOLAR-MOVE pilots, documented with the IEC 62559-2 use case template.

This repository collects the final reviewed Business Use Cases of the SOLAR-MOVE demonstrators. Each BUC has its own folder with the same structure, so the use cases can be read on GitHub, analysed in a spreadsheet or processed by machine.

## Use cases

| Pilot | BUC | Name | Version | System Use Cases | KPIs | Req. |
|-------|-----|------|---------|------------------|------|------|
| Albania | [BUC-AL-01](BUC-AL-01/) | Coordinated PV-Integrated EV Charging Cluster Operation and Virtual Power Plant Management | v1.0 | SUC-AL-01.1<br>SUC-AL-01.2<br>SUC-AL-01.3 | 9 | 58 |
| Denmark | [BUC-DK-01](BUC-DK-01/) | Coordinated ePIPV Charging Hub Operation | v1.0 | SUC-DK-01.1<br>SUC-DK-01.2<br>SUC-DK-01.3<br>SUC-DK-01.4<br>SUC-DK-01.5 | 9 | 96 |
| Greece | [BUC-GR-01](BUC-GR-01/) | Coordinated Municipal ePIPV Charging Infrastructure Operation | v1.0 | SUC-GR-01.1<br>SUC-GR-01.2<br>SUC-GR-01.3 | 7 | 89 |
| Portugal | [BUC-PT-01](BUC-PT-01/) | Day-Ahead Spot Market Participation of a Multi-Asset Prosumer Facility via VPP Aggregation, with Happy Hour EV Charging | v1.0 | SUC-PT-01.1<br>SUC-PT-01.2<br>SUC-PT-01.3<br>SUC-PT-01.4 | 5 | 49 |
| Portugal | [BUC-PT-02](BUC-PT-02/) | Manual Frequency Restoration Reserve (mFRR) Provision by a Multi-Asset Prosumer Facility via VPP Aggregation | v1.0 | SUC-PT-02.1<br>SUC-PT-02.2<br>SUC-PT-02.3<br>SUC-PT-02.4 | 4 | 47 |
| Portugal | [BUC-PT-03](BUC-PT-03/) | DSO Local Flexibility Market Service Provision by a Multi-Asset Prosumer Facility through a Periodic Auction Contract | v1.0 | SUC-PT-03.1<br>SUC-PT-03.2<br>SUC-PT-03.3<br>SUC-PT-03.4 | 6 | 45 |
| Portugal | [BUC-PT-04](BUC-PT-04/) | Local P2P Energy Exchange through Dynamic EV Charging Incentives | v1.0 | SUC-PT-04.1<br>SUC-PT-04.2 | 6 | 31 |
| Türkiye | [BUC-TR-01](BUC-TR-01/) | PV-Integrated Opportunity Charging for a Campus Passenger e-Bus | v1.0 | SUC-TR-01.1<br>SUC-TR-01.2<br>SUC-TR-01.3 | 8 | 64 |

## System Use Cases

**[BUC-AL-01](BUC-AL-01/) — Coordinated PV-Integrated EV Charging Cluster Operation and Virtual Power Plant Management**

- SUC-AL-01.1 — Integrated Energy Data Aggregation (7 steps)
- SUC-AL-01.2 — PV-Aware Smart Charging Optimisation (7 steps)
- SUC-AL-01.3 — Cluster Flexibility Management and Virtual Power Plant Operation (8 steps)

**[BUC-DK-01](BUC-DK-01/) — Coordinated ePIPV Charging Hub Operation**

- SUC-DK-01.1 — Coordinated EV Charging (9 steps)
- SUC-DK-01.2 — BESS and PV Optimisation (7 steps)
- SUC-DK-01.3 — Real-Time Power Allocation (5 steps)
- SUC-DK-01.4 — Brownout and Emergency Power (9 steps)
- SUC-DK-01.5 — Provision of Flexibility Services (7 steps)

**[BUC-GR-01](BUC-GR-01/) — Coordinated Municipal ePIPV Charging Infrastructure Operation**

- SUC-GR-01.1 — Integrated Municipal Energy Data Aggregation (13 steps)
- SUC-GR-01.2 — PV-Aware Charging Planning Optimisation (12 steps)
- SUC-GR-01.3 — PV-Aware Real-Time Dynamic Load Modulation (14 steps)

**[BUC-PT-01](BUC-PT-01/) — Day-Ahead Spot Market Participation of a Multi-Asset Prosumer Facility via VPP Aggregation, with Happy Hour EV Charging**

- SUC-PT-01.1 — Day-Ahead Schedule Optimisation and Happy Hour Identification (6 steps)
- SUC-PT-01.2 — Day-Ahead Market Bidding (5 steps)
- SUC-PT-01.3 — Real-Time EMS Execution and Happy Hour Activation (6 steps)
- SUC-PT-01.4 — Settlement (6 steps)

**[BUC-PT-02](BUC-PT-02/) — Manual Frequency Restoration Reserve (mFRR) Provision by a Multi-Asset Prosumer Facility via VPP Aggregation**

- SUC-PT-02.1 — mFRR Capacity Assessment and Optimisation (5 steps)
- SUC-PT-02.2 — mFRR Market Bidding and Contract Management (4 steps)
- SUC-PT-02.3 — Real-Time EMS Execution (9 steps)
- SUC-PT-02.4 — Settlement (7 steps)

**[BUC-PT-03](BUC-PT-03/) — DSO Local Flexibility Market Service Provision by a Multi-Asset Prosumer Facility through a Periodic Auction Contract**

- SUC-PT-03.1 — Flexibility Headroom Assessment (5 steps)
- SUC-PT-03.2 — Auction Participation and Contract Management (8 steps)
- SUC-PT-03.3 — Real-Time EMS Execution (7 steps)
- SUC-PT-03.4 — Settlement (5 steps)

**[BUC-PT-04](BUC-PT-04/) — Local P2P Energy Exchange through Dynamic EV Charging Incentives**

- SUC-PT-04.1 — Real-Time EMS Clearinghouse Operation and Dispatch (8 steps)
- SUC-PT-04.2 — Dynamic EV Charging Management (5 steps)

**[BUC-TR-01](BUC-TR-01/) — PV-Integrated Opportunity Charging for a Campus Passenger e-Bus**

- SUC-TR-01.1 — VIPV monitoring and route-based PV potential assessment (7 steps)
- SUC-TR-01.2 — PV-aware opportunity charging scheduling for the campus e-bus (6 steps)
- SUC-TR-01.3 — Real-time grid-friendly charging session execution (10 steps)

## Repository structure

```
.
├── README.md                      ← this index
├── BUC-AL-01/
├── BUC-DK-01/
├── BUC-GR-01/
├── BUC-PT-01/
├── BUC-PT-02/
├── BUC-PT-03/
├── BUC-PT-04/
└── BUC-TR-01/
```

Each BUC folder contains:

```
<BUC-ID>/
├── README.md                      ← full use case description (IEC 62559-2 sections 1–7)
├── SOLARMOVE_<BUC-ID>.v1.0.xlsx   ← the template tables, one sheet per section
├── SOLARMOVE_<BUC-ID>.v1.0.xml    ← IEC 62559-3-style serialization (draft)
└── images/                        ← use case diagram and SUC sequence diagrams
```

## Template

Every BUC follows the IEC 62559-2 use case template:

1. Description of the use case — name, version management, scope and objectives, narrative, KPIs, conditions, classification, remarks
2. Diagrams of the use case
3. Technical details — actors and references
4. Step-by-step analysis — overview of scenarios and the steps of each SUC
5. Information exchanged
6. Requirements — grouped into the harmonised SOLAR-MOVE requirement categories (CAT-xx)
7. Common terms and definitions

The XML files follow the structure and vocabulary of the IEC 62559-2 template as serialised by the Sparx EA / MODSARUS toolchain. They are a **draft** and have not been validated against the normative IEC 62559-3 XSD.

## License

The content of this repository is licensed under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE) licence. You may share and adapt it for any purpose, provided appropriate credit is given to the SOLAR-MOVE project.

## Acknowledgement

SOLAR-MOVE has received funding from the European Union's Horizon Europe research and innovation programme under Grant Agreement No. 101235635 (call topic HORIZON-CL5-2024-D3-02).

_Funded by the European Union. Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or the European Climate, Infrastructure and Environment Executive Agency (CINEA). Neither the European Union nor the granting authority can be held responsible for them._
