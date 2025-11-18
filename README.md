**Malaria Incidence in Nigeria: A Geospatial Analysis**

This study utilizes Geographic Information Systems (GIS) and interactive mapping to analyze the spatial and temporal distribution of malaria across Nigeria's 36 states and the Federal Capital Territory from 2010 to 2020. 
The research aims to identify high-risk areas and track seasonal trends in malaria transmission by integrating various environmental and demographic factors.

**Project Objective**
The primary goal of this research is to offer a data-driven approach to malaria surveillance, providing valuable insights for policymakers to design effective, region-specific public health strategies to reduce the disease burden on vulnerable populations, especially children under five and pregnant women.
 
**Methodology**
A geospatial approach was employed, involving the integration and disaggregation of multiple datasets:

**Data Sources:**

**Malaria Cases:** Obtained from the Malaria Atlas Project.

**Population Data:** State-level figures derived from Nigeria's National Population Census.

**Environmental Data:** Temperature and rainfall data analyzed from the Nigeria Meteorological Agency (NiMET).

**Land Use Land Cover (LULC):** Used to classify regions and apply weighting factors to population estimates, recognizing the influence of LULC on transmission.

**Administrative Boundaries:** World Bank geographic shapefiles were used for mapping Nigeria's states.

**Data Processing:** National-level data was disaggregated to the state level. This involved creating an Environmental Risk Index (ERI) by integrating temperature (optimal range is $20-32^{\circ}\text{C}$ for breeding) and rainfall data to identify high-risk zones (stagnant water). The national malaria case numbers were then allocated to each state based on these computed risk weights.
Tools: Python-based tools like pandas, geopandas, and rasterio were used for data manipulation and spatial analysis .

**Key Findings (Results)**

**Spatial Patterns (Hotspots):** Hotspot mapping revealed significant spatial variation in malaria incidence. States in the North and Central regions (like Kano, Kaduna, and Niger) consistently exhibited higher rates. These areas feature favorable conditions:  $20-30^{\circ}\text{C}$ temperatures, frequent rainfall, large agricultural areas, and high population density.Lower Incidence: Urban centers like Lagos and other southern cities showed notably lower incidence, attributed to factors like better healthcare infrastructure and effective control programs.

**Temporal Trends:** Analysis from 2010 to 2020 revealed important temporal patterns, with periodic spikes often linked to unusual weather events, emphasizing the need for continuous monitoring and adaptable control strategies. 

**Visualization and Analysis**
The project employs various GIS techniques and interactive tools for data exploration and accessibility:

**Hotspot Mapping:** Conducted using ArcGIS Online to identify regions with significantly higher case numbers.

**Temporal Trend Analysis:** Time-series charts covering 2010 to 2020 visualized seasonal fluctuations and long-term trends.

**Interactive Visualization:** A dashboard and story maps were developed, featuring a map for state-to-state comparison, bar charts for affected areas, pie charts for less affected areas, and a slider to visualize data across years.

## 🚀 View the Story Map

[![View Story Map](https://img.shields.io/badge/View%20Interactive%20Story%20Map-blue?style=for-the-badge)](https://geoportal22s.zgis.at/portal/apps/storymaps/stories/adb2b64fc6ce4c9eb186a9d026ec240e)

---
