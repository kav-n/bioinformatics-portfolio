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

## Input Data
- Public dataset: NA12878 (Genome in a Bottle)
- Reference genome: GRCh38
- Download details in `data/README.md`

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
