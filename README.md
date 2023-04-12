
MolBloom-Paper-Repository

Welcome to the MolBloom-Paper repository! This repository contains the code and documentation for our research paper on comparing different implementations of Bloom filters with various hashing variations and their time analysis in comparison to traditional internet search methods in datasets. Work based on package molbloom: https://github.com/whitead/molbloom.git

Introduction

This research paper focuses on two main aspects:

Studying various implementations of Bloom filters with different hashing variations.
Time analysis comparisons between Bloom filters and traditional internet search methods in datasets.
The code in this repository is divided into two primary files for each respective aspect mentioned above.


Cite
@article{medina_bloom_2023,
	title = {Bloom filters for molecules},
	copyright = {arXiv.org perpetual, non-exclusive license},
	url = {https://arxiv.org/abs/2304.05386},
	doi = {10.48550/ARXIV.2304.05386},
	abstract = {Ultra-large chemical libraries are reaching 10s to 100s of billions of molecules. A challenge for these libraries is to efficiently check if a proposed molecule is present. Here we propose and study Bloom filters for testing if a molecule is present in a set using either string or fingerprint representations. Bloom filters are small enough to hold billions of molecules in just a few GB of memory and check membership in sub milliseconds. We found string representations can have a false positive rate below 1\% and require significantly less storage than using fingerprints. Canonical SMILES with Bloom filters with the simple FNV hashing function provide fast and accurate membership tests with small memory requirements. We provide a general implementation and specific filters for detecting if a molecule is purchasable, patented, or a natural product according to existing databases at https://github.com/whitead/molbloom},
	urldate = {2023-04-12},
	author = {Medina, Jorge and White, Andrew D},
	year = {2023},
	keywords = {Chemical Physics (physics.chem-ph), FOS: Physical sciences},
}
