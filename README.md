# Huet et al. 2021

This is a R project used to analyze the data generated during the study published [insert paper information after publication].
You can download the whole file and open the project under R studio with R version 3.6.3.

The GlobalEnv.RData gather the data needed to run the R commander files. Raw data are presented in the Data subfile here and raw sequences were deposited at the NCBI under the accession number PRJNA763056 for 16S rRNA sequences and PRJNA763098 for the 18S rRNA sequences. 

The raw sequences were assembled and their quality was check using an in-house Python pipeline to generate the biom files, the tree files and calculte the alpha diversity indices. The in-house Python pipeline is available at the following link: https://forgemia.inra.fr/vasa/illuminametabarcoding/

All the other analyses were conducted using this R project scripts.
The R commander files should be run following this sequence:
* 1_Load_data.Rmd
* 2_alpha_div.Rmd
* 3_beta_div.Rmd
* 4_community_composition.Rmd
* 5_Differential_abundance_analysis.Rmd
* 6_PLN_models.Rmd
* 7_soil_properties_and_functions.Rmd
* 8_mixOmics_DIABLO.Rmd
