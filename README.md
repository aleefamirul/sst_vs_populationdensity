# Coastal Population Density vs Sea Surface Temperature

## 1. Project Overview

This project investigates the spatial relationship between coastal population density and sea surface temperature (SST).

The purpose of the project is to explore whether areas with different coastal population densities exhibit observable differences in nearby sea surface temperature.

This project is part of a portfolio of oceanographic and environmental data analysis projects.

---

## 2. Research Question

> Is there an observable spatial relationship between coastal population density and sea surface temperature along selected coastal areas?

The analysis focuses on identifying spatial patterns and statistical relationships rather than assuming that sea temperature directly causes population distribution.

---

## 3. Objectives

1. Obtain population data for selected coastal areas.
2. Obtain sea surface temperature data from an oceanographic dataset.
3. Process and standardize the population and SST datasets.
4. Match population density with nearby SST values.
5. Explore the relationship between population density and SST statistically.
6. Produce maps and plots to visualize the results.
7. Discuss the limitations and possible explanations for the observed patterns.

---

## 4. Data Sources

### Population Data

**Source:** data.gov.my

Population data will be used to estimate population density for selected coastal administrative areas.

### Sea Surface Temperature

**Source:** Copernicus Marine Service (CMEMS)

Sea surface temperature data will be extracted for locations corresponding to or near the selected coastal areas.

---

## 5. Methodology

The general workflow is:

```text
Data Acquisition
       ↓
Data Cleaning
       ↓
Spatial Processing
       ↓
SST Extraction
       ↓
Population-SST Matching
       ↓
Statistical Analysis
       ↓
Visualization
       ↓
Interpretation
```

### 5.1 Data Acquisition

Population and SST datasets are obtained from their respective sources.

### 5.2 Data Cleaning

The datasets are checked for:

* Missing values
* Incorrect coordinates
* Duplicate records
* Inconsistent units
* Invalid geographic locations

### 5.3 Spatial Processing

Coastal administrative areas and SST grid cells are processed using geographic coordinates.

### 5.4 SST Extraction

SST values are extracted from the CMEMS dataset for locations representing the selected coastal areas.

### 5.5 Population-SST Matching

Population density is matched with the corresponding coastal SST measurements.

### 5.6 Statistical Analysis

The relationship between population density and SST will be explored using descriptive statistics and correlation analysis.

Where appropriate, scatter plots and regression analysis may also be used.

### 5.7 Visualization

The results will be presented using:

* Geographic maps
* Scatter plots
* SST distributions
* Population-density maps
* Statistical plots

---

## 6. Results

*To be completed after the analysis.*

Potential results may include:

* Spatial distribution of population density
* Spatial distribution of coastal SST
* Population density versus SST relationship
* Correlation statistics
* Maps showing coastal population and SST patterns

---

## 7. Discussion

*To be completed after the results are obtained.*

The discussion will consider:

* Whether an observable relationship exists
* Geographic patterns in the data
* Possible environmental and socioeconomic explanations
* The influence of factors other than SST
* Limitations of using population density as a proxy for coastal settlement patterns

---

## 8. Limitations

Potential limitations include:

* Population data may be reported by administrative boundaries rather than exact coastal locations.
* SST represents ocean surface conditions and does not directly describe conditions experienced on land.
* Population distribution is influenced by many factors besides climate and ocean temperature.
* Spatial resolution differences between population and oceanographic datasets may introduce uncertainty.
* Correlation does not establish causation.

---

## 9. Tools & Technologies

* Python
* JupyterLab
* NumPy
* Pandas
* Xarray
* GeoPandas
* Cartopy
* Matplotlib
* SciPy
* Git
* GitHub
* Conda

---

## 10. Project Structure

```text
sst_vs_population/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── figures/
│
├── notebooks/
│   └── 01_exploration.ipynb
│
├── results/
│   └── sst_vs_population_notes.docx
│
├── scripts/
│
├── .gitignore
├── environment.yml
└── README.md
```

---

## 11. Status

**Project status:** In development

The project is currently in the data preparation and exploratory analysis stage.

---

## 12. Future Improvements

Possible extensions include:

* Adding coastal elevation
* Including rainfall and climate variables
* Comparing multiple years of SST
* Examining seasonal SST differences
* Expanding the analysis to additional coastal regions
* Testing additional socioeconomic variables
* Developing an interactive map

---

## Author

**Aleef Amirul**

MSc Physical Oceanography

GitHub: [aleefamirul](https://github.com/aleefamirul)
