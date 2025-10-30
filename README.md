# Chasing Chlorophyll
**Seasonal Chlorophyll Variability and Its Effects on Manta Ray Detection**  

## Research Questions
- How does seasonal variation in chlorophyll-a concentration influence manta ray detections around Lady Elliot Island (LEI)?  
- Are peaks in manta ray presence a proxy for primary productivity?
- How do physical oceanographic drivers affect this relationship?

---

## Hypothesis  
Increases in chlorophyll-a concentration, representing higher primary productivity, are expected to correspond with longer manta ray residence times. This relationship is likely also driven through other physical oceanagraphic processes.

---

## Datasets  
- **eReefs GBR4 Hydrodynamic Model** – https://thredds.nci.org.au/thredds/catalog/catalogs/fx3/catalog.html?dataset=gbr4_2.0
- **eReefs GBR4 BioGeoChemical Model** – https://thredds.nci.org.au/thredds/catalog/catalogs/fx3/catalog.html?dataset=GBR4_H2p0_B3p1_Cq3b_Dhnd
- **eReeds Model Descriptions** - https://research.csiro.au/ereefs/summary/
- **IMOS Acoustic Telemetry Data (Project Manta)** – https://animaltracking.aodn.org.au/detection

---

## Analysis Plan  
- Extract environmental data (chlorophyll-a, current speed, current direction, salinity, temperature, wind speed) from eReefs GBR4 models via the AIMS THREDDS Data Server.
- Subset datasets to the Lady Elliot Island region (−24.14° to −24.09°, 152.70° to 152.73°) at the surface layer (~0.5 m) for the years 2011–2013.
- Process IMOS acoustic telemetry detections from to identify consistently detected individuals and define residency period metric.
- Calculate monthly mean residence times for resident mantas and aggregate environmental variables to monthly means for comparison.
- Conduct correlation analyses to test relationships between manta residence periods and chlorophyll-a concentration as well as assess co-variation between individuals.
- Perform one-way ANOVA and chi-squared tests to examine time-of-day activity patterns and differences between individuals.
- Visualise the relationships using time-series plots, heatmaps, and bloxplots to understand environmental variability and manta behaviour seasonally.
- Merge manta and eReefs datasets by timestamp and conduct multiple regression to test the effects of chlorophyll-a and hydrodynamic variables on manta rays.

