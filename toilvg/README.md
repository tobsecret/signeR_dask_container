# Genome Graph Generation
[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/685)
This container just contains toil-vg, a cluster/cloud interface for running vg which is a tool for working with genome variation graphs. Important to note that this container does not actually include [vg](https://github.com/vgteam/vg) itself, which is a set of tools for working with genome variation graphs. 

Instead you run toil-vg, which can make use of appropriate containers which have vg and other necessary software.

* [toil](http://toil.ucsc-cgl.org/) - pipeline management system that toil-vg uses
* [toil-vg](https://github.com/vgteam/toil-vg) - distributed and cloud computing framework for vg
