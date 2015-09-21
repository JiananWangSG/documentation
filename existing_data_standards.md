# Existing Data Standards

* example data with references can be found in https://uofi.box.com/terraref-sample-data

## Agronomic data (trait vectors)

### ICASA 
http://research.agmip.org/display/it/Data+Interoperability
ag expt data API http://research.agmip.org/display/dev/The+AgMIP+Crop+Experiment+Database+API
json data objects
variables list

ICASA seems the most widely adopted for agronomic management, but also useful to consider these:

### BETYdb Biofuel Ecophysiological Traits and Yields database https://betydb.org
(will be used to store meta-data, provenance, not a standard 'data product')
API documentation: https://www.authorea.com/users/5574/articles/7062/_show_article

BETYdb traits: available as web-page, csv, json, xml. This can be extended to allow spatial, temporal, and taxonomic / genomic queries.

Will add a new field or new table to uniquely identify each line / accession / etc.. This would be similar to / an extension of the cultivars table What uniquely identifies a 'line' (see 'uniqueness' section of BETYdb documentation[1]? linked to any breeding and/or genomics database to track and visualize lineage, sequencing, and analytical output. 

Data.gov Ag data published on data.gov: http://www.data.gov/food/

AgMIP, using ICASA standards
see https://github.com/terraref/reference-data/issues/6

GODAN Global Open Data for Agriculture and Nutrition 
http://www.godan.info/
a network of Ag interested in Open Data (see statement of purpose
Our team could be a GODAN partner

DataOne 
List, description, and format specifications for meta-data conventions / standards supported by DataOne. 
https://releases.dataone.org/online/api-documentation-v1.2.0/design/WhatIsData.html

## Genomics

Gramene  http://www.gramene.org/
curated, open-source, integrated data resource for comparative functional genomics in crops and model plant species

## APIs

OADA Open Ag Data Alliance
academic-industry collaboration to define a common API for ag data
 http://openag.io/
iPlant / Agave 
BETYdb: see API documentation [2] 

https://www.betydb.org/search?&search=switchgrass+sla
https://www.betydb.org/search.csv?&search=switchgrass+sla
https://www.betydb.org/search.xml?&search=switchgrass+sla
https://www.betydb.org/search.json?&search=switchgrass+sla

## Sensor Data

Image / Sensor data (https://github.com/terraref/reference-data/issues/2)
NEON data products http://data.neoninc.org/documents
ATBDs (Algorithm Theoretical Basis Document) provide protocols for creating data products, e.g. 
ISO 19115, which is how NEON, ICOS, NASA, PEcAn and others are trying to rally around as a single standard. http://www.iso.org/iso/home/store/catalogue_ics/catalogue_detail_ics.htm?csnumber=53798

Meteorological data (also see https://github.com/terraref/reference-data/issues/3):
Climate Forecasting Conventions
ICASA has specifications for daily met summaries

### MsTMIP data formats


## Other
Generic Standards
NIEM National Information Exchange Model. “NIEM makes it possible for organizations to share critical data; as a result, people are empowered to make informed decisions that improve efficiency and help organizations advance their missions.”  
comment: perhaps too generic for our specific needs, but a useful reference point

### Date-Time: 

YYYY-MM-DD hh:mm:ssZ: 
based on ISO 8601 . Optional offset for local time; precision determined by data (e.g. could be YYYY-MM-DD and decimals specified by a period.

## References

[1] BETYdb constraints documentation, see section "uniqueness constraints"  https://www.authorea.com/users/5574/articles/6719/_show_article
[2] BETYdb data access section on API https://www.authorea.com/users/5574/articles/7062/_show_article