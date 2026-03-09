# Soil Organic Carbon Estimation – Machine Learning Experiment

This repository contains a machine learning experiment exploring Soil Organic Carbon (SOC) estimation using Earth Observation data. The work focuses on processing geospatial datasets, analyzing Above Ground Biomass (AGB) patterns, and investigating relationships between biomass regimes and soil carbon measurements.

The experiment was conducted as a small research task within a broader project studying soil carbon monitoring using machine learning and environmental datasets.

---

## Project Background

Soil carbon sequestration is an important natural mechanism for capturing atmospheric CO₂ and mitigating climate change. Soil Organic Carbon (SOC) serves as a key measurable indicator for assessing carbon stored in soil ecosystems.

However, direct measurement of SOC is expensive, labor-intensive, and spatially limited. Machine learning combined with satellite-based Earth Observation data can provide scalable approaches to estimate SOC across large geographic regions.

This experiment explores how biomass patterns derived from satellite data relate to soil carbon measurements.

---

## Objectives

The goal of this experiment is to explore relationships between biomass regimes and soil carbon levels using machine learning techniques.

Key objectives include:

- Load and process Soil Organic Carbon raster datasets
- Obtain Above Ground Biomass (AGB) data from Earth Observation sources
- Align geospatial datasets spatially to ensure matching resolution and extent
- Apply clustering algorithms to identify biomass regimes
- Analyze correlations between biomass clusters and SOC measurements
- Visualize temporal biomass trends for different clusters

---

## Methods and Approach

The analysis follows a typical geospatial machine learning workflow:

1. Load SOC raster data
2. Load AGB satellite datasets
3. Preprocess and spatially align datasets
4. Apply clustering algorithms to identify biomass regimes
5. Overlay SOC measurements to evaluate relationships
6. Analyze biomass trends over time
7. Visualize results

The experiment focuses on exploratory data analysis and machine learning experimentation rather than building a full production model.

---

## Technologies Used

The following tools and libraries were used in the project:

- Python
- NumPy
- Pandas
- Scikit-learn
- xarray
- rasterio
- Matplotlib
- Jupyter Notebook

These libraries were used for geospatial data processing, machine learning experimentation, and visualization.

---

## Repository Structure

soil-carbon-ml-experiment
│
├── README.md
├── soc_analysis.ipynb
└── docs
    └── AkPa_Carbon_Estimation.pdf


### Files

**soc_analysis.ipynb**

Jupyter Notebook containing the full workflow including:

- data preprocessing
- geospatial alignment
- clustering analysis
- visualization

**docs/project_description.pdf**

Document describing the original research task and dataset context.

---

## Dataset Information

This project uses environmental datasets including:

- Soil Organic Carbon raster data curated using **ISRIC – World Soil Information**
- Above Ground Biomass (AGB) data from the **ESA Climate Change Initiative**

Because of dataset size and licensing considerations, the datasets are not included in this repository.

Datasets can be accessed from:

ISRIC – World Soil Information  
https://www.isric.org

ESA Climate Change Initiative  
https://climate.esa.int

---

## Key Concepts Explored

This experiment explores several concepts relevant to machine learning and environmental data science:

- geospatial data processing
- raster data handling
- Earth Observation datasets
- clustering algorithms
- environmental data analysis
- machine learning for climate applications

---

## Possible Extensions

Future improvements could include:

- supervised learning models for SOC prediction
- integration of weather and land-use datasets
- spatial feature engineering
- deep learning approaches for geospatial data
- multimodal environmental data analysis

---

## Author

Sneha Zure  
M.Sc. Computer Science  
Rheinland-Pfälzische Technische Universität Kaiserslautern (RPTU)  
Kaiserslautern, Germany

---

## License

This repository is shared for educational and research demonstration purposes.
