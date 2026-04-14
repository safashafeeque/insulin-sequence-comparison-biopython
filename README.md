# Comparative Analysis of Insulin Protein Sequences Across Species Using Biopython

## Project Overview

This project compares insulin protein sequences across selected species using Biopython. The aim is to explore sequence similarity and basic protein properties in order to understand how strongly insulin is conserved across species.

## Research Question

How similar are insulin protein sequences across selected species, and what does this suggest about the biological conservation of insulin?

## Dataset

This project uses protein FASTA sequences for insulin from four species:
- Human
- Mouse
- Cow
- Zebrafish

The sequences were obtained from UniProt.

## Methods

- Parsed protein FASTA files using Biopython
- Extracted sequence length and metadata
- Calculated basic protein properties such as molecular weight, aromaticity, instability index, and isoelectric point
- Compared each sequence with human insulin using pairwise alignment
- Visualised sequence similarity across species

## Results

- Insulin showed a high degree of conservation across species, especially among mammals
- Human, mouse, and cow insulin sequences were more similar to each other than to zebrafish insulin
- Basic protein properties were broadly similar across species, supporting the conserved biological role of insulin
- This project introduced core bioinformatics concepts including FASTA parsing, protein analysis, and sequence comparison

## Tools Used

- Python
- Biopython
- pandas
- matplotlib
- Google Colab

## Files

- `insulin_sequence_comparison_biopython.ipynb` — main notebook containing the full analysis
- FASTA files for human, mouse, cow, and zebrafish insulin sequences

## Conclusion

This project helped me understand how biological sequence data can be analysed using Python and Biopython, and how comparative sequence analysis can reveal conserved molecular features across species.
