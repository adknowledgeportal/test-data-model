# AD Data Models

## Major files

This repository contains two major file types:
1. `*.data.model.csv` The CSV representation of the data model. This file is created by the collective effort of data curators and annotators from the AD community, and will be used to create a JSON-LD representation of the data model.
2. `*.data.model.jsonld` The JSON-LD representation of the data model, which is automatically created from the CSV data model using the schematic CLI. More details on how to convert the CSV data model to the JSON-LD data model can be found here. This is the central schema (data model) which will be used to power the generation of metadata manifest templates for various data types (e.g., scRNA-seq Level 1) from the schema. 
