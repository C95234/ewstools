# Tutorials
**A collection of iPython notebooks to demonstrate various applications of *ewstools*.**

To run these tutorials, [Jupyter notebook](https://jupyter.org/install) must be installed. Tutorial 1 is a prerequisite to all later tutorials.

### 1. Introduction to *ewstools* (tutorial_intro.ipynb)

- Initialise a TimeSeries object with your data
- Detrend your data using a specific filter and bandwidth
- Compute CSD-based early warning signals (EWS) over a rolling window
- Measure the trend of the EWS with Kendall tau values
- Visualise output

### 2. Spectral EWS (tutorial_spectral.ipynb)

- Compute and visualise changes in the power spectrum over a rolling window
- Compute spectral early warning signals as in [Bury et al. (2020) Royal Soc. Interface](https://royalsocietypublishing.org/doi/full/10.1098/rsif.2020.0482)

### 3. Deep learning classifiers for bifurcation prediction (tutorial_deep_learning.ipynb)

- Import a TensorFlow classifier and obtain its predictions on a section of time series data
- Compute predictions made from an ensemble of classifiers

### 5. Spatial EWS (tutorial_spatial.ipynb)

- Build a spatial weights matrix for a regular grid with `lattice_weights`
- Compute Moran's I and its permutation p-value at every time point with `SpatialEWS`
- Measure the trend of Moran's I with Kendall tau
- Tell critical slowing down apart from a strengthening spatial pattern with the trend-control recipe
