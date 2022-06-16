## Jupyter notebook: GRASS GIS 8 and processing multitemporal EO data

by Markus Neteler, https://www.mundialis.de/

presented at:

*Open Data Science Europe workshop 2022, 2022-06-14, 11:00-12:30, Workshop room 2 - C223*

https://opendatascience.eu/workshop-2022/

**Abstract**

GRASS GIS supports time-series processing for vector, raster, and volume data. This workshop offers a micro-introduction to Sentinel satellite data archives, and the various ways to access them. It also explores the i.sentinel toolset which allows querying Sentinel data coverage for a region of interest, downloading from multiple data sources, performing atmospheric and topographic corrections, and cloud/shadow masking. This workshop also gives a preparation of data for multitemporal analyses through automatic creation of a space-time raster dataset (strds), It explores the computation of NDVI time series. Eventually we run a simple RandomForest landuse classification on Sentinel-2 data.

This course is based on [workshop material](https://geo.fsv.cvut.cz/geoharmonizer/odse_workshop_2022/grass/html/units/06.html) by Martin Landa, CVUT.

We will run GRASS GIS 8.2 on Google Colab through a Jupyter Notebook.

**Jupyter Notebooks**

Google Colab (https://colab.research.google.com/) notebook version:
- https://github.com/neteler/jupyter_sentinel2_grass_gis/blob/main/sentinel2_grass_gis_colab.ipynb

Standard Jupyter Notebook for local usage or in Jupyterhub:
- https://github.com/neteler/jupyter_sentinel2_grass_gis/blob/main/sentinel2_grass_gis.ipynb
