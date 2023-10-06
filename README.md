# Relative Elevation Model (REM) Tutorial
> This is a forked repo form [DahnJ/REM-xarray](https://github.com/DahnJ/REM-xarray)


| Piura | Sullana |
| --- | --- |
| ![REM PIURA](data/rem_hillshade_piura.png) | ![REM SILLANA](data/rem_hillshade_sullana.png) |


# Relative Elevation Model 

Based on Creating a [relative elevation model](https://ngmdb.usgs.gov/Info/dmt/docs/DMT16_Coe.pdf) in Python using [xarray](https://xarray.pydata.org/) and [datashader](https://datashader.org/) by [Dahn Jahn](https://github.com/DahnJ)

# Results

### Piura
| Area of Interest | REM |
| --- | --- |
| ![AOI PIURA](data/aoi_piura.png) | ![REM PIURA](data/rem_map_piura.png) |

### Sullana
| Area of Interest | REM |
| --- | --- |
| ![AOI SULLANA](data/aoi_sullana.png) | ![REM SULLANA](data/rem_map_sullana.png) |

# Run locally

### Conda
```bash
conda env create -f environment.yaml
conda activate rem-tutorial
jupyter notebook
```

### venv
```bash
python -m venv rem-tutorial
source rem-tutorial/bin/activate
pip install -r requirements.txt
jupyter notebook
```