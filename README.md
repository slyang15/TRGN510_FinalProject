# TRGN510_FinalProject

# Title
Analyzing differential gene expression between African American and Caucasian prostate cancer patients.

## Author: 
Lynn Yang (seolynya@usc.edu)

## Overview of project:
•	RNA-sequencing is a powerful tool that is frequently used for gene expression analysis. Starting with the sequenced data, analysis can be conducted to determine differentially expressed genes. 

•	My project will be on utilizing the Bioconductor tool to analyze differential gene expression between African American and Caucasian prostate cancer patients.  

•	I will be following this vignette: https://www.bioconductor.org/packages/devel/workflows/vignettes/RNAseq123/inst/doc/limmaWorkflow.html

## Data:
•	Data will be obtained from the TCGA database on GDC.

African American men with prostate cancer:

• 176faa66-9eb4-4d1e-b7fe-08d34db0e44f.htseq.counts.gz

•	2a178039-8f10-43d6-b6f5-fae66d92b6a5.htseq.counts.gz

•	4e5e3af9-5d29-4ab0-a219-3242544064e4.htseq.counts.gz

•	30684606-b403-43ca-830f-05bc75ab7ac9.htseq.counts.gz

•	3b552b52-0bd4-458c-95f9-effe849ecc26.htseq.counts.gz

•	80d9227d-b41b-44eb-b230-cb1c14b5ee1a.htseq.counts.gz

•	acb3e352-b255-4c41-b90f-5e5ed2273b06.htseq.counts.gz

•	eff2d9bb-5bfd-451b-94f9-37080e4611ec.htseq.counts.gz

•	438b9759-ae94-4ba7-861c-9b1656ad8ed6.htseq.counts.gz

•	1b99466b-3732-43be-a4cd-cfb304736061.htseq.counts.gz

•	a97865ce-8a94-43aa-8998-4fc336300c77.htseq.counts.gz

•	c7116e13-54a3-41bc-ab15-c6a1d1e1247a.htseq.counts.gz	

• 8c36062e-bf1d-4d6c-be76-37d9fd4805bc.htseq.counts.gz

• 456b4981-9f37-42ff-b056-883a19ebc7a9.htseq.counts.gz

• 6f143139-d329-468d-ac0b-2552fb3362fd.htseq.counts.gz	

Caucasian men with prostate cancer:

•	94043a2d-b9e2-426d-9e89-6213034332f6.htseq.counts.gz

•	326bcde3-94ad-4b17-ab61-733e7cf6ff2f.htseq.counts.gz

•	b7174918-6cea-417e-8a86-f3a61ad81153.htseq.counts.gz

•	430669ee-998d-4917-83b6-ee7f0b6cae46.htseq.counts.gz

•	81ef037f-28d3-4960-b814-37af7ff8f972.htseq.counts.gz

•	5e3fd2aa-e0dd-4fe8-9944-05bba5d6bd91.htseq.counts.gz

•	362f67f1-4837-4245-ae7b-76d596575fd4.htseq.counts.gz

•	9fc9128a-5cf9-4991-81b5-754092c301b1.htseq.counts.gz

•	070af2c9-b54f-41e2-a48d-a7e3bfaa9025.htseq.counts.gz

•	ec4a2c9d-1d81-4129-b2b9-ac500f39f7ca.htseq.counts.gz

•	c7dec3e3-b999-48b9-8183-4b3515930b1d.htseq.counts.gz

•	d98aa6a3-c555-40d8-adcb-5dcf74f24a9e.htseq.counts.gz

• fe2ee510-b575-4983-b16e-c8c8dc699916.htseq.counts.gz	

• 9f7d2a09-038f-4a98-85c9-652bdbcc9d33.htseq.counts.gz	

•	992d1bbb-5540-4082-9e08-819e0272cf89.htseq.counts.gz


## Milestone 1
•	My first milestone is to download 15 raw datasets in HT-seq format for each group (total 30) from TCGA and load them onto R. I will be downloading the files individually and uploading them to R in order to be able to use these datasets for the specific vignette chosen.
   
     Update 11/3/20: Still in progress, will complete by 11/6/20 and post as a Rmd in Github

## Milestone 2
•	I’ll be generating plots of the differentially expressed genes, as well as generate differential analysis.
    
     Update 11/3/20: Will complete by 11/10/20

## Deliverable
•	R MarkDown
