The dataset is from https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE254054

The paper describing the data is at https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10879200/

20 patients, each has 3 regions and have both tumor (epi) and immune (non-epi) components. Total 120 samples.

The challenge is to get the response information for each patient and read the files into GeoMxSet object.

Following https://www.bioconductor.org/packages/release/bioc/vignettes/GeomxTools/inst/doc/GeomxSet_coercions.html

plot a boxplot for responders vs non-responders using PDCD1 and CD274.

The response information is in the supplementary PDF (second to last page) in the data folder.  

