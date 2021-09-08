## Installation instructions

Please install the following tools (available on all platforms):
* [Cytoscape v3.8.2](https://cytoscape.org/download.html)
* [R v4.1.0](https://cloud.r-project.org/)
* [RStudio v1.4](https://www.rstudio.com/products/rstudio/download/#download)

<hr/>

**Install required R-packages**

If you start RStudio, you can run the following code to install the required packages: 
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
BiocManager::install("clusterProfiler") 
BiocManager::install("igraph") 

install.packages("rstudioapi") 
install.packages("readr") 
install.packages("data.table")
```

<hr/>

**Contact**

Feel free to contact us in case you have problems installing the software or packages (ideally before the workshop!).
