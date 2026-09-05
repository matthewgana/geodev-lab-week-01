# Healthcare Accessibility and Health Intelligence in Bida Local Government Area, Niger State

**GeoDev Lab Africa — Week 01 Project**

**Author:** Matthew Santali Gana

**Study Area:** Bida Local Government Area, Niger State, Nigeria

**Project Status:** Week 01 — Project Definition and Data Planning

---

## 1. Project Overview

This project is part of my GeoDev Lab Africa training and focuses on applying geospatial analysis to a practical healthcare-accessibility problem in Bida Local Government Area, Niger State.

The project investigates the spatial relationship between administrative wards and existing healthcare facilities to identify areas where residents may have limited geographic access to healthcare services.

The first stage establishes the spatial question, study area, required datasets, data sources, and analytical direction. Subsequent stages will involve data acquisition, preparation, spatial analysis, and visualisation.

---

## 2. Spatial Question

> **Which wards in Bida Local Government Area are more than 2 kilometres from existing healthcare facilities?**

The analysis will use a 2-kilometre distance threshold to identify wards that may be geographically underserved based on the location of existing healthcare facilities.

Where suitable supporting datasets are available, settlement and population information will also be used to provide additional context on the communities and populations potentially affected by limited healthcare accessibility.

---

## 3. Study Area

The study area is **Bida Local Government Area in Niger State, Nigeria**.

The analysis will focus on the spatial relationship between administrative wards, healthcare facilities, settlements, population distribution, and the surrounding road network.

---

## 4. What I Am Investigating

The project will examine four main spatial dimensions:

### Ward Distribution

Where are the wards within Bida Local Government Area, and how are they spatially distributed?

### Healthcare Facility Distribution

Where are existing healthcare facilities located, and how are they distributed across the wards?

### Healthcare Accessibility

Which wards are located more than 2 kilometres from healthcare facilities?

### Population and Settlement Context

Where are settlements and population concentrations located in relation to healthcare accessibility gaps?

These factors will subsequently be examined together to provide a clearer picture of healthcare accessibility within Bida LGA.

---

## 5. Datasets and Data Sources

The project will use publicly available geospatial and demographic datasets. Each dataset will be assessed for geographic coverage, completeness, accuracy, date, and suitability before being incorporated into the analysis.

### 5.1 LGA and Ward Boundaries

**Purpose**

Administrative boundaries will provide the geographic framework for the analysis and allow the study to identify and compare wards within Bida Local Government Area.

**Primary Source**

GRID3 Nigeria Geospatial Data.

**Dataset**

GRID3 Nigeria operational administrative and ward boundary datasets.

**Source**

https://grid3.org/geospatial-data-nigeria

---

### 5.2 Healthcare Facilities

**Purpose**

Healthcare facility locations will provide the primary dataset for determining which wards fall beyond the 2-kilometre accessibility threshold.

**Primary Source**

GRID3 Nigeria Health Facilities.

**Additional Validation Source**

Niger State Primary Health Care Development Agency (NSPHCDA), where suitable facility records are available.

**Format**

Point vector/GIS feature layer.

**Sources**

https://grid3.org/geospatial-data-nigeria

https://nigerstatephcda.org/

---

### 5.3 Settlement Extents

**Purpose**

Settlement data will be used to identify populated places within Bida LGA and examine their relationship with healthcare facilities and accessibility gaps.

**Source**

GRID3 Nigeria.

**Dataset**

GRID3 Nigeria Settlement Extents.

**Format**

Polygon vector layer.

**Source**

https://grid3.org/geospatial-data-nigeria

---

### 5.4 Population Data

**Purpose**

Population data will provide additional context for understanding the number and distribution of people potentially affected by healthcare accessibility gaps.

**Primary Sources**

GRID3 Nigeria and WorldPop.

**Format**

GeoTIFF raster.

**Sources**

https://grid3.org/geospatial-data-nigeria

https://hub.worldpop.org/

The specific population dataset and reference year will be documented when the data is acquired.

---

### 5.5 Road Network

**Purpose**

Road-network data will provide supporting information for understanding practical connectivity between settlements and healthcare facilities.

The initial analysis will use straight-line distance to establish the 2-kilometre threshold. Road-network accessibility may subsequently be examined as an additional analysis where the available road data is sufficiently complete.

**Source**

OpenStreetMap.

**Format**

Vector road network.

**Source**

https://www.openstreetmap.org/

---

## 6. Planned Analytical Approach

The analysis will be carried out progressively.

### Stage 1 — Data Preparation

The datasets will be inspected and prepared for analysis.

This will include checking:

* Geographic coverage
* Coordinate reference systems
* Attribute information
* Missing values
* Duplicate features
* Data consistency
* Spatial accuracy
* Dataset dates and versions

### Stage 2 — Ward Analysis

The Bida LGA boundary and ward boundaries will be mapped to establish the administrative structure of the study area.

### Stage 3 — Healthcare Facility Analysis

Healthcare facilities will be mapped and reviewed to identify their spatial distribution across Bida LGA.

### Stage 4 — 2-Kilometre Accessibility Analysis

A 2-kilometre distance zone will be generated around the healthcare facilities.

The analysis will then identify wards that fall outside the defined healthcare-accessibility threshold.

### Stage 5 — Settlement and Population Analysis

Settlement and population datasets will be overlaid with the identified accessibility gaps to determine where potentially underserved communities and populations are concentrated.

### Stage 6 — Supporting Road Analysis

Where appropriate, the road network will be examined to provide additional context on accessibility beyond simple straight-line distance.

### Stage 7 — Integrated Spatial Analysis

The datasets will be combined to produce a final spatial representation of healthcare accessibility and potential service gaps across Bida LGA.

---

## 7. Expected Outputs

The project is expected to produce:

* A map of Bida Local Government Area and its wards.
* A healthcare facility distribution map.
* A 2-kilometre healthcare accessibility map.
* Identification of wards located more than 2 kilometres from healthcare facilities.
* Settlement distribution within and around accessibility gaps.
* Population distribution in relation to healthcare accessibility.
* Supporting road-network analysis.
* A final healthcare accessibility and health-intelligence map.

---

## 8. Interpretation and Limitations

The 2-kilometre threshold will be used as a defined **geographic accessibility indicator**, not as a complete measure of healthcare access.

Actual healthcare accessibility may also depend on road conditions, travel time, transportation availability, facility capacity, healthcare service type, opening hours, population characteristics, and other factors.

The quality of the analysis will therefore depend on the completeness, positional accuracy, resolution, date, and classification of the datasets used.

Particular attention will be given to validating healthcare facility locations and documenting the limitations of the available data.

---

## 9. Project Scope

The geographic scope of this project is limited to **Bida Local Government Area, Niger State, Nigeria**.

The core spatial relationship being investigated is:

**Wards → Healthcare Facilities → 2 km Accessibility Threshold → Underserved Areas**

Settlement, population, and road-network data will provide supporting spatial context where appropriate.

The project is intended to demonstrate a practical geospatial workflow for identifying healthcare accessibility gaps and generating evidence that can support health planning and decision-making.

---

## 10. Project Status

**Current Stage: Week 01 — Project Definition and Data Planning**

At this stage, the following have been established:

* Spatial research question
* Study area
* Required datasets
* Data sources
* Analytical direction
* Expected outputs
* Initial project limitations

The next stages will involve acquiring, preparing, validating, and analysing the selected datasets.

---

## 11. Repository Structure

```text
geodev-lab-africa-bida-healthcare/

│
├── README.md
├── project_brief.md
└── .gitignore
```

The repository structure will evolve as additional stages of the project are completed.

---

## 12. Project Documentation

The detailed project definition, spatial question, dataset requirements, sources, scope, and planned methodology are available in:

**[Project Brief](project_brief.md)**

---

## 13. Author

**Matthew Santali Gana**

GeoDev Lab Africa Training

Nigeria
