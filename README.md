## RNA-Seq-Analysis
Using high-throughput sequencing techniques to reveal transcriptomics dynamics.

Overview:
This repository contains a pipeline for processing RNA-Seq data. 
The pipeline includes several steps, such as quality control, trimming, indexing, mapping, alignment, and transcript quantification. 

### On SIngle-end Data used these tools
#### FastQC <- MultiQC <- Trimmomatic <- Indexing and a mapping/alignment with Bowtie2 <- Transcript quantifictaion with Featurecount.

### On paired-end Data:
#### Cutadapt(Trimmimg) <- Star(1-Pass Mode & 2-Pass Mode)[Aligning]  <- Bedtools(ReadCount)
