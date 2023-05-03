# AQI-Visualization
Visualizing Satellite CO2 and Air Quality Index Data in Oregon
## Satellite Carbon Dioxide Data and Air Quality Index Analysis
This repository contains a Jupyter Notebook for analyzing satellite-based Carbon Dioxide (CO2) data and Air Quality Index (AQI) data for Oregon. 

## Air Quality Index (AQI) Time Lapse Visualization by County

![AQI timelapse of counties](AQI_plot3.gif)


## Dependencies

To run the notebook, you will need the following Python libraries:

* numpy
* pandas
* seaborn
* matplotlib
** netCDF4
* xarray
* cartopy
* nc_time_axis
* ipywidgets
* geopandas
* shapely

You can install these packages using pip:

pip install numpy pandas seaborn matplotlib netCDF4 xarray cartopy nc_time_axis ipywidgets geopandas shapely
## Data 
The analysis uses the following data sources:

* dataset_satellite_data_carbon_dioxide.nc: NetCDF file containing satellite-based Carbon Dioxide (CO2) data.
* daily summary aqi_1990.csv: CSV file containing daily Air Quality Index (AQI) data from 1990.
* daily_aqi_by_county_2022.csv: CSV file containing daily AQI data by county for 2022.
* tl_2022_41_cousub.shp: Shapefile containing geometry data for Oregon counties.
* ne_50m_admin_1_states_provinces.shp: Shapefile containing geometry data for US state boundaries.

## Usage
To run the notebook, launch Jupyter Notebook or JupyterLab and open the provided notebook file. You can then run the cells to visualize and analyze the data.

Some key functions and visualizations include:

* 'plot_co2(time_index)': Plots CO2 levels at the specified time index using a PlateCarree projection map.
* 'plot_oregonAQI(time_index)': Plots the Air Quality Index (AQI) in Oregon for a specific time index.

Interactive widgets are also available to explore the data:

* Time index slider for CO2 visualization
* Time index slider for AQI visualization


