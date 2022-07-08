# Intro to Dashboard in Python

This repository provides a quick tour of packages useful to build dashboards in Python.


## Installation

The example notebook runs on Jupyter-on-NeSI.

To run it, you will need a kernel made out of the `Python/3.10.5` environment module:

```
module purge && module load JupyterLab
pip install -U pyviz_comms  # ensure Panel interactivity in notebooks
nesi-add-kernel python-3.10.5 Python/3.10.5-gimkl-2022a
```


## Getting started

The presentation will follow the [Dashboard Tour](dashboard_tour.ipynb) notebook.


## TODO

- provide an alternative conda environment or requirements.txt file
- add a self-contained example of panel + hvplot + xarray + datashader for geoscience, maybe use data from https://carpentries-lab.github.io/python-aos-lesson/
