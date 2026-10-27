# Astrophysics Research Projects

**Danessa Ruff**  
Michigan State University | Astrophysics

This repository contains three projects I developed independently from work I began in AST 208 at Michigan State University. Using datasets introduced in class, I expanded the original assignments to explore additional questions and methods in Python.

The projects focus on exoplanet transits, CCD photometry, and stellar kinematics. Each gave me an opportunity to work with different types of astronomical data and examine how measurement uncertainty, data selection, and modeling assumptions affect the results.

## Projects

### 1. Exoplanet Transit and Orbital Analysis

**Dataset:** TESS light-curve observations

I analyzed repeated transit signals in a TESS light curve to estimate the orbital period, transit depth, duration, and radius of a possible exoplanet. I also used Monte Carlo sampling to estimate uncertainties and numerical integration to model the orbital motion.

I measured an orbital period of approximately 4.72 days and estimated a planetary radius of 1.42 ± 0.05 Jupiter radii. These measurements are consistent with a close-in giant planet candidate, although the light curve alone cannot confirm that the object is a planet.

[View Exoplanet notebook](PASTE-EXOPLANET-URL-HERE)

### 2. CCD Calibration and Photometry of Messier 1

**Dataset:** Skynet Robotic Telescope Network, PROMPT 5 telescope

I worked with B, V, and r-band CCD images of Messier 1 (the Crab Nebula). I calibrated the images, created a three-color composite, and measured the flux of a selected star using aperture photometry.

I compared measurements from the raw and calibrated images and calculated instrumental B−V and V−r color indices to examine how CCD calibration affects photometric measurements.

[View Messier 1 notebook](M1-CCD-Photometry.ipynb)

### 3. Stellar Kinematics of M4

**Dataset:** Gaia Data Release 2

I used Gaia proper-motion measurements to investigate how stellar motions vary with distance from the center of the globular cluster M4.

I calculated proper-motion dispersion in radial bins, applied approximate corrections for measurement uncertainties, and compared the results using different membership and data-quality selections.

The estimated dispersion generally decreased farther from the cluster center, although the results depend on the membership criteria and measurement uncertainties.

[View M4 notebook](m4-stellar-kinematics.ipynb)

## Tools and Methods

- Python and Jupyter Notebook
- NumPy, Pandas, Matplotlib, and Astropy
- CCD calibration and aperture photometry
- Statistical analysis and uncertainty estimation
- Orbital calculations and numerical integration
- Gaia astrometry and proper-motion analysis

## Project Background

These projects build on AST 208 coursework at Michigan State University, taught by Dr. Joey Rodriguez. The datasets and introductory methods were provided through the course, while the additional analyses were developed independently.

Each notebook documents the methods, results, limitations, and acknowledgments.
