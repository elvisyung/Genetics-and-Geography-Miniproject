# Genes-and-Geograph-MiniProject
Mini-project bioinformatic project applying PCA on vcf files obtained through the international genome sample resource site. Furthermore, obtained population data to better visualise genes and geography. Principles Applied: PCA, tSNE, and matrices. 

Project was inspired by a Nature published article on understanding the genetic structure of human population by running PCA on genetic disease and geography data. Paper: https://www.nature.com/articles/nature07331

Languages Used: Python, google colab
Packages Used: Pandas, scikit-learn, altair, numpy, pysam 
Principles Applied: PCA, tSNE, 

Experimental Procedures Done: 

1) Sample were collected via https://www.internationalgenome.org/category/vcf website. ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp/release/20100804 was used to obtain data ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz through the command line (bash). 
2) The data used focused on chromosome 22 and variants present from the data collected in the international genome sample resource website. 
3) Located population label for the samples by collecting the data through https://www.internationalgenome.org/data-portal/population. 
4) Downlodad and located file containing specific sample ids and population code (phase1_integrated_calls.20101123.ALL.panel). 
5) 
