## README

Repository containing R code (*DArTSNPFilt.R*), tutorial, data, and outputs for DArTSeq (https://www.diversityarrays.com/) SNP visualisation and filtering. 

This repository steps through the process of filtering DArTSeq SNPs (although the steps are relevant to any reduced representation SNP data) using the following files in the Data/ folder as the starting input:  

### DArT supplied (example data file names):
* 1-row SNP csv (*Report_DDasy19-4717_1Row_NameEdit.csv*)  
* 2-row SNP csv (*Report_DDasy19-4717_2Row_NameEdit.csv*)  
* Read count csv (*ReadCounts_DDasy19-4717_NameEdit.csv*)  

### Study specific data (example data file names):  
* Sample meta-data csv (including ID, pop, lon/lat, other info; *Dasyurus_hallucatus_ind.metadata.csv*)  
* Shape file of study region (*PilbaraIBRA.shp*)  
* Optional: Tasmanian devil chromosome info (*TasDevil7.1_Scaffold_Info.csv*)  

Filtering outputs (plots, filtered data) can be found in the Filtering_outputs folder. The full process is outlined in detail in the html tutorial (*DArTSNPFilt.html*).