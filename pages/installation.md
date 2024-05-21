# Software Installation Instructions

Please install the following tools (available on all platforms):
* [Cytoscape v3.10.2](https://cytoscape.org/)
* [R v4.4.0](https://cloud.r-project.org/) - make sure you install R before you install RStudio!
* [RStudio v1.4](https://www.rstudio.com/products/rstudio/download/#download)

<hr/>

**Install required R-packages**

It would be great if you could already install some of the R packages. Open RStudio and run the following code below: 

```R
install.packages("BiocManager")
BiocManager::install("RCy3") 
BiocManager::install("rWikiPathways") 
BiocManager::install("clusterProfiler") 
BiocManager::install("org.Hs.eg.db") 
BiocManager::install("RColorBrewer") 
BiocManager::install("EnhancedVolcano") 
BiocManager::install("dplyr") 
BiocManager::install("tidyverse")
BiocManager::install("limma")
BiocManager::install("PCAtools")
BiocManager::install("illuminaio")
install.packages("rstudioapi") 
install.packages("readr") 
install.packages("data.table")
```

<hr/>

**Contact**

Feel free to contact us in case you have problems installing the software or packages (ideally before the workshop!).
