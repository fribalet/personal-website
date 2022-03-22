---
title: Computational Flow Cytometry Analysis of Marine Phytoplankton
date: "2018-03-01"
---
Since 2010, the shipboard underway cytometer [SeaFlow](https://seaflow.netlify.com) has been operated for 17,000 hours across 175,000 km of ocean, collecting over 350,000 samples in surface waters. We have created [reproducible analytical methods](https://github.com/topics/seaflow) to uniformly process and curate SeaFlow data. The datasets consist of cell abundance, cell diameter and cellular carbon content of small phytoplankton (< 10 μm), which includes the cyanobacteria <i>Prochlorococcus</i>, <i>Synechococcus</i> and <i>Crocosphaera</i>, and a mixture of unindentified protists.

* An example dataset representing the compilation of over 69,000 samples collected during 27 oceanographic cruises between 2010 and 2018 in the North Pacific Ocean is available [here](http://doi.org/10.5281/zenodo.2678021) without restriction. Data Description can be found in [Ribalet et al. 2019](https://doi.org/10.1038/s41597-019-0292-2).

* List of all datasets avaialble can be found [here](https://docs.google.com/spreadsheets/d/e/2PACX-1vT76VR2_VAulc6caxklUqOTOj_7EEnNJiFlHqaD1fC7Pc_zqw5i7wwcQUcDa8dtALZXoVHt2t0mdPS5/pubhtml).

We are currently working on a new Bayesian formulation of the [size-structured matrix population model](https://github.com/fribalet/Bayesian-matrixmodel) to estimate hourly cell growth and cell mortality rates for <i>Prochlorococcus</i> and <i>Synechococcus</i> across all SeaFlow data.

### Team
- [François Ribalet](https://francoisribalet.netlify.com) (Principal Investigator)
- [E Virginia Armbrust](https://armbrustlab.ocean.washington.edu/people/armbrust/) (co-Investigator)
- [Annette Hynes](https://armbrustlab.ocean.washington.edu/people/hynes/) (Research Scientist)
- [Chris Berthiaume](https://armbrustlab.ocean.washington.edu/people/beethiaume/) (Software Engineer)
- [Mattias Cape](https://armbrustlab.ocean.washington.edu/people/cape/) (Postdoctoral Research Associate)
- [Kristof Glauninger](https://www.stat.washington.edu/person/kristof-glauninger)(Graduate Student)

### Software
* [popcycle](https://github.com/armbrustlab/popcycle) - an R package that analyzing continuous flow cytometry data from SeaFlow repository. The software is built to perform both coarse real-time data analysis and fine-tuned population clustering analysis.

* [seaflowpy](https://github.com/armbrustlab/seaflowpy) - Python libraries and scripts to complement ```popcycle```.

* [bayesian-matrixmodel](https://github.com/fribalet/Bayesian-matrixmodel) - A size-structured matrix population model to estimate hourly division rates of microbial populations from particle size distribution provided by SeaFlow data.

### Funding sources
Project supported by grants from the [Simons Foundation](https://www.simonsfoundation.org/life-sciences/microbial-oceanography/)
(#574495 to FR, #426570SP and #549894 to EVA), [NASA](https://www.nasa.gov) (#80NSSC17K0561 to FR) and [NSF](https://www.nsf.gov) (#1536120 to EVA).

{{< figure library="true" src="seaflow.jpeg" title="" lightbox="true">}}
