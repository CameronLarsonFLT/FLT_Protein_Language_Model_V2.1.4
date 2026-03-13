# FLT Protein Language Model V2.1.4

This project implements a custom protein language model for de novo protein design from curated Pfam- or accession-derived sequence families. The workflow uses a user-defined Pfam ID or protein family input to build a focused training corpus, allowing generation within a specific structural and functional sequence space rather than from a broad mixed database. Sequence output can be tuned during sampling with temperature, where lower values produce more conservative, family-like designs and higher values increase diversity and exploration at the cost of plausibility. The pipeline also supports novelty filtering and regression-based scoring to help identify candidate variants for downstream evaluation. It is designed for rapid, hypothesis-driven protein engineering in Google Colab on CPU or GPU.

## Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/CameronLarsonFLT/FLT_Protein_Language_Model_V2.1.4/blob/main/Protein_Language_Model_V2.1.4.ipynb
)

## Example Designs

<p align="center">
  <img src="https://raw.githubusercontent.com/CameronLarsonFLT/FLT_Protein_Language_Model_V2.1.4/main/Immunoglobulins.gif" width="380">
  <img src="https://raw.githubusercontent.com/CameronLarsonFLT/FLT_Protein_Language_Model_V2.1.4/main/FP_Designed.gif" width="240">
  <img src="https://raw.githubusercontent.com/CameronLarsonFLT/FLT_Protein_Language_Model_V2.1.4/main/GvpA.gif" width="253">
</p>
