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

---

*Chapter 1: Data Sources and APIs*
------
* **1.1** [Introduction to IPUMS and the IPUMS API](https://mybinder.org/v2/gh/vavramusser/r-spatial/HEAD?labpath=1.01+Introduction+to+IPUMS+and+the+IPUMS+API.ipynb)
* **1.2** [Introduciton to Natural Earth](https://mybinder.org/v2/gh/vavramusser/r-spatial/HEAD?labpath=1.02+Introduction+to+Natural+Earth.ipynb)
* **1.3** [Introduction to OpenStreetMap (OSM)](https://mybinder.org/v2/gh/vavramusser/r-spatial/HEAD?labpath=1.03+Introduction+to+OpenStreetMap+%28OSM%29.ipynb)
* **1.4** [Introduction to Stadia Maps and Stamen Maps](https://mybinder.org/v2/gh/vavramusser/r-spatial/HEAD?labpath=1.04+Introduction+to+Stadia+Maps+and+Stamen+Maps.ipynb)
* **1.5** [Introduction to Google Maps](https://mybinder.org/v2/gh/vavramusser/r-spatial/HEAD?labpath=1.05+Introduction+to+Google+Maps.ipynb)
* **1.6** [Introduction to Google Earth Engine (GEE)](https://mybinder.org/v2/gh/vavramusser/r-spatial/HEAD?labpath=1.06+Introduction+to+Google+Earth+Engine+%28GEE%29.ipynb)
* **1.7** [Introduction to the National Land Cover Database (NLCD)](https://mybinder.org/v2/gh/vavramusser/r-spatial/HEAD?labpath=1.07+Introduction+to+the+USGS+National+Land+Cover+Database+%28NLCD%29.ipynb)
* **1.8** [Introduction to the EPA Air Quality System (AQS) Data Repository](https://mybinder.org/v2/gh/vavramusser/r-spatial/HEAD?labpath=1.08+Introduction+to+the+EPA+Air+Quality+System+%28AQS%29+Data+Repository+and+the+AQS+API.ipynb)

*Chapter 2: IPUMS Data Acquisition and Extraction*
------
* **2.1** [IPUMS USA Data Extraction Using ipumsr](https://mybinder.org/v2/gh/vavramusser/r-spatial/HEAD?labpath=2.01+IPUMS+USA+Data+Extraction+Using+ipumsr.ipynb)
* **2.2** [IPUMS CPS Data Extraction Using ipumsr](https://mybinder.org/v2/gh/vavramusser/r-spatial/HEAD?labpath=2.02+IPUMS+CPS+Data+Extraction+Using+ipumsr.ipynb)
* **2.3** [IPUMS International Microdata Extraction Using ipumsr](https://mybinder.org/v2/gh/vavramusser/r-spatial/HEAD?labpath=2.03+IPUMS+International+Data+Extraction+Using+ipumsr.ipynb)
* **2.4** [IPUMS NHGIS Data Extraction Using ipumsr](https://mybinder.org/v2/gh/vavramusser/r-spatial/HEAD?labpath=2.04+IPUMS+NHGIS+Data+Extraction+Using+ipumsr.ipynb)
* **2.5** IPUMS Time Use Data Extraction Using ipumsr
* **2.6** IPUMS Health Surveys Data Extraction Using ipumsr

*Chapter 3: Data Cleaning and Preparation*
------
* **3.1** [Data Preparation and Transformation with IPUMS USA](https://mybinder.org/v2/gh/vavramusser/r-spatial/HEAD?labpath=3.01+Data+Cleaning+and+Preparation+with+IPUMS+USA.ipynb)
* **3.2** [Spatial Data Exploration and Preprocessing with IPUMS NHGIS](https://mybinder.org/v2/gh/vavramusser/r-spatial/HEAD?labpath=3.02+Spatial+Exploration+and+Preprocessing+with+IPUMS+NHGIS.ipynb)

*Chapter 4: Exploratory Data Analysis (EDA)*
------
* **4.1** Exploratory Data Analysis (EDA) with IPUMS USA
* **4.2** Exploratory Spatial Data Analysis (ESDA) with IPUMS NHGIS

*Chapter 5: Mapping*
------
* **5.1** Mapping Point and Polygon Data
* **5.2** Choropleth Mapping
* **5.3** Introduction to Basemaps with ggmap and tmap
* **5.4** Adding Basemaps with ggmap and tmap
* **5.5** Interactive Mapping with leaflet

*Chapter 6: Foundational Spatial Analyses*
------
* **6.1** Distance Calculations
* **6.2** Buffer Analysis
* **6.3** Point-in-Polygon Analysis
* **6.4** Overlay Analysis

*Chapter 7: Advanced Spatial Analyses*
------
**Coming Soon!** Sign up for the [R Spatial Mailing List](https://mailchi.mp/ab01e8fc8397/r-spatial-email-signup) to receive project updates!

*Chapter 8: Raster Analysis*
------
* **8.1** Raster Aggregation

---
### Project FAQs

**Why is everything written in Jupyter Notebooks rather than R Markdown?**
This project was started while I was a postdoctoral scholar with the University of Minnesota and the NSF I-GUIDE project and the notebooks were specifically developed to be used and shared witin the I-GUDE platform.  The I-GUIDE platform supports the Jupyter Notebook framework which is why I wrote the notebooks in Jupyter rather than R Markdown.  I may write and make available R Markdown versions in the future if there is interest for it.

**Will you take a look at my code / suggest a workflow for my project / brainstorm my project with me?**
Sure!  Send me an email.  [vavramusser@gmail.com](vavramusser@gmail.com)
