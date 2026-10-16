# KELP — NASA PACE OCI Ocean Color Analysis

Jupyter notebook exploring NASA PACE OCI satellite data across processing levels (L1A → L3) using `earthaccess` and `xarray`.

Covers the Mid-Atlantic Bight (May 2024):
- **L1A/L1B** — raw and calibrated top-of-atmosphere reflectance
- **L2 AOP** — apparent optical properties (remote sensing reflectance Rrs)
- **L3M** — gridded monthly/daily Rrs and chlorophyll-a concentration

## Requirements

```bash
pip install earthaccess xarray h5netcdf cartopy matplotlib numpy pandas
```

NASA Earthdata login required (free at [urs.earthdata.nasa.gov](https://urs.earthdata.nasa.gov)).
