# Genome Graph Generation
[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/685)
This container has the software needed for a workflow that creates a genome graph using cactus (except bwa and samtools - those are included because they seem to always be required at some point).
* [bwa](http://bio-bwa.sourceforge.net/bwa.shtml), Burrows-Wheeler Alignment Tool - used for aligning short reads to a fasta reference
* [samtools](http://www.htslib.org/doc/samtools.html), Utilities for the Sequence Alignment/Map (SAM) format - used for indexing reference fasta files and bam files
* [progressivemauve](http://darlinglab.org/mauve/user-guide/progressivemauve.html) - algorithm for multiple sequence alignment
* [biopython](https://biopython.org) - python utilities for biological data; used here for converting alignment file formats via AlignIO
* [RAxML](https://cme.h-its.org/exelixis/web/software/raxml/index.html) - builds maximum likelihood phylogenetic trees from multiple sequence alignments
* [repeatmasker](http://www.repeatmasker.org/) - screens DNA sequences for interspersed repeats and low complexity DNA sequences
* [repeatmodeler](http://www.repeatmasker.org/RepeatModeler/) - de-novo repeat family identification and modeling package
* [cactus](https://github.com/ComparativeGenomicsToolkit/cactus) - reference-free whole-genome multiple alignment program
* [toil](http://toil.ucsc-cgl.org/) - pipeline management system that cactus uses
