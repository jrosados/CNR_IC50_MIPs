# CNR_IC50_MIPs
This repository contains R scripts and raw data used for the article:  "Assessment of ex-vivo antimalarial drug efficacy in African Plasmodium falciparum parasite isolates, 2016-2023: a genotype-phenotype association study"
Data is contained in the folder "raw_data"

R markdown files (.Rmd) contain scripts to perform the following analysis:

1.- Data processing from MIP to csv databases
	1.1 - Data processing from MIP wrangling to csv databases
	1.2 - Merging genotype database with IC50 database and COI data
	1.2 - Coverage heatmap 
	1.3 - COI distribution
	1.4 - Parasitemia distribution

2.- Epidemiological data
	2.1 - Epitable
	2.2 - Geographical distribution of samples
	2.3 - Distribution of countries per region in 2016-18 versus 2019-23

3.- Half-maximal inhibitory concentration IC50
	3.1.- Drug correlation matrix
	3.2.- Drug susceptibility by year
	3.3.- IC50 data stratified into 2016-18 vs 2019-23 periods
	3.4.- Drug susceptibility in 2016-18 versus 2019-23 by African region

4- Validated_mutations
	4.1.- Prevalence of validated key mutations
	4.2.- Prevalence of k13 mutations
	4.3.- Prevalence of background and other mutations
	4.4.- Raw data table per year
	4.5.- Raw data table in the top countries
	4.6.- Temporal change of key resistance mutations by year
	4.7.- Prevalence of key resistance mutations by year and by country

5.- Proportion_mixed_pure_genotypes
	5.1.- Proportion of mixed infections in key mutations
	5.2.- Proportion of mixed infections in k13 gene

6.- Haplotypes
	6.1.- CRT haplotypes
	6.2.- DHFR haplotypes
	6.3.- DHPS haplotypes
	6.4.- DHPS-DHFR haplotypes
	6.5.- MDR1 haplotypes
	6.6.- CRT_MDR1 Haplotypes
	6.7.- Time trend of CRT_MDR1 haplotypes
	6.8.- Grouped prevalence of CRT_MDR1 haplotypes before and after 2019

7.- LD
	7.1.- LD Plot of Ivory Coast and Cameroon samples

8.- SNP association
	8.1.- SNP association analysis for DHA
	8.2.- SNP association analysis for Lumefantrine
	8.3.- SNP association analysis for Mefloquine
	8.4.- SNP association analysis for MDAQ
	8.5.- SNP association analysis for Chloroquine
	8.6.- SNP association analysis for Piperaquine
	8.7.- Manhattan plots
	8.8.- List of associated SNP for the six drugs
	8.9.- Confirming SNPs associated when using CRT76 and CRT356 as covariable
	8.10.- Confirming SNPs associated when using CRT76 as covariable
8.11.- Confirming SNPs associated when using MDR86 as covariable
