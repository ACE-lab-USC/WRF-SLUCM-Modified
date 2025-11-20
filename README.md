# WRF–SLUCM LCZ_LA Modified Code and Parameter Tables

This repository provides the modified WRF source files and urban parameter table
used in **Quantifying Urban Morphology-Induced Uncertainty in Urban Meteorology and Heat Stress Simulations in Southern California**, where we develop an
LCZ-based urban morphology dataset for the Los Angeles region (LCZ_LA) and modified the code to output the intermediate variables.

The code in this repository is intended to make the model configuration
reproducible for reviewers and readers.

---

## 1. WRF version and physics configuration

- **WRF version:** 4.6.1  
- **Urban canopy model:** Single-Layer Urban Canopy Model (SLUCM)  

---

## 2. Contents of this repository

All files in this repository should replace the files with the same names in a
clean WRF v4.6.1 source tree.

- `Registry.EM_COMMON`  
- `URBPARM_LCZ.TBL`  
- `module_first_rk_step_part1.F`  
- `module_physics_init.F`  
- `module_sf_clm.F`  
- `module_sf_noahdrv.F`  
- `module_sf_noahmpdrv.F`  
- `module_sf_urban.F`  
- `module_surface_driver.F`  
- `start_em.F`  

---

## 3. How to use these files

From this repository, copy all files into the corresponding WRF directories, overwriting the existing files with the same names.
