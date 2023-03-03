# How to run the code
## Project structure
In the data folder there needs to be a raw and processed folders

## Data raw
Download the summary Drug comb file from https://drugcomb.org/download/

## Prepare the -omics data:
	-- First run the prepare_omics_data.ipynb to prepare the -omics data. If you are only running the baseline model , only run until the RNAseq gene expression data generation with the L1000 genes.

	-- Second, run the DDoS_Dataset_Generation for generating the dataset information

## Run the model 
Run the model_replicate.ipynb
