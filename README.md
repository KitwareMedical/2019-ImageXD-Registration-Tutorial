# 2019-ImageXD-Registration-Tutorial

## Super Quickstart

:[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/KitwareMedical/2019-ImageXD-Registration-Tutorial/master)


## Quickstart

```sh
git clone https://github.com/KitwareMedical/2019-ImageXD-Registration-Tutorial
cd 2019-ImageXD-Registration-Tutorial
pip3 install --upgrade --upgrade-strategy eager -r requirements.txt
jupyter notebook
```

## Format

The tutorial consists of lecture segments followed by hands-on
exercises.  We *strongly encourage* you to bring a laptop with all
required packages installed in order to fully participate.

## Software required

- **Python**

  If you are new to Python, please install the
  [Anaconda distribution](https://www.continuum.io/downloads) for
  **Python version 3** (available on OSX, Linux, and Windows).
  Everyone else, feel free to use your favorite distribution, but
  please ensure the requirements below are met:

  - `python` >= 3.6
  - `numpy` >= 1.12
  - `scipy` >= 1.0
  - `matplotlib` >= 2.1
  - `scikit-image` >= 0.15
  - `itk` >= 5.0.1
  - `itkwidgets` == 0.18

- **ITK**

  ITK is an open-source toolkit for multidimensional image analysis.
  If you are using Anaconda, it is easy to install ITK using the
  [conda-forge](https://conda-forge.org/) repository, through the
  following command:

  `$ pip3 install --upgrade --upgrade-strategy eager itk`

- **Jupyter**

  The lecture material includes Jupyter notebooks.  Please follow the
  [Jupyter installation instructions](http://jupyter.readthedocs.io/en/latest/install.html),
  and ensure you have version 4 or later:

  ```bash
  $ jupyter --version
  4.4.0
  ```

  Please also activate Jupyter Widgets:

  ```
  pip install -q ipywidgets
  jupyter nbextension enable --py --sys-prefix widgetsnbextension
  ```

## Download lecture material

1. [Install Git](https://git-scm.com/downloads)
2. Clone the repository at [https://github.com/KitwareMedical/2019-ImageXD-Registration-Tutorial](https://github.com/KitwareMedical/2019-ImageXD-Registration-Tutorial)

We may make editorial corrections to the material until the day before
the workshop, so please execute `git pull` to update.

## Install into an environment

Optionally, create a new conda environment or virtual environment.

Then, install the packages:

  `$ pip3 install --upgrade --pre --upgrade-strategy eager -r requirements.txt`

**If you do not have a working setup, please contact the instructors.**
