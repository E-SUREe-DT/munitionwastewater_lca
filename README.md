# Munitions Wastewater Life Cycle Assessment
openLCA files for munitions wastewater life cycle assessment. 

## Description
This repository contains the JSON files containing the data used for conducting a life cycle assessment for evaluating the environmental impacts of several wastewater treatment technologies considered for munitions wastewater treatment. These technologies include: granular activated carbon (GAC), ion exchange (IX), reverse osmosis (RO), anaerobic granular reactor (ANGR), aerobic granular reactor (AGR), ultra-violet light catalyzed hydrogen peroxide (UV/H2O2), and ozone. Since each of these technologies on their own serve different treatment purposes, the life cycle assessment considered combinations of technologies (e.g. IX with ANGR and ozone). 

The results of the life cycle assessment are included in (INSERT PUBLISHED PAPER HERE)
## Data formats and license requirements
The data included in the repository are JSON files. [openLCA software](https://www.openlca.org/download/) is a free, open-source software that is required to open the JSON files (v1.11.0 or higher). While many of the databases among the JSON files will be viewable after downloading the openLCA software, there are several JSON files that will require an [ecoinvent](https://ecoinvent.org/offerings/licences/) database license (v3.8) in order to view it. 

## Instructions for Download
1. After downloading the openLCA software, download the munitions_wwt.zip file
2. open the openLCA software
3. Open a database
4. Select File > Import > JSON-LD
5. When selecting the files, just choose the folder in which the zip file is located and click 'open'. You will then see the zip file in the import window of openLCA. Click on it and choose 'Finish'.

## Ecoinvent databases within openLCA.
Note that when downloading ecoinvent databases for the first time, 7-8GB of HDD space is required and may take several hours to import. 

## Authors
Development and maintenance of this package and the original .zolca file is supported by the following people at the University of Utah. 

* Dana Tran
dana.tran@utah.edu
* Jennifer Weidhaas
jennifer.weidhaas@utah.edu
