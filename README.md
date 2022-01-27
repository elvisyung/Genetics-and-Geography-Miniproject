# Genes-and-Geograph-MiniProject
Mini-project bioinformatic project applying PCA on vcf files obtained through the international genome sample resource site. Furthermore, obtained population data to better visualise genes and geography. Visualisation of final graphs are present in google colab link.    

Project was inspired by a Nature published article on understanding the genetic structure of human population by running PCA on genetic disease and geography data. Paper: https://www.nature.com/articles/nature07331

Languages Used: python, google colab
Packages Used: pandas, scikit-learn, altair, numpy, pysam and matplotlib
Principles Applied: PCA, tSNE, 

Experimental precedures: 

1) Sample were collected via https://www.internationalgenome.org/category/vcf website. ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp/release/20100804 was used to obtain data ALL.chr22.phase1_release_v3.20101123.snps_indels_svs.genotypes.vcf.gz through the command line (bash). 
2) The data used focused on chromosome 22 and variants present from the data collected in the international genome sample resource website. 
3) Located population label for the samples by collecting the data through https://www.internationalgenome.org/data-portal/population. 
4) Downlodad and located file containing specific sample ids and population code (phase1_integrated_calls.20101123.ALL.panel). 
5) Parsed VCF file via python script and identified genotypes (file name: vcf_to_matrix.py).
6) Continued developing python script for turning alleles to matrices using numpy arrays. 
7) Using Pandas to create dataframes and saving data
8) Aded population labels to matrices using the panel files collected 
9) Used google colab to visualise data by using pandas, sklearn, matplotlib and altair 
10) Ran additional data through tSNE for alternative visualisations 

## Google Colab Notebook:
https://colab.research.google.com/drive/11W2sHl7FyIkU8wDF3Q92IpPCZ2qSrKzI?usp=sharing
