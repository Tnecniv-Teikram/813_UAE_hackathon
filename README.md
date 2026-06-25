<div align="center">

<img src="https://space.gov.ae/app_themes/lg21016/images/logo.svg" height="60" alt="UAE Space Agency" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://spaceacademy-hackathons.space.gov.ae/logos/space42.jpg" height="60" alt="Space42" />

# 🛰️ Arab Satellite 813 Hackathon
### *From Light to Insight — Transforming Orbital Data into Climate, Urban & Environmental Solutions*

[![Hackathon](https://img.shields.io/badge/Hackathon-813%20Arab%20Satellite-0A2342?style=for-the-badge&logo=satellite&logoColor=white)](https://spaceacademy-hackathons.space.gov.ae/)
[![Apply Now](https://img.shields.io/badge/Apply%20Now-22%20June%20Deadline-E63946?style=for-the-badge)](https://spaceacademy-hackathons.space.gov.ae/register)
[![License: CC BY 4.0](https://img.shields.io/badge/Data%20License-CC%20BY%204.0-green?style=for-the-badge)](https://creativecommons.org/licenses/by/4.0/)
[![Planet STAC](https://img.shields.io/badge/Data-Planet%20Tanager%20STAC-blue?style=for-the-badge)](https://www.planet.com/data/stac/tanager-core-imagery/catalog.json)

**An initiative by the UAE Space Agency (UAESA) and Space42**  
*Regional online hackathon & incubation program — May 2026 → February 2027*

[🌐 Official Website](https://spaceacademy-hackathons.space.gov.ae/) · [📋 Apply Now](https://spaceacademy-hackathons.space.gov.ae/register) · [💬 Themes](https://spaceacademy-hackathons.space.gov.ae/#challenges)

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [About the Hackathon](#-about-the-hackathon)
- [Who Is It For?](#-who-is-it-for)
- [Program Structure & Timeline](#-program-structure--timeline)
- [The Six Challenge Themes](#-the-six-challenge-themes)
- [Data & Technology Stack](#-data--technology-stack)
- [Repository Structure](#-repository-structure)
- [Notebooks Guide](#-notebooks-guide)
  - [Getting Started — Data Exploration Notebook](#1-getting-started--data-exploration-notebook)
  - [Theme 1: Precision Agriculture & Crop Intelligence](#2-theme-1-precision-agriculture--crop-intelligence)
  - [Theme 2: Land Use & Land Cover Change](#3-theme-2-land-use--land-cover-change)
  - [Theme 3: Air Quality & GHG Plumes](#4-theme-3-air-quality--ghg-plumes)
  - [Theme 4: Climate-Induced Disasters](#5-theme-4-climate-induced-disasters)
  - [Theme 5: Ecosystem Health, Biodiversity & Blue Carbon](#6-theme-5-ecosystem-health-biodiversity--blue-carbon)
  - [Theme 6: Water Quality & Inland/Coastal Water Intelligence](#7-theme-6-water-quality--inlandcoastal-water-intelligence)
- [How to Run the Notebooks](#-how-to-run-the-notebooks)
- [Understanding Tanager Hyperspectral Data](#-understanding-tanager-hyperspectral-data)
- [Spectral Indices Reference](#-spectral-indices-reference)
- [Evaluation Criteria](#-evaluation-criteria)
- [Key Dates](#-key-dates)
- [Partners & Data Providers](#-partners--data-providers)
- [FAQ](#-faq)
- [Contributing](#-contributing)
- [License & Attribution](#-license--attribution)
- [Contact](#-contact)

---

## 🌍 Overview

This repository contains the **official data exploration notebooks, tutorials, and starter code** for the **Arab Satellite 813 Hackathon** — a multi-month regional challenge mobilising the Arab world's brightest minds to build satellite-powered solutions for climate, urban, and environmental challenges.

Participants use real hyperspectral imagery from **Planet's Tanager satellite** (426 spectral bands, 30 m resolution), **EnMAP** (Germany's hyperspectral satellite), and **Planet VHR imagery**..

These notebooks are designed so that a participant with **no prior remote sensing experience** can go from zero to computing advanced spectral indices within a single session. Each notebook is self-contained, extensively commented, and paired with explanatory markdown cells that explain the science behind every step.

---

## 🚀 About the Hackathon

The **Arab Hyperspectral Satellite 813** represents a landmark milestone in regional Earth observation. Its advanced hyperspectral sensor provides unprecedented spectral detail for fine-grained analysis of land, water, atmosphere, and ecosystems across the Arab world — capabilities that were previously only available to well-funded space agencies.

To unlock the full value of this mission, the **UAE Space Agency (UAESA)** and **Space42** have organised this regional online hackathon and incubation program. It is not a weekend sprint — it is a **structured, multi-month journey** from idea to working prototype, with expert mentoring, satellite data access, and a formal incubation phase for the best teams.

### What Makes This Hackathon Different

| Feature | Detail |
|---------|--------|
| **Duration** | May 2026 → February 2027 (multi-phase) |
| **Data** | Real hyperspectral satellite imagery, not synthetic datasets |
| **Platform** | Space42 gIQ — professional geospatial analytics and deployment |
| **Mentoring** | Weekly expert lectures + one-on-one sessions with EO and AI specialists |
| **Incubation** | Top 7 teams enter a structured incubation → MVP pathway |
| **Outcome** | Startup opportunities, pilot deployments, investor visibility |
| **Cost** | Entirely free to participate |

### Objectives

1. **Democratise hyperspectral EO** — make advanced satellite data accessible to the next generation of Arab scientists and engineers
2. **Build real solutions** — move beyond dashboards to deployable, policy-relevant tools
3. **Regional impact** — address challenges specific to Arab world environments (arid lands, coastal zones, rapid urbanisation, food security)
4. **Grow the ecosystem** — build a lasting network of Arab innovators, researchers, and space entrepreneurs

---

## 👥 Who Is It For?

The hackathon is designed for **multidisciplinary teams of 3–5 members** from any Arab country. Cross-country and cross-discipline teams are strongly encouraged.

| Profile | What You Bring |
|---------|---------------|
| 🔬 **Researchers** | Environmental science, remote sensing, ecology, climate science |
| 💻 **Data Scientists & ML Engineers** | Python, geospatial analysis, deep learning for satellite data |
| ⚙️ **Software & Systems Engineers** | API integration, platform development, data pipelines |
| 🎓 **University Students** | Fresh perspectives and commitment to the multi-month program |
| 🌿 **Environmental Domain Experts** | Water, agriculture, urban planning, disaster response |
| 🚀 **Entrepreneurs** | Startup ambition, business modelling, investor readiness |

**No prior satellite data experience is required.** These notebooks are your starting point — they introduce every concept from scratch.

---

## 📅 Program Structure & Timeline

```
June 2026  ->      Jul 2026   ->     Aug 2026    ->   Sep–Oct 2026   ->  Nov 2026
   │                 │                 │                   │                 │
   ▼                 ▼                 ▼                   ▼                 ▼
 Launch &         Application       Teams             PoC Development    Final
 Applications     Deadline          Selected          (10 weeks)         Presentations
 Open             22 July           (up to 20)        + Kickoff          (20 teams)
                                                      + Lectures
                                                      + Mentoring
                                                                               │
                                                                      Nov 2026 → Feb 2027
                                                                               │
                                                                               ▼
                                                                         Incubation Phase
                                                                         (7 teams → MVP)
                                                                               │
                                                                         Feb 2027
                                                                               │
                                                                               ▼
                                                                        Graduation &
                                                                        Awards Ceremony
```

| Phase | Dates | Description |
|-------|-------|-------------|
| **Registration & Selection** | May → July 2026 | Apply with a problem statement. Up to 20 teams selected. |
| **PoC Development** | September → October 2026 | 2-day kickoff, 10 weekly expert lectures, 3 mentor sessions. Build your Proof of Concept. |
| **PoC Submission** | 26 October 2026 | Code, notebooks, demos, and use-case description due. |
| **Final Presentations** | Early November 2026 | 18 teams present live (20–25 min each). 7 teams advance to incubation. |
| **Incubation Phase** | November 2026 → January 2027 | PoC → MVP. Advanced analytics, business coaching, 5 deep-dive mentor sessions. |
| **Graduation & Awards** | February 2027 | Ceremony alongside Arab Group meetings or GITEX. |

---

## 🎯 The Six Challenge Themes

Teams choose **one theme** and build a data-driven, AI-powered proof-of-concept solution using real hyperspectral satellite imagery.

---

### 🌾 Theme 1 — Precision Agriculture & Crop Intelligence

> *Leverage hyperspectral data to monitor crop health, optimize irrigation, and detect pest or disease stress across Arab agricultural zones.*

**Why it matters:** The Arab world faces acute food security challenges. Hyperspectral imagery can detect crop stress **weeks before visible damage appears**, enabling precision interventions that reduce water use, chemical inputs, and yield loss.

**Key capabilities unlocked by Tanager:**
- Chlorophyll content mapping (early disease/stress detection)
- Leaf water content (irrigation deficit monitoring)
- Crop type discrimination across fields
- Soil organic matter and salinity proxies

**Relevant STAC collection:**
```
https://www.planet.com/data/stac/tanager-core-imagery/agriculture/collection.json
```

**Starter notebook:** [`01_agriculture_crop_intelligence.ipynb`](notebooks/01_agriculture_crop_intelligence.ipynb)

---

### 🏙️ Theme 2 — Urban Expansion, Land Use Change & Heat Risk

> *Quantify urban growth, map land-use transitions, and assess urban heat island intensity and heat risk for cities across the Arab world.*

**Why it matters:** Arab cities are among the world's fastest-growing. Unchecked urban sprawl consumes agricultural land, increases heat stress, and strains water infrastructure.

**Key capabilities unlocked by Tanager:**
- Built-up surface detection (NDBI, BUI)
- Impervious surface extent mapping
- Land cover change detection across time
- Urban green space monitoring

**Relevant STAC collections:**
```
https://www.planet.com/data/stac/tanager-core-imagery/urban/collection.json
https://www.planet.com/data/stac/tanager-core-imagery/natural-lands/collection.json
```

**Starter notebook:** [`02_land_use_land_cover_change.ipynb`](notebooks/02_land_use_land_cover_change.ipynb)

---

### 💨 Theme 3 — Air Quality & GHG Plumes

> *Detect and quantify methane and CO₂ point-source emissions from oil and gas infrastructure, landfills, and agricultural facilities.*

**Why it matters:** Methane is 80× more potent than CO₂ over 20 years. Tanager is one of the few satellites that can detect individual facility-level methane plumes — a capability critical to achieving net-zero targets.

**Key capabilities unlocked by Tanager:**
- Methane absorption feature detection at 2,300 nm
- Plume mapping and source attribution
- CO₂ enhancement detection
- Integration with facility-level infrastructure data

**Relevant STAC collection:**
```
https://www.planet.com/data/stac/tanager-core-imagery/GHG-plumes/collection.json
```

**Starter notebook:** [`03_air_quality_ghg_plumes.ipynb`](notebooks/03_air_quality_ghg_plumes.ipynb)

---

### 🔥 Theme 4 — Climate-Induced Disasters

> *Early detection and impact assessment of climate-driven extreme events — floods, droughts, dust storms, wildfires — using satellite time series and AI.*

**Why it matters:** The Arab world is increasingly exposed to climate-driven disasters. Rapid, satellite-based assessment reduces emergency response time and supports early warning systems.

**Key capabilities unlocked by Tanager:**
- Burn scar mapping and fire severity classification (NBR, BAIM)
- Flood inundation extent (NDWI)
- Post-disaster change detection
- Drought stress indicators

**Relevant STAC collections:**
```
https://www.planet.com/data/stac/tanager-core-imagery/fire/collection.json
https://www.planet.com/data/stac/browser/disasters/collection.json
```

**Starter notebook:** [`04_climate_disasters_fire_flood.ipynb`](notebooks/04_climate_disasters_fire_flood.ipynb)

---

### 🌿 Theme 5 — Ecosystem Health, Biodiversity & Blue Carbon

> *Assess terrestrial and coastal ecosystem vitality — including mangrove extent, blue carbon stocks, and biodiversity corridors — using multi-source satellite data.*

**Why it matters:** Blue carbon ecosystems (mangroves, seagrass, salt marshes) store up to 5× more carbon per hectare than tropical forests. The Arabian Peninsula hosts some of the world's most climatically stressed mangrove ecosystems.

**Key capabilities unlocked by Tanager:**
- Mangrove species discrimination
- Chlorophyll and phytoplankton detection in coastal water
- Harmful algal bloom (HAB) early warning
- Ecosystem stress mapping

**Relevant STAC collection:**
```
https://www.planet.com/data/stac/tanager-core-imagery/coastal-water-bodies/collection.json
```

**Starter notebook:** [`05_ecosystem_health_blue_carbon.ipynb`](notebooks/05_ecosystem_health_blue_carbon.ipynb)

---

### 💧 Theme 6 — Water Quality & Inland/Coastal Water Intelligence

> *Monitor water clarity, algal blooms, turbidity, and pollution plumes in inland and coastal water bodies.*

**Why it matters:** Water scarcity is the defining challenge of the Arab world. Hyperspectral satellites can monitor reservoir health, detect pollution events, and track coastal water quality — at a fraction of the cost of field sampling.

**Key capabilities unlocked by Tanager:**
- Turbidity and suspended sediment mapping
- Chlorophyll-a concentration (algal biomass)
- Dissolved organic matter estimation
- Coastal water body change detection

**Relevant STAC collection:**
```
https://www.planet.com/data/stac/tanager-core-imagery/coastal-water-bodies/collection.json
```

> This theme shares the same STAC collection as Theme 5 but focuses on **water quality parameters** rather than vegetation. The base exploration notebook covers NDWI, NDCI, and turbidity proxies applicable here.

---

## 🛠️ Data & Technology Stack

### Satellite Data

| Dataset | Provider | Resolution | Bands | Coverage |
|---------|----------|-----------|-------|----------|
| **Tanager-1** | Planet Labs | 30 m | 426 bands (380–2500 nm) | Global, themed collections |
| **EnMAP** | DLR (Germany) | 30 m | 228 bands (420–2450 nm) | Global |
| **Planet VHR** | Planet Labs | 3–5 m | 4–8 multispectral bands | Global daily |

### Open Tools Used in This Repository

| Tool | Purpose |
|------|---------|
| `h5py` | Read Tanager HDF5 files |
| `numpy` | Array operations and index computation |
| `matplotlib` | Visualization and spectral plots |
| `geopandas` | Spatial data handling and footprint mapping |
| `leafmap` | Interactive web maps with COG layers |
| `pystac` / `pystac-client` | STAC catalog browsing |
| `requests` | HTTP download of STAC items and HDF5 files |
| `rioxarray` / `xarray` | Geospatial raster analysis |

---

## 📁 Repository Structure

```
arab-813-hackathon/
│
├── README.md                                     ← You are here
│
├── notebooks/
│   ├── 00_data_exploration_starter.ipynb         ← Start here: Sentinel-2 + Tanager basics
│   ├── 01_agriculture_crop_intelligence.ipynb    ← Theme 1: Crop health, NDVI/NDRE/NDMI/BSI
│   ├── 02_land_use_land_cover_change.ipynb       ← Theme 2: Urban mapping, NDBI/BUI
│   ├── 03_air_quality_ghg_plumes.ipynb           ← Theme 3: Methane detection, MBSI
│   ├── 04_climate_disasters_fire_flood.ipynb     ← Theme 4: Fire severity, NBR/BAIM
│   └── 05_ecosystem_health_blue_carbon.ipynb     ← Theme 5/6: Mangroves, NDCI, water quality
│
├── docs/
│   ├── spectral_indices_reference.md             ← Full index formula reference
│   ├── tanager_data_guide.md                     ← HDF5 structure & asset keys explained
│   └── stac_collection_map.md                    ← All collection URLs and item IDs
│
├── assets/
│   └── images/                                   ← Figures used in README
│
└── requirements.txt                              ← Python dependencies
```

---

## 📓 Notebooks Guide

All notebooks share a **common structure**. Each one is fully self-contained and follows the same 12-step pattern, so skills transfer directly between themes.

### Common Notebook Structure

```
Step 1  → Install dependencies
Step 2  → Fix titiler endpoint (prevents a known leafmap/Planetary Computer conflict)
Step 3  → Load STAC items from Planet's open data catalog
Step 4  → Inspect metadata and display thumbnail
Step 5  → Visualize scene on interactive map (COG overlay)
Step 6  → Download the HDF5 surface reflectance file
Step 7  → Check scene quality (cloud/nodata/cirrus masks)
Step 8  → Extract spectral wavelengths from STAC metadata
Step 9  → Select key wavelengths for the theme's indices
Step 10 → Load only the required bands (fast, memory-efficient)
Step 11 → Compute spectral indices
Step 12 → Visualize, summarize statistics, and plot mean spectrum
```

---

### 1. Getting Started — Data Exploration Notebook

**File:** `notebooks/00_data_exploration_starter.ipynb`

This is your **first stop**. It introduces every concept needed to work with satellite data, covering both Sentinel-2 (multispectral, 13 bands) and Planet Tanager (hyperspectral, 426 bands). No prior remote sensing experience required.

**What you learn:**
- What a STAC catalog is and why the industry uses it
- How to query satellite imagery by location and date
- How to visualize Cloud Optimized GeoTIFFs (COGs) on an interactive map
- The difference between radiance and surface reflectance
- How to read and explore a Tanager HDF5 file
- How spectral indices work and what they measure

**Key steps covered:**

| Step | What Happens |
|------|-------------|
| Connect to Planetary Computer STAC API | Search Sentinel-2 imagery for the UAE |
| Visualize Sentinel-2 RGB and false colour | Load COG layers on leafmap |
| Connect to Planet's open STAC catalog | Fetch Tanager coastal scenes |
| Explore STAC metadata | Understand all asset keys and band metadata |
| Download HDF5 surface reflectance | Stream or save to disk |
| Extract wavelengths | Read `eo:center_wavelength` from STAC `bands` |
| Compute NDVI, NDWI, NDCI, Turbidity | Four coastal water body indices |
| Plot mean spectrum | Full 426-band spectral signature |
| Remove water vapor bands | Clean spectrum for interpretation |

---

### 2. Theme 1: Precision Agriculture & Crop Intelligence

**File:** `notebooks/01_agriculture_crop_intelligence.ipynb`  
**STAC collection:** `agriculture`  
**Best for:** Teams working on food security, irrigation efficiency, or crop monitoring

**Indices computed:**

| Index | Formula | Interpretation |
|-------|---------|----------------|
| NDVI | `(NIR₈₆₀ − Red₆₆₅) / (NIR₈₆₀ + Red₆₆₅)` | General vegetation health; 0.4–0.9 = healthy crops |
| NDRE | `(NIR₈₆₀ − RE₇₀₅) / (NIR₈₆₀ + RE₇₀₅)` | Nitrogen/chlorophyll stress; more sensitive to early stress than NDVI |
| NDMI | `(NIR₈₆₀ − SWIR₁₆₅₀) / (NIR₈₆₀ + SWIR₁₆₅₀)` | Leaf water content and irrigation deficit |
| BSI | `((SWIR + Red) − (NIR + Green)) / ((SWIR + Red) + (NIR + Green))` | Bare soil exposure and harvest monitoring |

**What you produce:** A 4-panel index map showing crop greenness, stress, moisture, and soil exposure across the scene, plus summary statistics per index.

---

### 3. Theme 2: Land Use & Land Cover Change

**File:** `notebooks/02_land_use_land_cover_change.ipynb`  
**STAC collections:** `urban` + `natural-lands`  
**Featured scene:** Riyadh, Saudi Arabia  
**Best for:** Teams working on urban planning, sprawl detection, or green space mapping

**Indices computed:**

| Index | Formula | Interpretation |
|-------|---------|----------------|
| NDVI | `(NIR − Red) / (NIR + Red)` | Vegetation cover |
| NDBI | `(SWIR − NIR) / (SWIR + NIR)` | Built-up surfaces; positive = urban fabric |
| MNDWI | `(Green − SWIR) / (Green + SWIR)` | Open water bodies |
| BUI | `NDBI − NDVI` | Net built-up area, vegetation-corrected |

**What you produce:** A 4-panel index map + a 4-class land cover classification (Water / Vegetation / Built-up / Bare soil) with colour-coded legend and pixel count statistics.

---

### 4. Theme 3: Air Quality & GHG Plumes

**File:** `notebooks/03_air_quality_ghg_plumes.ipynb`  
**STAC collection:** `GHG-plumes`  
**Best for:** Teams working on methane detection, emission monitoring, or climate mitigation

> ℹ️ This notebook **auto-discovers** available scene IDs from the live `collection.json` at runtime — it always uses real, current items without hardcoded IDs.

**Indices computed:**

| Index | Formula | Interpretation |
|-------|---------|----------------|
| MBSI | `(R_ref1 + R_ref2) / (2 × R_abs) − 1` | Methane Band Suppression at 2,300 nm |
| Plume Proxy | `(ref_mean − R_abs) / ref_mean` | Normalized absorption anomaly in CH₄ window |
| NDSI-SWIR | `(SWIR − NIR) / (SWIR + NIR)` | Surface composition context |

**What you produce:** A 3-panel spatial map of the methane absorption anomaly + a full spectrum plot zoomed into the 2,100–2,500 nm range with the CH₄ absorption region highlighted in orange.

---

### 5. Theme 4: Climate-Induced Disasters

**File:** `notebooks/04_climate_disasters_fire_flood.ipynb`  
**STAC collections:** `fire` + `disasters`  
**Best for:** Teams working on disaster response, early warning, or climate resilience

> ℹ️ This notebook also **auto-discovers** scene IDs from the live `fire/collection.json`.

**Indices computed:**

| Index | Formula | Interpretation |
|-------|---------|----------------|
| NBR | `(NIR − SWIR₂₂₀₀) / (NIR + SWIR₂₂₀₀)` | Burn ratio; negative post-fire, positive healthy veg |
| BAIM | `1 / ((0.05 − ρNIR)² + (0.2 − ρSWIR)²)` | Burn Area Index Modified; highlights active burns |
| NDWI | `(Green − NIR) / (Green + NIR)` | Water / flood detection |
| NDVI | standard | Vegetation reference |

**What you produce:** A 4-panel index map + a UN/USGS 5-class burn severity classification (Unburned → High Severity) with pixel statistics.

---

### 6. Theme 5: Ecosystem Health, Biodiversity & Blue Carbon

**File:** `notebooks/05_ecosystem_health_blue_carbon.ipynb`  
**STAC collection:** `coastal-water-bodies`  
**Featured scenes:** UAE coastal waters — Abu Dhabi area  
**Best for:** Teams working on mangroves, seagrass, harmful algal blooms, or blue carbon accounting

**Indices computed:**

| Index | Formula | Interpretation |
|-------|---------|----------------|
| NDVI | `(NIR₈₀₀ − Red₆₆₅) / (…)` | Coastal vegetation (mangroves, saltmarsh) |
| NDWI | `(Green₅₆₀ − NIR₈₆₀) / (…)` | Open water extent |
| NDCI | `(RE₇₀₈ − Red₆₆₅) / (…)` | Chlorophyll — algae and phytoplankton |
| Turbidity | `(Red₆₆₅ − Green₅₆₀) / (…)` | Suspended sediment in water |
| Mangrove Proxy | NDCI where NDVI>0.2 & NDWI<0 | Dense coastal vegetation |

**What you produce:** A 6-panel dashboard (5 index maps + true-colour RGB composite) + a separate spectral comparison of water vs vegetation signatures, and summary statistics.

---

### 7. Theme 6: Water Quality & Inland/Coastal Water Intelligence

**Starter notebook:** Use `notebooks/05_ecosystem_health_blue_carbon.ipynb` as your base.

The ecosystem notebook computes NDWI (water extent), NDCI (chlorophyll/algae), and Turbidity — the three indices most relevant to water quality monitoring. Extend it by:

- Thresholding NDWI to isolate open water pixels
- Applying NDCI to water-masked pixels only (filtering out land)
- Computing a Floating Algae Index (FAI) using NIR/SWIR contrast
- Correlating with in-situ measurements if available

For reservoir / inland water scenes, also check the `coastal-water-bodies` collection — it includes scenes over both marine and freshwater environments.

---

## ▶️ How to Run the Notebooks

### Option 1: Google Colab (Recommended — no local setup)

Click the badge to open any notebook directly in Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-ORG/arab-813-hackathon/blob/main/notebooks/00_data_exploration_starter.ipynb)

All notebooks run `%pip install` in their first code cell — no local setup needed.

---

### Option 2: Local Jupyter Environment

**Prerequisites:** Python 3.9+

```bash
# 1. Clone this repository
git clone https://github.com/YOUR-ORG/arab-813-hackathon.git
cd arab-813-hackathon

# 2. Create a virtual environment (recommended)
python -m venv .venv
source .venv/bin/activate        # macOS/Linux
.venv\Scripts\activate           # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter
jupyter notebook notebooks/
```

---

### Space42 gIQ Platform

Selected teams receive access to the **Space42 gIQ Platform** — a pre-configured cloud environment with all dependencies installed, direct data access, and deployment tooling. No local installation needed.

---

### ⚠️ Known Issue: leafmap Titiler Endpoint Conflict

If you run the Planetary Computer (Sentinel-2) cells **before** the Planet Tanager cells in the same kernel session, leafmap caches a `PlanetaryComputerEndpoint` object and breaks all subsequent `add_cog_layer` calls with:

```
Invalid URL '<leafmap.stac.PlanetaryComputerEndpoint object at 0x...>/cog/info'
```

**Fix:** All Tanager notebooks include this near the top — ensure it runs before any map cell:

```python
import os
os.environ["TITILER_ENDPOINT"] = "https://titiler.xyz"
```

---

### ⚠️ HDF5 Download Times

Tanager surface reflectance HDF5 files are typically **1–5 GB** each.

| Connection Speed | Estimated Download Time |
|-----------------|------------------------|
| 100 Mbps | 1–5 minutes |
| 50 Mbps | 2–10 minutes |
| 10 Mbps | 10–45 minutes |

The notebooks check `os.path.exists(local_path)` before downloading — re-running a cell will **not** re-download an already saved file.

---

## 🔭 Understanding Tanager Hyperspectral Data

### What is hyperspectral imagery?

An ordinary photograph records **3 bands** (red, green, blue) — what the human eye sees. Tanager records **426 narrow bands** from 380 nm to 2,500 nm.

```
Ordinary camera:  [ Red | Green | Blue ]
                    3 bands — ~100 nm each

Tanager:          [||||||||||||||||||||||||||||||||||||||||||||||||||||||||]
                    426 bands — ~5 nm each, continuously from 380–2500 nm
```

This allows Tanager to detect:
- **Chlorophyll stress** before leaves visibly wilt (680 nm + red-edge at 720 nm)
- **Leaf water content** (NIR and SWIR contrast)
- **Soil composition** (clay, iron oxide, carbonate minerals have SWIR signatures)
- **Methane** (absorption at 2,300 nm)
- **Water quality** (blue/green ratios, turbidity)

### HDF5 File Structure

Every Tanager surface reflectance file follows this structure:

```
HDFEOS/GRIDS/HYP/Data Fields/
├── surface_reflectance      (426, rows, cols) float32  ← main data cube
├── beta_cloud_mask          (rows, cols) uint8
├── beta_cirrus_mask         (rows, cols) uint8
├── nodata_pixels            (rows, cols) uint8
├── aerosol_optical_depth    (rows, cols) float32
├── column_water_vapour      (rows, cols) float32
├── sensor_zenith            (rows, cols) float32
└── sun_zenith               (rows, cols) float32
```

### Reading Wavelength Metadata

Wavelengths are stored in the STAC item under the `bands` key as `eo:center_wavelength` (in micrometers):

```python
bands_meta = item["assets"][sr_key].get("bands", [])
spectral_bands = [b for b in bands_meta if "eo:center_wavelength" in b]
wavelengths_um = np.array([b["eo:center_wavelength"] for b in spectral_bands])
wavelengths_nm = wavelengths_um * 1000.0   # convert µm → nm
```

> **Common pitfall:** The key is `"eo:center_wavelength"` (with the `eo:` prefix), not `"center_wavelength"`. This tripped up even experienced users — all notebooks use the correct form.

### Water Vapor Absorption Windows

These two spectral regions measure **atmospheric opacity**, not ground reflectance. Always exclude them:

| Region | Wavelengths | Cause |
|--------|------------|-------|
| SWIR-1 water vapor | 1,350 – 1,450 nm | Atmospheric H₂O |
| SWIR-2 water vapor | 1,800 – 1,950 nm | Atmospheric H₂O |

All notebooks include:

```python
def is_water_vapor(wl):
    return (1350 <= wl <= 1450) or (1800 <= wl <= 1950)
```

---

## 📐 Spectral Indices Reference

### Vegetation Indices

| Index | Full Name | Formula | Healthy Range | Theme |
|-------|----------|---------|--------------|-------|
| NDVI | Normalized Difference Vegetation Index | `(NIR − Red) / (NIR + Red)` | 0.4–0.9 | All |
| NDRE | Normalized Difference Red Edge | `(NIR − RE₇₀₅) / (NIR + RE₇₀₅)` | 0.2–0.6 | Agriculture |
| NDMI | Normalized Difference Moisture Index | `(NIR − SWIR₁₆₅₀) / (NIR + SWIR₁₆₅₀)` | 0.0–0.6 | Agriculture |
| BSI | Bare Soil Index | `((SWIR + Red) − (NIR + Green)) / (…)` | < 0 = vegetated | Agriculture |

### Urban & Land Cover Indices

| Index | Full Name | Formula | Interpretation | Theme |
|-------|----------|---------|---------------|-------|
| NDBI | Normalized Difference Built-Up Index | `(SWIR − NIR) / (SWIR + NIR)` | > 0 = built-up | LULC |
| MNDWI | Modified Normalized Difference Water Index | `(Green − SWIR) / (Green + SWIR)` | > 0.1 = water | LULC, Water |
| BUI | Built-Up Index | `NDBI − NDVI` | > 0 = urban | LULC |

### Water & Coastal Indices

| Index | Full Name | Formula | Interpretation | Theme |
|-------|----------|---------|---------------|-------|
| NDWI | Normalized Difference Water Index | `(Green − NIR) / (Green + NIR)` | > 0 = open water | Water, Disasters |
| NDCI | Normalized Difference Chlorophyll Index | `(RE₇₀₈ − Red₆₆₅) / (RE₇₀₈ + Red₆₆₅)` | > 0.2 = algal bloom risk | Ecosystem, Water |
| Turbidity | Turbidity Proxy | `(Red₆₆₅ − Green₅₆₀) / (Red₆₆₅ + Green₅₆₀)` | > 0 = sediment-laden | Ecosystem, Water |

### Fire & Disaster Indices

| Index | Full Name | Formula | Burn Severity Thresholds | Theme |
|-------|----------|---------|--------------------------|-------|
| NBR | Normalized Burn Ratio | `(NIR − SWIR₂₂₀₀) / (NIR + SWIR₂₂₀₀)` | < −0.44 = high severity | Disasters |
| dNBR | Delta Normalized Burn Ratio | `NBR_pre − NBR_post` | > 0.66 = high severity | Disasters |
| BAIM | Burn Area Index Modified | `1 / ((0.05 − NIR)² + (0.2 − SWIR)²)` | High = active burn | Disasters |

### GHG Detection Indices

| Index | Full Name | Formula | Interpretation | Theme |
|-------|----------|---------|---------------|-------|
| MBSI | Methane Band Suppression Index | `(R_ref1 + R_ref2) / (2 × R_abs) − 1` | > 0 = absorption anomaly | Air Quality |
| Plume Proxy | CH₄ Absorption Anomaly | `(ref_mean − R_abs) / ref_mean` | High = plume candidate | Air Quality |

---

## 🏆 Evaluation Criteria

All submissions are judged across five criteria:

| # | Criterion | What Judges Look For |
|---|-----------|---------------------|
| 1 | 🌍 **Impact** | Scale of problem, breadth of population that benefits, policy relevance |
| 2 | 💡 **Creativity** | Originality — a novel concept or a meaningful advance on existing approaches |
| 3 | 🔬 **Validity** | Scientific and technical rigor, real-world applicability |
| 4 | 🎯 **Relevance** | Fit to theme, completeness, feasibility, usability |
| 5 | 🎤 **Presentation** | Clarity of storytelling, quality of visual delivery |

> **Bonus:** Teams using hyperspectral data (Tanager / EnMAP) receive additional consideration during selection. A complete working solution is **not** required at application — a well-articulated problem statement and approach is sufficient.

---

## 📆 Key Dates

| Date | Milestone |
|------|-----------|
| Mid-May 2026 | Program launch — applications open |
| **31 July 2026** | ⚠️ **Application deadline** |
| Early August 2026 | Teams notified, platform and data access granted |
| July – August 2026 | Summer preparation period |
| 24-25 August 2026 | Online kickoff and orientation |
| September 2026 | 2-day webinar trainings + weekly expert lectures begin |
| **11 October 2026** | **PoC submission deadline** |
| Early November 2026 | Live presentations — 20 teams, 7 advance to incubation |
| November 2026 – January 2027 | Incubation phase (PoC → MVP) |
| **25 January 2027** | Final MVP submission |
| February 2027 | Graduation ceremony and awards |

---

## 🤝 Partners & Data Providers

| Organisation | Role |
|-------------|------|
| **UAE Space Agency (UAESA)** | Organiser, technical steering, Arab 813 satellite mission owner |
| **Space42** | Organiser, gIQ platform access, mentoring network |
| **Planet Labs** | Tanager-1 hyperspectral open data (CC BY 4.0) |
| **EnMAP / DLR** | European hyperspectral satellite data |
| **Arab Youth Centre** | Regional outreach and youth engagement |
| **NSSTC** | Scientific and technical program partner |

---

## ❓ FAQ

<details>
<summary><strong>Is this a typical weekend hackathon?</strong></summary>

No. This is a structured, multi-month program running May 2026 → February 2027. It includes a proposal phase, a 10-week PoC development phase with expert lectures and mentoring, competitive selection for incubation, and a 10-week incubation phase producing MVP-level solutions.

</details>

<details>
<summary><strong>Do I need prior remote sensing or satellite data experience?</strong></summary>

No. The notebooks introduce every concept from scratch — what a STAC catalog is, what surface reflectance means, and how spectral indices work. If you can run a Python script, you can use these notebooks.

</details>

<details>
<summary><strong>Who can apply?</strong></summary>

Students, researchers, engineers, data scientists, and entrepreneurs from the UAE or any Arab country with an interest in Earth observation, GeoAI, sustainability, or space applications.

</details>

<details>
<summary><strong>Can I apply as an individual?</strong></summary>

Yes. Individual applicants may be matched into teams by the organisers after selection. Teams are 3–5 members and are fixed after the PoC kickoff.

</details>

<details>
<summary><strong>What data will participants use?</strong></summary>

All participants access Planet Tanager hyperspectral open data (via STAC, free) and EnMAP data. Selected teams additionally receive full access to the Space42 gIQ Platform, including Planet VHR imagery.

</details>

<details>
<summary><strong>Is hyperspectral data mandatory?</strong></summary>

No, but strongly encouraged and given bonus consideration during selection. Teams may also work with very high-resolution EO data.

</details>

<details>
<summary><strong>The HDF5 files are very large. Is there a faster way to access the data?</strong></summary>

Yes. The base notebook (cell 61) demonstrates streaming HDF5 data directly into memory using `h5py.File(io.BytesIO(data), "r")` — suitable for smaller scenes. For large files, the streaming download in cell 64 uses 1 MB chunks. Running on Google Colab also helps, as it has fast connections to the Google Cloud Storage buckets where the files are hosted.

</details>

<details>
<summary><strong>Are there prizes?</strong></summary>

Yes. Winning teams receive recognition at a formal ceremony, extended mentorship, regional visibility with space agency leadership and industry partners, and pathways to pilots, partnerships, or investor discussions. The top 5 teams in full incubation receive structured business coaching and startup acceleration support.

</details>

<details>
<summary><strong>Who owns the intellectual property?</strong></summary>

Teams retain full ownership of their solutions. Organisers may request permission to showcase outputs for non-commercial promotional purposes.

</details>

<details>
<summary><strong>Is there a participation fee?</strong></summary>

No. The program is entirely free.

</details>

---

## 🤝 Contributing

Contributions from participants and mentors are welcome:

1. **Bug fixes** — open a pull request with a clear description of the fix
2. **New spectral indices** — add to `docs/spectral_indices_reference.md` with formula, reference, and interpretation
3. **New STAC scene guides** — add item IDs and coverage notes to `docs/stac_collection_map.md`
4. **Arabic translations** — create `notebooks/ar/` with Arabic-language versions of any notebook

Please open an issue before starting significant work so the team can coordinate.

---

## 📄 License & Attribution

### Code & Notebooks

All code in this repository is released under the **MIT License**. See [`LICENSE`](LICENSE) for details.

### Satellite Data

All Planet Tanager data used in these notebooks is released under **Creative Commons CC-BY 4.0**.

Required attribution for any use or redistribution of Tanager data:

> *"Tanager STAC Data, available at www.planet.com/data/stac © [YEAR] Planet Labs PBC. All Rights Reserved."*

Where `[YEAR]` is the year the data was captured (visible in the scene ID timestamp, e.g. `20250223` = 2025).

For adapted material, prefix with *"Adapted from…"*

---

## 📬 Contact

| | |
|-|-|
| 🌐 **Hackathon website** | [spaceacademy-hackathons.space.gov.ae](https://spaceacademy-hackathons.space.gov.ae/) |
| 📋 **Apply** | [spaceacademy-hackathons.space.gov.ae/register](https://spaceacademy-hackathons.space.gov.ae/register) |
| 🏛️ **UAE Space Agency** | [space.gov.ae](https://space.gov.ae/en) |
| 🛰️ **Space42** | [space42.ai](https://www.space42.ai) |
| 🌍 **Planet open data** | [planet.com/data/stac](https://www.planet.com/data/stac/browser/tanager-core-imagery/catalog.json) |

---

<div align="center">

**Arab Satellite 813 Hackathon**  
An initiative by UAE Space Agency & Space42

*Application deadline: 22 June 2026*

[🚀 Apply Now](https://spaceacademy-hackathons.space.gov.ae/register)

`#ArabSatellite813` · `#FromLightToInsight` · `#SpaceTech` · `#EarthObservation`

</div>
