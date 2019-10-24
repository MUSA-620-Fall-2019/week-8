# Week 8<br>Raster Datasets in the Wild

## Two Case Studies

- Using satellite imagery to detect changes in lake volume
- Detecting urban heat islands in Philadelphia

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Fall-2019/week-8/master?filepath=lecture-8.ipynb)

## Updating your local environment

There are a few new packages we'll need for web scraping this week so we'll need
to update your Python environment. The `environment.yml` in this repository
contains all of the necessary packages. To update your local environment:

**Step 1.** Download the `environment.yml` file in this repository to your computer.

**Important:** Make sure you download the **raw** version of the file from GitHub and that the file extension on your computer is `.yml`.

**Step 2.** From either the Anaconda Prompt (Windows) or Terminal app (MacOS):

```
conda env update --file environment.yml --name musa-620
```

where `musa-620` should be the same name of the environment you have been using.

## Reference

- [EarthML](earthml.pyviz.org)
- [The Disappearing Walker Lake](https://earthobservatory.nasa.gov/images/91921/disappearing-walker-lake)
- [The Aral Sea](https://earthobservatory.nasa.gov/world-of-change/aral_sea.php)
- [Lake Orumiyeh](https://earthobservatory.nasa.gov/images/76327/lake-orumiyeh-iran)
- [Urban Heat Islands](http://urbanspatialanalysis.com/urban-heat-islands-street-trees-in-philadelphia/)
- [EarthML Tutorial on Heat Island](http://earthml.pyviz.org/topics/Heat_and_Trees.html)
- [Slicing with xarray](http://xarray.pydata.org/en/stable/indexing.html)
- [Slicing in Python](https://www.w3schools.com/python/ref_func_slice.asp)
- [rio-toa: Top Of Atmosphere (TOA) calculations for Landsat 8](https://github.com/mapbox/rio-toa)
- [rioxarray](https://corteva.github.io/rioxarray/html/index.html)
- [Landsat data on Google Cloud Storage](https://cloud.google.com/storage/docs/public-datasets/landsat)
