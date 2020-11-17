# TRGN510_FinalProject

# Title
Analyzing differential gene expression between African American and Caucasian lung cancer patients.

## Author: 
Lynn Yang (seolynya@usc.edu)

## Overview of project:
•	RNA-sequencing is a powerful tool that is frequently used for gene expression analysis. Starting with the sequenced data, analysis can be conducted to determine differentially expressed genes. 

•	My project will be on utilizing the Bioconductor tool to analyze differential gene expression between 18 African American and 18 Caucasian lung cancer patients.  

•	I will be following this vignette: https://www.bioconductor.org/packages/devel/workflows/vignettes/RNAseq123/inst/doc/limmaWorkflow.html

## Data:
•	Data will be obtained from the TCGA database on GDC.

         Update 11/12/20: The datasets that I was looking at did not have the information I needed so I changed my dataset entirely.
African Americans with lung cancer: 

• 12d2b9fa-1921-4033-bdb9-7e114c0d7812.htseq.counts.gz (female)

• 0c0d8887-ff41-46ae-9aba-f6f98f8c1c5e.htseq.counts.gz (female)

• 90af0faf-3e8c-4741-bf49-f87a5b21d54c.htseq.counts.gz (female)

• 16c42b24-fcaf-43e2-8f52-d7488f82257b.htseq.counts.gz (female)

• 6011bac0-a278-42b4-bfd9-97f1b618926e.htseq.counts.gz (female)

• 3532ec0a-2563-420a-b71c-3dcc632ef477.htseq.counts.gz (female)

• 156c4f8b-4467-46d0-bc55-085a29377f3e.htseq.counts.gz (female)

• f93932b6-c8c3-45d8-9911-c4d387d9bad0.htseq.counts.gz (female)

• e38ee2d6-eaad-4d39-a7f3-951b1532c9e5.htseq.counts.gz (female)

• ebe06b50-91d3-4a79-bc8f-6564742c1652.htseq.counts.gz (male)

• c9381f51-ec09-4487-88a4-8e94452e4893.htseq.counts.gz (male)

• 3ce57f19-ef4b-4bb9-8530-eb0752975f4b.htseq.counts.gz (male)

• 2cea6dae-c807-428b-90c8-617b260d3975.htseq.counts.gz (male)

• f67ccdd6-1577-45fd-9e49-251b289d1179.htseq.counts.gz (male)

• ac5bc405-b210-4bf3-a4e6-6ff071aa59c7.htseq.counts.gz (male)

• b32ed1d3-c9f1-42c7-ad2a-32794591a839.htseq.counts.gz (male)

• 96717cca-f561-43ee-8fac-74c9aa43c202.htseq.counts.gz (male)

• bf8dd7a7-37b1-4a81-9554-d63fdf2fe4f1.htseq.counts.gz (male)

Caucasians with lung cancer:

• cc54e123-c06a-48a8-b864-7497ecb37c0b.htseq.counts.gz (female)

• 6476b6b8-7e7e-44ac-9869-c93b654458a5.htseq.counts.gz (female)

• cc296619-683f-4339-ab1f-51d567fc678a.htseq.counts.gz (female)

• 7ea958f2-f45d-4549-9d45-07c51eebae99.htseq.counts.gz (female)

• 60be1c92-8f57-45b0-adc8-eb2f2d0e3805.htseq.counts.gz (female)

• f994e1d7-6427-4884-8993-f930c6331bff.htseq.counts.gz (female)

• d370b7a3-a534-4190-a6d0-79276273093c.htseq.counts.gz (female)

• 9c62a984-f89a-4838-af13-786468b293c1.htseq.counts.gz (female)

• 027ec9be-7e41-44df-8f61-1e5698303eac.htseq.counts.gz (female)

• 783a2365-c4a2-4db4-ab14-d52e603d8230.htseq.counts.gz (male)

• 6095fc44-4542-4435-8e6b-dba09b3f7f92.htseq.counts.gz (male)

• 5260addc-0596-42c0-85c6-b74744db9cda.htseq.counts.gz (male)

• f9ea29ab-6953-4646-b367-cff2483b9f46.htseq.counts.gz (male)

• 06b1bbf5-07e5-4a03-aea1-f7203bab2572.htseq.counts.gz (male)

• 4c8648f5-26ca-4550-b51b-bd2228b1e8e0.htseq.counts.gz (male)

• 8e1d09e8-6dbd-408d-a839-f5bbebe30a57.htseq.counts.gz (male)

• ce4ac30d-f2e6-40f3-a2db-fdcf0218b8fb.htseq.counts.gz (male)

• 057c6a18-e5f2-4eba-9c20-c483c5a67cc3.htseq.counts.gz (male)



## Milestone 1
•	My first milestone is to download 18 raw datasets in HT-seq format for each group (total 36) from TCGA and load them onto R. I will be downloading the files individually and uploading them to R in order to be able to use these datasets for the specific vignette chosen.
   
     Update 11/3/20: Still in progress, will complete by 11/6/20 and post as a Rmd in Github
     Update 11/6/20: Completed and posted in Github as milestone1.Rmd and milestone1.html

## Milestone 2
•	I’ll be generating plots of the differentially expressed genes, as well as generate differential analysis.
    
     Update 11/3/20: Will complete by 11/10/20
     Update 11/10/20: Completed
     
## Known Issues: 
• There is a problem with naming the genes that are differentially expressed: head(tfit$genes$SYMBOL[de.common], n = 2). The output comes out as [1] NA NA.
• The last part (Gene set testing with camera) did not work.
• The log-fold-change was changed from the original 1 to 0.1 in order to detect more up and down regulated genes.


## Deliverable
•	R MarkDown
