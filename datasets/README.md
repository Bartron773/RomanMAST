# RomanMAST Dataset Schemas

This directory contains representative schema and sample `.csv` files conceptualizing the three foundational datasets proposed for ingestion into the Mikulski Archive for Space Telescopes (MAST). These files demonstrate the interoperable structure required to unify historical ground-based and space-based microlensing data for seamless co-analysis with the Nancy Grace Roman Space Telescope.

## Folder Contents

### 1. OGLE-Gaia Seed Catalog Concept
- `01_OGLE_long_timescale_see.csv`: Baseline catalog logging long-timescale microlensing events.
- `02_Gaia_crossmatch_seed.csv`: Demonstration of cross-matching OGLE events with Gaia astrometric precision.
- `03_Roman_future_schema_seed.csv` & `real_long_timescale_blackhole_candidates.csv`: Future schema linking these candidates to Roman GBTDS detections.

### 2. Spitzer Parallax Catalog Concept
- `01_Spitzer_Parallax_Vector_Catalog.csv`: Table containing historical microlens parallax ($\pi_E$) vector components observed by the Spitzer Space Telescope from a 1 AU baseline.
- `02_Long_Timescale_BH_Candidates.csv`: Flagged high-mass candidates isolated by Spitzer's degeneracy-breaking data.
- `03_Roman_GBTDS_Overlap_Map.csv`: Coverage map demonstrating the spatial overlap of historical Spitzer pointings with Roman's survey footprint.

### 3. OGLE-KMTNet Trifecta Light Curves Concept
- `01_OGLE_KMTNet_LightCurves_Index.csv`: Index table synthesizing fragmented light curve metadata from both temporal surveys.
- `02_Long_Timescale_Trifecta_Candidates.csv`: Long timescale anomalies requiring combined survey analysis.
- `03_Roman_GBTDS_Trifecta_Overlap.csv` & `KMTNet.csv`: Demonstrative maps mapping these light curve histories directly onto the anticipated Roman observations.

---

> **Note:** These files are conceptual schema templates. They do not contain the exhaustive, multi-terabyte raw survey data. Their purpose is to prove the viability, structure, and minimal footprint required for a metadata-rich HLSP ingestion at MAST.
