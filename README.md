# Comparative Analysis of Insulin Protein Sequences Across Species Using Biopython

## Project Overview

This project compares insulin protein sequences from a few selected species using Biopython. The aim is to see how similar these sequences are and to understand how strongly insulin is conserved across species.

## Research Question

How similar are insulin protein sequences across selected species, and what does this suggest about the conservation of insulin?

## Dataset

This project uses insulin protein FASTA sequences from four species:

- Human
- Mouse
- Cow
- Zebrafish

The sequences were obtained from UniProt.

## Methods

- Uploaded and read FASTA files using Biopython
- Extracted sequence details and sequence length
- Calculated basic protein properties such as molecular weight, aromaticity, instability index, and isoelectric point
- Compared each sequence with human insulin using pairwise alignment
- Visualised sequence similarity across species using a bar chart

## Results

- Insulin appeared to be highly conserved across the selected species, especially among the mammalian ones.
- Human, mouse, and cow insulin sequences were more similar to each other than to zebrafish insulin.
- The sequence lengths were also fairly close across species, ranging from 105 to 110 amino acids.
- Basic protein properties were also fairly similar across species, although some differences were still present.
- Zebrafish showed the lowest similarity to human insulin in this comparison.

## Concepts Learned

- **FASTA file**: A simple text format used to store biological sequences.
- **Sequence parsing**: Reading biological sequence data from a file so it can be analysed in Python.
- **Sequence conservation**: When a sequence stays similar across different species, suggesting an important biological role.
- **Pairwise alignment**: A method used to compare two sequences and measure how similar they are.
- **Percent similarity**: A simple way to show how closely one sequence matches another.

## Tools Used

- Python
- Biopython
- Pandas
- Matplotlib
- Google Colab

## Files

- `insulin_sequence_comparison_biopython.ipynb` — main notebook containing the full analysis
- FASTA files for human, mouse, cow, and zebrafish insulin sequences

## Conclusion

This project helped me understand how biological sequence data can be analysed in Python using Biopython, and how comparing sequences can reveal how strongly a protein is preserved across species.

