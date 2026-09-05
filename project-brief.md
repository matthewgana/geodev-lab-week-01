# Healthcare Accessibility and Health Intelligence in Bida Local Government Area, Niger State

## 1. Spatial Question

Which wards in Bida Local Government Area are more than 2 kilometres from existing healthcare facilities?

## 2. Study Area

Bida Local Government Area, Niger State, Nigeria.

## 3. Data Required

### Ward Boundaries

* **What:** Operational ward boundaries within Bida LGA.
* **Source:** GRID3 Nigeria Geospatial Data.
* **Dataset:** GRID3 NGA – Operational Wards v3.0.
* **Format:** Shapefile/GeoPackage or GIS feature layer.
* **Source link:** https://grid3.org/geospatial-data-nigeria

### LGA Boundary

* **What:** Bida Local Government Area boundary for clipping and spatial analysis.
* **Source:** GRID3 Nigeria.
* **Dataset:** GRID3 NGA – Operational LGA Boundaries.
* **Format:** Shapefile/GeoPackage or GIS feature layer.
* **Source link:** https://grid3.org/geospatial-data-nigeria

### Healthcare Facilities

* **What:** Georeferenced healthcare facilities within and around Bida LGA, including facility locations and available attributes.
* **Source:** GRID3 Nigeria.
* **Dataset:** GRID3 NGA – Health Facilities v3.0.
* **Validation source:** Niger State Primary Health Care Development Agency (NSPHCDA).
* **Format:** Point vector/GIS feature layer.
* **Source links:**
  https://grid3.org/geospatial-data-nigeria
  https://nigerstatephcda.org/

### Settlement Extents

* **What:** Spatial extent and distribution of settlements within Bida LGA.
* **Source:** GRID3 Nigeria.
* **Dataset:** GRID3 NGA – Settlement Extents v4.1.
* **Format:** Polygon vector layer.
* **Source link:** https://grid3.org/geospatial-data-nigeria

### Population

* **What:** Gridded population estimates for assessing the population potentially affected by poor healthcare accessibility.
* **Source:** GRID3 Nigeria / WorldPop.
* **Dataset:** GRID3 NGA Population Estimates or WorldPop Nigeria Population Counts.
* **Format:** GeoTIFF raster.
* **Source links:**
  https://grid3.org/geospatial-data-nigeria
  https://hub.worldpop.org/geodata/summary?id=74733

### Road Network

* **What:** Roads within and around Bida LGA for supplementary network-based accessibility analysis.
* **Source:** OpenStreetMap and GRID3 Nigeria.
* **Format:** Vector road network.
* **Source links:**
  https://www.openstreetmap.org/
  https://grid3.org/geospatial-data-nigeria

## 4. Data Acquisition and Validation

The datasets will be clipped to Bida Local Government Area and checked for:

* Correct ward and LGA attribution.
* Coordinate reference system and spatial accuracy.
* Duplicate or missing healthcare facilities.
* Facility location and classification.
* Consistency between GRID3 and available Niger State health-facility records.
* Completeness of settlement and road data.
* Dataset version, date, and licensing.

The GRID3 health-facility dataset will be compared with available NSPHCDA records where possible to improve confidence in the facility locations used for the analysis.

## 5. Planned Analysis and Output

The analysis will:

1. Map all wards within Bida LGA.
2. Map existing healthcare facilities.
3. Create a 2-kilometre accessibility zone around healthcare facilities.
4. Identify wards that fall outside the 2-kilometre healthcare-accessibility threshold.
5. Overlay settlements and population data to determine where underserved populations are concentrated.
6. Use the road network as an additional layer for evaluating practical accessibility where appropriate.

### Expected Output

A healthcare accessibility map identifying:

* Healthcare facility locations.
* 2-kilometre healthcare accessibility zones.
* Wards within the accessibility threshold.
* Wards located more than 2 kilometres from healthcare facilities.
* Settlements and population potentially affected by limited healthcare access.

The analysis will provide a geospatial basis for identifying healthcare access gaps and supporting evidence-based health planning in Bida Local Government Area.
