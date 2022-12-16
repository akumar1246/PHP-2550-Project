# High-risk Sources and Seasons of C. Jejuni Outbreaks

![eacaea1be4b7e9b9c97d6124a4b4a10912a0130e07bfdad78ae03c0374c5e997-1](https://user-images.githubusercontent.com/55213658/208001426-026d0907-9b99-4190-a7d3-63f87ffe6c05.jpg)

# Introduction

In the United States, roughly 2.1-2.4 million individuals are diagnosed with human campylobacteriosis. These bacteria strains are classified as infectious diseases, and the broader symptoms of being infected include dysentery, abdominal cramping, etc. While less common, such strains, specifically that of Campylobacter jejuni (C. jejuni), can also result in septic arthritis, a condition which infects the joints. The strain of C. jejuni is most frequently reported in the United States, and is defined as the root cause of foodborne disease.

In this repository, we use secondary data on the foodborne pathogen Campylobacter jejuni to conduct an analysis investigating risk factors of outbreaks. For this project, our objective is to identify high-risk sources of Campylobacter jejuni infection and times of the year that have a high likelihood of seeing an outbreak.


# Data

In this section, we have two data sources. The dataset titled "isolates.csv" is downloaded from the "Isolates" browser of the National Library of Medicine's (NIH) NCBI Pathogen Detection Project which is located at:

https://www.ncbi.nlm.nih.gov/pathogens/isolates/#taxgroup_name:%22Campylobacter%20jejuni%22

The dataset titled "NationalOutbreakPublicDataTool.csv" is downloaded from the CDC's National Outbreak Reporting System (NORS) and contains data on the state, year, and month, of all Campylobacter jejuni outbreaks in the United States from 2012-2020. This dataset can be found here:

https://wwwn.cdc.gov/norsdashboard/

The dataset titled "isolates_clean.csv" is our final dataset after implementing data cleaning and management. It can be created by running the "DataManagement_and_EDA3.Rmd" syntax with the initial dataset, "isolates.csv". If you wish to run the code for our analysis syntax, please either use the cleaned data set, or run the data management syntax on the original dataset.


# Syntax

This folder includes all syntax that we have created or worked with to explore our data and implement our project. The "DataManagement_and_EDA3.Rmd" file contains all of our data cleaning and data exploration. The "Analysis.Rmd" file contains all of the syntax related to our analysis.


# Literature

This folder includes sources that we have used to investigate the topic of Campylobacter jejuni, sources that we have used in our literature review, as well as sources we have consulted to understand the potential limitations of our project.


# Packages

This folder includes any packages that will be needed to run our syntax that are not currently available on the CRAN repository.
