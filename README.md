# API Driven Workflows for Evaluating Open Access and APC Savings in Health Libraries

## Using APIs to aid in consistent documentation of publishing trends at the University of Toronto Faculty of Dentistry 

## Overview
This repository contains all input files necessary to extract University of Toronto Faculty of Dentistry data from OpenAlex and Scopus API. The aim of this project is to create a consistent approach to locating and documenting publications from the faculty.

The data was used by the Head Librarian as the University of Toronto’s Dentistry Library to demonstrate library value to the faculty dean. The data obtained from this repository’s code and the results were presented at the [2026 Canadian Health Libraries Association Conference](https://chla-absc.ca/welcome_to_chla_2026.php?set_lang=english) on June 3rd, 2026, in Quebec City, QC, Canada.

## Requirements
The code requires R and RStudio. To run the code stored in this github, you will need to have both of these installed. We recommend using RStudio on your local computer or Posit Cloud as your IDE. 

Following the download of R and RStudio, you will need to download the packages associated with this project. These are:
-   `tidyverse`
-   `openalexR`
-   `writexl`
-   `httr`
-   `openxlsx`
-   `XML`

## Downloading Data
To access the data through the you will need an API key from Scopus and OpenAlex. Documentation for accessing these keys can be found in the links:
- [Scopus API](https://dev.elsevier.com/)
- [OpenAlex](https://developers.openalex.org/api-reference/introduction)

APC data used for analysis was found through institutional resources and is not available. 



