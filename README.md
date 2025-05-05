# Investigate the Legacy of Redlining in Current Environmental (In)justice

## Project Overview

Present-day environmental justice may reflect legacies of injustice in the past. The United States has a long history of racial segregation which is still visible. During the 1930’s the Home Owners’ Loan Corporation (HOLC), as part of the New Deal, rated neighborhoods based on their perceived safety for real estate investment. Their ranking system, (A (green), B (blue), C (yellow), D (red)) was then used to block access to loans for home ownership. Colloquially known as “redlining”, this practice has had widely-documented consequences not only for community wealth, but also health.1 Redlined neighborhoods have less greenery2 and are hotter than other neighborhoods.3

A recent study found that redlining has not only affected the environments communities are exposed to, it has also shaped our observations of biodiversity.4 Community or citizen science, whereby individuals share observations of species, is generating an enormous volume of data. Ellis-Soto and co-authors found that redlined neighborhoods remain the most undersampled areas across 195 US cities. This gap is highly concerning, because conservation decisions are made based on these data.

## About the Data

### EJScreen

Data file: `ejscreen/EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb`

We will be working with data from the United States Environmental Protection Agency’s EJScreen: Environmental Justice Screening and Mapping Tool.

According to the US EPA website:

This screening tool and data may be of interest to community residents or other stakeholders as they search for environmental or demographic information. It can also support a wide range of research and policy goals. The public has used EJScreen in many different locations and in many different ways.

EPA is sharing EJScreen with the public:- to be more transparent about how we consider environmental justice in our work,- to assist our stakeholders in making informed decisions about pursuing environmental justice and,- to create a common starting point between the agency and the public when looking at issues related to environmental justice.

EJScreen provides on environmental and demographic information for the US at the Census tract and block group levels. We will be working with data at the block group level that has been downloaded from the EPA site. To understand the associated data columns, we will need to explore the following in the data folder:

Technical documentation: `ejscreen-tech-doc-version-2-2.pdf`

Column descriptions: `EJSCREEN_2023_BG_Columns.xlsx`


### HOLC Redlining

Data file: `mapping-inequality/mapping-inequality-los-angeles.json`

A team of researchers, led by the Digital Scholarship Lab at the University of Richmond have digitized maps and information from the HOLC as part of the Mapping Inequality project.

We will be working with maps of HOLC grade designations for Los Angeles. 

### Biodiversity observations

Data file: `gbif-birds-LA.shp`

The Global Biodiversity Information Facility is the largest aggregator of biodiversity observations in the world. Observations typically include a location and date that a species was observed.

We will be working observations of birds from 2021 onward.

**Note:** the data associated with this assignment is too large to include in the GitHub repo. Instead, download data from [here](https://drive.google.com/file/d/14CauXFZkVh_6z2Euq0m1Sq1kHQ31fiMk/view?usp=sharing). Unzip the folder and all the contents and store in your directory as follows. Don't include data when you submit your assignment!

```         
EDS223-assignment2
│   README.md
│   Rmd/Proj files    
│
└───data
    │
    └───ejscreen
    │   column descriptions: EJSCREEN_2023_BG_Columns.xlsx
    │   metadata explation: ejscreen-tech-doc-version-2-2.pdf
    │   spatial data: EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb
    │
    └───gbif-birds-LA
    |   biodiversity data: gbif-birds-LA/gbif-birds-LA.shp
    │
    └───mapping-inequality
    |    mapping-inequality-los-angeles.json
```
