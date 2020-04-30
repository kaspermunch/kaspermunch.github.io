---
layout: page
title: Software
---

## Tools for Jupyter on a SLURM cluster

[slurm-jupyter](https://github.com/kaspermunch/slurm-jupyter) lets you run a jupyter notebook in your browser from a compute node on the cluster. This way your analysis runs on the file system where your data is, and you can keep data, code and documentation in one place. slurm_jupyter is a script that starts and connects to a jupyter server on compute note and forwards the web display to your local machine. It only works using the Chrome browser.

[slurm-jupyter-run](https://github.com/kaspermunch/slurm-jupyter-run) is a command line tool, which lets you execute Jupyter notebooks on a SLURM cluster. Handy for notebooks that take a long time to run. It also makes it easy to run the same notebook with different parameter settings in an orderly way.

## SAP – Statistical Assignment Package
<p><span class="image right"><img src="images/sap.png" alt="" /></span>The assignment of DNA from organic material to species or taxonomic groups is integral to a number of scientific disciplines. Metagenomics is an approach particularly suitable for viruses and bacterial species, which have a relatively small genome. The approach can be used to characterize environments according to their genetic fingerprint. Even without taking genomic approaches, however, DNA sequencing of selected markers from environmental samples may provide ecological information or identify relevant species such as human pathogens. A related field where unknown specimens are identified based on Cytochrome Oxidase I (COI) has become known as DNA Barcoding. SAP is a tool answer the central question in these fields: what taxonomic group does an unknown organism represented by a DNA sequence belong to? SAP uses a Bayesian approach to calculate a probability distribution over all taxa represented in a sequence database. The probability of assignment to each taxa serves as a measure of confidence in the assignment.</p> 

SAP is available as both command line too and web service at [http://services.birc.au.dk/sap].

