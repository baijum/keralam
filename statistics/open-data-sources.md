# Kerala Open Data Sources

A comprehensive catalog of open data portals, datasets, and statistical publications
relevant to Kerala's development. Organized by domain, with notes on data availability,
formats, and actual downloadability.

Last updated: April 2026

---

## 1. Government Open Data Portals

### data.gov.in — National Open Data Portal

- **URL:** https://data.gov.in
- **Kerala data:** Searchable by filtering state/source to "Kerala"; contains
  datasets contributed by various Kerala departments
- **Format:** CSV, JSON, XML, API (OGDP API)
- **Downloadable:** Yes — bulk CSV/XLS downloads and programmatic API access
- **Notes:** The portal was returning 403 errors during verification (April 2026).
  Historically one of the best sources for structured Kerala government data.
  Search with `filters[field_source]=Kerala` or keyword "Kerala"

### data.kerala.gov.in — Kerala State Open Data Portal

- **URL:** https://data.kerala.gov.in
- **Status:** Connection refused (April 2026) — portal appears to be offline
- **Historical notes:** Was intended as Kerala's dedicated state open data portal.
  May have been merged with or replaced by other portals

### Open Data Kerala (Community Initiative)

- **URL:** https://opendatakerala.org
- **Type:** Community-driven open data initiative by Sahya Digital Conservation Foundation
- **Data available:**
  - LSG Elections 2025 (geospatial data for local body boundaries)
  - Map Kerala (LSG-level portal based on OpenStreetMap data)
  - OGD Portal (community mapping with IIT Palakkad)
- **Format:** Geospatial (GeoJSON, Shapefiles), Map tiles
- **License:** CC-BY-SA
- **Downloadable:** Yes
- **GitHub:** https://github.com/opendatakerala

### Kerala GIS / OpenSDI Portal

- **URL:** https://opensdi.kerala.gov.in
- **Status:** SSL certificate expired (April 2026)
- **Historical notes:** Kerala's Spatial Data Infrastructure portal for GIS/geospatial
  layers including administrative boundaries, land use, infrastructure, water bodies.
  When operational, provided WMS/WFS services and downloadable shapefiles

---

## 2. Statistical Publications and Databases

### Kerala State Planning Board (SPB)

- **URL:** https://spb.kerala.gov.in
- **Data available:**
  - Kerala Economic Review (annual, ~700 pages, comprehensive state-of-the-state report)
  - State Development Reports
  - Sector-specific analyses
  - Statistical databases
- **Format:** PDF
- **Downloadable:** Yes
- **Notes:** Economic Review is the single most comprehensive data source for
  Kerala's economy, social indicators, and development metrics

### Directorate of Economics and Statistics (DES)

- **URL:** https://ecostat.kerala.gov.in
- **Data available:**
  - **Population/Demographics:** Vital statistics, Medical Certification of Cause of Death
  - **Agriculture:** EARAS statistics, Agriculture Census, Cost of Cultivation
  - **Industries:** Annual Survey of Industries, Index of Industrial Production
  - **Macro-economy:** State Income, GSDP, Consumer Price Index
  - **Social:** NSS data, Labour & Housing, Economic Census, Gender statistics
  - **Prices:** Daily commodity prices, Market Intelligence pricing, Rubber/timber prices
  - **Environment & Infrastructure:** Environment statistics
- **Format:** CSV, Excel (via data catalogue), PDF (publications), interactive dashboards
- **Downloadable:** Yes — offers unit-level data downloads, open datasets, dynamic
  data analytics with time-series
- **Rating:** EXCELLENT — the single best portal for structured Kerala statistical data.
  Features data catalogue, analytics tools, and downloadable datasets

### SDG Kerala Portal

- **URL:** https://sdg.kerala.gov.in
- **Data available:** Kerala's performance across all 17 Sustainable Development Goals
  using SDG India Index framework (scores from 2018, 2019-20, 2020-21, 2023-24)
- **Format:** Dashboard, PDF reports
- **Downloadable:** Partially (dashboard viewable; some reports downloadable)
- **Notes:** Kerala ranked first nationally in all four SDG Index editions

### RBI Handbook of Statistics on Indian States

- **URL:** https://rbi.org.in/Scripts/AnnualPublications.aspx?head=Handbook%20of%20Statistics%20on%20Indian%20States
- **Data available:** 168 tables covering Kerala across: demographics, health, state
  domestic product, agriculture, environment, prices, industry, infrastructure,
  banking/finance, fiscal data
- **Format:** PDF and Excel (.XLSX) — each table downloadable separately
- **Downloadable:** Yes — excellent structured state-level data
- **Rating:** EXCELLENT for financial and banking data at state level

### Census of India

- **URL:** https://www.censusindia.gov.in
- **Data available:** Complete population census data for Kerala (2011 census;
  2021 census postponed)
- **Format:** Excel, PDF
- **Downloadable:** Yes
- **Notes:** SSL certificate issues reported; data accessible through alternative mirrors

### NCRB — Crime Statistics

- **URL:** https://ncrb.gov.in
- **Publications containing Kerala data:**
  - Crime in India (annual)
  - Accidental Deaths and Suicides in India (annual)
  - Prison Statistics India (annual)
- **Format:** PDF (reports), Excel (data tables)
- **Downloadable:** Yes

---

## 3. Election Data

### Kerala Chief Electoral Officer (CEO)

- **URL:** https://ceo.kerala.gov.in
- **Data available:**
  - Kerala SIR Final Electoral Roll 2026 (downloadable by booth)
  - Electoral Roll search (voter lookup)
  - Booth-level electoral roll downloads
  - e-EPIC (electronic Electoral Photo Identity Card) download
  - Candidate affidavits and counter-affidavits
  - Disqualified persons list
  - General Election 2024 materials
  - Gazette Notifications
- **Format:** PDF (electoral rolls, affidavits), searchable web interface
- **Downloadable:** Yes (booth-level rolls in PDF)
- **Rating:** GOOD — actual electoral roll data is downloadable

### Election Commission of India

- **URL:** https://www.eci.gov.in
- **Data available:** Statistical reports on all Kerala elections (Assembly and
  Parliamentary), historical results, voter turnout
- **Format:** PDF
- **Downloadable:** Yes (returns 403 at times)

---

## 4. Health Data

### Kerala Health Department Portal

- **URL:** https://health.kerala.gov.in
- **Data available:**
  - Health Portal Dashboard (TFR: 1.5, IMR: 5, NMR: 4, MMR: 30)
  - Data Bank: fact sheets, SDG indicators, demographic/vital statistics
  - Publications: research reports, newsletters, district-level health reports
  - Vaccination services facility lists (downloadable spreadsheets)
  - Annual and monthly reports, technical registries
  - IEC materials across disease categories
- **Format:** PDF (reports), Excel/CSV (spreadsheets), Dashboard
- **Downloadable:** Yes (reports, facility lists)

### DISHA Kerala Health Dashboard

- **URL:** https://disha.kerala.gov.in
- **Status:** Connection refused (April 2026) — portal appears offline
- **Historical notes:** Was Kerala's health information dashboard tracking health
  facility performance, disease surveillance, and service delivery metrics

### COVID-19 Death Information System (CDIS)

- **URL:** https://covid19.kerala.gov.in
- **Data available:** COVID-19 death declaration list, vaccination certificate
  verification, death document verification
- **Format:** Web interface
- **Downloadable:** Limited — primarily a verification tool
- **Status:** Still operational as of April 2026 (v1.1.2.389)

### National Family Health Survey (NFHS)

- **URL:** https://nfhs.iipsindia.org
- **Data available:** NFHS-5 (2019-21) Kerala state and district fact sheets
  covering fertility, mortality, nutrition, child health, HIV, women's empowerment,
  domestic violence, disability
- **Format:** PDF (fact sheets), Stata/SPSS (microdata via DHS Program)
- **Downloadable:** Yes
- **Status:** Connection issues reported (April 2026)

---

## 5. Education Data

### Sametham — Kerala School Databank

- **URL:** https://sametham.kite.kerala.gov.in
- **Data available:**
  - Complete data for 15,369 schools (Government, Aided, Unaided Recognized)
  - 43.6 lakh students tracked across all categories
  - District-wise and section-wise school browsing
  - Class-wise student strength reports
  - School infrastructure and academic details
  - HiTech Schools and Vidyakiranam dashboards
  - Reports at school, sub-district, district, and state level
- **Format:** Web dashboard with report generation
- **Downloadable:** Partially (reports viewable; some may be exportable)
- **Rating:** EXCELLENT — publicly accessible, no login required, rich school-level data

### Sampoorna — School Management System

- **URL:** Accessible via education.kerala.gov.in
- **Data available:** Student details, Transfer Certificates, various reports
- **Format:** Web interface
- **Downloadable:** Requires authentication (school-level login)
- **Notes:** Not publicly accessible for research; requires institutional credentials

### Kerala Results Portal

- **URL:** https://keralaresults.nic.in
- **Data available:** SSLC, Higher Secondary (HSE), VHSE exam results
- **Format:** Web search interface
- **Downloadable:** No — individual result lookup only
- **Status:** Connection refused (April 2026)

### KITE (Kerala Infrastructure and Technology for Education)

- **URL:** https://kite.kerala.gov.in
- **Data available:** IT education statistics, Hi-Tech school coverage, KFON connectivity
- **Format:** Web interface, PDF reports

---

## 6. Financial and Economic Data

### Kerala Budget Portal

- **URL:** https://budget.kerala.gov.in
- **Data available:**
  - Budget speeches and briefs (2025-26, 2026-27)
  - Detailed revenue and expenditure estimates
  - Annual financial statements
  - Citizen's guide to the budget
  - Gender and Child Budget
  - Environmental budget
  - Elderly Budget (new in 2026-27)
  - R&D funding details
  - Performance metrics and evaluations
  - Public undertakings reviews
  - Medium-term fiscal policy documents
  - Revenue/expenditure trend data (in Crore)
- **Format:** PDF (English and Malayalam)
- **Downloadable:** Yes
- **Rating:** EXCELLENT — comprehensive budget documentation

### Kerala Finance Department

- **URL:** https://finance.kerala.gov.in
- **Status:** SSL certificate issues (April 2026)
- **Notes:** Likely hosts Government Orders, financial circulars, and pay revision data

### Kerala Treasury Portal (IFMS)

- **URL:** https://portal.treasury.kerala.gov.in
- **Data available:**
  - Bill details via UTR (Unique Transaction Reference)
  - GRN (Government Receipt Note) information
  - Fixed deposit account details
  - Government Orders and forms
- **Sub-systems:** IFMS, e-Treasury, BIMS, BAMS, WAMS
- **Format:** PDF
- **Downloadable:** Partially — document retrieval by reference number; bulk data
  requires authentication within IFMS/BAMS

### KIIFB (Kerala Infrastructure Investment Fund Board)

- **URL:** https://kiifb.kerala.gov.in
- **Status:** Connection refused (April 2026)
- **Historical notes:** Published project-level data, bond issuance details,
  disbursement data. One of the planned additions for this repository

---

## 7. Land and Property

### Kerala Registration Department (PEARL)

- **URL:** https://registration.kerala.gov.in
- **Sub-portal:** https://pearl.registration.kerala.gov.in (online applications)
- **Data available:**
  - Property registration online applications
  - Fair value of land data (via igr.kerala.gov.in)
  - Societies/organizations registration (via egroops.kerala.gov.in)
  - E-Stamp verification
  - Government orders, acts, rules, circulars
- **Format:** Web interface, PDF
- **Downloadable:** Limited — fair value lookups, not bulk data

### IGR Kerala — Fair Value Portal

- **URL:** https://igr.kerala.gov.in
- **Data available:** Fair value of land by location (updated per SRO No. 420/2023)
- **Format:** Web search interface
- **Downloadable:** No — lookup tool only

### Kerala Land Records (ReLICS / eRekha)

- **URL:** https://erekha.kerala.gov.in
- **Status:** SSL certificate expired (April 2026)
- **Data available:** Digital cadastral maps, land ownership records, patta/chitta data
- **Format:** Web interface with map viewer
- **Downloadable:** No — view/search only

### Kerala Survey and Land Records Department

- **URL:** https://survey.kerala.gov.in
- **Status:** Connection refused (April 2026)

---

## 8. Transport

### Kerala Motor Vehicle Department (MVD)

- **URL:** https://mvd.kerala.gov.in
- **Data available:**
  - Links to Vahan (vehicle registration) and Sarathi (driving license) national dashboards
  - Road accident statistics
  - Fee schedules and tax information
  - RTA contact directories across districts
  - Road safety materials
- **Format:** Web interface, PDF
- **Downloadable:** Limited — statistics viewable, forms downloadable

### Vahan / Parivahan National Dashboard

- **URL:** https://vahan.parivahan.gov.in/vahan4dashboard/
- **Data available:** Vehicle registration statistics filterable by state (Kerala),
  district, vehicle type, fuel type, year
- **Format:** Dashboard with charts; some data exportable
- **Downloadable:** Partially — dashboard data; connection issues reported

### KSRTC Kerala

- **URL:** https://keralartc.com (Kerala SRTC, distinct from Karnataka's ksrtc.in)
- **Data available:** Bus route information, schedules
- **Format:** Web interface
- **Downloadable:** No — booking portal, no open data or APIs documented

---

## 9. Agriculture, Environment, and Natural Resources

### Kerala Agriculture Department (Karshika Keralam)

- **URL:** https://www.keralaagriculture.gov.in
- **Data available:**
  - Compendium of Agricultural Statistics - Kerala 2023
  - AIMS (Agriculture Information Management System): farmer registrations (42.30 lakh+),
    applications (54.59 lakh+), financial disbursement tracking
  - Crop insurance data
  - Vegetable base price information
- **Format:** PDF (statistical reports), Web dashboard (AIMS)
- **Downloadable:** Yes (statistical compendium in PDF)

### Kerala State Pollution Control Board (KSPCB)

- **URL:** https://kspcb.kerala.gov.in
- **Data available:**
  - **Air Quality:** CAAQMS (Continuous Ambient Air Quality Monitoring), NAMP, SAMP
    — daily, monthly, yearly AQI reports
  - **Water Quality:** NWMP (National Water Monitoring Program), SWMP
    — monthly datasets with automatic monitoring
  - **Noise Quality:** Automatic monitoring data
- **Format:** PDF (daily, monthly, yearly reports)
- **Downloadable:** Yes — chronological archives of all monitoring reports
- **Rating:** GOOD — consistent, regularly updated environmental monitoring data

### Kerala Forest Department

- **URL:** https://www.forest.kerala.gov.in
- **Data available:**
  - Forest statistics reports
  - Working plans and management plans
  - Administrative reports
  - Data on protected areas: wildlife sanctuaries, tiger reserves, national parks,
    biosphere reserves
  - Endemic species and endangered fauna/flora documentation
- **Format:** PDF
- **Downloadable:** Yes (reports and statistics)

### Kerala Fisheries Department

- **URL:** https://fisheries.kerala.gov.in
- **Data available:**
  - Marine fish production by district and species
  - Inland fish production by district and species
  - Fishing population data (10.49 lakh total)
  - Registered fishworkers (309,806)
  - Fishing vessels registered (43,298)
  - Fishing harbors (21), fishing villages (222 coastal, 113 inland)
  - Government hatcheries (31)
  - FIMS and REALCRAFT databases
- **Format:** Web interface, PDF
- **Downloadable:** Partially — aggregate statistics on portal; detailed data via FIMS

### Kerala State Disaster Management Authority (KSDMA)

- **URL:** https://sdma.kerala.gov.in
- **Data available:**
  - Real-time alerts: rainfall, dam levels, temperature, lightning, high waves, wind
  - Heavy rainfall forecasting (IMD linked)
  - Tsunami/cyclone/earthquake monitoring
  - UV radiation indices
  - Interactive flood mapping
  - Dam water level monitoring
  - Disaster management plans, guidelines, research reports
  - Training data: 95,560 total trained personnel through 2023
- **Format:** Dashboard, PDF (reports, guidelines)
- **Downloadable:** Partially — reports and plans downloadable; real-time data viewable

### India Meteorological Department (IMD)

- **URL:** https://mausam.imd.gov.in
- **Data available:** Kerala weather forecasts, rainfall, temperature observations
- **Format:** Web interface, recently launched API for programmatic access
- **Downloadable:** Yes via API (new); historical data via data requests

---

## 10. Local Governance and Welfare

### Kerala Local Self Government Department (LSGD)

- **URL:** https://lsgkerala.gov.in
- **Data available:**
  - Statistics on 1,200 local bodies: 941 gram panchayats, 152 block panchayats,
    14 district panchayats, 87 municipalities, 6 corporations
  - Government orders, circulars, gazettes
  - Project implementation progress
  - Master plans for municipalities and panchayats
  - Beneficiary lists
  - Annual financial statements
- **Format:** Web interface, PDF
- **Downloadable:** Limited — mostly informational; financial statements in PDF

### Sulekha — LSG Plan Monitoring System

- **URL:** https://plan.lsgkerala.gov.in / https://sulekha.lsgkerala.gov.in
- **Data available:**
  - Development plan formulation, appraisal, approval, revision tracking
  - ~2 lakh annual decentralized plan projects
  - Expenditure tracking of plan projects across all local governments
  - Historical project reports across plan periods
- **Format:** Web interface
- **Downloadable:** Limited — primarily a monitoring tool; guidelines and GOs downloadable

### Kudumbashree

- **URL:** https://www.kudumbashree.org
- **Data available:**
  - 1,32,327 houses assisted
  - 2,56,227 Neighborhood Groups (NHGs)
  - 1,17,247 individuals trained
  - 51,942 micro-enterprises established
  - District-specific performance data
  - Program-wise analytics (NRLM, DAY-NULM, DDU-GKY)
  - Graphs, charts, and data visualizations
  - Publications: magazines, newsletters, books
- **Format:** Web dashboard, PDF (publications)
- **Downloadable:** Partially — aggregate data on portal; publications downloadable

### Kerala Civil Supplies Department (PDS)

- **URL:** https://civilsupplieskerala.gov.in
- **Data available:**
  - Total ration shops: 13,911
  - Total ration cards: 95,60,714
  - E-service accounts: 1,70,68,871
  - Card categories: AAY, Priority, Subsidy, Non-Priority Institution, Non-Priority General
  - District-wise e-service submission data (all 14 districts)
  - Monthly allotment orders
- **Format:** Web dashboard
- **Downloadable:** Limited — dashboard viewable; allotment orders in PDF

---

## 11. Police and Crime

### Kerala Police

- **URL:** https://keralapolice.gov.in
- **Data available:**
  - Total cognizable crimes (IPC/BNS and SLL): 2020-2026 time series
  - Crimes against children and women
  - SC/ST atrocity cases
  - Cyber crime statistics
  - Missing person data
  - Road accident statistics
  - POCSO cases
  - Organized crime data (including gold smuggling)
  - Interactive trend charts across years
  - Janamaithri newsletters and reports
- **Format:** Dashboard (interactive charts), PDF (reports)
- **Downloadable:** Partially — charts viewable; reports downloadable

---

## 12. Energy and Utilities

### Kerala State Electricity Board (KSEB)

- **URL:** https://kseb.in
- **Data available:**
  - Monthly and historic consumption dashboards
  - Power availability status and outage information
  - Tariff orders and gazette notifications
  - Quarterly financial and administrative reports
  - Fuel surcharge details
  - Power purchase agreements
- **Format:** Dashboard, PDF
- **Downloadable:** Yes (reports, tariff orders)

### Kerala Water Authority (KWA)

- **URL:** https://kwa.kerala.gov.in
- **Data available:** Limited public data — primarily a service portal for bill
  payment, grievances, and tariff information
- **Format:** Web interface
- **Downloadable:** No — service-oriented portal

---

## 13. Tourism

### Kerala Tourism (Official)

- **URL:** https://www.keralatourism.org
- **Data available:** Promotional content, destination guides, event calendars,
  travel information
- **Format:** Web interface, e-brochures
- **Downloadable:** No structured tourism statistics on the public portal
- **Notes:** Tourism statistics (visitor numbers, revenue, foreign tourist arrivals)
  are published via Economic Review and DES

---

## 14. Government Publications and Information

### Kerala Public Relations Department

- **URL:** https://prd.kerala.gov.in
- **Data available:**
  - Press releases and government announcements
  - Kerala Calling (monthly e-magazine)
  - Janapadham (monthly e-magazine)
  - Kerala Legislative Assembly Election History (1957-2025)
  - Loka Kerala Sabha 2026
  - Government circulars, orders, gazettes
- **Format:** PDF (publications), web interface
- **Downloadable:** Yes (publications)

---

## 15. Community and Academic Data Sources

### GitHub Repositories

| Repository | Description | URL |
|-----------|-------------|-----|
| opendatakerala/map.opendatakerala.org | LSG-level portal based on OSM data | github.com/opendatakerala/map.opendatakerala.org |
| CODD-K/covid19kerala.info-data | Collective open dataset of COVID-19 in Kerala | github.com/CODD-K/covid19kerala.info-data |
| Climate change of Kerala | 10-year climate data analysis with shapefiles | github.com/utkarsh-313/Climate-change-of-kerala-over-past-10-year- |
| Kerala Flood Damage Assessment | 2018 flood damage analysis using neural networks | github.com/aparnawarrier8/Kerala-Flood-Damage-Assessment-using-Ternausnet-v2-rgb |

### Academic Institutions

- **Centre for Development Studies (CDS):** https://www.cds.ac.in — research
  publications and working papers on Kerala development (connection issues April 2026)
- **Kerala Agricultural University (KAU):** https://kau.in — agricultural research
  data (SSL issues April 2026)

---

## 16. National Portals with Kerala Data

| Portal | URL | Kerala Data | Format |
|--------|-----|-------------|--------|
| Census of India | censusindia.gov.in | Full population census (2011) | Excel, PDF |
| RBI Handbook | rbi.org.in | 168 tables on state economics | Excel, PDF |
| NCRB Crime in India | ncrb.gov.in | Annual crime statistics | PDF, Excel |
| NFHS | nfhs.iipsindia.org | Health/demographic surveys | PDF, Stata/SPSS |
| Vahan/Parivahan | parivahan.gov.in | Vehicle registration data | Dashboard |
| IMD | mausam.imd.gov.in | Weather/rainfall data | API, Web |
| MGNREGA MIS | nrega.nic.in | Employment guarantee data | Web reports |

---

## Summary: Best Sources by Data Quality

### Highly Recommended (structured, downloadable data)

1. **ecostat.kerala.gov.in** — DES data catalogue with CSV/Excel downloads, dashboards
2. **budget.kerala.gov.in** — Complete budget documentation in PDF
3. **spb.kerala.gov.in** — Economic Review (comprehensive annual report)
4. **RBI Handbook** — State-level financial/economic data in Excel
5. **ceo.kerala.gov.in** — Electoral rolls, candidate data
6. **sametham.kite.kerala.gov.in** — School-level education data (no login needed)
7. **kspcb.kerala.gov.in** — Air/water quality monitoring reports
8. **data.gov.in** — National open data with Kerala datasets (CSV, API)

### Good Sources (viewable data, limited downloads)

9. **keralapolice.gov.in** — Crime trend data with interactive charts
10. **health.kerala.gov.in** — Health indicators and facility data
11. **fisheries.kerala.gov.in** — Fisheries production statistics
12. **sdma.kerala.gov.in** — Disaster/weather alerts and flood data
13. **sdg.kerala.gov.in** — SDG performance tracking
14. **kudumbashree.org** — Poverty alleviation program data
15. **civilsupplieskerala.gov.in** — PDS distribution data

### Service Portals (lookup only, no bulk data)

16. **igr.kerala.gov.in** — Land fair value lookup
17. **mvd.kerala.gov.in** — Vehicle/license queries
18. **portal.treasury.kerala.gov.in** — Transaction lookups
19. **registration.kerala.gov.in** — Property registration services

### Currently Offline (April 2026)

- data.kerala.gov.in (state open data portal)
- disha.kerala.gov.in (health dashboard)
- kiifb.kerala.gov.in (infrastructure fund)
- opensdi.kerala.gov.in (GIS portal — SSL expired)
- erekha.kerala.gov.in (land records — SSL expired)
