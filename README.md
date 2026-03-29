# Interpolation-of-growth-references

This repository provides a systematic approach to transforming standard, periodic **LMS (Lambda-Mu-Sigma)** growth reference values into continuous **daily** values. 

Most official growth references (such as WHO) provide LMS parameters at monthly or yearly intervals. Most clinical and research applications require the LMS values in more detail (e.g. daily). This project fills that gap by providing the interpolation scripts and the resulting datasets. Cubic interpolation was used as described for the STATA plugin written by Vidmar et al.: [https://dx.doi.org/10.1177/1536867x1301300211.](https://dx.doi.org/10.1177/1536867x1301300211.)

---

## Project Overview

* **data/raw:** Publicly available LMS tables sourced from publications or official websites. The LMS values of the Braegger et al. references were kindly provided by pädiatrie schweiz.
* **R-and-qmd-scripts** .qmd script for data processing and documentation of the code.
* **data/processed/Interpolated-growth-references:** This folder contains the interpolated LMS values for the various growth references with daily interval LMS values.

## ⚖️ License & Data Attribution

> [!IMPORTANT]
> **Data Usage & Credits:** The interpolated data provided in this repository is derived from publicly available growth references. The original LMS values remain the intellectual property of their respective creators and are subject to their original licensing terms. In particular, rhe LMS files of the Braegger et al. references are owned by pädiatrie schweiz and subject to their original licensing terms. Please ensure you cite the original sources if using this data in a publication.
