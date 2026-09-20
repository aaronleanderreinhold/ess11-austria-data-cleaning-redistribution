# Subjective Financial Strain and Redistribution Preferences in Austria

Small empirical project using Austrian data from Round 11 of the European Social Survey (ESS).

## Research Question

**At similar household income levels, is feeling more financially strained linked to stronger support for redistribution?**

The project examines if subjective financial strain is associated with redistribution preferences after accounting for respondents position in the household income distribution.

## Data

The analysis uses the **European Social Survey Round 11 Integrated File, Edition 4.2**, restricted to respondents from Austria.

The raw ESS data are not included in the repository, since it's not my data and also rather large, but it can be downloaded from the European Social Survey Data Portal.

## Methods

The notebook includes:

- selection and cleaning of Austrian ESS11 survey data
- recoding of ESS special missing-value categories
- descriptive analysis
- use of the ESS analysis weight
- weighted regression models with robust standard errors

## Tools

Python with:

- pandas
- numpy
- matplotlib
- statsmodels

## Main File

`ess11_austria_financial_strain_redistribution.ipynb`

The notebook contains the complete data preparation, analysis and interpretation.
