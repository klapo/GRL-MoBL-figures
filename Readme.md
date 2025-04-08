# Overview

This repository contains the notebooks demonstrating how to recreate the figures for the GRL manuscript on using mrCOSTS for scale aware evaluation of the mountain boundary layer. The data used are included. These data were altered slightly from their original versions for ease of use (i.e., subsets, converting to xarray friendly formats, temporal averaging).

## Requirements

- numpy
- scipy
- matplotlib
- seaborn
- xarray
- pandas
- pydmd newer than March 2025
- netcdf4
- h5netcdf

You might have to do some trouble shooting. This repository is provided as a demonstration, not a tutorial.

## Set up

You will need to populate the `mrCOSTS fit` subdirectory with the model fits by first running the fit notebook. The fits themselves are not included do to their size. mrCOSTS is explicitly not for dimensionality reduction!
