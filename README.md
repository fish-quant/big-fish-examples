# Big-FISH examples

[![License](https://img.shields.io/badge/license-BSD%203--Clause-green)](https://github.com/fish-quant/big-fish/blob/master/LICENSE)
[![Python version](https://img.shields.io/pypi/pyversions/big-fish.svg)](https://pypi.python.org/pypi/big-fish/)

**Big-FISH-examples** is a repository where we provide images, Jupyter notebooks and Python scripts to illustrate how to use the different workflows available in [Big-FISH](https://github.com/fish-quant/big-fish).

| smFISH image and its coordinates representation |
| ------------- |
| ![](images/plot_cell.png "Nucleus in blue, mRNAs in red, foci in orange and transcription sites in green") |

## Local installation

To avoid dependency conflicts, we recommend the the use of a dedicated [virtual](https://docs.python.org/3.6/library/venv.html) or [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) environment.  In a terminal run the command:

```bash
conda create -n bigfish_env python=X.Y
```

With X.Y a valid Python version greater or equal than 3.6. Note that Big-FISH is tested only for Python 3.6, 3.7, 3.8 and 3.9.

To run these notebooks, you will need to clone this repository:

```bash
git clone git@github.com:fish-quant/big-fish-examples.git
```

Activate your environment and install Big-FISH and Jupyter notebook dependencies inside:

```bash
source activate bigfish_env
cd big-fish-examples
pip install .
```

Then launch the notebooks:

```bash
jupyter notebook
```

## Binder

You can run this examples on mybinder.org without the need for a local Python installation

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fish-quant/fq-imjoy/binder?urlpath=git-pull%3Frepo%3Dhttps%253A%252F%252Fgithub.com%252Ffish-quant%252Fbig-fish-examples%26urlpath%3Dtree%252Fbig-fish-examples%252Fnotebooks%26branch%3Dmaster)
