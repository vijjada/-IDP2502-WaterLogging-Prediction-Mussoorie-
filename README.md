# -IDP2502-WaterLogging-Prediction-Mussoorie-
IDP2502 group project at GD Goenka University: Predictive water logging model for Mussoorie using hyperspectral imaging, GIS terrain analysis (DEM, TWI, NDWI), and rainfall-runoff simulations. Achieved 85% validation accuracy identifying high-risk zones like Kempty Falls. Supports SDG 6, 11, 13 for sustainable urban planning

# 🌊 IDP2502: Hyperspectral Image Analysis for Water Logging Prediction in Mussoorie

> **Predictive Modeling for Sustainable Urban Development using Remote Sensing & GIS**

## 📌 Project Overview

This is a **group research project** developed as part of **IDP2502: Advancing Hyperspectral Image Analysis for Sustainable Development** at GD Goenka University. The project develops a **GIS-based predictive model** to identify water logging-prone zones in Mussoorie, a Himalayan city facing increasing flood risks due to extreme weather and rapid urbanization.

Using **hyperspectral remote sensing**, terrain analysis, and hydrological modeling, we designed an actionable flood risk assessment framework that achieved **85% validation accuracy** and an **AUC score of 0.82**, directly supporting UN Sustainable Development Goals (SDG 6, 11, 13).

---

## 👥 Team Members

| Name            | ID           | Department  | Role / Contribution                 |
|-----------------|-------------|------------|-------------------------------------|
| V. Prem Sai     | 240160226358 | SOES SEC C | Hydrology & Literature Review       |
| Piyush Jha      | 240160226203 | SOES SEC C | GIS Mapping & Terrain Analysis      |
| Chirag Sharma   | 240160226251 | SOES SEC C | Data Compilation & Documentation    |
| Khushbu         | 240160227014 | SOES SEC C | SDG Mapping & Conceptual Framework  |
| Sanya           | 240160226275 | SOES SEC C | Report Structuring & Editing        |
| Drishti Guptha  | 240160226202 | SOES SEC C | Results Interpretation & Validation |
| Mahitha         | 240160226172 | SOES B1    | Case Study & Field Context          |
| Sasi Kumar      | 240160226144 | SOES B2    | Figures, Tables & Presentation      |

> Note: Roles are indicative of contributions; this was a **collaborative group effort** and not a single-lead project.

**Mentor**: Dr. Manu Banga, School of Earth and Environmental Sciences

---

## 🎯 Research Objectives

1. **Analyze Mussoorie's Hydrology**  
   Compile rainfall records and map existing drainage channels, streams, and reservoirs.

2. **Characterize Terrain & Land Use**  
   Use high-resolution Digital Elevation Models (DEMs) to classify slopes, plateaus, and impervious surfaces within the urban boundary.

3. **Develop Flood Risk Indicators**  
   Derive indicators such as the Topographic Wetness Index (TWI), flow accumulation, and slope classes to identify potential water accumulation zones.

4. **Build a Predictive Water Logging Framework**  
   Integrate rainfall intensity–duration–frequency (IDF) characteristics with terrain parameters in a GIS environment to simulate runoff and highlight likely waterlogged zones.

5. **Validate Findings**  
   Compare predicted high-risk zones with historically flood-affected locations (e.g., 2025 cloudburst, 2010 flash floods) to assess reliability.

6. **Propose Mitigation Strategies**  
   Recommend location-specific interventions such as rain gardens, retention basins, and improved drainage infrastructure to reduce flooding.

---

## 🔬 Research Methodology

### Data Collection

- **Digital Elevation Model (DEM)**  
  10-meter resolution DEM of Mussoorie from Survey of India for slope and flow network analysis.

- **Satellite Imagery**  
  Medium- to high-resolution imagery (e.g., Landsat, Sentinel) for land-use/land-cover classification and identification of built-up vs. green areas.

- **Rainfall Data**  
  Approximately 20 years of daily rainfall data from IMD stations covering Dehradun–Mussoorie region.

- **Infrastructure & Administrative Data**  
  Drainage maps, road networks, and ward boundaries from municipal and development authority records.

### Terrain & Hydrologic Analysis

- **Topographic Wetness Index (TWI)**  
  Used to estimate potential saturation zones and soil moisture accumulation.

- **Flow Accumulation & Flow Direction**  
  Derived from DEM to locate natural runoff convergence and potential bottlenecks.

- **Slope and Aspect**  
  Classified to understand where water is likely to move quickly vs. where it may pond.

- **Land-Use / Land-Cover (LULC)**  
  Mapped to distinguish impervious urban surfaces from vegetated and natural areas that influence infiltration.

- **Rainfall–Runoff Modeling (Conceptual)**  
  Used standard hydrological approaches (e.g., SCS-CN and urban drainage concepts) to conceptualize how different rainfall events translate into surface runoff and water logging.

### Tools & Platforms

- **GIS Platforms**: QGIS, GRASS GIS  
- **Remote Sensing Tools**: Standard EO processing tools for spectral indices and classification  
- **Cartographic Tools**: Map composition and visualization tools within GIS environments

*(No programming scripts or code modules are part of this repository; the focus is on methodology, analysis, and documentation.)*

---

## 📊 Key Findings & Results

### Model Performance (Conceptual Evaluation)

| Metric               | Value | Interpretation              |
|----------------------|-------|-----------------------------|
| Validation Accuracy  | 85%   | Model aligns well with known flood-prone locations |
| ROC–AUC Score        | 0.82  | Good ability to distinguish high-risk vs. low-risk areas |

### High-Risk Zones Identified

- **Chamba Point Region**  
  Gentle slopes with converging drainage paths; consistently indicated as high water depth zones.

- **Kempty Falls & Surroundings**  
  Narrow valleys and tourism-driven construction create drainage bottlenecks; matches recent flood debris accumulation.

- **Library Chowk Area**  
  Flatter central zone where runoff from uphill roads overwhelms available drainage capacity during intense rainfall.

- **Hathipaon Road**  
  Area where field observations and reported impacts from 2025 events match the modeled high-risk patterns.

- **Ward 7 (Kyarkiyan Region)**  
  Emerges as one of the highest-risk wards, making it a priority candidate for drainage upgrades and targeted interventions.

### Key Insights

- **Topography Controls Flood Paths**  
  Flat convergence zones and valley bottoms act as traps for water, while steeper vegetated slopes help in faster runoff and less pooling.

- **Anthropogenic Cover Intensifies Flooding**  
  Dense construction and high impervious surface ratios (e.g., hotel zones, commercial streets) markedly increase surface runoff and reduce infiltration.

- **Infrastructure Gaps Are Critical**  
  Undersized culverts and blocked drains act as pinch points, significantly increasing local waterlogging risk during peak rainfall.

- **Nature-Based Solutions Are Effective**  
  Locations with existing rainwater harvesting and green infrastructure show reduced simulated waterlogging, supporting blue–green infrastructure approaches.

---

## 🌍 Contribution to Sustainable Development Goals (SDGs)

### SDG 6 – Clean Water and Sanitation

- Supports **monitoring and management** of water-related hazards that affect water quality and availability.  
- Contributes to **target 6.3**, which focuses on improving water quality and reducing pollution by identifying stagnant and polluted water zones.

### SDG 11 – Sustainable Cities and Communities

- Directly supports **target 11.5** by helping reduce the impact of water-related disasters in urban areas through spatial risk mapping.  
- Informs **target 11.3** via evidence-based inputs for sustainable urban planning, zoning, and infrastructure placement.  
- Helps address **target 11.6** by highlighting areas prone to stagnant water, which can lead to environmental degradation and health risks.

### SDG 13 – Climate Action

- Enhances **resilience to climate-related hazards** such as extreme rainfall and cloudburst events through predictive analysis.  
- Supports **climate-informed policy making** by providing spatial evidence for adaptation strategies in hill towns like Mussoorie.

---

## 📈 Recommendations

1. **Drainage & Infrastructure Upgrades**  
   - Prioritize high-risk wards (e.g., Ward 7, Library Chowk belt) for culvert enlargement and drain rehabilitation.  
   - Regular desilting and maintenance of existing drainage channels, especially before monsoon onset.

2. **Blue–Green Infrastructure**  
   - Introduce rain gardens, bioswales, and permeable pavements in central urban areas.  
   - Protect and enhance upstream forested slopes to serve as natural runoff buffers.

3. **Urban Planning & Land-Use Regulation**  
   - Restrict high-density construction in mapped flood corridors and high-risk pockets.  
   - Incorporate flood risk maps into the Master Plan to preserve recharge zones and natural drainage paths.

4. **Monitoring & Early Warning**  
   - Periodically update risk maps with newer rainfall and land-use data.  
   - Integrate flood risk mapping into local disaster management and early warning systems.

---

## ⚠️ Limitations

- **High Dimensionality of Hyperspectral Data**  
  Many bands and complex spectral signatures can make analysis challenging without advanced dimensionality reduction.

- **Data Redundancy and Noise**  
  Overlapping spectral information and environmental noise (e.g., atmosphere, seasonal variation) complicate feature extraction.

- **Limited Ground Truth**  
  Field-verified waterlogging records are not uniformly available across all wards, which constrains validation.

- **Spatial and Temporal Resolution**  
  Trade-offs between spatial detail and temporal coverage limit continuous fine-scale monitoring.

- **Complex Soil–Water–Vegetation Interactions**  
  Real-world processes are complex, and spectral responses are not always uniquely interpretable.

---

## 🛠️ Tools & Techniques (Non-Programming)

| Category                | Tools / Techniques                        |
|-------------------------|-------------------------------------------|
| GIS & Mapping           | QGIS, GRASS GIS                           |
| Terrain Analysis        | DEM-based slope, aspect, flow analysis    |
| Remote Sensing Concepts | Hyperspectral indices (e.g., moisture)    |
| Hydrological Concepts   | Runoff, waterlogging, drainage capacity   |
| Cartography             | Thematic mapping and spatial visualization|

---

IDP2502-WaterLogging-Mussoorie/
├── README.md # Project overview and documentation
├── IDP-REPORT.pdf # Full report as submitted for IDP2502
├── images/
│ ├── flood-risk-map.png
│ ├── mussoorie-dem-slope.png
│ ├── ndwi-moisture-zones.png
│ └── lulc-map.png
└── docs/

---

## 📚 References

The project draws on peer-reviewed literature, government reports, and news articles related to:

- Urban flooding and blue–green infrastructure  
- Landslide and slope stability in the Mussoorie region  
- Carrying capacity and environmental impact of tourism in Mussoorie  
- Extreme rainfall events and monsoon variability in Uttarakhand  

(Full reference list is available in **IDP-REPORT.pdf**.)

---

## 📝 Note

This repository documents our **IDP2502 group project report and presentation**.  
The **final detailed research paper** or any extended analysis, if prepared later, will be added or linked separately.

---

## 📧 Contact & Collaboration

For academic or collaboration queries:

- **Mentor**: Dr. Manu Banga, GD Goenka University  
- For questions about this repository, please open an issue or contact any team member via LinkedIn or institutional email.

---

## 📄 License

You may optionally include a simple open license (e.g., **MIT License** or **CC BY 4.0**) if you want others to reuse figures or concepts with attribution.  
If you add a license file, mention it here clearly.

---

