# Data Directory

This directory contains Xarray datasets used for internal project testing and modeling of bridge grillage structures.

## Purpose

- Store sample datasets for testing analysis functions
- Hold intermediate computation results
- Maintain example grillage configurations

## Data Format

Data files should be in NetCDF or Zarr format, which are native to Xarray and provide efficient storage for multi-dimensional arrays.

## Example Dataset Structure

```
data/
├── sample_grillage_2d.nc      # 2D grillage model
├── sample_grillage_3d.nc      # 3D grillage model
├── load_patterns/             # Various loading scenarios
└── results/                   # Computed results
```

## Note

Large data files should not be committed to version control. Add them to `.gitignore` if necessary.
