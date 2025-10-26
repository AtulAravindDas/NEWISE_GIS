# NEWISE_GIS: The New England WISE Geographic Information System

## Prerequisites

To set up the environment and install dependencies, run the following commands:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

## Problem Statement

New England stands out as one of the most desirable regions in the United States, known for its high living standards and quality of life. However, when it comes to choosing where to settle—down to the best state or even the right county—the process can quickly turn into a maze of Google searches and scattered data. That’s where **NEWISE_GIS** steps in.

This innovative platform visualizes the performance of New England’s states and counties across key parameters such as **income**, **education**, **crime rates**, **educational attainment**, and **population**. With **NEWISE_GIS**, users can easily explore and compare regions through intuitive visualizations, gaining a clear, data-driven understanding of how each area measures up in the factors that matter most.

## Directory Descriptions

The project repository is organized as follows:

```bash
NEWISE_GIS/
├── New_England_Datasets/           # Contains all CSV files for state-level data
├── counties_shapefiles/            # Massachusetts county-level shapefiles
├── ct_county_shapefiles/           # Connecticut county shapefiles
├── me_county_shapefiles/           # Maine county shapefiles
├── nh_county_shapefiles/           # New Hampshire county shapefiles
├── ri_county_shapefiles/           # Rhode Island county shapefiles
├── vt_county_shapefiles/           # Vermont county shapefiles
├── shapefiles/                     # Base shapefiles for New England map boundaries
├── ipynb_files/                    # Jupyter notebooks for data cleaning and visualization
└── maps/                           # Output map visualizations and rendered GIS plots
```
## Other files 

```bash
NEWISE_GIS/
├── .gitignore #Ignores the virtual environments
├── LICENSE #The Apache License
├── README.md #This file 🤓
├── index.html #File used to deploy maps
├── requirements.txt #Contains all the important packages present
```

## Overview

**NEWISE_GIS** aims to make regional comparisons across New England effortless.  
Whether you’re a **data enthusiast**, **policymaker**, or just someone dreaming of that cozy Vermont life 🏡, this project transforms **raw data into meaningful insights** — all visualized beautifully through **interactive geographic maps**.

With clear, data-driven visuals, **NEWISE_GIS** helps users explore how each state and county in New England performs across key factors like income, education, crime rates, and population — making complex regional analysis simple, intuitive, and accessible to everyone.




