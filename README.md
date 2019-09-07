**[summary](#summary) | [contents](#contents) | [usage](#usage) | [running the notebooks](#running-the-notebooks) | [issues](#issues) | [citation](#citation) | [license](#license)**

# lbnl-2019-resistive-casing


[![Build Status](https://travis-ci.org/simpeg-research/lbnl-2019-resistive-casing.svg?branch=master)](https://travis-ci.org/simpeg-research/lbnl-2019-resistive-casing)
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/simpeg-research/lbnl-2019-resistive-casing/master?filepath=resistive-casing.ipynb)
[![License](https://img.shields.io/github/license/simpeg-research/lbnl-2019-resistive-casing.svg)](https://github.com/simpeg-research/lbnl-2019-resistive-casing/blob/master/LICENSE)
[![SimPEG](https://img.shields.io/badge/powered%20by-SimPEG-blue.svg)](http://simpeg.xyz)

## Summary

This notebook simulates a frequency domain EM experiment in which we have a current-dipole inside of a resistive casing. We plot the fields and fluxes and compute electric field-data on the surface and in a borehole. 

## Contents

There is one notebooks in this repository:

- [resistive-casing.ipynb](resistive-casing.ipynb)

## Usage

### online
You can run these notebooks online through mybinder by clicking on the badge below:

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/simpeg-research/lbnl-2019-resistive-casing/master?filepath=resistive-casing.ipynb)

### locally
To run the notebooks locally, you will need to have python installed,
preferably through [anaconda](https://www.anaconda.com/download/). Please download 
Python 3.7 or greater. 

Once you have downloaded and installed anaconda, you can then clone this repository. 
From a command line (if you are on windows, please use the anaconda terminal that came with the installation)
run

```
git clone https://github.com/simpeg-research/lbnl-2019-resistive-casing.git
```

Then `cd` into the `lbnl-2019-resistive-casing` directory:

```
cd lbnl-2019-resistive-casing
```

To setup your software environment, we recommend you use the provided conda environment

```
conda env create -f environment.yml
conda activate lbnl-resistive-casing
```

You can then launch Jupyter

```
jupyter notebook
```

Jupyter will then launch in your web-browser.

## Running the notebooks

Each cell of code can be run with `shift + enter` or you can run the entire notebook by selecting `cell`, `Run All` in the toolbar.

<img src="https://em.geosci.xyz/_images/run_all_cells.png" width=80% align="middle">

For more information on running Jupyter notebooks, see the [Jupyter Documentation](https://jupyter.readthedocs.io/en/latest/)

If you are new to Python, I highly recommend taking a look at:
- [A Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/)
- [The Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)

## Issues

Please [make an issue](https://github.com/simpeg-research/lbnl-2019-resistive-casing/issues) if you encounter any problems while trying to run the notebooks.

## Citation

If you build upon or use these examples in your work, please cite:

Heagy, L. J., & Oldenburg, D. W. (2018). Modeling electromagnetics on cylindrical meshes with applications to steel-cased wells. Computers & geosciences. [https://doi.org/10.1016/j.cageo.2018.11.010](https://doi.org/10.1016/j.cageo.2018.11.010)

```
@article{Heagy2018,
author = {Heagy, Lindsey J. and Oldenburg, Douglas W.},
doi = {10.1016/j.cageo.2018.11.010},
issn = {00983004},
journal = {Computers {\&} Geosciences},
month = {nov},
title = {{Modeling electromagnetics on cylindrical meshes with applications to steel-cased wells}},
url = {https://linkinghub.elsevier.com/retrieve/pii/S009830041830390X},
year = {2018}
}

```

The paper is also available on the ArXiv: [1804.07991](https://arxiv.org/abs/1804.07991).

## License
These notebooks are licensed under the [BSD 3](/LICENSE) which allows academic and commercial re-use and adaptation of this work.
