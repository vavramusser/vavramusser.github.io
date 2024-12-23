---
permalink: /intro-to-ipums/
title: "Introduction to IPUMS and the IPUMS API"
excerpt: "Introduction to IPUMS and the IPUMS API"
author_profile: true
redirect_from: 
  - "/intro-to-r-spatial.html"
---

The [**IPUMS (Integrated Public Use Microdata Series)**](https://www.ipums.org) provides access to high-quality, harmonized data on population and health from around the world. Developed and maintained by the [Institute for Social Research and Data Innovation (ISRDI)](https://isrdi.umn.edu) at the [University of Minnesota's Minnesota Population Center (MPC)](https://pop.umn.edu), IPUMS datasets cover a range of demographic, health, and geographic topics that support research in fields like public health, economics, geography, and social sciences. IPUMS data offerings include U.S. Census data, global demographic surveys, and health datasets, all standardized across time and location to allow for easy cross-temporal and cross-national comparisons.

### Available Data

#### United States Data
* [**IPUMS USA**](https://usa.ipums.org/usa): United States microdata from 1850 to the present
  * Decennial Census
  * American Community Survey (ACS)
* [**Current Population Survey (CPS)**](https://cps.ipums.org/cps): CPS microdata including basic monthly surveys and supplements from 1962 to the present
* [**National Historic Geographic Information System (NHGIS)**](https://www.nhgis.org): Tabular US Census and GIS boundary files from 1790 to present
* [**Time Use**](https://timeuse.ipums.org): Historical and contemporary time use data from 1930 to present
  * American Time Use Survey (ATUS)
  * American Heritage Time Use Study (AHTUS)
* [**Health Surveys**](https://healthsurveys.ipums.org): Historical and contemporary US health survey data
  * National Health Interview Series (NHIS)
  * Medical Expenditure Panel Survey (MEPS)
* [**Higher Education**](https://highered.ipums.org/highered): Survey data on the science and engineering workforce in the US from 1993 to present
  * National Survey of College Graduates (NSCG)
  * Survey of Doctorate Recipents (SDR)
  * National Survey of Recent College Graduates (NSRCG)

#### International Data
* [**IPUMS International**](https://international.ipums.org/international): The world's largest collection of census microdata covering over 100 countries, contemporary and historical
* [**Global Health**](https://globalhealth.ipums.org): Health survey data from around the world
  * Demographic and Health Surveys (DHS)
  * Performance Monitoring for Action (PMA)
  * Multiple Indicator Cluster Surveys (MICS)
* [**International Historic Geographic Information System (IHGIS)**](https://ihgis.ipums.org): Tabular and GIS data from population, housing, and agricultural censuses aroud the world
* [**Time Use**](https://timeuse.ipums.org): Historical and contemporary time use data from 1930 to present
  * Multinational Time Use Study (MTUS)

## The ipumsr R Package
The [**ipumsr package**](https://cran.r-project.org/web/packages/ipumsr/index.html) is a tool for loading, managing, and analyzing IPUMS data within R. Designed to simplify the process of working with IPUMS extracts, ipumsr provides functions to import data, handle metadata, and apply labeled values directly, making it easier to move from raw data to analysis. This package supports both the classic rectangular datasets from IPUMS as well as more complex hierarchical files.

## The IPUMS API
The ipumsr package uses the [**IPUMS API**](https://developer.ipums.org/docs/v2/apiprogram) to extract data requests from IPUMS.

An [API (Application Programming Interface)](https://en.wikipedia.org/wiki/API) is a set of rules and protocols that allow different software applications to communicate with each other. APIs enable automated access to data and services, allowing users to retrieve, manipulate, and manage information without directly interacting with a website or user interface.

In the case of IPUMS, the API provides a streamlined, programmatic way to access data, making it possible to request and download datasets directly within R.

### ★ Create Your IPUMS Account and API Key ★
To download IPUMS data **you will need to set up an IPUMS account** and to submit data requests using the IPUMS API **you will need to obtain an IPUMS API key**.  You can register for an IPUMS account and get your IPUMS API key by following the instructions on [the IPUMS website](https://account.ipums.org/api_keys).

### IPUMS API Functionality for IPUMS Data

As of December 2024, ipumsr supports the following levels of functionality for each IPUMS project.

##### Browse Metadata, Request and Download Data, Read Data Extracts
* [IPUMS NHGIS](https://www.nhgis.org) U.S. Census Data Tables and Mapping Files

##### Request and Download Data, Read Data Extracts
* [IPUMS USA](https://usa.ipums.org/usa) U.S. Census Data for Social, Economic, and Health Research
* [IPUMS CPS](https://cps.ipums.org/cps) Current Population Survey (CPS) Data for Social, Economic, and Health Research
* [IPUMS International](https://international.ipums.org/international) Harmonized International Census Data for Scoial Science and Health Research
* [IPUMS Time Use](https://timeuse.ipums.org) from the American Time Use Survey (ATUS), American Heritage Time Use Study (AHTUS), and Multinational Time Use Study (MTUS)
* [IPUMS Health Surveys](https://healthsurveys.ipums.org) Harmonized Data from U.S. National Health Surveys including the National Health Interview Series (NHIS) and the Medical Expenditure Panel Survey (MEPS)

##### Read Data Extracts only
* [IPUMS Global Health](https://globalhealth.ipums.org) Harmonized International Survey Data on Maternal, Child, and Reproductive Health from the Demographic and Health Surveys (DHS), Performance Monitoring for Action (PMA), and Multiple Indicator Cluster Surveys (MICS)
* [IPUMS Higher Education](https://highered.ipums.org/highered) Survey Data on Scientists and Engineers

##### Not Currently Supported
* [IPUMS IHGIS](https://ihgis.ipums.org) Analysis Ready Tables from International Censuses

## Recommended Next Steps
* **Continue with Chapter 1: Data Sources and APIs**
  * 1.2: Introduciton to Natural Earth
  * 1.3: Introduction to OpenStreetMap (OSM)
  * 1.4: Introduction to Stadia Maps and Stamen Maps
  * 1.5: Introduction to Google Maps
  * 1.6: Introduction to Basemaps with ggmap
  * 1.7: Introduction to Google Earth Engine (GEE)
  * 1.8: Introduction to the National Land Cover Database (NLCD)
  * 1.9: Introduction to the EPA Air Quality System (AQS) Data Repository
* **Move on to Chapter 2: IPUMS Data Acquisition and Extraction**
  * 2.1: IPUMS USA Data Extraction Using ipumsr
  * 2.2: IPUMS CPS Data Extraction Using ipumsr
  * 2.3: IPUMS International Microdata Extraction Using ipumsr
  * 2.4: IPUMS NHGIS Data Extraction Using ipumsr
  * 2.5: IPUMS Time Use Data Extraction Using ipumsr
  * 2.6: IPUMS Health Surveys Data Extraction Using ipumsr
  * 2.7: Reading IPUMS Global Health Data Extracts Using ipumsr
  * 2.8: Reading IPUMS Higher Education Data Extracts Using ipumsr
