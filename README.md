# Hyperparameter_tutorial
Tutorial that is used for the HDS-LEE course on hpyerparameter optimization.

The tutorial consists of two parts:
* Tutorial_Part1 is used for an introduction to the considered regression problem. Furthermore, it gives a very short introduction to Keras.
* Tutorial_Part2 uses Talos for machine-assisted hyperparameter optimization. There is a further notebook '*_solution' that contains the solution to the exercises in this notebook.

## Installation

Before using the notebooks, you need to install  talos, keras and all other dependencies. First, create a virtual environment (or conda environment) and activate it:

On macOS and Linux:
```bash
python3 -m venv env

source env/bin/activate
```
 
On Windows:
```bash
py -m venv env

.\env\Scripts\activate
```

Install all requirements 

```bash
pip install -r requirements.txt
```

## Running the notebooks

```bash
jupyter notebook
```

## Fallback solution (nothing works)

Alternatively, if nothing works, you can also run your Jupyter notebooks
in a live environment using Binder. Just click on the following link

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DLR-SC/Hyperparameter_tutorial/HEAD) 