# Yeast sequencing project — quality control

Bioinformatics coursework: quality-checking a *Saccharomyces cerevisiae* (yeast)
sequencing dataset as the first stage of a genome analysis project.

## What it does

- Downloads the yeast sequencing reads (`downloads.R`)
- Runs quality control with **Sequali**, producing per-read quality reports
  (`ERR1539001_filtered.fastq.gz.html` / `.json`)
- Documents the QC step and its findings in `sequali.qmd`

## Tools

R / Quarto and Sequali.

## Running it

Open `Week2_Yeast_Project_ab.Rproj` in RStudio and render `sequali.qmd`.

Part of the Genomics & Transcriptomics microcredential (Langara College).
