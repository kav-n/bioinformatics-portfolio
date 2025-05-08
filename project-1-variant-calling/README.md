# Project 1: Germline Variant Calling and Annotation (WGS)

## Project Overview
This project demonstrates a simplified variant calling pipeline using whole genome sequencing (WGS) data. It replicates the key steps used in NHS Genomic Laboratory Hubs (GLHs) to detect and interpret germline variants that may be clinically significant.

## Objectives
- Align raw sequencing reads to a reference genome
- Call germline variants using GATK HaplotypeCaller
- Annotate variants using Ensembl VEP
- Explore and interpret variants for potential clinical relevance

## Tools & Technologies
- `bwa` for alignment
- `samtools` for BAM/SAM processing
- `gatk` for variant calling
- `vep` for annotation
- `conda` for reproducibility

### 📦 Dataset Used

For testing and demonstration purposes, this pipeline uses paired-end whole-genome sequencing (WGS) data from the **1000 Genomes Project**.

- **Sample ID**: HG00096  
- **ENA Accession**: [ERR000589](https://www.ebi.ac.uk/ena/browser/view/ERR000589)  
- **Source**: European Nucleotide Archive (ENA)  
- **Data Type**: Illumina HiSeq paired-end FASTQ files  
- **File Size**: ~150 MB per file (compressed)

#### 🔗 Download Links:
- [ERR000589_1.fastq.gz (R1)](https://ftp.sra.ebi.ac.uk/vol1/fastq/ERR000/ERR000589/ERR000589_1.fastq.gz)
- [ERR000589_2.fastq.gz (R2)](https://ftp.sra.ebi.ac.uk/vol1/fastq/ERR000/ERR000589/ERR000589_2.fastq.gz)

This dataset provides real human sequencing data while being small enough for quick testing, development, and demonstration of the variant calling pipeline. It replaces the previously intended Genome in a Bottle (GIAB) HG002 dataset for easier accessibility and faster processing during development.


## Project Structure
project-1-variant-calling/ ├── data/ ├── scripts/ ├── results/ ├── reports/ ├── environment.yml ├── README.md

## Output
- Raw VCF and annotated variants
- Short clinical-style interpretation
- Summary plots or tables (optional)

## NHS Relevance
This pipeline mimics workflows used in NHS Genomic Medicine Services to process germline WGS data for rare disease diagnosis and hereditary cancer screening.

## Getting Started
Full setup and run instructions coming soon.
