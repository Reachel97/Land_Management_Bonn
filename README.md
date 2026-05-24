# Land Management Project - Site Development & Land Readjustment, Endenich (Bonn)

MSc Geodetic Engineering · University of Bonn · Summer Term 2023
Module: *Land Management* — Chair of Urban Planning and Land Management (Prof. Dr.-Ing. Theo Kötter)
Author: **Reachel Sabir**

---
<img width="1618" height="1158" alt="image" src="https://github.com/user-attachments/assets/f700741e-06e9-465c-ba29-b519bea4bd84" />

## Project at a glance

A full five-stage urban site development for a ~5-hectare greenfield site in **Endenich, Bonn**, applying the German planning system end-to-end — from initial site appraisal all the way to a value-based **land readjustment** (*Umlegung*) under German Building Code (BauGB).

The brief: turn an underused field bounded by *Am Bleichgraben*, *Maria-von-Linden-Weg*, *Steinweg* and the planned *Am Probsthof / Erich-Hoffmann-Straße* connection into a **mixed-use, medium-density** urban area — shops/offices on the ground floor, offices on the first floor, flats above; multi-modal traffic; public amenities; a mix of dwelling types for different incomes; integration with the existing surrounding fabric.

The site:

| | |
|---|---|
| **Location** | Endenich, Bonn |
| **Total area (U)** | 54,632 m² (~5.46 ha) |
| **Land value before planning** | 275 €/m² |
| **Land value after planning** | 440 €/m² |
| **Owners (private)** | A, B, C, D |
| **Public authority** | City of Bonn |

---

## Methodology — the *Layer Method*

The project follows the layer method taught in the module: each stage builds on the previous one, so the final readjustment plan is the legal/cadastral consequence of every planning decision made above it.

| Stage | Output | Purpose |
|---|---|---|
| **A.1** Site appraisal | Map | Systematic inventory of the site — boundaries, surroundings, access, existing uses, constraints, opportunities |
| **A.2** Structure plan | Plan | First spatial concept — main uses, zones, circulation, density distribution |
| **A.3** Design plan | Plan | Detailed urban design — block structure, building footprints, public space, green network |
| **A.4** Binding land-use plan (*Bebauungsplan*) | Plan | Legally binding plan under German planning law: building zones, plot ratios, building lines, public facilities |
| **A.5** Land readjustment plan (*Umlegungsplan*) | Plan, spreadsheet | Cadastral reshuffle: old irregular parcels → new building plots, with each owner's legal claim, actual allocation, and financial compensation computed |

---

## Maps

> Add your PNGs to the [`maps/`](./maps) folder using the filenames below.

### A.1 — Site appraisal
![Site appraisal](./maps/A1_site_appraisal.png)

### A.2 — Structure plan
![Structure plan](./maps/A2_structure_plan.png)

### A.3 — Design plan
![Design plan](./maps/A3_design_plan.png)

### A.4 — Binding land-use plan (B-Plan)
![Binding land use plan](./maps/A4_binding_land_use_plan.png)

### A.5 — Land readjustment plan
![Land readjustment plan](./maps/A5_land_readjustment_plan.png)

---

## A.5 — Land readjustment results

The land readjustment was carried out using the **value-based method** (*Bauwert-Verfahren*) of the German Building Code. The pre-planning land value is 275 €/m², the post-planning value 440 €/m². Public places (roads, green space, kindergarten lot) grow from 5,665 m² before planning to 17,281 m² after planning.

### Global parameters

| Quantity | Symbol | Value |
|---|---|---|
| Whole area | U | 54,632 m² |
| Old public places | A | 5,665 m² |
| Old distributable area | E = U − A | 48,967 m² |
| New public places | N | 17,281 m² |
| Area to subtract | f = N − A | 11,616 m² |
| Subtraction share | S = f / E | 0.24 |
| New distributable area | V = U − N | 37,351 m² |
| **Distribution ratio** | **q** | **1.22** |

So although roughly a quarter of each private holding is removed for public use, the post-planning rise in land value (275 → 440 €/m²) more than compensates: the value-based distribution ratio is **q = 1.22**, meaning each private owner is legally entitled to 1.22 × the value of their old land in the form of new building land.

### Per-owner results

| Owner | Old area (m²) | Old value (€) | Legal claim Vi (m²) | Allocated Z (m²) | Allocated value (€) | Financial compensation (€) |
|---|---:|---:|---:|---:|---:|---:|
| **A** | 2,127  | 584,925   | 1,621.83  | 1,594  | 701,360   | **+116,435** |
| **B** | 6,690  | 1,839,750 | 5,101.13  | 3,516  | 1,547,040 | **−292,710** |
| **C** | 8,079  | 2,221,725 | 6,160.23  | 3,671  | 1,615,240 | **−606,485** |
| **D** | 32,071 | 8,819,525 | 24,454.14 | 22,563 | 9,927,720 | **+1,108,195** |
| City of Bonn | 5,665 | 1,557,875 | — | 17,281 | 7,603,640 | — |
| **Total** | **54,632** | **15,023,800** | — | **48,625** | **21,395,000** | — |

> **Reading the compensation column**: a positive number means the owner has received *more* than their legal claim and must pay the city; a negative number means they received less and are owed compensation. Owner D, holding by far the largest original area, ends up taking the largest net positive position; Owners B and C are compensated financially because their built-up allocation came out smaller than their legal claim in m² terms.

### Before vs. after summary

| | Private (m²) | Public (m²) | Total (m²) | Value (€) |
|---|---:|---:|---:|---:|
| **Before planning** | 48,967 | 5,665 | 54,632 | 15,023,800 |
| **After planning**  | 31,344 | 17,281 | 48,625 | 21,395,000 |

The post-planning total area is smaller (48,625 vs 54,632 m²) because the readjustment computation works on the distributable mass; the difference is absorbed into the public-area accounting.

---

## Repository structure

```
Land_Management_Bonn_Endenich/
├── README.md                                  ← this file
├── docs/
│   ├── Course_Brief_Land_Management.pdf       ← assignment brief (Dr.-Ing. J. M. Stielike, summer 2023)
│   └── Final_Presentation_Land_Readjustment.pptx   ← final presentation
├── maps/                                      ← place your A.1–A.5 PNGs here
│   └── README.md
└── results/                                   ← optional: spreadsheets, exports
    └── README.md
```

---

## Tools & methods used

- **QGIS** — site analysis, base maps, land-use mapping
- **CAD** — binding land-use plan and land readjustment plan (per module requirement)
- **Microsoft Excel** — value-based land readjustment calculations
- **PowerPoint** — final presentation
- **German Building Code (BauGB)**, in particular §§ 45–84 *Umlegung* — legal framework for land readjustment

---

## What this project demonstrates

- End-to-end urban planning workflow under the **German planning system**, from concept to legal cadastral implementation.
- Application of the **layer method** — each step is technically and legally justified by the one above.
- Quantitative **land readjustment** using the value-based *Bauwert-Verfahren*, including distribution-ratio derivation and financial-compensation accounting across multiple owners.
- Integration of **planning law, cadastre, urban design and valuation** in a single coherent deliverable — the core competence the *Land Management* module is designed to teach.

---

## Acknowledgements

Course taught by **Dr.-Ing. Jan Matthias Stielike** under the Chair of Urban Planning and Land Management (**Prof. Dr.-Ing. Theo Kötter**), Institute of Geodesy and Geoinformation (IGG), University of Bonn.
