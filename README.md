# PGST Decarbonization Archive

Final project archive for the UW CEI Community Capstone in partnership with the Port Gamble S'Klallam Tribe (PGST), completed June 2026.

**Project team:** Mick Deines, Hannah Chavla, Marion Garabedian, Naudia Watkins, Samantha Kravitz  
**Faculty advisor:** Prof. Daniel Schwartz, UW Clean Energy Institute  
**Client contact:** Rachel Gates, PGST Energy Program Manager

---

## What This Project Does

Evaluates decarbonization pathways for the PGST administrative campus, focusing on replacing the propane boiler serving the Longhouse and Career Education Center. Three heating technologies were analyzed (electric boiler, high-temperature air-to-water heat pumps, and standard air-to-water heat pumps) alongside rooftop PV and battery storage, using NREL's REopt optimization tool.

**Bottom line:** Standard AWHPs paired with an 80 kW rooftop PV array are the recommended pathway — the only full-cost scenario that beats the propane boiler baseline over 25 years, reducing campus propane emissions by ~58 tCO₂e/yr.

---

## Repository Structure
├── report/                   # Final report and design statement (PDF + DOCX)
├── reopt-profiles/           # REopt-ready load profiles and COP tables
├── design-matrix/            # REopt scenario design matrix (heating × PV × battery × rate structure)
├── raw-data/                 # Source propane delivery records and PSE electricity interval data
├── presentations/            # Meeting slide decks from throughout the project (Jan–Jun 2026)
└── archive/                  # Working files, old notebooks, and superseded REopt attempts

---

## Key Files

| File | Description |
|------|-------------|
| `report/PGST_Final_Report.pdf` | Primary deliverable |
| `design-matrix/Boiler_REopt_Design_Matrix.xlsx` | All REopt scenarios, inputs, and outputs |
| `reopt-profiles/Propane input loads (MMBtu-hr)/` | Hourly boiler load profiles fed into REopt |
| `reopt-profiles/ASHP input COPs/` | COP vs. temperature tables for each heating technology |
| `raw-data/Port_Gamble_Ferrell_Gas_Consumption.xlsx` | Propane delivery records (2005–2025) |
| `raw-data/PSE_meter_23-24.csv` / `PSE_meter_24-25.csv` | 15-minute electricity interval data |

---

## Analysis Environment

Python notebooks, computed load profiles, and intermediate data files (ERA5 weather, pickle bundles, regression outputs) live in the companion repository: **[link to existing GitHub]**

That repo is the full computation environment; this one is the archival deliverable package.

---

## License

CC0 1.0 Universal — public domain dedication. No rights reserved.
