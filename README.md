# Chromosome structure network

## Description
This Google Colab Notebook is designed to constract a chromosome structure network (CSN) from bulk Hi-C data and calculat site-resolved (node-based) network properties of the CSN.

## Input format
The input data should be a tab-separated text file containing three columns: position 1, position 2, and their contact values. Each position represents the starting point of a segment. The resolution is defined within the corresponding Python module. Please refer to "exp_input.csv" as an example.

The example data is Hi-C result of gm12878 chromosme 21, sourced from Rao et al., 2014.

