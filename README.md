🧬 RNA-Seq Pipeline: FASTQ to Counts (Bash Workflow) 
This project involves building a complete RNA-Seq preprocessing pipeline using Bash scripting to automate the transformation of raw sequencing data (.fastq) into gene-level expression counts. The workflow integrates widely used bioinformatics tools—FastQC, Trimmomatic, HISAT2, and featureCounts—to carry out essential steps such as quality control, read trimming, genome alignment, and quantification.
The pipeline is modular, reproducible, and designed for easy execution on Linux-based systems. It provides a foundational understanding of how RNA-Seq data is processed in real-world bioinformatics applications and can be extended for downstream analyses like differential expression.

📂 Pipeline Overview
Tools used:
FastQC – Quality control of raw and trimmed reads
Trimmomatic – Trimming low-quality bases
HISAT2 – Aligning reads to the reference genome
featureCounts – Counting reads aligned to genomic features

🧪 Steps Implemented
Quality Check: FastQC on raw FASTQ files
Trimming: Trimmomatic for quality filtering
Alignment: HISAT2 for aligning reads
Quantification: featureCounts for gene-level counting

📁 Files Included
RNASeqpipeline.sh – Bash script to automate the workflow
output.html – Example report generated from FastQC or summary

📊 View Results 
1. https://github.com/Aishwary099/RNA-Seq-Workflow-From-FASTQ-to-Gene-Counts-Using-Bash/blob/main/demo_fastqc.html
2. https://github.com/Aishwary099/RNA-Seq-Workflow-From-FASTQ-to-Gene-Counts-Using-Bash/blob/main/demo_trimmed_fastqc.html


