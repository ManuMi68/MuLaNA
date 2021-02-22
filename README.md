# MuLaNA
Muzzio Lab Neuroscience Analysis

This is a set of statistical analysis codes written in R.   
It is oriented for the robust analysis of experimental designs,   
including on-way, two-way & three-way, between and Mixed.   
   
# The code is organized in an html file that includes all the explanations and details:   
"Differentia-Sleep-Deprivation-Place-Cell-Young-Old-Mice.html".   
The complete code is included for the analysis of all the data of the paper  
  "Differentia effect of sleep deprivation on place cell representations,   
  sleep architecture, and memory in young and old mice".   
The code can be copied from the different chunks, organized from the Figures on the paper.   
   
# The data is included in the folder "Design_Sleep3".  
   
# Once in the R program, install the libraries:   
install.packages(c("rtf"), repos = "http://cran.r-project.org").  
install.packages(c("parallel","data.table","ggplot2","dplyr", "ARTool", "lubridate", "kableExtra","caret","hrbrthemes", "modeest")).  
devtools::install_github("kassambara/ggpubr").  
   
For Robust Analysis:   
install.packages("WRS2").  
Source Rand Wilcox Robust Analysis Code from https://dornsife.usc.edu/labs/rwilcox/software/.  
This program uses the version: source("Rallfun-v37.txt")   
