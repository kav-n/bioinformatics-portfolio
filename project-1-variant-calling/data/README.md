# Data Folder

This folder contains input data required to run the variant calling pipeline.

## Contents

- **Paired-end FASTQ files**  
  Raw sequencing reads used as input for alignment (e.g., `ERR000589_1.fastq.gz`, `ERR000589_2.fastq.gz`).

- **Reference genome**  
  The reference FASTA file used for alignment and variant calling (e.g., `GRCh38.fa`) and its associated index files (`.fai`, `.dict`, BWA index files).

## Notes

- Large data files such as FASTQs and reference genomes should **not be committed to version control**. These files are listed in `.gitignore`.
- Download instructions and dataset details are documented in the main `README.md` file.
- Ensure filenames are clearly labeled (e.g., `_1` and `_2` for paired-end reads) for compatibility with the pipeline.
