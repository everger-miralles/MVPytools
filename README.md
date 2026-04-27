# MVPytools
This repository contains a complete Python toolbox designed to process high-resolution Moving Vessel Profiler (MVP) data. Originally developed for the FaSt-SWOT and BioSWOT-Med oceanographic campaigns, this suite of scripts transforms raw `.m1` instrument files into processed NetCDF datasets. 

- Fast-SWOT experiment, R/V SOCIB, April-May 2023 (Leg 1 & Leg 2), https://doi.org/10.20350/digitalCSIC/15276
- BioSWOT-Med experiment, R/V Atlante, April-May 2023, https://doi.org/10.13155/100060

The workflow integrates instrumental quality control, a fall-rate-dependent dynamic lag correction, specialized Locally Weighted Scatterplot Smoothing (LOESS) filtering, and a final offset calibration. 
The folder figures include the codes the reproduce the figures associated to the paper "A new open-source Python Toolbox for Oceanic Moving Vessel Profiler Data Processing" Verger-Miralles et al.

Author: Elisabet Verger-Miralles
