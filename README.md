<div align="center">
<img src="https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS/blob/main/images/LIFDlogo.png"></a>
<a href="https://www.cemac.leeds.ac.uk/">
  <img src="https://github.com/cemac/cemac_generic/blob/master/Images/cemac.png"></a>
  <br>
</div>

# Leeds Institute for Fluid Dynamics Machine Learning For Earth Sciences #

# Random Forests

[![GitHub release](https://img.shields.io/github/release/cemac/LIFD_RandomForests.svg)](https://github.com/cemac/LIFD_RandomForests/releases) [![GitHub top language](https://img.shields.io/github/languages/top/cemac/LIFD_RandomForests.svg)](https://github.com/cemac/LIFD_RandomForests) [![GitHub issues](https://img.shields.io/github/issues/cemac/LIFD_RandomForests.svg)](https://github.com/cemac/LIFD_RandomForests/issues) [![GitHub last commit](https://img.shields.io/github/last-commit/cemac/LIFD_RandomForests.svg)](https://github.com/cemac/LIFD_RandomForests/commits/master) [![GitHub All Releases](https://img.shields.io/github/downloads/cemac/LIFD_RandomForests/total.svg)](https://github.com/cemac/LIFD_RandomForests/releases) ![GitHub](https://img.shields.io/github/license/cemac/LIFD_RandomForests.svg)[![DOI](https://zenodo.org/badge/366734586.svg)](https://zenodo.org/badge/latestdoi/366734586)

[![LIFD_ENV_ML_NOTEBOOKS](https://github.com/cemac/LIFD_RandomForests/actions/workflows/python-package-conda-RF.yml/badge.svg)](https://github.com/cemac/LIFD_RandomForests/actions/workflows/python-package-conda-RF.yml)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cemac/LIFD_RandomForests/HEAD?labpath=RandomForests.ipynb)

This notebook explores Random Forests to find out what variables control leaf temperature.

## Recommended Background Reading

If you are unfamiliar with some of the concepts covered in this tutorial it's recommended to read through the background reading below either as you go through the notebook or beforehand.

* [Decision Tree Introductory Video](https://www.youtube.com/embed/kakLu2is3ds)
* [Random Forests Introductory Video](https://www.youtube.com/embed/v6VJ2RO66Ag)
* [Random Forest overview linked with python](https://towardsdatascience.com/an-implementation-and-explanation-of-the-random-forest-in-python-77bf308a9b76)

## Quick look

If you want a quick look at the contents inside the notebook before deciding to run it please view the [md file](https://github.com/cemac/LIFD_RandomForests/blob/main/RandomForests.md) generated (*note some HTML code not fully rendered*)


### Quick start

**Binder**

You can run this notebook on your personal laptop or via the [binder](https://mybinder.readthedocs.io/en/latest/index.html#what-is-binder) link above (please allow a few minutes for set up).

**Running Locally**

If you're already familiar with git, anaconda and virtual environments the environment you need to create is found in RF.yml and the code below to install activate and launch the notebook. The .yml file has been tested on the latest linux, macOS and windows operating systems.

```bash
git clone git@github.com:cemac/LIFD_RandomForests.git
cd LIFD_RandomForests
conda env create -f RF.yml
conda activate RF
jupyter-notebook
```

## Installation and Requirements

This notebook is designed to run on a laptop with no special hardware required therefore recommended to do a local installation as outlined in the repository [howtorun](https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS/howtorun.md) and [jupyter_notebooks](https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS/jupyter_notebooks.md) sections.


# Licence information #

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">LIFD_ENV_ML_NOTEBOOKS</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://cemac.leeds.ac.uk/" property="cc:attributionName" rel="cc:attributionURL">cemac</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

## Acknowledgements

Thanks to Chetan Deva for the basis of this tutorial. This tutorial is part of the [LIFD ENV ML NOTEBOOKS](https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS) please refer to for full acknowledgements.
