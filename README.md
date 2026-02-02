
## Overview
This project implements a bioinformatics pipeline to identify differential Transcription Factor (TF) occupancy from ATAC-seq data. While standard ATAC-seq analysis identifies open chromatin regions (peaks), this pipeline utilizes **TF Footprinting** to pinpoint specific regulatory protein binding sites within those regions.


1. **Preprocessing:** Tn5 shift correction and signal normalization.
2. **Footprinting:** Calculation of footprint scores across open chromatin.
3. **Motif Matching:** Integrating JASPAR/HOCOMOCO motifs to identify candidate TFs.
4. **Differential Analysis:** Statistical comparison of TF binding between conditions (e.g., Control vs. Treated).

## Tech Stack
- **Languages:** Python, Bash
- **Bioinformatics:** TOBIAS, BEDTools, Samtools
- **Data Science:** Pandas, Scipy, Matplotlib/Seaborn

## Repository Structure
- `scripts/`: Python scripts for data parsing and enrichment analysis.
- `notebooks/`: Exploratory Data Analysis and visualization of TF profiles.
- `data/`: Sample metadata and BED files (BAM files ignored via .gitignore).

# TF-Footprint-Analysis
Identify Transcription Factor Occupancy in ATAC-seq Data 
