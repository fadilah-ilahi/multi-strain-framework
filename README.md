# multi-strain-framework
This repository contains the code documentation for the paper Robust Numerical Framework for Multi-Strain Epidemics.
Repository contents:
1. Data. The COVID-19 data for Indonesia was collected from GISAID (https://gisaid.org/). The data saved as 'Covid-Variant-Indonesia-GISAID.csv'
2. Code Scripts. The code is organised into three separate scripts:
* Two-strain matrix framework. Implements the matrix framework for a two-strain epidemic model.
The framework is designed to be extendable to five and eleven strains by modifying the parameters within the same script.
* Delta-Omicron replacement. Validates the framework against COVID-19 data from Indonesia, capturing the displacement of the Delta variant by Omicron.
* Model benchmark. Compares the traditional ODE system approach with the matrix-based system under the same environment.
