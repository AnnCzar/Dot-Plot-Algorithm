# Pairwise Sequence Alignment: Dot Plot Algorithm

## Introduction

This program visually compares pairs of protein-coding sequences (single-letter amino acid codes) and DNA sequences (nucleotide codes) using the dot plot algorithm. The program allows sequence input in multiple ways, generates dot plot matrices, filters results, and visualizes the output graphically.

## Features

1. **Sequence Input**:
    - From a FASTA file.
    - Using an ID from Uniprot (programmatic access to Uniprot to retrieve sequences).

2. **Dot Plot Matrix Generation**:
    - Creating a dot plot matrix as a 2-dimensional array.

3. **Dot Plot Matrix Filtering**:
    - Filtering the matrix using specified parameters: window size and filter threshold.

4. **Dot Plot Visualization**:
    - Displaying the filtered dot plot matrix graphically with annotations (plot titles and axes, scale, legend).

5. **Saving Results**:
    - Saving the generated matrix to a graphical file with filtering parameters.
