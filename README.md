# RNA-seq Metadata QC

Author: Annie Christie

## Purpose
This repository demonstrates a small RNA-seq sample metadata quality-control workflow.

## Project Structure
- `data/`: Contains sample metadata.
- `scripts/`: Contains the R quality-control script.

## How to Run
From the repository root, run:

`Rscript scripts/qc_check.R`

## Expected Result
The script checks required columns and duplicate sample identifiers, prints the metadata, and shows the number of samples in each condition.

## Data Policy
Raw sequencing data, private data, passwords, tokens, SSH keys, credentials, and large generated files must not be committed.