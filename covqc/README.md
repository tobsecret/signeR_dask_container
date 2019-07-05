# Mutational signatures
[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/685)
This container has the software needed for my DNA sequencing data coverage and quality control workflow.
* [bwa](http://bio-bwa.sourceforge.net/bwa.shtml), Burrows-Wheeler Alignment Tool - used for aligning short reads to a fasta reference
* [samtools](http://www.htslib.org/doc/samtools.html), Utilities for the Sequence Alignment/Map (SAM) format - used for indexing reference fasta files and bam files
* [mosdepth](https://github.com/brentp/mosdepth), fast BAM/CRAM depth calculation for WGS, exome, or targeted sequencing - used to calculate read depth over the reference genome.
* [pandas](https://pandas.pydata.org/pandas-docs/stable/), dataframes and more in python - used for reading and transforming depth bed file from mosdepth
* [seaborn](https://seaborn.pydata.org/), statistical data visualization in python - used for making coverage plots
