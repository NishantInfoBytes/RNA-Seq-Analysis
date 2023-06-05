## RNA-Seq-Analysis
Using high-throughput sequencing techniques to reveal transcriptomics dynamics.

Overview:
This repository contains a pipeline for processing RNA-Seq data. 
The pipeline includes several steps, such as quality control, trimming, indexing, mapping, alignment, and transcript quantification. 

[*1.Script for RNA-seq-single-end-data-processing*](https://github.com/shekharnishant/RNA-Seq-Analysis/blob/main/rna-seq-single-end-data.ipynb)

### On single-end data used following tools[script name: rna-seq-single-end-data.ipynb]
#### FastQC <- MultiQC <- Trimmomatic <- Indexing and a mapping/alignment with Bowtie2 <- Transcript quantifictaion with Featurecount.

### On paired-end data [script name: usage_example_cutadapt_star(1and2pass)_bedtools.ipynb]
#### Cutadapt(Trimmimg) <- Star(1-Pass Mode & 2-Pass Mode)[Aligning]  <- Bedtools(ReadCount)
