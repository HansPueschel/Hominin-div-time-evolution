
[![DOI](https://zenodo.org/badge/335695240.svg)](https://zenodo.org/badge/latestdoi/335695240)
------

# Divergence-time estimates for hominins provide insight into encephalization and body mass trends in human evolution #

This repository contains all the code and data used in the manuscript [Link to paper]()

To cite the paper: 
>

Corresponding authors:

- **Hans P. Püschel**

  affiliation: University of Edinburgh
  
  email: h.p.puschel-rouliez@sms.ed.ac.uk
  
- **Thomas A. Püschel**  

  affiliation: University of Oxford
  
  email: thomas.puschelrouliez@anthro.ox.ac.uk 

date: 2021-02-03

journal: Nature Ecology & Evolution

url: 

doi: 

date_published: 

------

## Hominin-div-times-evolution ##

Data and analyses used in Püschel et al. 2021, Nature Ecology and Evolution, doi:

>These are the files necessary to replicate the study “Divergence-time estimates for hominins provide insight into encephalization and body mass trends in human evolution” by Hans P. Püschel, Ornella C. Bertrand, Joseph E. O’Reilly, René Bobe & Thomas A. Püschel

------

## Contents ##

1) The `Nexus_files` folder contains all the nexus files necessary to replicate the TED analyses in MrBayes for the four topological hypothesis tested in our paper (see the methods section for more details). 

2) The `.con.tre` files correspond to the majority rule consensus trees obtained in the TED analyses for the four topological hypotheses. These files are necessary to run the R scripts contained in `R_scripts_TED_hominin.Rmd`. These files can also be obtained if the full analysis is replicated using the nexus files in MrBayes.

3) The `.csv` files correspond to tables with information about body mass, brain mass and PEQ for each one of the taxa analysed in our paper. These files are necessary to run the R scripts contained in `R_scripts_TED_hominin.Rmd`.

4) The `post_tc_trees.txt` files contained the 9002 time-calibrated posterior trees sampled for each one of the four analyses. These are necessary to run the fifth section of the script in `R_scripts_TED_hominin.Rmd`. These files can also be obtained if the full analysis is replicated using the nexus files in MrBayes, and then using the code available in the fifth section of `R_scripts_TED_hominin.Rmd` with the `.t` and `.p files`. 

5) The `R_scripts_TED_hominin.Rmd` file contains all the scripts necessary to replicate this study.

------

## Session information

For reproducibility purposes, here is the output of `devtools::session_info()` used to perform the analyses in the publication.

─ Session info ──────────────────────────────────────────────────────────────────────────────────────────────────────────
 setting  value                       
 version  R version 4.0.2 (2020-06-22)
 os       macOS  10.16                
 system   x86_64, darwin17.0          
 ui       RStudio                     
 language (EN)                        
 collate  en_GB.UTF-8                 
 ctype    en_GB.UTF-8                 
 tz       Europe/London               
 date     2021-03-01                  

─ Packages ──────────────────────────────────────────────────────────────────────────────────────────────────────────────
 package           * version    date       lib source        
 AICcmodavg        * 2.3-1      2020-08-26 [1] CRAN (R 4.0.2)
 ape               * 5.4-1      2020-08-13 [1] CRAN (R 4.0.2)
 assertthat          0.2.1      2019-03-21 [1] CRAN (R 4.0.0)
 bitops              1.0-6      2013-08-17 [1] CRAN (R 4.0.0)
 boot                1.3-25     2020-04-26 [1] CRAN (R 4.0.2)
 callr               3.5.1      2020-10-13 [1] CRAN (R 4.0.2)
 caper               1.0.1      2018-04-17 [1] CRAN (R 4.0.0)
 cli                 2.2.0      2020-11-20 [1] CRAN (R 4.0.2)
 clusterGeneration   1.3.7      2020-12-15 [1] CRAN (R 4.0.2)
 coda              * 0.19-4     2020-09-30 [1] CRAN (R 4.0.2)
 codetools           0.2-18     2020-11-04 [1] CRAN (R 4.0.2)
 colorspace          2.0-0      2020-11-11 [1] CRAN (R 4.0.2)
 combinat            0.0-8      2012-10-29 [1] CRAN (R 4.0.0)
 crayon              1.3.4      2017-09-16 [1] CRAN (R 4.0.0)
 DBI                 1.1.1      2021-01-15 [1] CRAN (R 4.0.2)
 desc                1.2.0      2018-05-01 [1] CRAN (R 4.0.0)
 deSolve             1.28       2020-03-08 [1] CRAN (R 4.0.0)
 devtools            2.3.2      2020-09-18 [1] CRAN (R 4.0.2)
 digest              0.6.27     2020-10-24 [1] CRAN (R 4.0.2)
 dplyr               1.0.3      2021-01-15 [1] CRAN (R 4.0.2)
 ellipsis            0.3.1      2020-05-15 [1] CRAN (R 4.0.0)
 evaluate            0.14       2019-05-28 [1] CRAN (R 4.0.0)
 expm                0.999-6    2021-01-13 [1] CRAN (R 4.0.2)
 fansi               0.4.2      2021-01-15 [1] CRAN (R 4.0.2)
 farver              2.0.3      2020-01-16 [1] CRAN (R 4.0.0)
 fastmatch           1.1-0      2017-01-28 [1] CRAN (R 4.0.0)
 fs                  1.5.0      2020-07-31 [1] CRAN (R 4.0.2)
 geiger            * 2.0.7      2020-06-02 [1] CRAN (R 4.0.0)
 generics            0.1.0      2020-10-31 [1] CRAN (R 4.0.2)
 geoscale          * 2.0        2015-05-14 [1] CRAN (R 4.0.1)
 ggmap             * 3.0.0      2019-02-05 [1] CRAN (R 4.0.1)
 ggplot2           * 3.3.3      2020-12-30 [1] CRAN (R 4.0.2)
 glue                1.4.2      2020-08-27 [1] CRAN (R 4.0.2)
 gtable              0.3.0      2019-03-25 [1] CRAN (R 4.0.0)
 gtools              3.8.2      2020-03-31 [1] CRAN (R 4.0.2)
 htmltools           0.5.1.1    2021-01-22 [1] CRAN (R 4.0.2)
 httr                1.4.2      2020-07-20 [1] CRAN (R 4.0.2)
 igraph              1.2.6      2020-10-06 [1] CRAN (R 4.0.2)
 jpeg                0.1-8.1    2019-10-24 [1] CRAN (R 4.0.0)
 jsonlite            1.7.2      2020-12-09 [1] CRAN (R 4.0.2)
 KernSmooth          2.23-18    2020-10-29 [1] CRAN (R 4.0.2)
 knitr               1.31       2021-01-27 [1] CRAN (R 4.0.2)
 ks                  1.11.7     2020-02-11 [1] CRAN (R 4.0.0)
 labeling            0.4.2      2020-10-20 [1] CRAN (R 4.0.2)
 lattice             0.20-41    2020-04-02 [1] CRAN (R 4.0.2)
 lifecycle           0.2.0      2020-03-06 [1] CRAN (R 4.0.0)
 lme4                1.1-26     2020-12-01 [1] CRAN (R 4.0.2)
 magrittr            2.0.1      2020-11-17 [1] CRAN (R 4.0.2)
 maps              * 3.3.0      2018-04-03 [1] CRAN (R 4.0.0)
 MASS                7.3-53     2020-09-09 [1] CRAN (R 4.0.2)
 Matrix              1.3-2      2021-01-06 [1] CRAN (R 4.0.2)
 mclust              5.4.7      2020-11-20 [1] CRAN (R 4.0.2)
 memoise             1.1.0      2017-04-21 [1] CRAN (R 4.0.0)
 minqa               1.2.4      2014-10-09 [1] CRAN (R 4.0.0)
 mnormt              2.0.2      2020-09-01 [1] CRAN (R 4.0.2)
 motmot            * 2.1.3      2019-11-25 [1] CRAN (R 4.0.2)
 munsell             0.5.0      2018-06-12 [1] CRAN (R 4.0.0)
 mvtnorm             1.1-1      2020-06-09 [1] CRAN (R 4.0.0)
 nlme              * 3.1-151    2020-12-10 [1] CRAN (R 4.0.2)
 nloptr              1.2.2.2    2020-07-02 [1] CRAN (R 4.0.2)
 nortest           * 1.0-4      2015-07-30 [1] CRAN (R 4.0.2)
 numDeriv            2016.8-1.1 2019-06-06 [1] CRAN (R 4.0.0)
 paleotree         * 3.3.25     2019-12-12 [1] CRAN (R 4.0.0)
 phangorn            2.5.5      2019-06-19 [1] CRAN (R 4.0.0)
 phytools          * 0.7-70     2020-09-19 [1] CRAN (R 4.0.2)
 pillar              1.4.7      2020-11-20 [1] CRAN (R 4.0.2)
 pkgbuild            1.2.0      2020-12-15 [1] CRAN (R 4.0.2)
 pkgconfig           2.0.3      2019-09-22 [1] CRAN (R 4.0.0)
 pkgload             1.1.0      2020-05-29 [1] CRAN (R 4.0.0)
 plotrix           * 3.7-8      2020-04-16 [1] CRAN (R 4.0.0)
 plyr                1.8.6      2020-03-03 [1] CRAN (R 4.0.0)
 png                 0.1-7      2013-12-03 [1] CRAN (R 4.0.2)
 prettyunits         1.1.1      2020-01-24 [1] CRAN (R 4.0.0)
 processx            3.4.5      2020-11-30 [1] CRAN (R 4.0.2)
 ps                  1.5.0      2020-12-05 [1] CRAN (R 4.0.2)
 purrr               0.3.4      2020-04-17 [1] CRAN (R 4.0.0)
 quadprog            1.5-8      2019-11-20 [1] CRAN (R 4.0.0)
 R6                  2.5.0      2020-10-28 [1] CRAN (R 4.0.2)
 raster              3.4-5      2020-11-14 [1] CRAN (R 4.0.2)
 Rcpp                1.0.6      2021-01-15 [1] CRAN (R 4.0.2)
 RCurl               1.98-1.2   2020-04-18 [1] CRAN (R 4.0.0)
 remotes             2.2.0      2020-07-21 [1] CRAN (R 4.0.2)
 RgoogleMaps         1.4.5.3    2020-02-12 [1] CRAN (R 4.0.1)
 rjson               0.2.20     2018-06-08 [1] CRAN (R 4.0.0)
 rlang               0.4.10     2020-12-30 [1] CRAN (R 4.0.2)
 rmarkdown           2.6        2020-12-14 [1] CRAN (R 4.0.2)
 rprojroot           2.0.2      2020-11-15 [1] CRAN (R 4.0.2)
 rr2               * 1.0.2      2019-05-09 [1] CRAN (R 4.0.2)
 rstudioapi          0.13       2020-11-12 [1] CRAN (R 4.0.2)
 scales              1.1.1      2020-05-11 [1] CRAN (R 4.0.0)
 scatterplot3d       0.3-41     2018-03-14 [1] CRAN (R 4.0.2)
 sessioninfo         1.1.1      2018-11-05 [1] CRAN (R 4.0.0)
 sp                  1.4-5      2021-01-10 [1] CRAN (R 4.0.2)
 statmod             1.4.35     2020-10-19 [1] CRAN (R 4.0.2)
 strap             * 1.4        2014-11-05 [1] CRAN (R 4.0.0)
 stringi             1.5.3      2020-09-09 [1] CRAN (R 4.0.2)
 stringr             1.4.0      2019-02-10 [1] CRAN (R 4.0.0)
 subplex             1.6        2020-02-23 [1] CRAN (R 4.0.0)
 survival            3.2-7      2020-09-28 [1] CRAN (R 4.0.2)
 testthat            3.0.1      2020-12-17 [1] CRAN (R 4.0.2)
 tibble            * 3.0.5      2021-01-15 [1] CRAN (R 4.0.2)
 tidyr               1.1.2      2020-08-27 [1] CRAN (R 4.0.2)
 tidyselect          1.1.0      2020-05-11 [1] CRAN (R 4.0.0)
 tmvnsim             1.0-2      2016-12-15 [1] CRAN (R 4.0.0)
 unmarked            1.0.1      2020-07-02 [1] CRAN (R 4.0.2)
 usethis             2.0.0      2020-12-10 [1] CRAN (R 4.0.2)
 vctrs               0.3.6      2020-12-17 [1] CRAN (R 4.0.2)
 VGAM                1.1-5      2021-01-14 [1] CRAN (R 4.0.2)
 withr               2.4.0      2021-01-16 [1] CRAN (R 4.0.2)
 xfun                0.21       2021-02-10 [1] CRAN (R 4.0.2)
 xtable              1.8-4      2019-04-21 [1] CRAN (R 4.0.0)
 yaml                2.2.1      2020-02-01 [1] CRAN (R 4.0.0)

[1] /Library/Frameworks/R.framework/Versions/4.0/Resources/library

## Checkpoint for reproducibility
To rerun all the analyses with the packages as they existed at the time of our analyses, we suggest using the `checkpoint` [package](https://cran.r-project.org/web/packages/checkpoint/index.html), and running the following code before carrying out the analysis:

```{r}
checkpoint("2020-02-01") 
```
