# Code for accelerating boreal CO2 seasonality

Analysis and figure-generation code for the manuscript **“Accelerating increase in northern high-latitude atmospheric CO2 seasonality driven by local ecosystems and atmospheric transport.”**

## Repository structure

- `main-text/`: Jupyter notebooks for the analyses and Figures 1–4 in the main manuscript.
- `SI-code/`: Jupyter notebooks for supplementary analyses and figures, including trend matrices, cumulative carbon amplitude (CCA), SCA reconstruction, and regional and driver attribution.

SCA denotes the seasonal cycle amplitude of atmospheric CO2. CCA denotes the seasonal cumulative carbon amplitude of surface carbon exchange.

## Running the notebooks

The code uses Python 3 and Jupyter Notebook. Main dependencies include NumPy, pandas, xarray, SciPy, Matplotlib, statsmodels, and pymannkendall. Some notebooks also use Cartopy, GeoPandas, Shapely, seaborn, and arch. Seasonal-cycle processing uses the NOAA `ccg_filter` module.

Before running a notebook, install its imported packages, provide the required input files, and update the data, module, and output paths to match your local environment. Execute the code cells in order.

## Data and code availability

The notebooks are provided in their current working form. Input datasets are not included in this repository, and the notebooks retain paths from the original computing environment.

When the manuscript proceeds to the next stage, the complete data and code, together with detailed documentation, will be deposited in Zenodo.
