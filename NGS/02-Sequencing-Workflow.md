# Sequencing Workflow

## 1. Raw Data

Sequencing instruments generate raw reads in FASTQ format.

## 2. Quality Control (QC)

Quality Control is performed to evaluate sequencing quality, remove low-quality reads, and detect contamination.

## 3. Genome Assembly

If no reference genome is available, sequencing reads are assembled into longer DNA sequences (contigs).

## 4. Genome Alignment

If a reference genome is available, sequencing reads are aligned to the reference genome.

## 5. Variant Calling

After alignment, genetic variants such as SNPs and insertions/deletions (Indels) are identified for downstream analysis.

## Summary

Raw Data → Quality Control → Assembly or Alignment → Variant Calling → Biological Interpretation
