# Astrophysics Research Projects

**Danessa Ruff**  
Michigan State University | Astrophysics

This repository contains three astrophysics projects I developed as extensions of my AST 208 coursework at Michigan State University. Each project started with observational data and methods introduced in class, which I used as a starting point for further analysis in Python.

The projects cover exoplanet transits, CCD image processing, and stellar motions in a globular cluster. My goal was to explore the data beyond the original assignments and gain more experience with astronomical data analysis, uncertainty, and computational methods.

## Projects

### 1. Exoplanet Transit and Orbital Analysis

**Dataset:** TESS light-curve observations

I analyzed repeated transit signals in a TESS light curve to estimate the orbital period, transit depth, duration, and radius of a possible exoplanet. I also used Monte Carlo sampling to estimate uncertainties and numerical integration to model the orbital motion.

The analysis gave an orbital period of approximately 4.72 days and an estimated planetary radius of 1.42 ± 0.05 Jupiter radii. These results are consistent with a close-in giant planet candidate, although the light curve alone cannot confirm its planetary nature.

### 2. CCD Calibration and Photometry of Messier 1

**Dataset:** Skynet Robotic Telescope Network, PROMPT 5 telescope

For this project, I worked with B, V, and r-band CCD images of Messier 1 (the Crab Nebula). I calibrated the images, created a three-color composite, and measured the flux of a selected star using aperture photometry.

I compared measurements from the raw and calibrated images and calculated instrumental B−V and V−r color indices. This allowed me to examine how image calibration affects photometric measurements.

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
- Astronomical image processing and aperture photometry
- Statistical analysis and uncertainty estimation
- Orbital calculations and numerical integration
- Gaia astrometry and stellar proper motions

## Project Background

All three projects build on material from AST 208 at Michigan State University, taught by Dr. Joey Rodriguez. The datasets were provided through coursework, while the additional analyses were developed independently.

Each notebook includes the methods, calculations, results, limitations, and acknowledgments for its respective project.
