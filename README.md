# Catalog of Filaments over 0.4 < z < 4.0 in COSMOS2020 (Ejercito et al. 2025)

## Overview of the Catalog

This repository contains images of intergalactic filaments identified over 0.4 < z < 4.0 in COSMOS2020 [(Weaver et al. 2022)](https://ui.adsabs.harvard.edu/abs/2022ApJS..258...11W/abstract) with DisPerSE [(Sousbie 2011)](https://ui.adsabs.harvard.edu/abs/2011MNRAS.414..350S/abstract). Filaments were identified in 113 redshift slices using density maps measured by [Taamoli et al. (2024)](https://ui.adsabs.harvard.edu/abs/2024ApJ...966...18T/abstract). We direct the reader to that work for details on how the density maps were measured. DisPerSE was run on these maps by [Ejercito et al. (2025)](link TBD) and details in work can be found regarding the parameters used to run DisPerSE. 

## Description of the Data Products

The catalog consists of 113 images, one for each redshift slice. They can be found in the _filament\_fits_ directory. They are stored in the Flexible Image Transport System (FITS) format. Each image has a pixel scale of ~0.01 deg / pixel.

The naming convention for each image is as follows: fil_z_c1_aX.XX.S003.BRK.ASMB.fits, where z is the mean redshift of a given slice and X.XX is a number larger than unity and represents the value passed to the --assemble command in DisPerSE. Details can be found in Sec. 2.2 in [Ejercito et al. (2025)](link TBD). 

## Citing the Catalog

If you use this catalog in your research, please cite [Ejercito et al. (2025)](link TBD). 
