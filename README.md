# The heritability of migration behaviours in a wide-ranging ungulate

This repository contains pipelines for data processing and analysis for the manuscript titled "The heritability of migration behaviours in a wide-ranging ungulate".

## Project Overview

Using GPS and genomic data from 143 individuals (151 animal-years) in a pedigree-free quantitative genetic approach, we estimated heritability, repeatability, and sources of environmental variation for migration traits in migrating mule deer (*Odocoileus hemionus*).

## Repository Structure

This repository was made for reproducibility purposes, the full script for each analysis is provided in an .Rmd file with corresponding html

Description of the scripts in order of execution:

- **1. RADseq raw data processing** - Raw data processing and SNP genotyping for RADseq samples
- **2. Phenotype and GRM setup** - Generate distributions of migratory traits and body size traits, filter GRM for use in animal model
- **3. Animal models** - MCMCglmm models for migration and body size traits
- **4. Heritability** - Calculate heritability, repeatability and sources of environmental variation from animal models

## Contact

- **Author**: Maegwin Bonar
- **Email**: maegwinbonar@gmail.com
- **Institution**: Trent University
