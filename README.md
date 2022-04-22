# EC22-neotoma-actR

<!-- badges: start -->
[![Launch Rstudio Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nickmckay/EC22-neotoma-actR/main?urlpath=rstudio)
<!-- badges: end -->

# Notebook
[Rendered version available here](https://nickmckay.github.io/EC22-neotoma-actR/)


# Abstract

The paleogeosciences are becoming more and more interdisciplinary, and studies increasingly rely on large collections of data derived from multiple data repositories. Integrating diverse datasets from multiple sources into complex workflows increases the challenge of creating reproducible and open science, as data formats and tools are often noninteroperable, requiring manual manipulation of data into standardized formats, resulting in a disconnect in data provenance and confounding reproducibility. Here we present a notebook that demonstrates how the Linked PaleoData (LiPD) framework is used as an interchange format to allow data from multiple data sources to be integrated in a complex workflow using emerging packages in R for geochronological uncertainty quantification and abrupt change detection. Specifically, in this notebook, we use the neotoma2 and lipdR packages to access paleoecological data from the Neotoma Database, and paleoclimate data from compilations hosted on Lipdverse. Age uncertainties for datasets from both sources are then quantified using the geoChronR package, and those data, and their associated age uncertainties, are then investigated for abrupt changes using the actR package, with accompanying visualizations. The result is an integrated, reproducible workflow in R that demonstrates how this complex series of multisource data integration, analysis and visualization can be integrated into an efficient, open scientific narrative.