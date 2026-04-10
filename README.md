# kastamonu-landslide-gee
Google Earth Engine scripts for Sentinel-1 based landslide detection and comparison with official inventories in Kastamonu Türkiye (2015–2025).
# Landslide Detection in Kastamonu Using Google Earth Engine

This repository contains the Google Earth Engine (GEE) scripts used in the study entitled:

**Sentinel 1 based landslide detection using Google Earth Engine and comparison with official inventories in Kastamonu Türkiye**

## Study Area
The study focuses on Kastamonu Province in the northern Black Sea region of Türkiye, an area characterized by steep topography and intense precipitation that frequently trigger landslides.

## Data
- Sentinel-1 SAR data
- VV polarization
- Time period: 2015 to 2025
- Accessed and processed in Google Earth Engine

## Method
The workflow is based on annual Sentinel-1 SAR backscatter composites and interannual backscatter difference analysis. Areas showing a backscatter decrease greater than 2 dB were identified as potential landslide-prone zones.

## Outputs
- Annual backscatter composites
- Interannual backscatter difference maps
- Potential landslide detection layers

## Reproducibility
The workflow is implemented in Google Earth Engine and is reproducible using the script provided in this repository.

## Contact
For questions regarding the workflow or materials, please contact the corresponding author.
