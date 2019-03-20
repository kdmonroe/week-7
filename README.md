# Week 7<br>Analyzing and Visualizing Large Datasets

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Spring-2019/week-6/master?filepath=lecture-7.ipynb)

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

## New Packages

- [dask](http://docs.dask.org/en/latest/)
- [datashader](http://datashader.org/index.html)

## Useful Links and Reference Materials

- [pyViz Large Data Tutorial](http://pyviz.org/tutorial/10_Working_with_Large_Datasets.html)
- [Datashader User Guide](https://www.w3schools.com/html/html_intro.asp)
- [Datashader Use Cases](http://datashader.org/topics/index.html)
