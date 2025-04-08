---
permalink: /r-spatial/
title: "The R Spatial Notebook Series"
excerpt: "Introduction and Chapter Outline for the R Spatial Notebook Series"
author_profile: true
redirect_from: 
  - "/r-spatial.html"
---

## A Guide to Producing Reproducible Social Science Workflows in R

Welcome to the R Spatial Notebook, a collection of interactive code notebooks designed to support researchers, analysts, and data enthusiasts create reproducible spatial workflows in R.  These notebooks introduce users to automated data extraction for multiple key social and environmental data sources (including IPUMS, Natural Earth, OSM, and many others), data cleaning and integration for both tabular and spatial data, foundational and advanced spatial tools and workflows, and mapping tips and techniques - all using R.

The notebook series is designed to be used like a book with earlier chapters providing foundational concepts and workflows necessary to complete later chapters.  However, each notebook is also a standalone resource and designed to be downloaded and modified to support the user's specific research and education needs.

Whether you're new to spatial data science looking for a place to get started or an experience R coder looking to expand your existing workflows, these notebooks are designed to support your journey in understanding and applying spatial methodologies with R.

### Receive Project Updates
The R Spatial Notebooks Series is an ongoing project with new notebooks currently in development.  Sign up for the [R Spatial Mailing List](https://mailchi.mp/ab01e8fc8397/r-spatial-email-signup) to receive project updates, new notebook announcements, and opportunities to connect.

### Make a Suggestion
Do you have a specific topic or notebook idea you would like to see included in the R Spatial Notebooks?  Drop a message in the [suggestion box!](https://us19.list-manage.com/survey?u=746bf8d366d6fbc99c699e714&id=54590a28ea&attribution=false).

### View Past Webinars
* **April 9, 2025** [Automating IPUMS USA Data Extraction and Management Workflows in R](https://i-guide.io/i-guide-vco/introduction-to-the-r-spatial-notebooks-automating-ipums-usa-data-extraction-and-management-workflows-in-r)
* **January 15, 2025** [Introducing R Spatial Notebook Series: Supporting Reproducible Geospatial Analysis for the Social Sciences in R](https://i-guide.io/i-guide-vco/introducing-r-spatial-notebook-series-supporting-reproducible-geospatial-analysis-for-the-social-sciences-in-r)

[Check out my article **Unlocking Spatial and Social Data with R: Introducing the R Spatial Notebook Series** published on the IPUMS Blog.](https://blog.popdata.org/introducing-the-r-spatial-notebook-series)

---

# R Spatial Notebooks Chapter List

*Chapter 1: Data Sources and APIs*
------
* **1.1** [Introduction to IPUMS and the IPUMS API](https://platform.i-guide.io/notebooks/82d3b176-e4e6-4307-8186-318a3fe6c81a)
* **1.2** [Introduciton to Natural Earth](https://platform.i-guide.io/notebooks/924c7ca6-3d12-4a80-ab4d-814cc80f7f79)
* **1.3** Introduction to OpenStreetMap (OSM) - *coming soon: release 2*
* **1.4** Introduction to Stadia Maps and Stamen Maps - *coming soon: release 3*
* **1.5** Introduction to Google Maps - *coming soon: release 3*
* **1.6** Introduction to the National Land Cover Database (NLCD) - *coming soon: release 4*

*Chapter 2: Fundamentals of Spatial Data*
------
* **2.1** [Introduction to sf: Reading, Writing, and Inspecting Vector Data](https://platform.i-guide.io/notebooks/9968babe-22e4-4c3d-98e2-d8b45e9672cd)
* **2.2** [Working with CRS: Reprojection and Transformation](https://platform.i-guide.io/notebooks/76912ca7-73e4-437e-8ecf-0cb456bd7282)
* **2.3** [Preparing Vector Data for Analysis](https://platform.i-guide.io/notebooks/44926d85-7f08-4774-a103-a22ff3876cad)
* **2.4** Introduction to terra: Reading, Writing, and Inspecting Raster Data - *coming soon: release 4*

*Chapter 3: IPUMS Data Acquisition and Extraction*
------
* **3.1** [IPUMS USA Data Extraction Using ipumsr](https://platform.i-guide.io/notebooks/ab5cad39-6d00-43d2-bc51-17fd4e6b98f2)
* **3.2** [IPUMS NHGIS Data Extraction Using ipumsr](https://platform.i-guide.io/notebooks/be08e56e-1c08-458e-a230-263c64d386bc)
  * **3.2.1** [IPUMS NHGIS Data Extraction Using ipumsr: Supplemental Exercise 1](https://platform.i-guide.io/notebooks/a74fff96-4db5-430f-b346-958b0c5f7b38)
  * **3.2.2** [IPUMS NHGIS Data Extraction Using ipumsr: Supplemental Exercise 2](https://platform.i-guide.io/notebooks/bc79eda6-8353-42ea-8cb7-5db70aa6febf)
  * **3.2.3** [IPUMS NHGIS Data Extraction Using ipumsr: Supplemental Exercise 3](https://platform.i-guide.io/notebooks/55dd96e5-fdf6-408f-a050-7fcd006d0575)
* **3.3** IPUMS CPS Data Extraction Using ipumsr - *coming soon*

*Chapter 4: Open-Source GIS Data Acquisition and Extraction*
------
* **4.1** [Importing Data from Natural Earth with rnaturalearth and rnaturalearthdata](https://platform.i-guide.io/notebooks/934e764c-d727-4bab-bc1c-198233484adc)
* **4.2** Importing Data from OpenStreetMap (OSM) with osmdata - *coming soon: release 2*

*Chapter 5: Data Cleaning, Preparation, and Exploratory Data Analysis (EDA)*
------
* **5.1** [Data Cleaning and Preparation with IPUMS USA](https://platform.i-guide.io/notebooks/b4b29b13-d832-495d-8db7-1545a30549f1)
* **5.2** [Exploratory Data Analysis (EDA) with IPUMS USA](https://platform.i-guide.io/notebooks/29c5c2da-4bfe-4150-9c05-b65956c997b4)
* **5.3** [Spatial Data Exploration and Preprocessing with IPUMS NHGIS](https://platform.i-guide.io/notebooks/2927de7d-45a4-46d7-8f76-a569af637d82)

*Chapter 6: Mapping and Visualization*
------
* **6.1** [Visualization and Quick Plots](https://platform.i-guide.io/notebooks/dfe8fd72-f896-4dd2-9d61-6d9982394f1f)
* **6.2** [Mapping Point and Polygon Data](https://platform.i-guide.io/notebooks/2b9f579c-32b0-4078-af39-994bb31d50ec)
* **6.3** [Choropleth Mapping](https://platform.i-guide.io/notebooks/f2f973df-2412-49f0-ad39-d80051f20d4d)
* **6.4** Importing Basemaps from OpenStreetMap (OSM) with rosm - *coming soon: release 2*
* **6.5** Importing Basemaps from OpenStreetMap (OSM) with ggspatial - *coming soon: release 2*
* **6.6** Importing Basemaps from OpenStreetMap (OSM), Stadia Maps, Stamen Maps, and Google Maps with ggmap - *coming soon: release 3*
* **6.7** Importing Local Basemap Files with terra - *coming soon: release 4*
* **6.8** Interactive Mapping with Leaftlet - *coming soon: release 3*
* **6.9** Interactive Mapping with Shiny - *coming soon: release 3*

*Chapter 7: Foundational Spatial Analyses*
------
* **7.1** [Geometric Binary Predicates: The Building Blocks of Geometric Queries](https://platform.i-guide.io/notebooks/06a40182-91cc-4ed4-befb-7dad6ff99966)
* **7.2** [Spatial Joins and Filter by Location](https://platform.i-guide.io/notebooks/a4f2cf0c-b777-4811-8aa1-6d5420795)
* **7.3** [Distance and Nearest Neighbor Calculations](https://platform.i-guide.io/notebooks/02f7f46b-c45f-4a06-81e0-d7df3f81ca23)
* **7.4** Buffer Analysis - *coming soon*

*Chapter 8: Advanced Spatial Analyses*
------
**Coming Soon!** Sign up for the [R Spatial Mailing List](https://mailchi.mp/ab01e8fc8397/r-spatial-email-signup) to receive project updates!

*Chapter 9: Raster Analysis*
------
* **8.1** Raster Analysis and Aggregation - *coming soon: release 4*
* **8.2** Raster Data Mapping and Visualization - *coming soon: release 4*

---
### Project FAQs

**Why is everything written in Jupyter Notebooks rather than R Markdown?**
This project was started while I was a postdoctoral scholar with the University of Minnesota and the NSF I-GUIDE project and the notebooks were specifically developed to be used and shared witin the I-GUDE platform.  The I-GUIDE platform supports the Jupyter Notebook framework which is why I wrote the notebooks in Jupyter rather than R Markdown.  I may write and make available R Markdown versions in the future if there is interest for it.
