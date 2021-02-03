---
Title: New divergence-time estimates for hominins provide insight into encephalization and body mass trends in human evolution 

Corresponding authors:
- name: Hans P. Püschel
  affiliation: University of Edinburgh
  email: h.p.puschel-rouliez@sms.ed.ac.uk
- name: Thomas A. Püschel 
  affiliation: University of Oxford
  email: thomas.puschelrouliez@anthro.ox.ac.uk 
date: 2021-02-03
journal: Nature Ecology & Evolution
url: 
doi: 
date_published: 
...

# Hominin-div-times-evolution #

Data and analyses used in Püschel et al. 2021, Nature Ecology and Evolution, doi:

>These are the files necessary to replicate the study “New divergence-time estimates for hominins provide insight into encephalization and body mass trends in human evolution” by Hans P. Püschel, Ornella C. Bertrand, Joseph E. O’Reilly, René Bobe & Thomas A. Püschel

# Contents #

1) The folder Nexus_files contains the nexus files necessary to replicate the TED analyses in MrBayes for the four topological hypothesis tested on the paper (see methods for more details). 

2) the .con.tre files are the majority rule consensus trees obtained in the TED analyses for the four topological hypotheses. These are necessary to run the R scripts contained in R_scripts_TED_hominin.Rmd.You can also obtain these files if you replicate the full analysis using the nexus files in MrBayes.

3) the .csv files are tables with information about body mass, brain mass and PEQ of the taxa of interest of the paper. These are necessary to run the R scripts contained in R_scripts_TED_hominin.Rmd.

4) The _post_tc_trees.txt files are files that contained total of 9002 time-calibrated posterior trees sampled for each one of the four analyses. These are necessary for point 5) of the script in R_scripts_TED_hominin.Rmd. You can also obtain these files if you replicate the full analysis using the nexus files in MrBayes, and then using the code in the point 5) of R_scripts_TED_hominin.Rmd with the .t and .p files. 

5) The R_scripts_TED_hominin.Rmd contains all the scripts necessary to replicate this study.
