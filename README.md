# iTARI
This is the project to refine a set of target gene using a iterative way.
Usage:
(1) download the iTARI_0.0.1.tar.gz file
(2) install the package using install.package("path/iTARI_0.0.1.tar.gz")
(3) library("iTARI_0.0.1.tar.gz")
(4) refined_gset <- iTARI(geneExp = "TCGA", tarGene = "MSigDB", iterativeMax = 10, setMin = 20, 
                          corCut = 0.1, permTimes = 1000, channel = T)
                          
