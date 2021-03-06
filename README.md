[![Twitter Follow](https://img.shields.io/twitter/follow/iprophage.svg?style=social)](https://twitter.com/iprophage)

# patPRO 1.1.0
Visualizing Temporal Microbiome Data

## About This Package
patPRO (Patient Profiler)

Follow on **Twitter** for live update.

This is an R package developed for easy visualization of longitudinal microbiome data. This package allows you to process and visualize taxonomic relative and estimated absolute abundance, diversity, and bacterial load. These plots can be merged together to create longitudinal microbiome profiles. The example we use describes profiles of patient microbiomes over time (patient profiles). It works well with default Qiime output, but can also be used easily with Mothur.

## Example Usage
* A) Flow chart outlining the data processing and visualization steps included in the patPRO package. 
* B) Example of a single patient profile including normalized alpha diversity (top panel), bacterial load (middle panel), and relative abundance with annotated surgical events (bottom panel). 
* C) Single patient profile including taxonomic relative abundance normalized to bacterial load (bottom panel). 
* D) Example of a patient profile depicting the mean values of five patients, compared to a single patient profile in section (B). Bars represent standard error.

![patPRO Example Image](https://github.com/Microbiology/patPRO/blob/master/Images/Figure1.jpg)

## Installation
You can easily download the [package from CRAN](https://cran.r-project.org/web/packages/patPRO/). If you want the most up-to-date version included here on GitHub, just download the GitHub release and load it into R.

## Citing This Package
Did using patPRO help your research? Give us a shout-out by citing it! Simply include the following:

Hannigan GD, Loesche MA, Hodkinson BP, Mehta S and Grice EA (2015). patPRO: Visualizing Temporal Microbiome Data. R package version 1.0.0. http://CRAN.R-project.org/package=patPRO
