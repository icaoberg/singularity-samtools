# singularity-samtools
![Release](https://img.shields.io/badge/release-v1.10-green.svg)
[![Build Status](https://travis-ci.org/icaoberg/singularity-samtools.svg?branch=master)](https://travis-ci.org/icaoberg/singularity-samtools)
[![GitHub issues](https://img.shields.io/github/issues/icaoberg/singularity-samtools.svg)](https://github.com/icaoberg/singularity-samtools/issues)
[![GitHub forks](https://img.shields.io/github/forks/icaoberg/singularity-samtools.svg)](https://github.com/icaoberg/singularity-samtools/network)
[![GitHub stars](https://img.shields.io/github/stars/icaoberg/singularity-samtools.svg)](https://github.com/icaoberg/singularity-samtools/stargazers)
[![GitHub license](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://www.gnu.org/licenses/quick-guide-gplv3.en.html)

samtools is a suite of programs for interacting with high-throughput sequencing data.

## Pre-requisites

* [Singularity v3.5.+](https://sylabs.io/docs/).

## Building the image using the recipe

### To build the image locally
Run the script `build.sh` to build image locally.

```
bash ./build.sh
```

### To build the image remotely
Run the script `rbuild.sh` to build image remotely.

```
bash ./rbuild.sh
```

You will need to edit the script above to match your account on [SyLabs.io](https://sylabs.io/).

## Disclaimer

I am nothing but a humble programmer creating the container for this wonderful app.

---
Copyright © 2020 [icaoberg](http://www.andrew.cmu.edu/~icaoberg) at the [Pittsburgh Supercomputing Center](http://www.psc.edu) in [Carnegie Mellon University](http://www.cmu.edu)
