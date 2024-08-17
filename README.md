# Human TNF Gene Analysis
## Project Objective  
This project aims to perform a comprehensive analysis of the Human Tumor Necrosis Factor (TNF) gene sequence using various bioinformatics tools such as NCBI, BioEdit, PROMO, GENSCAN, and MEME Suite. This mini project is the first task of the BioinformHER Module 1. BioinformHER is an initiative taken by HackBio aimed at introducing young women in STEM to Bioinformatics using simple and easy-to-follow guidelines.
### Steps involved in gene analysis
* Download the Human TNF gene sequence from NCBI and View/Edit it using BioEdit 
  ![image](https://github.com/user-attachments/assets/c7d77834-ce36-43a4-9b02-daf2dc73a798) 

* Generate the translated sequence of the gene using BioEdit 
  ![image](https://github.com/user-attachments/assets/f69cabd2-0ecb-491d-829f-b151a5bb00a4) 

* Identify Open Reading Frames (ORFs) present within the gene sequence using the BioEdit ORF Finder Tool and record the start/stop positions, lengths, and protein translations of the ORFs 
  ![image](https://github.com/user-attachments/assets/b97fb25d-2388-429a-a490-f74d6510bfaa) 

* Analyze the sequence nucleotide composition using BioEdit by calculating the frequencies of each nucleotide, and overall GC content. Interpret the results. 
  ![image](https://github.com/user-attachments/assets/939ca183-2c9d-4ece-9860-5633a6d04b93) 

* Identify transcription factor binding sites using the PROMO tool 
  ![image](https://github.com/user-attachments/assets/71ed1e13-5a5c-4920-bf5d-98b82c24b1b9) 

* Search for functional motifs in the TNF gene sequence using the MEME Suite 
  ![Uploading image.png…]() 

* Predict the coding/non-coding regions within the gene sequence using the GENSCAN tool 
  ![Uploading image.png…]() 

* Convert sequence file format from FASTA to PHYLIP in BioEdit 

## Discussion and Future Directions 
The analysis of the Human Tumor Necrosis Factor (TNF) gene provides significant insights into the gene's structure, function, and regulatory elements. By identifying Open Reading Frames (ORFs), we can pinpoint regions of the gene that have the potential to code for proteins, which is essential for understanding its role in various biological processes. The nucleotide composition analysis revealed the frequencies of adenine, thymine, guanine, and cytosine within the gene, along with the overall GC content. This information is crucial because the GC content can influence gene stability, transcription efficiency, and the overall functionality of the gene. Transcription factor binding sites identified using the PROMO tool highlight key regulatory regions that could influence the expression of the TNF gene. Understanding these regions can provide insights into how TNF expression is controlled in response to various physiological and pathological stimuli. The identification of functional motifs within the TNF gene sequence is done using the MEME Suite. These motifs often represent conserved sequences that play critical roles in gene function, such as binding sites for proteins or RNA, which can have implications in disease mechanisms. The prediction of coding and non-coding regions using GENSCAN further refines our understanding of the gene's structure. Knowing which regions are likely to code for proteins and which are non-coding can help in annotating the gene and predicting its behavior under different conditions.  
Further analysis of the gene can be done by exploring the gene's expression patterns in different tissues and under various conditions, which could provide insights into its role in immune responses, inflammation, and diseases such as cancer and autoimmune disorders. The translated protein sequence can also be analyzed further to predict its structure and determine its functions using various bioinformatics tools available open source. Furthermore, integrating this bioinformatics analysis with wet-lab experiments, such as reporter assays or gene knockdown studies, could validate the computational predictions and offer a more comprehensive understanding of the TNF gene's biological functions.  

## How to use this Repository 
1. Clone this repository to your local machine using the following code:
   ```git clone https://github.com/mahiiC/Human_TNF_Gene_Analysis.git```
2. Folder navigation
   * The `README.md` file contains an overview of the project
   * The `Data/`, `Screenshots/`, and `Outputs/` folders contain the raw data and the outputs and their screenshots
   * The final report with the interpretations for all the observations can be found by accessing the `Report.pdf` file
  
## References 
1. Alzohairy, Ahmed. (2011). BioEdit: An important software for molecular biology. GERF Bulletin of Biosciences. 2. 60-61. 
2. Xavier Messeguer, Ruth Escudero, Domènec Farré, Oscar Nuñez, Javier Martínez, M.Mar Albà. PROMO: detection of known transcription regulatory elements using species-tailored searches. Bioinformatics, 18, 2, 333-334, 2002. 
3. Domènec Farré, Romà Roset, Mario Huerta, José E. Adsuara, Llorenç Roselló, M.Mar Albà, Xavier Messeguer. Identification of patterns in biological sequences at the ALGGEN server: PROMO and MALGEN. Nucleic Acids Res, 31, 13, 3651-3653, 2003.
4. Timothy L. Bailey, James Johnson, Charles E. Grant, William S. Noble, "The MEME Suite", Nucleic Acids Research, 43(W1):W39-W49, 2015. [full text]
5. Burge, C. and Karlin, S. (1997) Prediction of complete gene structures in human genomic DNA. J. Mol. Biol. 268, 78-94.
6. National Center for Biotechnology Information (NCBI)[Internet]. Bethesda (MD): National Library of Medicine (US), National Center for Biotechnology Information; [1988] – [cited 2017 Apr 06]. Available from: https://www.ncbi.nlm.nih.gov/



