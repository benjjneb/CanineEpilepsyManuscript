# Reproducible Analyses from the First Canine Epilepsy Manuscript

This repository hosts the reproducible workflow that performed the analyses presented in the manuscript "Evaluation of fecal Lactobacillus populations in dogs with idiopathic epilepsy: A pilot study" by Munana, Jacob & Callahan.

Rmarkdown documents are hosted in the root directory. The input sequencing data is not included in the repository for size reasons, and is instead available from the SRA under BioProject Accession PRJNA612483. Auxiliary data is included in the `Docs/` directory, RDS files holding intermediate data objects suitable for performing the analyses of the processed sequencing data are in the `RDS/` directory, and figures created by the Rmarkdown documents are in the `Figures/` directory. 

You can run these analyses on your own machine by (1) cloning the repository, (2) obtaining the raw sequencing data, (3) modifying the paths defined at the start of each Rmd document, (4) installing required libraries, and (5) pressing Run! Even without the sequencing data, the analysis Rmarkdown document can be run using the stored data objects in the `RDS/` directory.

These Rmarkdown documents have also been rendered into html format, and can be viewed in your web browser:

* [Processing of the raw 16S sequencing data](https://benjjneb.github.io/CanineEpilepsyManuscript/process.html).
* [Statistical analysis and visualizations of the microbiome and Lactobacillus data](https://benjjneb.github.io/CanineEpilepsyManuscript/analyze.html).

Questions and comments are welcome on the Issues tracker for this repository: https://github.com/benjjneb/CanineEpilepsyManuscript/issues

Benjamin Callahan (benjamin DOT j DOT callahan AT gmail DOT com). Twitter: [\@bejcal](https://twitter.com/bejcal)
