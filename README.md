# hpc-ml: Machine-learning Singularity images for UA HPC
The recipes in this repository are designed for the University of Arizona High Performance Computing systems.
They build Singularity images that include common machine learning libraries including scikit-learn, tensorflow, keras, torch, as well as the Nvidia CUDNN.

## Usage

This GitHub repository is connected to Singularity Hub (https://singularity-hub.org/).
Please see their documentation on [interacting with Singularity images from Singularity Hub](https://singularityhub.github.io/singularityhub-docs/docs/interact).
Note that there are [hard limits on how many times a container can be pulled from Singularity Hub each week](https://singularityhub.github.io/singularityhub-docs/docs/regulatory/limits), so please make sure that you always ``singularity pull`` to get a local copy, for example:
```
singularity pull shub://vikasy95/hpc-ml:centos7-python37
```
That will download a Singularity image named `hpc-ml_centos7-python37.sif` that you can then use with other Singularity commands.
