# cds_hacking

[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/ocean-transport/cds_hacking/main)

## Installation

Create and activate the conda environment:

```shell
$ conda env create -f environment.yml -y
$ conda activate hack_3d_viz
```

Then enable the jupyterlab extensions with the supplied script:

```shell
$ ./postBuild
```

And off we go:
```shell
$ jupyter lab
```